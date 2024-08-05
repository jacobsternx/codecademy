FSE 1 Web Development Foundations
Get started with the foundations. By the end of this section, you'll be able to build a stylized and responsive website with HTML and CSS

> FSE 1.1 Web Dev - Fundamentals of HTML
FSE 1.2 Web Dev - Fundamentals of CSS
FSE 1.3 Web Dev - Developing Websites Locally
FSE 1.4 Web Dev - Deploying Websites
FSE 1.5 Web Dev - Improved Styling with CSS
FSE 1.6 Web Dev - Making a Website Responsive
FSE 1.7 Web Dev - Review, Web Development Foundations
Certification exam, Objective assessments 1 and 2

FSE 1.1 Web Dev - Fundamentals of HTML

Certificate :  Full-Stack Engineer
Course       :  Web Development Foundations
Lesson       :  Fundamentals of HTML
Unit            :  Exercise/Quiz/Material/Project/Forum/Comment
Purpose     :  Learn to build a structure for a website using HTML

FSE 1.1.1. Informational Introduction: Fundamentals of HTML

FSE 1.1.2. Learn HTML: Elements
* Introduction to HTML 
* HTML Anatomy
* The Body
* HTML Structure
* Headings
* Divs
* Attributes
* Displaying Text
* Styling Text
* Line Breaks
* Unordered Lists
* Ordered Lists
* Images
* Image Alts
* Videos
* Review
* Quiz: Introduction to HTML
* Project: Brown Bear Blog

FSE 1.1.3. Learn HTML: Structure
* HTML Document Standards
* Quiz: HTML Document Standards
* Aritcle: Intro to Mozilla Developer Network
* Article: HTML on MDN Web Docs: Debugging
* Project: Fashion Blog

FSE 1.1.4. Learn HTML: Tables
* HTML Tables 
* Quiz HTML Tables
* Project: Wine Festival Schedule

FSE 1.1.5. Semantic HTML
* Header and Nav
* Main and Footer
* Article and Section
* Aside
* Figure and Figcaption
* Audio and Attributes
* Video and Embed
* Practice
* Quiz: Semantic HTML
* Project: New York City Blog

FSE 1.1.6. Review: Fundamentals of HTML

---

### FSE 1.1.1. Informational Introduction: Fundamentals of HTML
#### Introduction > Fundamentals of HTML

HREF tags are external resources
SRC tags are resources, put at end of HTML file to increase rendering speed.

:: js function to set random color on button click
:: unit 1, page 11/13
```
<html>
  <head>
    <link rel="stylesheet" type="text/css" href="style.css">

  </head>

  <body>
      <button onclick="changeColor()">Repaint!</button>
  </body>
  
      <script>
        function getRandomColor(){
          let letters = '0123456789ABCDEF';
          let color = '#';
          for (let i = 0; i < 6; i++) {
            color += letters[Math.floor(Math.random() * 16)];
          }
          return color;
        }
        function changeColor(){
          let newColor = getRandomColor();
          document.body.style.backgroundColor = newColor;
        }
    </script>
  
</html>
```

### FSE 1.1.2. Learn HTML: Elements
Learn HTML > Elements

The \<strong> tag is used to define text with strong importance. The content inside is typically displayed in bold. 
Use the \<b> tag to specify bold text without any extra importance!
The \<em> tag is used to define emphasized text. The content inside is typically displayed in italic.
The \<i> tag defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic.
The \<i> tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.
Tags 
```
<!DOCTYPE HTML>, <HEAD>, <BODY>, <H1-H6>, <STRONG>, <EM>, <P>, <BR>, <DIV>, <SPAN>, <ID>, <UL>, <OL>, <LI>, <IMG>, <STYLE>, <-- -->, <BLOCKQUOTE>
```

Self-closing Tags
```
<!DOCTYPE HTML>, <BR>, <COL>, <EMBED>, <HR>, <IMG>, <INPUT>, <LINK>, <META>, <SOURCE>
```

#### HTML Attributes
target=_blank

\<a target="_blank|_self|_parent|_top|framename">
Attribute Values
Value	Description
_blank	Opens the linked document in a new window or tab
_self	Opens the linked document in the same frame as it was clicked (this is default)
_parent	Opens the linked document in the parent frame
_top	Opens the linked document in the full body of the window
framename	Opens the linked document in the named iframe

```
src="/path/to/file"
alt="description"
href=""
style="color=blue"
class="header"
id="unique value"
rel=""
name=""
translate="whether to transalate localized text"
title="page name"
type=""
meta charset="utf-8"
```

List elements (in particular, ol and ul elements) cannot be children of p elements. When a sentence contains a bulleted list, therefore, one might wonder how it should be marked up.

For instance, this fantastic sentence has bullets relating to

wizards,
faster-than-light travel, and telepathy,
and is further discussed below.

The solution is to realize that a paragraph, in HTML terms, is not a logical concept, but a structural one. In the fantastic example above, there are actually five paragraphs as defined by this specification: one before the list, one for each bullet, and one after the list.

The markup for the above example could therefore be:
```
<p>For instance, this fantastic sentence has bullets relating to</p>
<ul>
 <li>wizards,
 <li>faster-than-light travel, and
 <li>telepathy,
</ul>
<p>and is further discussed below.</p>
```
Authors wishing to conveniently style such "logical" paragraphs consisting of multiple "structural" paragraphs can use the div element instead of the p element.

Thus for instance the above example could become the following:
```
<div>For instance, this fantastic sentence has bullets relating to
<ul>
 <li>wizards,
 <li>faster-than-light travel, and
 <li>telepathy,
</ul>
and is further discussed below.</div>
```
This example still has five structural paragraphs, but now the author can style just the div instead of having to consider each part of the example separately.

Learn to build a structure for a website using HTML.

The Brown Bear html+css exercise were somewhat different from previous Odin, and it'd be best to take a moment to review. For example, there are 3 types of elements:

:: Inline elements:
respect left & right margins and padding, but not top & bottom
cannot have a width and height set
allow other elements to sit to their left and right
see very important side notes on this here

:: Block elements:
respect left, right, top, and bottom margins and padding
force a line break after the block element
acquires full-width if width not defined

:: Inline-block elements
allow other elements to sit to their left and right
respect top & bottom margins and padding
respect height and width

inline - Treats the element as though it were an inline span of text; width and height are meaningless

block - Treats the element as as rectangle; width and height can be specified

**Note: Whitespace between block elements will generally be ignored when HTML is rendered**

inline-block - Flows an element inline with the text, but allows width and height to be specified. It's used naturally for images, and useful when you want to have small blocks flowing left-to-right, top-to-bottom like regular text, but still have them like blocks.

Elements default to one of these anyway. For example:

inline elements: \<span>, \<em>, \<strong>
block elements: \<div>, <p>

### FSE 1.1.3. Learn HTML: Structure 
#### HTML Document Standards: Tags

#### Intro to Mozilla Developer Network

### FSE 1.1.4. Learn HTML: Tables 
HTML on MDN Web Docs: Debugging

#### HTML TABLES 

#### HTML Tables: Headings

To add titles to rows and columns, you can use the table heading element: \<th>.

The table heading element is used just like a table data element, except with a relevant title. Just like table data, a table heading must be placed within a table row.

```
<table>
  <tr>
    <th></th> <!--Empty table corner-->
    <th scope="col">Saturday</th>
    <th scope="col">Sunday</th>
  </tr>
  <tr>
    <th scope="row">Temperature</th>
    <td>73</td>
    <td>81</td>
  </tr>
</table>
```
What happened in the code above?

First, a new row was added to hold the three headings: a blank heading, a Saturday heading, and a Sunday heading. The blank heading creates the extra table cell necessary to align the table headings correctly over the data they correspond to.

In the second row, one table heading was added as a row title: Temperature.

When rendered, this code will appear similar to the image below:Table Example

The scope attribute is used by screen readers to enhance accessibility for visually impaired users. In addition to the row and col values shown in this exercise, the scope attribute can also have the following values:

rowgroup: used for table headings that group multiple rows.
colgroup: used for table headings that group multiple columns.
auto: the default value
In lessons 8 and 9 you will learn how to create cells that span multiple rows or columns. For improved accessibility, we should use the appropriate rowgroup and colgroup values within these headings.

#### HTML Tables: Table Borders

So far, the tables you’ve created have been a little difficult to read because they have no borders.

In older versions of HTML, a border could be added to a table using the border attribute and setting it equal to an integer. This integer would represent the thickness of the border.

```
<table border="1">
  <tr>
    <td>73</td>
    <td>81</td>
  </tr>
</table>
```
The code in the example above is deprecated, so please don’t use it. It’s meant to illustrate older conventions you may come across when reading other developers’ code.

The browser will likely still interpret your code correctly if you use the border attribute, but that doesn’t mean the attribute should be used.

We use CSS to add style to HTML documents, because it helps us to separate the structure of a page from how it looks. You can learn more about CSS in our CSS courses.

You can achieve the same table border effect using CSS.
```
table, td {
  border: 1px solid black;
}
```
The code in the example above uses CSS instead of HTML to show table borders.

#### HTML Tables: Spanning Columns

What if the table contains data that spans multiple columns?

For example, a personal calendar could have events that span across multiple hours, or even multiple days.

Data can span columns using the colspan attribute. The attribute accepts an integer (greater than or equal to 1) to denote the number of columns it spans across.

```
<table>
  <tr>
    <th>Monday</th>
    <th>Tuesday</th>
    <th>Wednesday</th>
  </tr>
  <tr>
    <td colspan="2">Out of Town</td>
    <!--Note: Skip the spanned column-->
    <td>Back in Town</td>
  </tr>
</table>
```
In the example above, the data Out of Town spans the Monday and Tuesday table headings using the value 2 (two columns). The data Back in Town appears only under the Wednesday heading.
The colspan attribute can also be used on \<th> tags. For improved accessibility, when we create table headings that span multiple columns, we should also include the scope=”colgroup” attribute within the opening \<th> tag.

#### HTML TABLES: Spanning Rows

Data can also span multiple rows using the rowspan attribute.

The rowspan attribute is used for data that spans multiple rows (perhaps an event goes on for multiple hours on a certain day). It accepts an integer (greater than or equal to 1) to denote the number of rows it spans across.
```
<table>
  <tr> <!-- Row 1 -->
    <th></th>
    <th>Saturday</th>
    <th>Sunday</th>
  </tr>
  <tr> <!-- Row 2 -->
    <th>Morning</th>
    <td rowspan="2">Work</td>
    <td rowspan="3">Relax</td>
  </tr>
  <tr> <!-- Row 3 -->
    <th>Afternoon</th>
  </tr>
  <tr> <!-- Row 4 -->
    <th>Evening</th>
    <td>Dinner</td>
  </tr>
</table>
```
In the example above, there are four rows:

The first row contains an empty cell and the two column headings.
The second row contains the Morning row heading, along with Work, which spans two rows under the Saturday column. The “Relax” entry spans three rows under the Sunday column.
The third row only contains the Afternoon row heading.
The fourth row only contains the Dinner entry, since “Relax” spans into the cell next to it.

#### HTML TABLES: Table Body
4 min
Over time, a table can grow to contain a lot of data and become very long. When this happens, the table can be sectioned off so that it is easier to manage.

Long tables can be sectioned off using the table body element: \<tbody>.

The \<tbody> element should contain all of the table’s data, excluding the table headings (more on this in a later exercise).
```
<table>
  <tbody>
    <tr>
      <th></th>
      <th>Saturday</th>
      <th>Sunday</th>
    </tr>
    <tr>
      <th>Morning</th>
      <td rowspan="2">Work</td>
      <td rowspan="3">Relax</td>
    </tr>
    <tr>
     <th>Afternoon</th>
    </tr>
    <tr>
      <th>Evening</th>
      <td>Dinner</td>
    </tr>
  </tbody>
</table>
```
In the example above, all of the table data is contained within a table body element. Note, however, that the headings were also kept in the table’s body — we’ll change this in the next exercise.

A TABLE element has four direct child sectioning elements:
caption
thead
tbody
tfoot
Under accessibility guidelines, CAPTION is required, and should be just inside the TABLE element, followed by the other three in that order. THEAD contains header information such as table title and column headings. TBODY contains the table rows and table data. TFOOT contains the boilerplate and small print such as appendix and other footnote details.

#### HTML TABLES: Table Head

In the last exercise, the table’s headings were kept inside of the table’s body. When a table’s body is sectioned off, however, it also makes sense to section off the table’s column headings using the \<thead> element.
```
<table>
  <thead>
    <tr>
      <th></th>
      <th scope="col">Saturday</th>
      <th scope="col">Sunday</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">Morning</th>
      <td rowspan="2">Work</td>
      <td rowspan="3">Relax</td>
    </tr>
    <tr>
     <th scope="row">Afternoon</th>
    </tr>
    <tr>
      <th scope="row">Evening</th>
      <td>Dinner</td>
    </tr>
  </tbody>
</table>
```
In the example above, the only new element is \<thead>. The table headings are contained inside of this element. Note that the table’s head still requires a row in order to contain the table headings.

Additionally, only the column headings go under the \<thead> element. We can use the scope attribute on \<th> elements to indicate whether a \<th> element is being used as a "row" heading or a "col" heading.

#### HTML TABLES: Table Footer
2 min
The bottom part of a long table can also be sectioned off using the <tfoot> element.
```
<table>
  <thead>
    <tr>
      <th>Quarter</th>
      <th>Revenue</th>
      <th>Costs</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Q1</th>
      <td>$10M</td>
      <td>$7.5M</td>
    </tr>
    <tr>
      <th>Q2</th>
      <td>$12M</td>
      <td>$5M</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th>Total</th>
      <td>$22M</td>
      <td>$12.5M</td>
    </tr>
  </tfoot>
</table>
```
In the example above, the footer contains the totals of the data in the table. Footers are often used to contain sums, differences, and other data results.

#### HTML TABLES: Styling with CSS
5 min
Tables, by default, are very bland. They have no borders, the font color is black, and the typeface is the same type used for other HTML elements.

CSS, or Cascading Style Sheets, is a language that web developers use to style the HTML content on a web page. You can use CSS to style tables. Specifically, you can style the various aspects mentioned above.

table, th, td {
  border: 1px solid black;
  font-family: Arial, sans-serif;
  text-align: center;
}

The code in the example above demonstrates just some of the various table aspects you can style using CSS properties.

#### HTML TABLES: Review

Let’s review what we’ve learned so far:

The \<table> element creates a table.
The \<tr> element adds rows to a table.
To add data to a row, you can use the \<td> element.
Table headings clarify the meaning of data. Headings are added with the \<th> element.
Table data can span columns using the colspan attribute.
Table data can span rows using the rowspan attribute.
Tables can be split into three main sections: a head, a body, and a footer.
A table’s head is created with the \<thead> element.
A table’s body is created with the \<tbody> element.
A table’s footer is created with the \<tfoot> element.
All the CSS properties you learned about in this course can be applied to tables and their data.
Congratulations on completing HTML Tables!

#### HTML Tables: Quiz
Q: Which tag adds a new row header to an HTML table?
```
a. <th scope="row"></th>
Correct answer
(Selected)Incorrect:
b. <th></th>
This will create a heading, but we don’t know if it is for a row or a column.
c. <th scope="col"></th>
d. <tr></tr>
```
#### Project: Wine Festival Schedule
In this project, we’re going to practice tabular organization in HTML so you can hone your skills and feel confident taking them to the real world. Why? If you’re going to have data on a webpage, you’ve got to master the skill of effectively and aesthetically organizing it – an HTML table is the perfect solution.
* This is not an exam, so you can refer to other resources.
* Get AI-generated hints when you need help to complete a task.

> Note: To copy a code block in C_ IDE, press Cmd-C while highlighting code block
> Note: To paste a code block in C_ IDE, press Cmd-V while highlighting code block

### 1.1.5.
Semantic HTML
By using Semantic HTML, we select HTML elements based on their meaning, not on how they are presented. Elements such as \<div> and \<span> are not semantic elements since they provide no context as to what is inside of those tags.

For example, instead of using a \<div> element to contain our header information, we could use a \<header> element, which is used as a heading section. By using a \<header> tag instead of a \<div>, we provide context as to what information is inside of the opening and closing tag.

Why use Semantic HTML?

Accessibility: Semantic HTML makes webpages accessible for mobile devices and for people with disabilities as well. This is because screen readers and browsers are able to interpret the code better.

SEO: It improves the website SEO, or Search Engine Optimization, which is the process of increasing the number of people that visit your webpage. With better SEO, search engines are better able to identify the content of your website and weight the most important content appropriately.

Easy to Understand: Semantic HTML also makes the website’s source code easier to read for other web developers.

To better understand this, you can think of comparing non-semantic HTML to going into a store with no signs on the aisles. Since the aisles aren’t labeled, you don’t know what products are in those aisles. However, stores that do have signs for each aisle make it a lot easier to find the items you need, just like Semantic HTML.

> Note: While div tag is used for styling related document parts, section tag is used for standalone document parts, which should usually be used with a header.

### 1.1.5.
SEMANTIC HTML
Header and Nav
5 min
Let’s take a look at some semantic elements that assist in the structure of a web page. A \<header> is a container usually for either navigational links or introductory content containing \<h1> to \<h6> headings.

The example below shows \<header> in action:
```
<header>
  <h1>
     Everything you need to know about pizza!
  </h1>
</header>
```
This can be compared to the code below which uses a \<div> tag instead of a \<header> tag:
```
<div id="header">
  <h1>
    Everything you need to know about pizza!
  </h1>
</div>
```
By using a \<header> tag, our code becomes easier to read. It is much easier to identify what is inside of the \<h1>‘s parent tags, as opposed to a \<div> tag which would provide no details as to what was inside of the tag.

A \<nav> is used to define a block of navigation links such as menus and tables of contents. It is important to note that \<nav> can be used inside of the \<header> element but can also be used on its own.

Let’s take a look at the example below:
```
<header> 
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>   
    </ul>
  </nav>
</header>
```
By using \<nav> as a way to label our navigation links, it will be easier for not only us, but also for web browsers and screen readers to read the code.

> Note: nav tag included in div > header discussion

### 1.1.5.
SEMANTIC HTML
Main and Footer
4 min
Two more structural elements are \<main> and \<footer>. These elements along with \<nav> and \<header> help describe where an element is located based on conventional web development standards.

The element \<main> is used to encapsulate the dominant content within a webpage. This tag is separate from the \<footer> and the \<nav> of a web page since these elements don’t contain the principal content. By using \<main> as opposed to a \<div> element, screen readers and web browsers are better able to identify that whatever is inside of the tag is the bulk of the content.

So how does \<main> look when incorporated into our code? That’s a great question.
```
<main>
  <header>
    <h1>Types of Sports</h1>
  </header>
  <article>
    <h3>Baseball</h3>
    <p>
      The first game of baseball was played in Cooperstown, New York in the summer of 1839.
    </p>
  </article>
</main>
```
As we see above, \<main> contains an \<article> and \<header> tag with child elements that hold the most important information related to the page.

The content at the bottom of the subject information is known as the footer, indicated by the \<footer> element. The footer contains information such as:

Contact information
Copyright information
Terms of use
Site Map
Reference to top of page links
For example:
```
<footer>
  <p>Email me at Codey@Codecademy.com</p>
</footer>
```
In the example above, the footer is used to contain contact information. The \<footer> tag is separate from the \<main> element and typically located at the bottom of the content.

> Note: header, main, footer, nav, article are semantic in that they describe content relevance for accessibility

### FSE 1.1.5. Semantic HTML
#### SEMANTIC HTML > Article and Section
4 min
Now that we covered the body of Semantic HTML, let’s focus on what can go in the body. The two elements we’re going to focus on now are \<section> and \<article>.
\<section> defines elements in a document, such as chapters, headings, or any other area of the document with the same theme. For example, content with the same theme such as articles about cricket can go under a single \<section>. A website’s home page could be split into sections for the introduction, news items, and contact information.

Here is an example of how to use \<section>:
```
<section>
  <h2>Fun Facts About Cricket</h2> </section>
```
In the code above we created a \<section> element to encapsulate the code. In \<section> we added a \<h2> element as a heading.

The \<article> element holds content that makes sense on its own. \<article> can hold content such as articles, blogs, comments, magazines, etc. An \<article> tag would help someone using a screen reader understand where the article content (that might contain a combination of text, images, audio, etc.) begins and ends.

Here is an example of how to use \<article>:
```
<section>
  <h2>Fun Facts About Cricket</h2>
  <article>
    <p>A single match of cricket can last up to 5 days.</p>
  </article>
</section>
```
In the code above, the \<article> element containing a fact about cricket was placed inside of the \<section> element. It is important to note that a \<section> element could also be placed in an \<article> element depending on the context.

Related Forum Discussion:

(Forum question regarding placement of H2 elements inside the article and section, while the lesson had the H2 element inside the section only.)

The H2 is inside the ARTICLE likely because it pertains to the content of the article, not the section that contains it. Search robots determine how to index based on how we structure the document. The headings are important and should not be too far removed from their related textual content.

The page is the primary document, so it would have its own outline. In this instance headings would be hierarchical, with only one H1 traceable back to the page, the primary document. If articles are to be portable then they need to be treated as primary documents in their own right. As we section the articles, the section headings would be H2 as applies to the outline to which they belong.

A document outline is tricky enough to comprehend. The web has compounded that with user created content and blogs/forums, &c. 

> The main message from the non-Codecademy video mentioned is that an ARTICLE is a portable object by definition. A section is not intended to be portable. Where it occurs in the markup needs to be traced back to which object is their parent. 

(Also stated is recommendations would not usually provide for a section H1.)

#### SEMANTIC HTML > The Aside Element
2 min
The \<aside> element is used to mark additional information that can enhance another element but isn’t required in order to understand the main content. This element can be used alongside other elements such as \<article> or \<section>. Some common uses of the \<aside> element are for:

* Bibliographies
* Endnotes
* Comments
* Pull quotes
* Editorial sidebars
* Additional information

Here’s an example of \<aside> being used alongside \<article>:
```
<article>
  <p>The first World Series was played between Pittsburgh and Boston in 1903 and was a nine-game series.</p>
</article>
<aside>
  <p>
   Babe Ruth once stated, “Heroes get remembered, but legends never die.” 
  </p>
</aside>
```
As shown above, the information within the \<article> is the important content. Meanwhile, the information within the \<aside> enhances the information in \<article> but is not required in order to understand it.

Forum:
* The \<aside> element is semantic HTML and used to represent content tangentially related to the main content on a webpage.
* It often appears alongside an \<article> or \<section> element, providing additional information or context.
* However, the \<aside> element itself does not inherently define any specific alignment or styling.
* If you want your \<aside> tags on the left, in your style.css write: 
 aside { float:left; }

#### SEMANTIC HTML > Figure and Figcaption
5 min
With \<aside>, we learned that we can put additional information next to a main piece of content, but what if we wanted to add an image or illustration? That is where \<figure> and \<figcaption> come in.

\<figure> is an element used to encapsulate media such as an image, illustration, diagram, code snippet, etc, which is referenced in the main flow of the document.
```
<figure>
  <img src="overwatch.jpg">
</figure>
```
In this code, we created a \<figure> element so that we can encapsulate our \<img> tag. In \<figure> we used the \<img> tag to insert an image onto the webpage. We used the src attribute within the \<img> tag so that we can link the source of the image.

It’s possible to add a caption to the image by using \<figcaption>.

\<figcaption> is an element used to describe the media in the \<figure> tag. Usually, \<figcaption> will go inside \<figure>. This is different than using a <p> element to describe the content; if we decide to change the location of \<figure>, the paragraph tag may get displaced from the figure while a \<figcaption> will move with the figure. This is useful for grouping an image with a caption.
```
<figure>
  <img src="overwatch.jpg">
  <figcaption>This picture shows characters from Overwatch.</figcaption>
</figure>
```
In the example above, we added a \<figcaption> into the \<figure> element to describe the image from the previous example. This helps group the \<figure> content with the \<figcaption> content.

While the content in \<figure> is related to the main flow of the document, its position is independent. This means that you can remove it or move it somewhere else without affecting the flow of the document.

#### Semantic HTML > Audio and Attributes
5 min
Now that we learned about text-based content, let us dig into \<audio>! Surely everyone needs \<audio>—how else would you listen to your Korean hip hop?

The <audio> element is used to embed audio content into a document. Like \<video>, \<audio> uses src to link the audio source.
```
<audio>
  <source src="iAmAnAudioFile.mp3" type="audio/mp3">
</audio>
```
In this example, we created an \<audio> element. Then we created a \<source> element to encapsulate our audio link. In this case, iAmAnAudioFile.mp3 is our audio file. Then we specified the type by using type and named what kind of audio it is. Although not always necessary, it’s recommended that we state the type of audio as it helps the browser identify it more easily and determine if that type of audio file is supported by the browser.

We linked our audio file into the browser but now we need to give it controls. This is where attributes come in. Attributes provide additional information about an element.

Attributes allow us to do many different things to our audio file. There are many attributes for \<audio> but today we’re going to be focusing on controls and src.

controls: automatically displays the audio controls into the browser such as play and mute.

src: specifies the URL of the audio file.

As you might have noticed, we already used the src attribute in the example code above. Most attributes go in the opening tag of \<audio>. For example, here’s how we could add both autoplay functionality and audio controls:

\<audio autoplay controls>

#### Semantic HTML > Video and Embed
6 min
As demonstrated in the previous exercise, media content can be a useful addition to a website. By using a \<video> element, we can add videos to our website. The \<video> element makes it clear that a developer is attempting to display a video to the user.

Some attributes that can alter a video playback include:

controls: When added in, a play/pause button will be added onto the video along with volume control and a fullscreen option.
autoplay: The attribute which results in a video automatically playing as soon as the page is loaded.
loop: This attribute results in the video continuously playing on repeat.
Below is an example of \<video> being used with the controls attribute:

\<video src="coding.mp4" controls>Video not supported</video>

In the code above, a video file named coding.mp4 is being played. The “Video not supported” will only show up if the browser is unable to display the video.

Another tag that can be used to incorporate media content into a page is the \<embed> tag, which can embed any media content including videos, audio files, and gifs from an external source. This means that websites that have an embed button have some form of media content that can be added to other websites. The \<embed> tag is a self-closing tag, unlike the \<video> element. Note that \<embed> is a deprecated tag and other alternatives, such as \<video>, \<audio> and \<img>, should be used in its place, but is being taught for legacy purposes.

Below we’ll take a look at \<embed> being used in action.

\<embed src="download.gif"/>

In the example above, \<embed> is being used to add in a gif from a local file known as download.gif. Embed can be used to add local files as well as media content straight from some other websites.

** Note: Forum points out that \<embed> used to be used for gif and flash, but that flash is no longer supported and \<img src=“download.gif”> can be used for gif, so use \<video>, \<img>, or \<audio>.

### Practice

\<section> defines elements in a document, such as chapters, headings, or any other area of the document with the same theme. \<article> holds content that makes sense on its own such as articles, blogs, and comments. Generally developers will use \<section> to define a theme for the webpage and use \<article> to write independent content for that theme. 

Element Placement

Semantic HTML introduces elements that can tell developers exactly what the element does or where it’s placed based on the name of that element. Some of these elements are \<header>, \<nav>, \<main>, and \<footer>. \<header> describes the content at the top of the page \<body>. It may include a logo, navigational links or a search bar. \<nav> encapsulates the page’s navigational links. It is often placed inside the \<header> or \<footer>. \<main> encapsulates the main content of a page between the header/navigation and the footer areas. \<footer> includes the page’s footer content at the bottom of the \<body>.

Note that \<embed> and \<video>, if they were both supported, would both provide semantic information, however \<video> would provide more semantical specificity.

#### Web Development Foundations > New York City Blog
After researching New York City, you decide to create a blog for your viewers who want to know more about the city. It’s time to create a blog to show off how amazing the Big Apple is. You got this!

Don’t forget to save your code after each step. By pressing save to run your code you will see the changes you’ve made in the browser.

Note: While you are developing the webpage, you will notice that the elements are automatically assigned colors, borders, and positioned properly. This is because of the CSS file. Don’t worry about CSS right now, it’s only there so that the webpage looks nice.
```
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <nav>
      <ul>
        <li>
          <a href="#blog">Blog</a>
        </li>
        <li>
          <a href="#media">Media</a>
        </li>
        <li>
          <a href="#about">About</a>
        </li>
      </ul>
    </nav>
    <header>
      <h1>New York City</h1>
    </header>
    <main>
      <section id="blog">
        <article>
          <p>New York City is made up of five boroughs which include Queens, Manhattan, Brooklyn, the Bronx, and Staten Island. The city is the home of approximately 8 million people. In 1876, France gifted the City of New York what is known as the Statue of Liberty, which is currently located on Liberty Island and commonly visited by tourists. However, it took 10 years to assemble and therefore wasn’t unveiled until 1886. Another tourist destination is Times Square. Times Square is commonly known for the big buildings, Broadway shows, and bright neon signs. This famous location was named after The New York Times after the Times moved to that location. Prior to that, it was named Longacre Square. New York City is also known for its bridges that connect the boroughs and allow ease of transportation.</p>
          <h2>The Scenery in NYC</h2>
        </article>
        <figure>
          <img src="https://content.codecademy.com/courses/Semantic%20HTML/statue-of-liberty.jpeg">
          <figcaption>This is the Statue of Liberty, a popular tourist attraction located on Liberty Island. </figcaption>
        </figure>
      </section>
      <aside>
        <p>New York City is very popular for the variety of great food it has. Some of the top food items in NYC include:
        <ol>
          <li>Pizza</li>
          <li>Bagels</li>
          <li>Burgers and Sandwiches</li>
          <li>Ramen</li>
          <li>Tacos</li>
          <li>Pasta</li>
          <li>Desserts</li>
        </ol>
        </p>
      </aside>
      <section id="media">
        <article>
          <h2>The Scenery in NYC</h2>
          <p>While the view in the city is beautiful, the sounds are not as lovely. Below you'll see an example of the view and the sounds you'll deal with in NYC on a daily basis.</p>
        </article>
        <video src="https://content.codecademy.com/courses/Semantic%20HTML/nyc-skyline-timelapse.mp4" controls></video>
        <embed src="https://content.codecademy.com/courses/Semantic%20HTML/nyc-skyline.jpeg">
        </embed>
        <audio controls>
          <source src="https://content.codecademy.com/courses/Semantic%20HTML/nyc-sounds.mov" type="audio/mpeg">
        </audio>
      </section>
    </main>
    <footer>
      <p>Posted by: Jacob Stern</p>
      <p>Contact information: Codecademy.com</p>
    </footer>
  </body>
  ```
  #### Review: Fundamentals of HTML
In this unit, you learned about the fundamentals of HTML.

Congratulations! The goal of this unit was to get an introduction to the fundamentals of HTML, one of the languages essential to developing websites.

Having completed this unit, you are now able to:

Understand how HTML is used for web development
Use HTML to build a structure for a website
Create tables in HTML documents
Write clearer, more accessible HTML using Semantic HTML tags
If you are interested in learning more about these topics, here are some additional resources:

Book: HTML & CSS, Jon Duckett, Chapters 1-5 (pp. 12-124)
Learning is social. Whatever you’re working on, be sure to connect with the Codecademy community in the forums. Remember to check in with the community regularly, including for things like asking for code reviews on your project work and providing code reviews to others in the projects category, which can help to reinforce what you’ve learned.

"Create a table header at the top of the table with one row and three cells labeling the columns: Name, Feet, and Wings."
```
<!doctype html>

<html>
  <head>
    <link href="./styles.css" rel="stylesheet" type="text/css">
  </head>
  <body>
    <h1>Animal Facts</h1>
    <table>
      <thead>
        <tr>
          <th scope="col">Name</th>
          <th scope="col">Feet</th>
          <th scope="col">Wings</th>
        </tr>
      </thead>
      <tr>
        <td>Chicken</td>
        <td>2</td>
        <td>2</td>
      </tr>
      <!-- Trimmed rows: Whale, Griffin, Millipede, Butterfly -->
    </table>
    
  </body>
</html>
```
"Include three \<td> elements in your header row."
Apparently, this question wanted th elements to be replaced with td elements???

"Add link to image element to be taken to WIkipedia page on separate tab."
```
<!doctype html>
<html>
  <head>
    <title>Cindy Sherman</title>
  </head>
  <body>
    <a href="https://en.wikipedia.org/wiki/Cindy_Sherman" target="_blank">
      <img
        width="350"
        src="https://content.codecademy.com/practice/code-challenges/sherman.jpeg"
        alt="Cindy Sherman, Untitled Film Still 21"
      />
    </a>
  </body>
</html>
```
