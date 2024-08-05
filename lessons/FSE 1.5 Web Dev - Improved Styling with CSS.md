FSE 1 Web Development Foundations
Get started with the foundations. By the end of this section, you'll be able to build a stylized and responsive website with HTML and CSS

FSE 1.1 Web Dev - Fundamentals of HTML
FSE 1.2 Web Dev - Fundamentals of CSS
FSE 1.3 Web Dev - Developing Websites Locally
FSE 1.4 Web Dev - Deploying Websites
> FSE 1.5 Web Dev - Improved Styling with CSS
FSE 1.6 Web Dev - Making a Website Responsive
FSE 1.x Web Dev - Review, Web Development Foundations
Certification exam, Objective assessments 1 and 2

FSE 1.5 Web Dev - Improved Styling with CSS

Certificate :  Full-Stack Engineer
Course       :  Web Development Foundations
Lesson       :  Improved Styling with CSS
Unit            :  Exercise/Quiz/Material/Project/Forum/Comment
Purpose     :  Use intermediate-level CSS to customize styles and implement navigation elements

FSE 1.5.0. Introduction, Improved Styling with CSS 
FSE 1.5.1. Learn CSS Colors
FSE 1.5.2. Learn CSS Typography
FSE 1.5.3. Challenge Project Build Your Own Cheat Sheet
FSE 1.5.4. Learn Links and Buttons
FSE 1.5.5. Learn Secondary Navigation
FSE 1.5.6. Wireframing
FSE 1.5.7. Challenge Project: Build a Website Design System
FSE 1.5.8. Review, Improved Styling with CSS 

---

### FSE 1.5.0. Introduction, Improved Styling with CSS 
#### Introduction: Improved Styling with CSS
In this unit, you will learn about intermediate topics in CSS and navigation design.

The goal of this unit is to dig deeper into CSS and improve your ability to style websites. You will also learn more about navigation design.

After this unit, you will be able to:

Apply more custom colors and fonts
Style navigation elements like links and buttons
Create secondary (breadcrumb) navigation
Learning is social. Whatever you’re working on, be sure to connect with the Codecademy community in the forums. Remember to check in with the community regularly, including for things like asking for code reviews on your project work and providing code reviews to others in the projects category, which can help to reinforce what you’ve learned.

### FSE 1.5.1. Learn CSS Colors
#### Learn > Color > Foreground vs Background
3 min
Before discussing the specifics of color, it’s important to make two distinctions about color. Color can affect the following design aspects:

The foreground color
The background color
Foreground color is the color that an element appears in. For example, when a heading is styled to appear green, the foreground color of the heading has been styled.

Conversely, when a heading is styled so that its background appears yellow, the background color of the heading has been styled

In CSS, these two design aspects can be styled with the following two properties:

color - this property styles an element’s foreground color.
background-color - this property styles an element’s background color.
```
h1 {
  color: red;
  background-color: blue;
}
```
In the example above, the text of the heading will appear in red, and the background of the heading will appear blue.

#### Learn > Color > Hexadecimal
4 min
One syntax that we can use to specify colors is called hexadecimal. Colors specified using this system are called hex colors. A hex color begins with a hash character (#) which is followed by three or six characters. The characters represent values for red, blue and green.

darkseagreen: #8FBC8F
sienna:       #A0522D
saddlebrown:  #8B4513
brown:        #A52A2A
black:        #000000 or #000
white:        #FFFFFF or #FFF
aqua:         #00FFFF or #0FF

In the example above, you may notice that there are both letters and numbers in the values. This is because the hexadecimal number system has 16 digits (0-15) instead of 10 (0-9) like in the standard decimal system. To represent 10-15, we use A-F. Here is a list of many different colors and their hex values.

Notice that black, white, and aqua are all represented with both three characters and six characters. This can be done with hex colors whose number pairs are the same characters. In the example above, aqua can be represented as #0FF because both of the first two characters are 0 and the second and third pairs of characters are both Fs. Keep in mind that all three character hex colors can be represented with six characters (by repeating each character twice) but the same is not true in reverse.

You can include hex colors just as you would include named colors: background-color: #9932cc;, and the letters can be uppercase or lowercase.

Note: I changed colors from names to hex as requested, but would not generally advise

#### Learn > Color > RGB Colors
2 min
There is another syntax for representing RGB values, commonly referred to as “RGB value” or just “RGB”, that uses decimal numbers rather than hexadecimal numbers, and it looks like this:
```
h1 {
  color: rgb(23, 45, 23);
}
```
Each of the three values represents a color component, and each can have a decimal number value from 0 to 255. The first number represents the amount of red, the second is green, and the third is blue. These colors are exactly the same as hex, but with a different syntax and a different number system.

In general, hex and RGB color representations are equivalent. Which you choose is a matter of personal taste. That said, it’s good to choose one and be consistent throughout your CSS, because it’s easier to compare hex to hex and RGB to RGB.

Note: So, the point of this exercise is that colors can be expressed by name, hex, or rbb. 
Note: There are many more colors than those named.

#### Learn > Color > Hue, Saturation, and Lightness
4 min
The RGB color scheme is convenient because it’s very close to how computers represent colors internally. There’s another equally powerful system in CSS called the hue-saturation-lightness color scheme, abbreviated as HSL.

The syntax for HSL is similar to the decimal form of RGB, though it differs in important ways. The first number represents the degree of the hue, and can be between 0 and 360. The second and third numbers are percentages representing saturation and lightness respectively. Here is an example:

color: hsl(120, 60%, 70%);

Hue is the first number. It refers to an angle on a color wheel. Red is 0 degrees, Green is 120 degrees, Blue is 240 degrees, and then back to Red at 360. You can see an example of a color wheel below.

[color wheel image]

Saturation refers to the intensity or purity of the color. The saturation increases towards 100% as the color becomes richer. The saturation decreases towards 0% as the color becomes grayer.

Lightness refers to how light or dark the color is. Halfway, or 50%, is normal lightness. Imagine a sliding dimmer on a light switch that starts halfway. Sliding the dimmer up towards 100% makes the color lighter, closer to white. Sliding the dimmer down towards 0% makes the color darker, closer to black.

HSL is convenient for adjusting colors. In RGB, making the color a little darker may affect all three color components. In HSL, that’s as easy as changing the lightness value. HSL is also useful for making a set of colors that work well together by selecting various colors that have the same lightness and saturation but different hues.

Note: Though nice, learning the ins and outs of HSL seems beyond the scope of FSE

#### Learn > Color > Opacity and Alpha
4 min
All of the colors we’ve seen so far have been opaque, or non-transparent. When we overlap two opaque elements, nothing from the bottom element shows through the top element. In this exercise, we’ll change the opacity, or the amount of transparency, of some colors so that some or all of the bottom elements are visible through a covering element.

To use opacity in the HSL color scheme, use hsla instead of hsl, and four values instead of three. For example:

color: hsla(34, 100%, 50%, 0.1);

The first three values work the same as hsl. The fourth value (which we have not seen before) is the alpha. This last value is sometimes called opacity.

Alpha is a decimal number from zero to one. If alpha is zero, the color will be completely transparent. If alpha is one, the color will be opaque. The value for half-transparent would be 0.5.

You can think of the alpha value as, “the amount of the background to mix with the foreground”. When a color’s alpha is below one, any color behind it will be blended in. The blending happens for each pixel; no blurring occurs.

The RGB color scheme has a similar syntax for opacity, rgba. Again, the first three values work the same as rgb and the last value is the alpha. Here’s an example:

color: rgba(234, 45, 98, 0.33);

A little unconventional, but still worth mentioning is how hex colors can also have an alpha value. By adding a two-digit hexadecimal value to the end of the six-digit representation (#52BC8280), or a one-digit hexadecimal value to the end of the three-digit representation (#F003), you can change the opacity of a hexadecimal color. Hex opacity ranges from 00 (transparent) to FF (opaque).

Alpha can only be used with HSL, RGB, and hex colors; we cannot add the alpha value to name colors like green.

There is, however, a named color keyword for zero opacity, transparent. It’s equivalent to rgba(0, 0, 0, 0), and it’s used like any other color keyword:

color: transparent;

Note: Points of this exercise are transparency changes overlapping colors, both rgba and hsla colors have an alpha channel, and color keyword transparent

#### Learn > Color > Review
<1 min
We’ve completed our extensive tour of the colors in CSS! Let’s review the key information we’ve learned.

There are four ways to represent color in CSS:

Named colors—there are more than 140 named colors, which you can review here on MDN.
Hexadecimal or hex colors
Hexadecimal is a number system that has sixteen digits, 0 to 9 followed by “A” to “F”.
Hex values always begin with # and specify values of red, blue, and green using hexadecimal numbers such as #23F41A.
Six-digit hex values with duplicate values for each RGB value can be shorted to three digits.
RGB
RGB colors use the rgb() syntax with one value for red, one value for blue and one value for green.
RGB values range from 0 to 255 and look like this: rgb(7, 210, 50).
HSL
HSL stands for hue (the color itself), saturation (the intensity of the color), and lightness (how light or dark a color is).
Hue ranges from 0 to 360 and saturation and lightness are both represented as percentages like this: hsl(200, 20%, 50%).
You can add opacity to color in RGB and HSL by adding a fourth value, a, which is represented as a percentage.
Great job! Feel empowered to add a bit of color to each of your projects!

Note: I'm not sure how shortening six character hex color values to thee characters is relevant to a FSE
Note: Even color coding systems seem, although loosely affiliated, beyond scope for FSE
Note: Opacity means not transparency, or opaqueness.

#### Objective > Web Development Foundations > Paint Store (Project)
In this project, you will follow step-by-step instructions to improve a vibrant, color-rich web page for a home paint business. It displays information about using color in a home and color swatches with varying lightness, saturation, and hue.

The page is almost ready to be published. You’ll be making the following color-related changes:

Exchange some named colors with hexadecimal color values.
Add some semi-transparent overlays to the banner and footer using RGBA.
Fill in the first color column of the swatch samples using HSL colors.
The website’s existing index.html and style.css document files are displayed in the text editor.

Note: in practice, hash symbol is called an octothorp

### FSE 1.5.2. Learn CSS Typography
#### Learn > Typography > Typography
1 min
In this lesson, we’ll focus on typography, the art of arranging text on a page. We’ll look at:

* How to style and transform fonts.
* How to lay text out on a page.
* How to add external fonts to your web pages.

Some of the most important information a user will see on a web page will be textual. Styling text to make page content accessible and engaging can significantly improve user experience. Let’s begin!

#### Learn > Typography > Font Family
7 min
You may remember from the Visual Rules lesson that the font of an element can be changed using the font-family property.
```
h1 {
  font-family: Arial;
}
```
In the example above, the font family for all \<h1> heading elements have been set to Arial.

Let’s talk about some things to keep in mind when setting font-family values.

Multi-Word Values
When specifying a typeface with multiple words, like Times New Roman, it is recommended to use quotation marks (' ') to group the words together, like so:
```
h1 {
  font-family: 'Times New Roman';
}
```
Web Safe Fonts
There is a selection of fonts that will appear the same across all browsers and operating systems. These fonts are referred to as web safe fonts. You can check out a complete list of web safe fonts here.

Fallback Fonts and Font Stacks
Web safe fonts are good fallback fonts that can be used if your preferred font is not available.
```
h1 {
  font-family: Caslon, Georgia, 'Times New Roman';
}
```
In the example above, Georgia and Times New Roman are fallback fonts to Caslon. When you specify a group of fonts, you have what is known as a font stack. A font stack usually contains a list of similar-looking fonts. Here, the browser will first try to use the Caslon font. If that’s not available, it will try to use a similar font, Georgia. And if Georgia is not available, it will try to use Times New Roman.

Serif and Sans-Serif
You may be wondering what features make a font similar to another font. The fonts Caslon, Georgia, and Times New Roman are Serif fonts. Serif fonts have extra details on the ends of each letter, as opposed to Sans-Serif fonts, which do not have the extra details.

Serif and Sans-Serif fonts

serif and sans-serif are also keyword values that can be added as a final fallback font if nothing else in the font stack is available.
```
h1 {
  font-family: Caslon, Georgia, 'Times New Roman', serif;
}
```
In this final example, the font stack has 4 fonts. If the first 3 fonts aren’t available, the browser will use whatever serif font is available on the system.

#### Learn > Typography > Font Weight
3 min
In CSS, the font-weight property controls how bold or thin text appears. It can be specified with keywords or numerical values.

Keyword Values
The font-weight property can take any one of these keyword values:

bold: Bold font weight.
normal: Normal font weight. This is the default value.
lighter: One font weight lighter than the element’s parent value.
bolder: One font weight bolder than the element’s parent value
Numerical Values
Numerical values can range from 1 (lightest) to 1000 (boldest), but it is common practice to use increments of 100. A font weight of 400 is equal to the keyword value normal, and a font weight of 700 is equal to bold.
```
.left-section {
  font-weight: 700;
}

.right-section {
  font-weight: bold; 
}
```
In the example above, text in elements of both .left-section and .right-section classes will appear bold.

> It’s important to note that not all fonts can be assigned a numeric font weight, and not all numeric font weights are available to all fonts. It’s a good practice to look up the font you are using to see which font-weight values are available.

#### Learn > Typography > Font Style
2 min
You can also italicize text with the font-style property.
```
h3 {
  font-style: italic;
}
```
The italic value causes text to appear in italics. The font-style property also has a normal value which is the default.

#### Learn > Typography > Text Transformation
2 min
Text can also be styled to appear in either all uppercase or lowercase with the text-transform property.
```
h1 {
  text-transform: uppercase;
}
```
The code in the example above formats all <h1> elements to appear in uppercase, regardless of the case used for the heading within the HTML code. Alternatively, the lowercase value could be used to format text in all lowercase.

Since text can be directly typed in all uppercase or lowercase within an HTML file, what is the point of a CSS rule that allows you to format letter case?

Depending on the type of content a web page displays, it may make sense to always style a specific element in all uppercase or lowercase letters. For example, a website that reports breaking news may decide to format all <h1> heading elements such that they always appear in all uppercase, as in the example above. It would also avoid uppercase text in the HTML file, which could make code difficult to read.

#### Learn > Typography > Text Layout
5 min
You’ve learned how text can be defined by font family, weight, style, and transformations. Now you’ll learn about some ways text can be displayed or laid out within the element’s container.

Letter Spacing
The letter-spacing property is used to set the horizontal spacing between the individual characters in an element. It’s not common to set the spacing between letters, but it can sometimes help the readability of certain fonts or styles. The letter-spacing property takes length values in units, such as 2px or 0.5em.
```
p {
  letter-spacing: 2px;
}
```
In the example above, each character in the paragraph element will be separated by 2 pixels.

Word Spacing
You can set the space between words with the word-spacing property. It’s also not common to increase the spacing between words, but it may help enhance the readability of bolded or enlarged text. The word-spacing property also takes length values in units, such as 3px or 0.2em.
```
h1 {
  word-spacing: 0.3em;
}
```
In the example above, the word spacing is set to 0.3em. For word spacing, using em values are recommended because the spacing can be set based on the size of the font.

Line Height
diagram of line height property

We can use the line-height property to set how tall we want each line containing our text to be. Line height values can be a unitless number, such as 1.2, or a length value, such as 12px, 5% or 2em.
```
p {
  line-height: 1.4;
}
```
In the example above, the height between lines is set to 1.4. Generally, the unitless value is preferred since it is responsive based on the current font size. In other words, if the line-height is specified by a unitless number, changing the font size will automatically readjust the line height.

Text Alignment
The text-align property, which you may already be familiar with from the CSS Visual Rules lesson, aligns text to its parent element.
```
h1 {
  text-align: right;
}
```
In the example above, the \<h1> element is aligned to the right side, instead of the default left.

Note: while thorough, setting letter-spacing, word-spacing, line-height seems bespoke; Also, text-align: justify looks unusual
Note: Unitless values: You can use a unitless number (e.g., 1.2). The computed value is this unitless number multiplied by the element’s own font size. This is often preferred to avoid unexpected results due to inheritance

#### Learn > Typography > Web Fonts
1 min
Previously, we learned about web safe fonts, a group of fonts supported across browsers and operating systems. However, the fonts you can use for your website are limitless—web fonts allow you to express your unique style through a multitude of different fonts found on the web.

Free font services, like Google Fonts and Adobe Fonts, host fonts that you can link to from your HTML document with a provided \<link> element.

You can also use fonts from paid font distributors like fonts.com by downloading and hosting them with the rest of your site’s files. You can create a @font-face ruleset in your CSS stylesheet to link to the relative path of the font file.

Both techniques for including web fonts into your site allow you to go beyond the sometimes “traditional” appearance of web safe fonts. In the next two exercises, you’ll learn exactly how to use each of these techniques!

Learn > Typography > Web Fonts Using \<link>
6 min
Online font services, like Google Fonts, make it easy to find and link to fonts from your site. You can browse and select fonts that match the style of your website.

Google Fonts Roboto Styles Page

When you select a font in Google Fonts, you’ll be shown all of the different styles available for that particular font. You can then select the styles you want to use on your site.

Showing Selected Font Families
When you’re done selecting a font and its styles, you can review your selected font family, and a \<link> element will be automatically generated for you to use on your site!
```s
<head>
  <!-- Add the link element for Google Fonts along with other metadata -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap" rel="stylesheet">
</head>
```
The generated <link> element needs to be added to the <head> element in your HTML document for it to be ready to be used in your CSS.
```
p {
  font-family: 'Roboto', sans-serif;
}
```
You can then create font-family declarations in your CSS, just like how you learned to do with other fonts!

#### Learn > Typography > Web Fonts Using @font-face
12 min
Fonts can also be added using a @font-face ruleset in your CSS stylesheet instead of using a <link> element in your HTML document. As mentioned earlier, fonts can be downloaded just like any other file on the web. They come in a few different file formats, such as:

* OTF (OpenType Font)
* TTF (TrueType Font)
* WOFF (Web Open Font Format)
* WOFF2 (Web Open Font Format 2)

The different formats are a progression of standards for how fonts will work with different browsers, with WOFF2 being the most progressive. 
> It’s a good idea to include TTF, WOFF, and WOFF2 formats with your @font-face rule to ensure compatibility on all browsers.

Let’s take a look at how to use @font-face using the same Roboto font as before:

Google Fonts Download
Within the “Selected Families” section, you can use the “Download” button to download the font files to your computer. The files will be downloaded in a single format, in this case, TTF. You can use additional tools to generate additional file types for WOFF and WOFF2, check out MDN’s list of font generators for more information.

When you have the files you need, move them to a folder inside your website’s working directory, and you’re ready to use them in a @font-face ruleset!
```
@font-face {
  font-family: 'MyParagraphFont';
  src: url('fonts/Roboto.woff2') format('woff2'),
       url('fonts/Roboto.woff') format('woff'),
       url('fonts/Roboto.ttf') format('truetype');
}
```
Let’s take a look at the example above, line by line:

The @font-face at-rule is used as the selector. It’s recommended to define the @font-face ruleset at the top of your CSS stylesheet.

Inside the declaration block, the font-family property is used to set a custom name for the downloaded font. The name can be anything you choose, but it must be surrounded by quotation marks. In the example, the font is named 'MyParagraphFont', as this font will be used for all paragraphs.

The src property contains three values, each specifying the relative path to the font file and its format. In this example, the font files are stored inside a folder named fonts within the working directory.

Note that the ordering for the different formats is important because our browser will start from the top of the list and search until it finds a font format that it supports. Read more on format prioritization on CSS-Tricks.

https://css-tricks.com/snippets/css/using-font-face-in-css/
Note: See link for more ways of accessing fonts

Once the @font-face at-rule is defined, you can use the font in your stylesheet!
```
p {
  font-family: 'MyParagraphFont', sans-serif;
}
```
Like using any other fonts, you can use the font-family property to set the font on any HTML element. The downloaded font can be referenced with the name you provided as the font-family property’s value in the @font-face ruleset—in this case, 'MyParagraphFont'.

#### Learn > Typography > Review
<1 min
Great job! You learned how to style an important aspect of the user experience—typography.

Let’s review what you’ve learned so far:

* Typography is the art of arranging text on a page.
* Text can appear bold or thin with the font-weight property.
* Text can appear in italics with the font-style property.
* The vertical spacing between lines of text can be modified with the line-height property.
* Serif fonts have extra details on the ends of each letter. Sans-Serif fonts do not.
* Fallback fonts are used when a certain font is not installed on a user’s computer.
* The word-spacing property changes how far apart individual words are.
* The letter-spacing property changes how far apart individual letters are.
* The text-align property changes the horizontal alignment of text.
* Google Fonts provides free fonts that can be used in an HTML file with the \<link> tag or the @font-face property.
* Local fonts can be added to a document with the @font-face property and the path to the font’s source.

Using your new knowledge of CSS typography, feel free to edit the code further to make the web page more appealing!

Note: To make more appealing, delete  p{text-align: justify;]

#### Objective > Web Development Foundations (practical)
Typography
Aoife Conleavy is a novelist who has been writing about her travels for nearly two decades. Before the launch of her new novel Tide Blade, which features the stories of real-life characters in Morocco, the author wants to spruce up her professional website. You’ll modify the typography on her site, changing the size, style, and font families, to make the page easier to read.

Using your understanding of typography, help Aoife Conleavy improve the readability of her site for her readers.

Note: seems like fonts are best called in an html head\<link> and not renamed in a css file

### FSE 1.5.3. Challenge Project Build Your Own Cheat Sheet
#### Objective
Web Development Foundations
Challenge Project: Build Your Own Cheat Sheet
Overview
This project is slightly different than others you have encountered thus far on Codecademy. Instead of a step-by-step tutorial, this project contains a series of open-ended requirements which describe the project you’ll be building. There are many possible ways to correctly fulfill all of these requirements, and you should expect to use the internet, Codecademy, and other resources when you encounter a problem that you cannot easily solve.

Project Goals
In this project, you’ll be building your own reference cheat sheet to help you build more websites in the future! Although there are great places to learn HTML & CSS like Codecademy, the best reference for yourself is often your own notes and projects.

Setup Instructions
If you choose to do this project on your computer instead of Codecademy, you can download what you’ll need by clicking the “Download” button below. If you need help setting up your computer, read our article about setting up a text editor for HTML/CSS development.

Download
Tasks
6/6 complete
Mark the tasks as complete by checking them off
Prerequisites
1.
To complete this project, you should have completed the codecademy Introduction to HTML course through the HTML tables lesson, and lessons in Learn CSS: Selectors and Visual Rules.

Project Requirements
2.
Your project should document at least one HTML or CSS topic. In our example project, we documented the tags and attributes used in HTML tables layouts, but you can choose any HTML or CSS topic that you’ve learned so far—the sky is the limit!

Possible topics could be:

HTML Tables
Other HTML tags
CSS selectors and specificity
Common CSS properties
If you choose to document HTML tags, open the hint to see how to include HTML tags as text in your code.

3.
Your site uses HTML tables to display the documentation. Be sure to label the columns in your HTML.

In our example site, we used tables with columns for:

The tag or attribute name
The actual formatted tag (eg. \<table>)
A description of what to use the tag for.
You can use these same columns or choose your own.

4.
Your site should utilize a custom color scheme. You can use any of the named CSS colors.

5.
Your site should use custom styles for any code such as HTML tags (like \<h1>) or CSS properties or values (like font-family). Represent code using a monospace font family and a different background color.

Solution
6.
Great work! Visit our forums to compare your project to our sample solution code. You can also learn how to host your own solution on GitHub so you can share it with other learners!

Your solution might look different from ours, and that’s okay! There are multiple ways to solve these projects, and you’ll learn more by seeing others’ code.

If you’d like to extend your cheat sheet, keep adding new topics to it as you continue to learn more HTML, CSS, and more. As you become more advanced with CSS, you’ll also be able to improve the styling and layout of the cheat sheet itself.

Interesting solutions
https://ofras99.github.io/mycheatsheet.github.io/
https://anchorweb.github.io/

### FSE 1.5.4. Learn Links and Buttons
#### Learn > Learn Links and Buttons > Browser Link Styles
6 min
Web browsers have always taken account of the importance of using signifiers for navigation. By default, browsers include a user agent stylesheet, a set of default styles included with the browser (“user agent”) for use on all web pages. The HTML5 specification defines a set of default behavior for rendering content. These styles are used to ensure that a raw HTML file is styled to be reasonably readable by any user, and user agent stylesheets include styling for headings, tables, links, and more basic HTML elements. Most users do not see these styles too often, because designers override them with their own custom designs. However, it’s important to note that maintaining a consistent user experience pattern, like the default behavior applied by browsers, is important for creating a consistent experience.

Traditionally, links are differentiated from regular text using blue text and underlines to draw users’ attention to their clickability. Many websites and user agent stylesheets still use these link styles.

Browsers also style two other link states: clicked (‘active’), and previously visited. In most user agent stylesheets, clicked (but not yet followed) links appear with red text, and previously visited links are styled with purple text.

#### Learn > Learn Links and Buttons > Link Styling
3 min
The most important aspect of styling links is differentiating links from surrounding text. The default blue-text, underlined link style accomplishes this differentiation using two CSS properties: color and text-decoration. These are both good ways to differentiate a link, and they are strong, familiar signifiers to most web users. Additionally, you could use CSS properties for background-color, font-weight, or border.

Link styles should not be replicated in other page text. Link color should sufficiently contrast the text colors in the rest of the design. For example, if links are underlined, other text should not be.

Anchor text, the text itself of a link, should be descriptive of the linked resource. Although this is not strictly a design problem, it is important for usability, accessibility, and SEO. For example, the link at the beginning of this paragraph would be much more difficult to parse with a screen reader if it were re-written as follows:

Text for links, known as anchor text, should be \<a href="https://en.wikipedia.org/wiki/Anchor_text" rel="noopener noreferrer" target="_blank">descriptive</a>.

#### Learn > Learn Links and Buttons > Tooltips and Titles
6 min
In addition to providing descriptive anchor text, it is sometimes helpful to provide additional context to explain links. This context can be particularly helpful when a link contains or consists of an image, icon, or another non-text element.

Additional context can be provided as text using the HTML title attribute. Although the title attribute can be provided to any HTML element, it is often extremely useful as additional context or advisory text for clickable elements.

Most browsers will display the text of a title attribute as a tooltip, meaning when a user hovers their cursor over an element, the text will appear in a small box near the cursor.

To add tooltips to a clickable element like a link, add it as the title attribute.
```
<p>
  <a href="https://www.codecademy.com" title="Codecademy is an online learning platform">Codecademy</a> is the best place to learn to code!
</p>
```
Mouse over the word “Codecademy” below to see this behavior in action!

Codecademy is the best place to learn to code!

NOTE: The title attribute is HTML’s built-in way of creating tooltips, but is known to cause a variety of accessibility issues. Developers have come up with a number of ways to create tooltips that are more accessible, but this generally requires using CSS and JavaScript, which fall out of the scope of this lesson. When creating tooltips in the wild, you should research ways to make them accessible for everyone.

#### Learn > Learn Links and Buttons > Hover States and Cursors
6 min
In addition to styling elements themselves, other signifiers and visual feedback can be utilized during user interaction. The CSS pseudo-class :hover can be used to style elements on mouse hover. For instance, to change the color of link anchor text from blue to orange when a user hovers over it, the following CSS could be used:
```
a {
  color: blue;
}

a:hover {
  color: orange;
}
```
The first rule sets link colors to blue by default, and when a user mouses over a link, the second rule will override the color attribute of the \<a> tag and cause the text to turn orange. When the user moves the cursor away from the link, the text color will revert to blue.

In addition to any text style changes when hovering over a link, the user’s cursor should change from the default appearance to a pointing hand. The CSS cursor property is used to control this behavior. For example, to add this behavior to all \<a> tags, the following rule could be used:
```
a {
  cursor: pointer;
}
```
Luckily, this behavior is generally included in browser user agent stylesheets, and it also exists in the HTML5 default styles.

Hover state styling should never be used as the sole indication that something is a link. Users should not be forced to move their mouse over an entire document to tell what might be clickable. Additionally, hover states are not accessible in mobile browsers. Mobile devices do not generally have on-screen cursors, and users must actually touch the device (and possibly trigger a click event) to interact.

> Change the cursor to pointer. Even though this behavior is seen when the mouse is hovered over, you should add it to the rule for all \<a> tags, as the browser will only change cursor styles on hover by default. Putting the rule on an a:hover rule can cause unwanted behavior in some cases.

#### Learn > Learn Links and Buttons > Link States
10 min
Links have four main states: normal (not clicked), hover, active (clicked), and visited. These four states have associated CSS pseudo-classes: :link, :hover, :active, and :visited. These four states can be used to give a full range of visual feedback to users about the status of their link interaction.

Each state should still make it clear that the element in question is a link, meaning it should not make text identical to non-link text or alter the link’s appearance so much that users could perceive its behavior differently.

The ordering of link state pseudo-class rules is important to reveal the proper information. When a user hovers and then clicks a link, those styles should always override the static styling surrounding a user’s history with the link (unvisited :link and :visited). The proper order of these rules is:

:link
:visited
:hover
:active
This ordering will ensure that the rules cascade properly and the user can receive the most applicable visual feedback about the state of the link.

#### Learn > Learn Links and Buttons > Skeuomorphism and Flat Design
6 min
Buttons are another fundamental element of user interaction and navigation. They are called ‘buttons’ because they are often modeled on the appearance and behavior of real-life buttons. The concept of UI elements that replicate or imitate real-life counterparts is known as skeuomorphism.

In design, skeuomorphism is helpful for lowering the learning curve for users. If users can draw a metaphor between a familiar real-life object and an interface element, they are more likely to know how to use it without training. In the example of the button, if a web button appears similar to a real-life button on a physical interface, users can reliably figure out that the way to interact with the button is to press it.

Flat design is an alternative approach to skeuomorphism that embraces the fact that computer interfaces do not necessarily need to model real-life interfaces. As users grow more familiar with digital displays and interfaces, designers have felt less need to model physical interactions and instead rely on other signifiers to indicate interactive elements. To generalize, flat design uses simplicity and lack of clutter for its UI elements.

Note: We will be using the HTML \<button> element to create these designs. \<button>s come with some default styles, such as a border and background-color, which give them a built-in “buttony” look. In this exercise and the exercises that follow, you will use CSS to create customized buttons that override these defaults. To learn more about the HTML \<button>, you can visit the MDN Web Docs.

#### Learn > Learn Links and Buttons > Buttons: Skeuomorphic styling
12 min
Skeuomorphic button design aims to imitate the appearance and interactivity of a real-life button, often including a ‘raised’ appearance while the button is unpressed and a ‘pressed’ appearance when clicked.

Skeuomorphic button design can be implemented using image files, CSS rules, or a combination of both. CSS styles should be preferred over image files if possible, since they are faster to load, have smaller file sizes, and allow for a more consistent scaling and appearance across different screen sizes and resolutions. Modern CSS3 has support for many 2-D and 3-D effects and animations and can create many skeuomorphic button designs on its own.

If using CSS rules, the use of hover and/or active states is important in order to model interaction with a real button. For example, to implement a bare minimum 3-D button design, the following CSS ruleset could be used:
```
button {
  padding: 5px;
  border: 1px solid black;
  border-radius: 5px;
  text-decoration: none;
  box-shadow: 0px 5px;
}

button:hover {
  cursor: pointer;
}

button:active {
  margin-top: 5px;
  color: black;
  box-shadow: 0px 0px;
}
```
A button element can then be created with the following HTML:

\<button>Click me\</button>

The default state of this \<button> has some basic ‘buttony’ appearance with a rounded border (border and border-radius properties) and a slightly raised appearance with the use of the box-shadow. The :hover cursor is added for visual feedback. When the button is clicked (:active), the box-shadow is removed, and the margin-top moves the button down by 5px, making it appear to be pressed.

The above example is only one very basic implementation of a 3-D button; there are many additional (and more attractive) ways to create skeuomorphic buttons.

#### Learn > Learn Links and Buttons > Buttons: Flat Design
4 min
Flat design is so-called because of its 2-D appearance. Elements appear flat on the screen, and designers must rely on other styling and signifiers to indicate clickability.

Flat design buttons commonly appear as rectangles, rounded rectangles, or circles. These shapes are used ubiquitously for button elements, so users often perceive them as buttons and expect them to be clickable.

Since there are fewer obvious signifiers surrounding buttons in a flat design, they should be visually distinct from other page elements.

In flat designs in particular, button text is very important for clarity—the possibility of user confusion is reduced by pairing buttons with specific, descriptive labels. A button with ‘Click here’ leaves many more open questions than a button that reads ‘Submit form’.

#### Learn > Learn Links and Buttons > Buttons: Hover States
4 min
Just as with links, buttons should make use of hover states and the cursor: pointer declaration. All the caveats about the shortcomings of hover states on mobile devices apply to buttons, but their use is still encouraged.

Users expect buttons to be clickable. Since buttons can consist of any number of total elements (rectangular/circular body, text, image(s)), all elements should be clickable, should display their clickability, and should result in the same behavior.

Note: Make sure that the :hover rule comes before the :active rule so that the styles cascade correctly. (proper cascade order below)
:link
:visited
:hover
:active

#### Learn > Learn Links and Buttons > Review
<1 min
Great work! You’ve made this survey site much easier to understand and interact with! Let’s review what changes you made to improve usability:

1. Added styles to make links recognizable and distinguishable from ordinary text.
2. Added link styles that depend upon mouse interaction state, providing users with visual feedback for cursor hovering and mouse clicks.
3. Added additional context text with the HTML title attribute.
4. Styled buttons to be easily recognizable (in both skeuomorphic and flat design styles) using box shapes, border, hover, and active states.

Remember that the styles that you implemented here are only one of countless ways to communicate clickability and provide users with visual feedback. There is a huge amount of opportunity for variety and creativity while still following best practices and common user experience patterns.

#### Affordances, Signifiers, and Clickability
This article covers the design concepts of affordances and signifiers as well as some of their applications in web design.

Clickability
For users on the web, the mouse click is perhaps the most fundamental human-computer interaction. The web became the web partially through the power of hypertext, or text in one document that links to other documents or resources. To this day, users navigate the web largely through mouse clicks (and finger taps on mobile and tablet devices).

Affordances
Objects afford the ability of users to interact with them in various ways. For instance, a bench affords a person the ability to sit on it, but if it is not affixed to the ground, it also affords the user the ability to turn it over, throw (if the user is physically able), or perform any number of other actions. Even though the designer was probably not designing the bench with throwing in mind as the primary user behavior, the object still affords this action. 

> Potentials for interaction are collectively called the affordances of an object.

Signifiers
Signifiers are aspects of an object that a designer uses to indicate potential and intended affordances of an object. For example, a teacup with no handle affords the ability to lift it and drink out of it. But 
> designers and potters often add handles to signify that users can and should lift up the object and take a sip. The handle is an example of a common user experience pattern.

UX Patterns
User experience (UX) patterns establish reusable solutions to common problems. Handles are ubiquitous—they are used on objects of all shapes, sizes, and purposes to indicate that users can initiate an action by grabbing the handle with their hand(s).

Affordances and Signifiers in Web Design
In computer interactions, the possible affordances of any computer are usually relatively limited. Consider a web application in a browser—a user can essentially click, execute key commands or type, and potentially execute touch events or voice commands. Because of the relatively limited range of affordances, using proper signifiers is especially important to direct users properly. Users can click anywhere on a page, but not every click will have a result. Often, websites and applications use a combination of visual feedback and common UX patterns to help solve this issue. In web browsers, one common example of visual feedback is the cursor image itself: it can demonstrate what behavior might be expected from a click: a pointing hand indicating that an interaction will occur, an i-beam shape indicating that text can be selected, a four-directional arrow showing that an element can be moved, and [many more cursor styles and interactions.](https://developer.mozilla.org/en-US/docs/Web/CSS/cursor)

As stated above, the hovering, pointing hand cursor is a nearly universal pattern to indicate that an element or text is clickable. But users do not want to hover a cursor over every element to determine if it is clickable, and mobile devices do not even have the ability to hover a cursor! For this reason, designers also use signifiers to demonstrate elements that afford interaction. On the web, these signifiers come in the form of CSS styles that differentiate clickable from non-clickable elements. A ubiquitous example is the styling of hyperlinks—hyperlinks should be easily differentiated from other text in a block by different colors, underline styles, or font weights.

There is no universal “right answer” to the issues surrounding signifiers and affordances on the web, but web designers should always keep these ideas in mind while creating web designs and interfaces.

#### Objective > Web Development Foundations > The Summit
Time to put some navigation design knowledge to the test! Your goal is to improve the user experience of this ski lodge landing page. Currently, none of the clickable elements are very clear or offer good visual feedback to users.

The exact implementation and styling will be up to you; take the opportunity to be creative in your designs! Keep in mind that slick styling is cool, but it is just as important to clearly demonstrate to users how to interact with the site. We’ll provide some hints along the way if you’re stuck.

Note: :active, increase font size, hover reverse color/background, remove underline for obvious buttons, text-transform uppercase and border to increase visibility.

### FSE 1.5.5. Learn Secondary Navigation
#### Learn > Learn Secondary Navigation > Introduction
2 min
Consider the website to the right. We can see that the site is listing hotels in Singapore. Do you know if this site offers any other categories of travel products (tours, flights, experiences) or products in other regions? There is no way to tell from the current view.

What is primary vs secondary navigation?

The primary navigation system typically contains the most important links and buttons that need to be displayed on every single page of the site.

Secondary navigation, or breadcrumb navigation, usually consists of a clickable list of pages or attributes that led to the current page. It can help users understand the extent of the site and also where they are currently.
For example, a shopping site may have a breadcrumb trail leading to a pair of shoes like so:

Why do we call them breadcrumbs?
Think about the story of Hansel and Gretel, where the kids drop breadcrumbs as they walked in the woods so that they would be able to find their way back.

Benefit of using breadcrumbs
Breadcrumb navigation provides a lot of benefits for users that come to random pages in a website through direct links or search results. Even if they enter to a seemingly random page on our site, they already have an idea of where they are in the website. The breadcrumb also hints at the extent of the site. For the example above, users could safely assume the site had shoes for other categories, shoes in different styles, and shoes in more colors.

Breadcrumbs also provide a way for a user to quickly jump backward in their navigation of the site. For example, if a user wanted to browse another style of shoe, they could click directly on the “Shoes” page and navigate to their desired style. Without the breadcrumbs, they would likely need to click “back” twice in their browser or start their search over from the home page.

The decision to use breadcrumbs is a judgment call depending on the type, depth, and complexity of your site. In this lesson, we’ll discuss some of the benefits of including breadcrumb navigation, how to implement it using HTML and CSS, and some of the pitfalls to avoid.

#### Learn > Learn Secondary Navigation > Simple Example of Breadcrumbs
10 min
As you saw in the introduction, it is difficult to understand where you are on a website that lacks breadcrumb navigation. By adding it to a site, users can get a quick feel for where they are on a site.

It also hints at the breadth of the site. If a user sees something like “Fashion > Shoes” in the breadcrumb structure, they could reasonably expect the site contains other clothing items or accessories besides shoes.

Breadcrumbs are usually displayed as a horizontal list of pages and take up minimal space. Users expect to find them in the header, left-aligned, and below any primary navigation. Typically they are separated with a “>” or a “/“ symbol.

Let’s practice setting CSS rules to conform to the expectations for breadcrumb navigation. You will start with a plain looking list, but by the end you will have created a breadcrumb!

Note: Breadcrumbs require complex CSS, 
```
.breadcrumb > li {
  display: inline;
}

.breadcrumb li+li::before {
	padding: 10px;
  content: ">";
}

.breadcrumb a {
   text-decoration:none;
}

.breadcrumb a:hover {
  color: red;
}
```
#### Learn > Learn Secondary Navigation > Where do Breadcrumbs Lead
9 min
In the previous examples, if you clicked on any of the breadcrumbs, it wouldn’t take you to a new page. This is because we have set href="#". With this value, a click on the link will cause the page to scroll to the top of the current page.

In a full site, these breadcrumbs would link to their respective pages. This is accomplished by setting the href property to the appropriate page.

Since breadcrumbs are typically relative to the current page, the breadcrumb list on each page needs to be different. However, as a user moves around the breadcrumb list, they should expect the breadcrumb style and list to stay consistent.

For example, if the breadcrumb list was:
Fashion > Shoes > Flats > Brown

and a user clicked on “Flats”, the breadcrumb list on that page should look like:
Fashion > Shoes > Flats

It would be confusing for a user if the categories or order of them changed like:
Shoes > Shopping > Flats

#### Learn > Learn Secondary Navigation > Where do Breadcrumbs Lead
9 min
In the previous examples, if you clicked on any of the breadcrumbs, it wouldn’t take you to a new page. This is because we have set href="#". With this value, a click on the link will cause the page to scroll to the top of the current page.

In a full site, these breadcrumbs would link to their respective pages. This is accomplished by setting the href property to the appropriate page.

Since breadcrumbs are typically relative to the current page, the breadcrumb list on each page needs to be different. However, as a user moves around the breadcrumb list, they should expect the breadcrumb style and list to stay consistent.

For example, if the breadcrumb list was:
Fashion > Shoes > Flats > Brown

and a user clicked on “Flats”, the breadcrumb list on that page should look like:
Fashion > Shoes > Flats

It would be confusing for a user if the categories or order of them changed like:
Shoes > Shopping > Flats

Note: I'm following the example, but am not sure about the breadcrumb concept. My breadcrumb.css looks like this:
```
.breadcrumb {
  text-align: left;
}
.breadcrumb li {
  display: inline;
}
.breadcrumb li+li::before {
  color: gray;
  content: ">";
}
.breadcrumb a {
  display: inline;
}
```
#### Learn > Learn Secondary Navigation > Breadcrumb Styles
14 min
The previous exercise demonstrated the most basic styling for breadcrumbs. When designing your own site, you’ll need to make a judgment call if this approach is sufficient. If you want to invite the user to interact with the breadcrumbs, you can style them to make them a more prominent part of the page design.

The example below makes use of a couple of CSS tricks to create an arrow effect. We’re using the ::before and ::after pseudo-elements to add filled rectangles (with empty content) before and after each list item:
```
.breadcrumb li a::before, .breadcrumb li a::after {
  content: "";
  position: absolute;
  border-color: darkcyan;
  border-style: solid;
  border-width: 15px 5px;
}
```
By setting a portion of the border to transparent, it creates the “tail” of the arrow:
```
.breadcrumb li a::before {
  left: -10px;
  border-left-color: transparent;
}
```
This effect works because the element borders are drawn from the center of the element. We use similar CSS to draw the head of the arrow.

We’ll walk through the individual steps in the exercises so you can see how each step affects the resulting look.

#### Learn > Learn Secondary Navigation > Breadcrumb Types
14 min
There are three major types of breadcrumbs:
* Location
* Attribute
* Path

You’ve seen the first two types in our examples so far.

Location based breadcrumbs are based on where you are with respect to the navigation structure of the website. In our previous shoe shopping example, the first three li elements are location based. We are in the “shoes” section of the website, which is contained within the “fashion” section, which is contained within the “shopping” section.

Attribute based breadcrumbs are based on the attributes of the page or product that you are browsing. In our previous example, the final two li elements are attribute based. We are shopping for shoes that are “flats” and “brown”. Since the order of these attributes is not prescriptive, you’ll see some sites display these at the same level in the UI. If you want to allow users to remove attributes, provide an (x) button or similar to indicate they can be removed.

Finally, breadcrumbs can be based on a user’s unique path through the site. For example, if they landed on the home page, browsed to the about page and finally the registration page, their breadcrumb trail may look like:

Home > About > Register

Note that this breadcrumb trail will be different for each user and each visit. For even mildly complex sites, the number of steps will become large. To simplify the display, the beginning of the trail is often abbreviated:

... > About > Register

Note: when we added breadcrumb classes, we added them to the links not anchors
Note: we're glossing over that we really don't know much about pseudo-elements
Note: in provided css, a non-functional close breadcrumb feature was added, X 
```
.breadcrumb {
  text-align: left;
}
.breadcrumb li {
  display: inline;
}
.breadcrumb li.location+li.location::before {
  content: ">";
}
.attribute a {
  color: gray;
}
.breadcrumb a {
  display: inline;
}
.attribute a::after {
  content: " x";
  font-size: 8px;
  vertical-align: super;
}
```
#### Learn
Learn Secondary Navigation
Breadcrumb Pitfalls
1 min
Sometimes it is not appropriate to use breadcrumbs as a means of secondary navigation within a website. Users expect breadcrumbs to behave a certain way and attempts to deviate from this may confuse them. Most users are expecting breadcrumbs to expose the hierarchy of the site or display attributes of the page they are on.

Path based breadcrumbs are unique to a user’s journey and are not commonly implemented. Only use this type of breadcrumbs if there is a compelling reason for it.

While breadcrumbs are common, it is not the primary way users will navigate a site. Don’t make the breadcrumbs the only navigation structure.

In general, the rule of not adding anything extraneous to the design applies here. If the site only contains a few pages or if the pages in the breadcrumbs are already available through primary navigation, there is little reason to include breadcrumbs in the design.

#### Learn
Learn Secondary Navigation > Summary > 
<1 min
In this lesson we covered the concept of using breadcrumbs as a secondary navigation method for a site:

* Use breadcrumbs to indicate where a user is and the extent of the site
* Breadcrumbs are implemented using unordered lists in HTML with custom CSS styling
* Three types of breadcrumbs exist:
  * location - based on hierarchical structure of site
  * attribute - based on attributes of current page or item
  * path - unique to a user’s journey on the site
* Path-based breadcrumbs can be confusing, only use if needed
* Ensure breadcrumbs will add value before adding to a site

Note: unordered lists are used to create the breadcrumb trail
Note: following is another practical exercise of a website.

#### Objective > Web Development Foundations > FreshDeals: Blueberries
In the browser to the right, you should see a site for buying groceries. The currently selected product is “Organic Blueberries”. If you landed on this page, you may have some questions.

* Can I buy anything besides blueberries?
* Is everything on this site organic or can I buy conventional produce?
* Does this site offer non-produce items?

By adding breadcrumbs to this site, you will be adding a UI element that hints to some of the questions above. By doing so, users will have a better feeling for what the site provides and the optional attributes of the product they are purchasing.

We are focused on the layout of this page and will be implementing the breadcrumbs via HTML and CSS. The links to the breadcrumbs will not function.

Check off the project steps as you complete them.

If you get stuck during this project or would like to see an experienced developer work through it, click “Get Unstuck“ to see a project walkthrough video.

Note: The box-sizing: border-box property in CSS is used to include the padding and border within the element’s total width and height. This means that when you set the width and height of an element, it will include the content, padding, and border, making it easier to manage the size of elements without unexpected overflow or layout issues.
```
.element {
  width: 300px;
  height: 100px;
  padding: 20px;
  border: 10px solid black;
  box-sizing: border-box;
}
```

### FSE 1.5.6. Wireframing

Note: a grid design is probably a p tag
nav bar tied with footer
2 column
similar style probably means same css rules
gather content, make design decisions, add style guide

Process:
Take it one section at a time
Allow HTML and CSS to inform your layout
Look for similarities and differences as you begin to choose HTML tags and CSS selectors
Continue to apply and build your ‘style guide’
Be open to changes as you move through your design process

Suggestion......
Start with HTMLS5 tags to define overall site sections
```
<header>
<nav>
<main>
<section>
<footer>
```
Build HTML and CSS together to see their fit

#### Everything You Need to Know about Wireframes and Prototypes
Learn about website design deliverables: wireframes and prototypes.

[Everything You Need to Know about Wireframes and Prototypes](https://medium.com/thinking-design/everything-you-need-to-know-about-wireframes-and-prototypes-76f828a1bcbc)

In this article, you will learn about wireframes and prototypes: what they are, why they’re useful and how they’re involved with the user experience design process. This is helpful if you’d like to understand the design process before development and how multiple iterations of a design must be critiqued and revised in order to present the ideal product to the user. After you finish reading the article, return to this page and complete the following assessments.

Wireframes use grayscale, X boxes, and lorem ipsum in low fidelity and inexpensive representations meant to create a foundation for designers to set a creative team direction and plan forward direction without getting bogged down in details.

Wireframes should be produced early and experimented with moving objects around, together, and add or subtract.

Wireframes are a communication tool and documentation as a design deliverable.

Prototype to tie visual and interaction design together before development begins.
* Pitching ideas
* Deeper understanding
* Feedback, validation, research
* Not documentation

1. Native prototyping means writing code
2. Don't settle on first design prototype
3. Select right fidelity for project
I4. terate from low to high fidelity prototyping
5. Create reusable prototypes.

### FSE 1.5.7. Challenge Project: Build a Website Design System
#### Objective > Web Development Foundations > Challenge Project: Build a Website Design System
Overview
This project is slightly different than others you have encountered thus far on Codecademy. Instead of a step-by-step tutorial, this project contains a series of open-ended requirements which describe the project you’ll be building. There are many possible ways to correctly fulfill all of these requirements, and you should expect to use the internet, Codecademy, and other resources when you encounter a problem that you cannot easily solve.

Project Goals
In this project, you’ll be building your own basic design system for a website. In essence, you’ll be building a website to help you build MORE websites in the future! On your site, you’ll collect all the colors, fonts, and some of the repeating styles.

Setup Instructions
If you choose to do this project on your computer instead of Codecademy, you can download what you’ll need by clicking the “Download” button below. If you need help setting up your computer, read our article about setting up a text editor for HTML/CSS development.

Download
Tasks
1/7 complete
Mark the tasks as complete by checking them off
Prerequisites
1.
To complete this project, you should have completed the Codecademy lessons covering the CSS box model, display and positioning, colors, and typography. You can use more advanced CSS layout concepts like flexbox, CSS grid, or responsive design, but they won’t be required.

Project Requirements
2.
In this project, you’ll build a style guide/design system for your website. Developers and designers use design systems in order to organize the look and feel of a website or web application. Design systems help to document the visual vocabulary and reusable components of a large website.

As your websites grow larger and more complex, having a consistent set of styles will help them stay cohesive and enjoyable for users! It also helps as you start working with other developers, as you can have a consistent reference for how your website should be built.

Your style guide/design system will include at least a section on colors, fonts, and specific text styles, but it can be extended to as many other areas as you’d like. You can take a look at our basic example site for a taste of what you’ll be building (yours will be customized).

3.
Your style guide should include a labeled section outlining the colors to be used.

Each color should have:

A name (you can come up with this name yourself)
A box displaying the color itself.
The CSS value used to create the color (in hex, rgb(), rgba(), hsl(), or hsla()).
An optional description of how you intend to use the colors.
4.
Your style should include a labeled section of the fonts to be used (we recommend importing fonts from Google Fonts).

For each font, the goal is to to demonstrate the various styles that you intend to use (font weight, style, size, and text decorations). To do this, you should include the following for every font:

The font name
A series of styles that you intend to use (for example, styles could include: plain, bold and italic, underlined).
For each style, include a sentence or series of words to demonstrate the text style (our example site uses the quick brown fox…).
Make sure to display each of the sections in the proper font, size, and style.

5.
In addition to the list of possible fonts, your style guide should include a section for specific text styles for page elements. For example, you could set main heading (<h1>) guidelines about text size, fonts, font styles, font weight, and more.

Include at least 3 element styles, and ideally as many as you’d like to use in future sites.

For each page element, include:

A page element name (for example, “Subheading”).
All style rules (for example, font-weight: 700).
6.
Add any additional styles that you’d like to include to make your style guide/design system look great. This could include positioning, layout, additional colors, box model properties, and more.

If you’d like some inspiration, you can look to the following samples:

Salesforce’s Lightning Design System
Google’s Material Design
Twitter’s Bootstrap.
Solution and Extensions
7.
Great work! Visit our forums to compare your project to our sample solution code. You can also learn how to host your own solution on GitHub so you can share it with other learners! Your solution might look different from ours, and that’s okay! There are multiple ways to solve these projects, and you’ll learn more by seeing others’ code.

If you’d like to extend your site, consider:

Adding additional components (you could document the various buttons that you’d like to use).
Learning how and then implementing a responsive design so that your site looks great on all screen sizes.
Adding navigation and splitting up your site so that each section has its own HTML page.

### FSE 1.5.8. Review, Improved Styling with CSS 
#### Review: Improved Styling with CSS
In this unit, you learned more about styling web pages with CSS and navigation design.

Congratulations! The goal of this unit was to introduce more intermediate topics in CSS styles. You also learned more about navigation design.

Having completed this unit, you are now able to:

Apply more custom colors and fonts
Style navigation elements like links and buttons
Create secondary (breadcrumb) navigation
If you are interested in learning more about these topics, here are some additional resources:
Book: HTML & CSS, Jon Duckett, Chapters 11 (pp. 246-262) and 12 (pp. 264-298)
https://archive.org/details/htmlandcss/page/246/mode/1up
