FSE 1 Web Development Foundations
Get started with the foundations. By the end of this section, you'll be able to build a stylized and responsive website with HTML and CSS

FSE 1.1 Web Dev - Fundamentals of HTML
FSE 1.2 Web Dev - Fundamentals of CSS
FSE 1.3 Web Dev - Developing Websites Locally
FSE 1.4 Web Dev - Deploying Websites
FSE 1.5 Web Dev - Improved Styling with CSS
> FSE 1.6 Web Dev - Making a Website Responsive
FSE 1.x Web Dev - Review, Web Development Foundations
Certification exam, Objective assessments 1 and 2

FSE 1.6 Web Dev - Making a Website Responsive

Certificate :  Full-Stack Engineer
Course       :  Web Development Foundations
Lesson       :  Making a Website Responsive
Unit            :  Exercise/Quiz/Material/Project/Forum/Comment
Purpose     :  Learn how to utilize responsive web design practices using CSS grid, flexbox, and media queries

FSE 1.6.0. Introduction, Making a Website Responsive
FSE 1.6.1. Learn Responsive Design: Grids and Spacing
* Grids and Spacing
FSE 1.6.2. Layout with Flexbox
* Flexbox
* Flexbox To-Do App
* Off-Platform Project, Tea Cozy
FSE 1.6.3. Learn CSS Grid
* Grid Essentials
* Grid
* Advanced CSS Grid
* Grid
* PupSpa
* CSS Grid, Task Board
FSE 1.6.4. Learn Responsive Design
FSE 1.6.5. Learn CSS, Documentation and Debugging
* Documentation and Research
* Off-Platform Project, Fotomatic
FSE 1.6.6. Challenge Project, Company Home Page
FSE 1.6.7. Challenge Project, Responsive Club Website
FSE 1.6.8. Review, Making a Website Responsive

---

### FSE 1.6.0. Introduction, Making a Website Responsive
#### Introduction: Making a Website Responsive
In this unit, you will utilize responsive web design practices.

The goal of this unit is to utilize responsive web design practices. You will learn how to create websites that can be viewed on a variety of devices and use different layouts and positioning.

After this unit, you will be able to:
* Understand responsive web design
* Use CSS Grid and Flexbox for layout, positioning, and responsiveness
* Use media queries

You will put all of this knowledge into practice with an upcoming Challenge Project. You can complete the Challenge Project either in parallel with or after taking the prerequisite content—it’s up to you!

Learning is social. Whatever you’re working on, be sure to connect with the Codecademy community in the forums. Remember to check in with the community regularly, including for things like asking for code reviews on your project work and providing code reviews to others in the projects category, which can help to reinforce what you’ve learned.

#### Learn > Grids and Spacing > Grid Types
1 min
Various types of grids exist and are used within all types of visual design. With the creation of the printing press, bookmakers developed a manuscript-style grid, or a block grid, to bring structure to text on pages. Within news design, the column grid allowed publishers to break the page apart into sections to emphasize different pieces of content.

Similar to news design, the most common type of grid a web designer will use is the column grid. The column grid breaks up a page into vertical units that span the width of the content, and this grid structure can dictate how elements are laid out with precision and elegance.

Let’s continue to explore the anatomy of a grid and what it comprises.

#### Learn > Grids and Spacing > Grid Anatomy
2 min
When designing a website, the grid comprises three major components: columns, gutters, and margins.

Columns are defined as the vertical sections that span the width of a page. In web design, it’s common to see layouts consisting of 12 or 16 columns, while other may only feature three columns. Defining the number of columns depends on what’s appropriate for your design, device, and or screen viewing size.

Next, a gutter is the negative space between each column. Gutters help in ensuring the columns don’t run together, which would negate the purpose of using a column-based grid.

Margins appear on the left and right sides of the column-based grid. These ensure the content of your designs doesn’t match up to the edges of the browser window.

It’s important to note, margins may vary depending on the width of the grid, browser window, or device. For larger displays, margins may be very noticeable while on smaller screens, they may have the same width as a gutter.

#### Learn > Grids and Spacing > Grid Columns
2 min
Columns are the vertical containers that span the width of the page. They can be dependent on each other, meaning they are used to organize related content such as a continuation of a paragraph. They can also be independent of each other, meaning they are used for organizing the layout of unrelated content such as a sidebar. This allows for the flexibility of organizing information.

Within a grid, content can span multiple columns. What this means is that a website does not need to maintain the same column layout throughout. For example, a section of a website with a 12 column grid can have content that spans 4 columns, three times.

As the designer, you have the option to maintain this layout throughout the website. Or you can choose to use various layouts, including having the content span the whole width of the grid, half the grid or only a small portion of the grid.

While we will talk about this in more detail in just a few exercises, columns are separated by gutters. This design term is referred to as the space or gap between two columns. No content can spill into the gutter unless it is using the next column.

Columns can also be used to push, or offset content. Say you want to only display content on the right 4 columns of a page while using a 12 column grid. To do this, you can easily offset the content by 8 columns so the content is pushed to those right 4 columns.

#### Learn > Grids and Spacing > Grid Rows
2 min
Rows are the horizontal lines on a grid. 

> Think of rows as invisible boxes that group content together by height. Rows are commonly used in web designs to group content together and re-order other content to allow for more whitespace.

> For example, let’s say you have a set of items that all span the same amount of columns and you want them to align across the page without being disrupted by other elements. One way to achieve this outcome is to wrap the content in a row component. This will force any content, not inside of the row, to be pushed away.

> Again, remember that a row can be used to force content away from an area that has remaining columns not used. What does this mean? Great question.

> Let’s say our design uses a 12 column grid and we want one element to span seven columns. That means we still have five unfilled columns to either the left or the right side. Naturally, any new content added to our document will try and fill this unused space. However, by placing a row element around our component that spans 7 columns we can force any new content to start beneath our component and leave the remaining 5 columns empty.

#### Learn > Grids and Spacing > Grid Gutters
1 min
Gutters make up the negative space between columns. This design element helps to provide a natural break between elements aligned horizontally, while also helping to break rows of content vertically.

Note, there will always be one less gutter than the total number of columns. For example, if you are designing on a 12 column grid, then you will only have 11 gutters, one for every gap that separates each column.

While there is no set standard for a gutter width, it’s best practice to select a size that visually separates horizontal columns but is significantly thinner than the width of a column. The same can be said for vertical gutters.

Moreover, vertical and horizontal gutters do not need to match in size for a given grid layout. This is because you as a designer may want more vertical spacing than horizontal spacing when separating elements on a page.

> Remember, if the gutter space is too tight, it can be hard to visually tell where one element ends and another starts. On the other hand, if the gutter space is too large, the design can be hard to follow.

#### Learn > Grids and Spacing > Responsive Grid
2 min
When designing web content, a designer needs to take into account the different screen-sizes a user might encounter and how that will affect a website’s layout. Many websites utilize responsive design, a set of techniques that allow a website’s content to shift based on the device or screen size. Because of these changes, responsive design requires a different number of total columns based on screen size, in order to accommodate content and keep it from being squished.

Consider your mobile, tablet and desktop devices. Now, think about their viewable areas. All are substantially different in size. Thus, it’s common practice in web design to create responsive grid sizes. On a large or desktop device you may start with a 12 column grid, but on a small or mobile device, you adjust the 12 column grid to a 4 column grid.

As a designer, responsive grid design enables you to maximize the content on the screen, ensuring a more accessible experience for users. Additionally, your design elements will have sufficient space to breathe and content can naturally flow across the page.

### FSE 1.6.1. Learn Responsive Design: Grids and Spacing
#### Learn > Grids and Spacing > Responsive Grid
2 min
When designing web content, a designer needs to take into account the different screen-sizes a user might encounter and how that will affect a website’s layout. Many websites utilize responsive design, a set of techniques that allow a website’s content to shift based on the device or screen size. Because of these changes, responsive design requires a different number of total columns based on screen size, in order to accommodate content and keep it from being squished.

Consider your mobile, tablet and desktop devices. Now, think about their viewable areas. All are substantially different in size. Thus, it’s common practice in web design to create responsive grid sizes. On a large or desktop device you may start with a 12 column grid, but on a small or mobile device, you adjust the 12 column grid to a 4 column grid.

As a designer, responsive grid design enables you to maximize the content on the screen, ensuring a more accessible experience for users. Additionally, your design elements will have sufficient space to breathe and content can naturally flow across the page.

#### Learn > Grids and Spacing > Whitespace 
1 min
Space is an important aspect of creating balanced and harmonious layouts in web design. As a designer, it’s important to understand how space can enhance as well as hurt your designs.

Whitespace, or negative space, refers to the emptiness between elements, whether that’s in the gutter of the columns, or additional padding around a block of text. As a designer, don’t be afraid of using space to enhance the usability of your site and prioritize the content.

Let’s explore some examples of good whitespace. If you look at the examples in the workspace, you will notice that the website on the left embraces whitespace on its landing page. It focuses the user’s attention solely on the primary action, which is searching for content. In this case, the whitespace is white in color as well. However, whitespace isn’t always going to be white.

In the example on the right, you’ll notice that too much whitespace can negatively impact the flow of your site. By including too much spacing in between elements, it can cause issues for users trying to navigate seamlessly through the content.

Whitespace is broken up into passive and active, which we’ll explore in the next two exercises!

#### Learn > Grids and Spacing > Passive Whitespace
2 min
The first type of whitespace we will discuss is called passive whitespace or micro whitespace. Used to improve the aesthetics of the layout without guiding the user through a specific reading, flow, or content order; 
> passive whitespace is sometimes referred to as the unconsidered space. The most frequent use of passive whitespace comes within text elements.

> Different font families have varying amounts of passive whitespace and you can control aspects of them within your design by altering CSS properties such as line-height or margin when setting type.

By adjusting the space between your lines of text, you can improve the design’s overall legibility and balance.

If a site’s text is too tight or lacks sufficient margin below headings and paragraphs, it can be hard for users to consume the content. However, if the site’s text is too spaced out, it can make it just as hard to read.

Finding a healthy balance between text that lacks sufficient spacing and text that has too much is an important task for designers.

#### Learn > Grids and Spacing > Active Whitespace
1 min
> Unlike passive whitespace, which occurs more naturally, active whitespace is intentional. Also called macro whitespace, active whitespace refers to enhancing the overall page structure through space to emphasize content or guide users from one point to the next.

> By adding active whitespace to a site’s design, we can spread our different sections out. This technique helps guide the user through the page’s content more effectively, allowing users to consume and absorb content more easily.

> Active whitespace comes in many forms. But traditionally, it is achieved by adding space between a site’s elements. For instance, adding space to an article’s sidebar helps to visually separate the content from the page’s main content.

Additionally, this type of whitespace allows readers to quickly understand what they should be focusing on versus what is just supplementary details.

#### Learn > Grids and Spacing > Review
<1 min
Congratulations! You should have an understanding of grid structure, the components that make up a grid, and how to use them to properly space elements within your design.

Remember, the reasons we design using grids are:
* Promote consistency within our designs
* Properly align elements on our page
* Provide ample spacing between content

Remember a grid is made up of:
* Columns
* Gutters
* Margins

Spacing is incredibly important within a design to ensure:
* Elements have ample room to breathe
* Denote emphasis on certain parts of a page
* Promote harmonious patterns and rhythms within your designs

Following these guidelines will allow you to create elegant and usable sites!

### FSE 1.6.2. Layout with Flexbox
#### Learn > Flexbox > What is Flexbox?
2 min
CSS provides many tools and properties that you can use to position elements on a webpage. Codecademy’s lessons on the box model and CSS display introduce a couple of these techniques.

In this lesson, you will learn about Flexible Box Layout or flexbox, a tool that greatly simplifies how to position elements.

> There are two important components to a flexbox layout: flex containers and flex items. A flex container is an element on a page that contains flex items. All direct child elements of a flex container are flex items. This distinction is important because some of the properties you will learn in this lesson apply to flex containers while others apply to flex items.

To designate an element as a flex container, set the element’s `display` property to `flex` or `inline-flex`. Once an item is a flex container, there are several properties we can use to specify how its children behave. In this lesson we will cover these properties:

* `justify-content`
* `align-items`
* `flex-grow`
* `flex-shrink`
* `flex-basis`
* `flex`
* `flex-wrap`
* `align-content`
* `flex-direction`
* `flex-flow`

Flexbox is an elegant tool that makes it easy to address positioning issues that may have been difficult before. Let’s get started!

#### Learn > Flexbox > display: flex
4 min
> Any element can be a flex container. Flex containers are helpful tools for creating websites that respond to changes in screen sizes. Child elements of flex containers will change size and location in response to the size and position of their parent container.

For an element to become a flex container, its display property must be set to flex.
```
div.container {
  display: flex;
}
```
> In the example above, all divs with the class container are flex containers. If they have children, the children are flex items. A div with the declaration display: flex; will remain block level — no other elements will appear on the same line as it.

> However, it will change the behavior of its child elements. Child elements will not begin on new lines. In the exercises that follow, we will cover how the flex display property impacts the positioning of child elements.
```
display: flex;  <!-- default styles -->
flex-direction: row;
justify-content: flex-start;
flex-shrink: 1;
align-items: stretch;
flex-basis: auto;
flex-wrap: nowrap;
```

#### Learn > Flexbox > inline-flex
5 min
In the previous exercise, you might have observed that when we gave a div — a block level element — the display value of flex that it remained a block level element. What if we want multiple flex containers to display inline with each other?

If we didn’t want div elements to be block-level elements, we would use display: inline. 

> Flexbox, however, provides the inline-flex value for the display property, which allows us to create flex containers that are also inline elements.
```
<div class='container'>
  <p>I’m inside of a flex container!</p>
  <p>A flex container’s children are flex items!</p>
</div>
<div class='container'>
  <p>I’m also a flex item!</p>
  <p>Me too!</p>
</div>

.container {
  width: 200px;
  height: 200px;
  display: inline-flex;
}
```
> In the example above, there are two container divs. Without a width, each div would stretch the entire width of the page. The paragraphs within each div would also display on top of each other because paragraphs are block-level elements.

> When we change the value of the display property to inline-flex, the divs will display inline with each other if the page is wide enough. As we progress through this lesson, we will cover in more detail how flex items are displayed.

> Notice that in the example above, the size of the flex container is set. Currently, the size of the parent container will override the size of its child elements. If the parent element is too small, the flex items will shrink to accommodate the parent container’s size. We’ll explain why in a later exercise.

```
<div class='container'>
  <div class='child'>
    <h1>1</h1>
  </div>
  <div class='child'>
    <h1>2</h1>
  </div>
</div>

.container {
  width: 200px;
}

.child {
  display: inline-flex;
  width: 150px;
  height: auto;
}
```
In the example above, the .child divs will take up more width (300 pixels) than the container div allows (200 pixels). The .child divs will shrink to accommodate the container’s size. In later exercises, we will explore several ways to handle this.

#### Learn > Flexbox > justify-content
8 min
In previous exercises, when we changed the display value of parent containers to flex or inline-flex, all of the child elements (flex items) moved toward the upper left corner of the parent container. This is the default behavior of flex containers and their children. We can specify how flex items spread out from left to right, along the main axis. We will learn more about axes in a later exercise.

To position the items from left to right, we use a property called justify-content.
```
.container {
  display: flex;
  justify-content: flex-end;
}
```
In the example above, we set the value of justify-content to flex-end. This will cause all of the flex items to shift to the right side of the flex container.

Below are five commonly used values for the justify-content property:
* flex-start — all items will be positioned in order, starting from the left of the parent container, with no extra space between or before them.
* flex-end — all items will be positioned in order, with the last item starting on the right side of the parent container, with no extra space between or after them.
* center — all items will be positioned in order, in the center of the parent container with no extra space before, between, or after them.
* space-around — items will be positioned with equal space before and after each item, resulting in double the space between elements.
* space-between — items will be positioned with equal space between them, but no extra space before the first or after the last elements.

In the definitions above, “no extra space” means that margins and borders will be respected, but no more space (than is specified in the style rule for the particular element) will be added between elements. The size of each individual flex item is not changed by this property.

#### Codecademy Forums
Can I use margin: auto; on a flex item that is being positioned with justify-content declared on its parent flex container?

Answer
Yes! When using margin/margin-top/margin-right/margin-bottom/margin-left: auto; on a flex item we can easily position our flex item to one side of its parent flex container:

#### Learn > Flexbox > flex-grow
8 min
In Exercise 3, we learned that all flex items shrink proportionally when the flex container is too small. However, if the parent container is larger than necessary then the flex items will not stretch by default. The flex-grow property allows us to specify if items should grow to fill a container and also which items should grow proportionally more or less than others.
```
<div class='container'>
  <div class='side'>
    <h1>I’m on the side of the flex container!</h1>
  </div>
  <div class='center'>
    <h1>I'm in the center of the flex container!</h1>
  </div>
  <div class='side'>
    <h1>I'm on the other side of the flex container!</h1>
  </div>
</div>

.container {
  display: flex;
}

.side {
  width: 100px;
  flex-grow: 1;
}

.center {
  width: 100px;
  flex-grow: 2;
}
```
In the example above, the .container div has a display value of flex, so its three child divs will be positioned next to each other. If there is additional space in the .container div (in this case, if it is wider than 300 pixels), the flex items will grow to fill it. The .center div will stretch twice as much as the .side divs. For example, if there were 60 additional pixels of space, the center div would absorb 30 pixels and the side divs would absorb 15 pixels each.

If a max-width is set for an element, it will not grow larger than that even if there is more space for it to absorb.

All of the previous properties we have learned are declared on flex containers, or the parent elements. This property — flex-grow — is the first we have learned that is declared on flex items.

#### Codecademy Forum

I’ll add that the flex-grow value is only relevant in relation to other flex-items that have a flex-grow value defined. Having it defined means that particular child will consume the excess space if present within the parent, but if there are no other flex-child elements with a flex-grow value, it wouldn’t matter if the value was 1 or 100; it would behave the same.

Also, decimal values work as proportions

#### Learn > Flexbox > flex-shrink
6 min
Just as the flex-grow property proportionally stretches flex items, the flex-shrink property can be used to specify which elements will shrink and in what proportions.

> You may have noticed in earlier exercises that flex items shrank when the flex container was too small, even though we had not declared the property. This is because the default value of flex-shrink is 1. However, flex items do not grow unless the flex-grow property is declared because the default value of flex-grow is 0.

```
<div class='container'>
  <div class='side'>
    <h1>I'm on the side of the flex container!</h1>
  </div>
  <div class='center'>
    <h1>I'm in the center of the flex container!</h1>
  </div>
  <div class='side'>
    <h1>I'm on the other side of the flex container!</h1>
  </div>
</div>

.container {
  display: flex;
}

.side {
  width: 100px;
  flex-shrink: 1;
}

.center {
  width: 100px;
  flex-shrink: 2;
}
```

In the example above, the .center div will shrink twice as much as the .side divs if the .container div is too small to fit the elements within it. If the content is 60 pixels too large for the flex container that surrounds it, the .center div will shrink by 30 pixels and the outer divs will shrink by 15 pixels each. Margins are unaffected by flex-grow and flex-shrink.

Keep in mind, minimum and maximum widths will take precedence over flex-grow and flex-shrink. As with flex-grow, flex-shrink will only be employed if the parent container is too small or the browser is adjusted.

#### Codecademy Forums

Both flexboxes and media queries are elements of responsive web design. So, I don’t think these concepts should be viewed as opposing concepts.

From what I’ve seen in practice, media queries are defined for breakpoints and those are where a device’s screen size usually demands a different visual appearance of the website in order to keep delivering an adequate ux. If a flexbox design lives up to those demands because all visual elements grow, shrink and wrap accordingly, so be it. But I wouldn’t rule out the use of media queries because of it as you might want to replace a navbar with a hamburger menu as the screen size shrinks etc.

#### Learn > Flexbox > flex-basis
8 min
In the previous two exercises, the dimensions of the divs were determined by heights and widths set with CSS. Another way of specifying the width of a flex item is with the flex-basis property. flex-basis allows us to specify the width of an item before it stretches or shrinks.
```
<div class='container'>
  <div class='side'>
    <h1>Left side!</h1>
  </div>
  <div class='center'>
    <h1>Center!</h1>
  </div>
  <div class='side'>
    <h1>Right side!</h1>
  </div>
</div>

.container {
  display: flex;
}

.side {
  flex-grow: 1;
  flex-basis: 100px;
}

.center {
  flex-grow: 2;
  flex-basis: 150px;
}
```
In the example above, the .side divs will be 100 pixels wide and the .center div will be 150 pixels wide if the .container div has just the right amount of space (350 pixels, plus a little extra for margins and borders). If the .container div is larger, the .center div will absorb twice as much space as the .side divs.

The same would hold true if we assigned flex-shrink values to the divs above as well.

#### Codecademy Forum 

Question
Is flex-basis the same as setting width?

Answer
It’s not! We can think of flex-basis as the width OR height (depending on flex-direction) of our flex items before they are constrained by a flex container.

Also, a few notes about using flex-basis and width/height:

* flex-basis is limited by both max-width/max-height and min-width/min-height
* When declared, flex-basis will override the width/height property set on a flex container
* If no flex-basis is specified the default is the set width/height value, if width/height isn’t specified the default is the width/height of the content
* When there is not enough space for our flex items our items will shrink at an even rate to fit within the container by default
* If there is too much space we can declare flex-grow: 1; on our flex items to make them grow at an even rate

#### Learn > Flexbox > flex
7 min
The shorthand flex property provides a convenient way for specifying how elements stretch and shrink, while simplifying the CSS required. The flex property allows you to declare flex-grow, flex-shrink, and flex-basis all in one line.
```
.big {
  flex-grow: 2;
  flex-shrink: 1;
  flex-basis: 150px;
}

.small {
  flex-grow: 1;
  flex-shrink: 2;
  flex-basis: 100px;
}
```
In the example above, all elements with class big will grow twice as much as elements with class small. Keep in mind, this doesn’t mean big items will be twice as big as small items, they’ll just take up more of the extra space.

The CSS below declares these three properties in one line.
```
.big {
  flex: 2 1 150px;
}

.small {
  flex: 1 2 100px;
}
```
In the example above, we use the flex property to declare the values for flex-grow, flex-shrink, and flex-basis (in that order) all in one line.
```
.big {
 flex: 2 1;
}
```
In the example above, we use the flex property to declare flex-grow and flex-shrink, but not flex-basis.
```
.small {
  flex: 1 20px;
}
```
In the example above, we use the flex property to declare flex-grow and flex-basis. Note that there is no way to set only flex-shrink and flex-basis using 2 values.

The browser to the right has two flex containers, each with three flex items. In style.css, examine the values for each of these items. Notice that the flex-grow and flex-basis values are set for the blue divs.

Stretch the browser window to increase its width. Observe that once the top outer divs reach 100 pixels wide, they begin to grow faster than the top center div. Also notice that once the bottom center div reaches 100 pixels wide, it begins to grow faster than the outer divs.

Now, shrink the browser window and notice that once the top center div reaches 50 pixels wide it begins to shrink faster than the outer divs and when the bottom outer divs reach 75 pixels, they begin to shrink faster than the center div.

#### Learn > Flexbox > flex-wrap
7 min
[](https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-web-development-foundations/tracks/fscj-22-making-a-website-responsive/modules/wdcp-22-layout-with-flexbox-8a62abed-21fe-442a-8d4d-2b84f3d4ee3a/lessons/learn-flexbox/exercises/flex-wrap)

Sometimes, we don’t want our content to shrink to fit its container. Instead, we might want flex items to move to the next line when necessary. This can be declared with the flex-wrap property. The flex-wrap property can accept three values:

1. wrap — child elements of a flex container that don’t fit into a row will move down to the next line
2. wrap-reverse — the same functionality as wrap, but the order of rows within a flex container is reversed (for example, in a 2-row flexbox, the first row from a wrap container will become the second in wrap-reverse and the second row from the wrap container will become the first in wrap-reverse)
3. nowrap — prevents items from wrapping; this is the default value and is only necessary to override a wrap value set by a different CSS rule.
```
<div class='container'>
  <div class='item'>
    <h1>We're going to wrap!</h1>
  </div>
  <div class='item'>
    <h1>We're going to wrap!</h1>
  </div>
  <div class='item'>
    <h1>We're going to wrap!</h1>
  </div>
</div>

.container {
  display: inline-flex;
  flex-wrap: wrap;
  width: 250px;
}

.item {
  width: 100px;
  height: 100px;
}
```
In the example above, three flex items are contained by a parent flex container. The flex container is only 250 pixels wide so the three 100 pixel wide flex items cannot fit inline. The flex-wrap: wrap; setting causes the third, overflowing item to appear on a new line, below the other two items.

Note: The flex-wrap property is declared on flex containers.

#### Codecademy Forums
Question
Can we use flex-wrap and flex-shrink on the same flex container?

Answer
We can use flex-wrap and flex-shrink on the same container, flex-wrap does not negate the use of flex-shrink. Take for example an instance where our content would otherwise overflow our container:

#### Learn > Flexbox > align-content
8 min
Now that elements can wrap to the next line, we might have multiple rows of flex items within the same container. In a previous exercise, we used the align-items property to space flex items from the top to the bottom of a flex container. align-items is for aligning elements within a single row. If a flex container has multiple rows of content, we can use align-content to space the rows from top to bottom.

Below are some of the more commonly used align-content values:

* `flex-start` — all rows of elements will be positioned at the top of the parent container with no extra space between.
* `flex-end` — all rows of elements will be positioned at the bottom of the parent container with no extra space between.
* `center` — all rows of elements will be positioned at the center of the parent element with no extra space between.
* `space-between` — all rows of elements will be spaced evenly from the top to the bottom of the container with no space above the first or below the last.
* `space-around` — all rows of elements will be spaced evenly from the top to the bottom of the container with the same amount of space at the top and bottom and between each element.
* `stretch` — if a minimum height or no height is specified, the rows of elements will stretch to fill the parent container from top to bottom (default value).
```
<div class='container'>
  <div class='child'>
    <h1>1</h1>
  </div>
  <div class='child'>
    <h1>2</h1>
  </div>
  <div class='child'>
    <h1>3</h1>
  </div>
  <div class='child'>
    <h1>4</h1>
  </div>
</div>

.container {
  display: flex;
  width: 400px;
  height: 400px;
  flex-wrap: wrap;
  align-content: space-around;
}

.child {
  width: 150px;
  height: 150px;
}
```
In the example above, there are four flex items inside of a flex container. The flex items are set to be 150 pixels wide each, but the parent container is only 400 pixels wide. This means that no more than two elements can be displayed inline. The other two elements will wrap to the next line and there will be two rows of divs inside of the flex container. The align-content property is set to the value of space-around, which means the two rows of divs will be evenly spaced from top to bottom of the parent container with equal space before the first row and after the second, with double space between the rows.

Below, we will see each of the properties in action!

Note: The align-content property is declared on flex containers.

#### Codecademy Forums

Question
Does align-content override the vertical/horizontal margins on flex items?

Answer
No, just like justify-content, align-content will respect margins!

#### Learn > Flexbox > flex-direction
9 min
Up to this point, we’ve only covered flex items that stretch and shrink horizontally and wrap vertically. As previously stated, flex containers have two axes: a main axis and a cross axis. By default, the main axis is horizontal and the cross axis is vertical.

> The main axis is used to position flex items with the following properties:
1. `justify-content`
2. `flex-wrap`
3. `flex-grow`
4. `flex-shrink`

> The cross axis is used to position flex items with the following properties:
1. `align-items`
2. `align-content`

The main axis and cross axis are interchangeable. We can switch them using the flex-direction property. If we add the flex-direction property and give it a value of column, the flex items will be ordered vertically, not horizontally.
```
<div class='container'>
  <div class='item'>
    <h1>1</h1>
  </div>
  <div class='item'>
    <h1>2</h1>
  </div>
  <div class='item'>
    <h1>3</h1>
  </div>
  <div class='item'>
    <h1>4</h1>
  </div>
  <div class="item">
    <h1>5</h1>
  </div>
</div>

.container {
  display: flex;
  flex-direction: column;
  width: 1000px;
}

.item {
  height: 100px;
  width: 100px;
}
```
In the example above, the five divs will be positioned in a vertical column. All of these divs could fit in one horizontal row. However, the `column` value tells the browser to stack the divs one on top of the other. As explained above, properties like `justify-content` will not behave the way they did in previous examples.

The `flex-direction` property can accept four values:

1. `row` — elements will be positioned from left to right across the parent element starting from the top left corner (default).
2. `row-reverse` — elements will be positioned from right to left across the parent element starting from the top right corner.
3. `column` — elements will be positioned from top to bottom of the parent element starting from the top left corner.
4. `column-reverse` — elements will be positioned from the bottom to the top of the parent element starting from the bottom left corner.
Below, we’ll investigate how these work.

Note: The `flex-direction` property is declared on flex containers.

#### MDN Flexbox
[MDN Flexbox, or CSS flexible box layout module] {https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout)
The flexible box layout module (usually referred to as flexbox) is a one-dimensional layout model for distributing space between items and includes numerous alignment capabilities. When we describe flexbox as being one-dimensional we are describing that flexbox deals with layout in one dimension at a time — either as a row or as a column. This can be contrasted with the two-dimensional model of CSS Grid Layout, which controls columns and rows together.

#### Learn > Flexbox > flex-flow
3 min
Like the shorthand flex property, the shorthand flex-flow property is used to declare both the flex-wrap and flex-direction properties in one line.
```
.container {
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
}
```
In the example above, we take two lines to accomplish what can be done with one.
```
.container {
  display: flex;
  flex-flow: column wrap;
}
```
In the example above, the first value in the flex-flow declaration is a flex-direction value and the second is a flex-wrap value. All values for flex-direction and flex-wrap are accepted.

#### Codecademy Forums
While flex-flow can be used with single values, or values in any order, the standard order is flex-direction flex-wrap.

#### Learn > Flexbox > Nested Flexboxes
7 min
So far, we’ve had multiple flex containers on the same page to explore flex item positioning. It is also possible to position flex containers inside of one another.
```
<div class='container'>
  <div class='left'>
    <img class='small' src='#'/>
    <img class='small' src='#'/>
    <img class='small' src='#' />
  </div>
  <div class='right'>
    <img class='large' src='#' />
  </div>
</div>

.container {
  display: flex;
  justify-content: center;
  align-items: center;
}

.left {
  display: inline-flex;
  flex: 2 1 200px;
  flex-direction: column;
}

.right {
  display: inline-flex;
  flex: 1 2 400px;
  align-items: center;
}

.small {
  height: 200px;
  width: auto;
}

.large {
  height: 600px; 
  width: auto;
}
```
In the example above, a div with three smaller images will display from top to bottom on the left of the page (.left). There is also a div with one large image that will display on the right side of the page (.right). The left div has a smaller flex-basis but stretches to fill more extra space; the right div has a larger flex-basis but stretches to fill less extra space. Both divs are flex items and flex containers. The items have properties that dictate how they will be positioned in the parent container and how their flex item children will be positioned in them.

#### Learn
Flexbox
Review: Flexbox
6 min
You should be proud of yourself! You have learned the most important properties of flexbox. Flexbox is an art and a science; you can use it to make laying out multiple elements a piece of cake. You know everything necessary to begin using it in your own projects.

* `display: flex` changes an element to a block-level container with flex items inside of it.
* `display: inline-flex` allows multiple flex containers to appear inline with each other.
* `justify-content` is used to space items along the main axis.
* `align-items` is used to space items along the cross axis.
* `flex-grow` is used to specify how much space (and in what proportions) flex items absorb along the main axis.
* `flex-shrink` is used to specify how much flex items shrink and in what proportions along the main axis.
* `flex-basis` is used to specify the initial size of an element styled with flex-grow and/or flex-shrink.
* `flex` is used to specify flex-grow, flex-shrink, and flex-basis in one declaration.
* `flex-wrap` specifies that elements should shift along the cross axis if the flex container is not large enough.
* `align-content` is used to space rows along the cross axis.
* `flex-direction` is used to specify the main and cross axes.
* `flex-flow` is used to specify `flex-wrap` and `flex-direction` in one declaration.
* Flex containers can be nested inside of each other by declaring `display: flex` or `display: inline-flex` for children of flex containers.

> The align-items property is used to space flex items on the cross axis. We use justify-content to position them on the main axis.
> Both align-items and align-content align items vertically, but the key difference is that the align-items property is used to align items within a single row, whereas the align-content property is used for multiple rows.
> Based on the code below where #container is a flex container and .box are its flex items, what can we assume about the width of the .box elements?
```
div#container {
   display: flex;
}
.box {
   width: 300px;
}
```
Given sufficient space, the width of flex elements will be declared width, otherwise they will shrink to fit the screen. 
> The align-items property is used to align items within a single row, whereas the align-content property is used to align multiple rows.
> Which three values do the justify-content and align-items properties share?
flex-start, flex-end, center
Also, flex-center is not a valid value for either justify-content or align-items.

> If there are only two values after `flex:`, they are for grow and shrink; basis is not declared. 

#### 

### To Do or Not To Do app 
#### Flexbox: To-Do App > Set the Flexbox properties for a to-do app.

#### Objective > Web Development Foundations > Flexbox: To-Do App
In this project, you will follow step-by-step instructions to fix a to-do web app. All of the HTML and most of the CSS is intact, however, a few Flexbox values are missing.

In order to complete this project, you must know how to set an element’s Flexbox properties.

We recommend that you review our Flexbox Lesson before beginning.

The website’s existing index.html and style.css files are displayed in the text editor to the right. Good luck!

### Off-Platform Project, Tea Cozy
#### Objective > Web Development Foundations > Off-Platform Project: Tea Cozy
In this project, you will create a fictional tea shop website on your own computer.

We will provide a design spec and image assets to help you along the way. A design spec is an image of a web page outlined with all of its CSS properties and values. These are usually created by a designer as a source of instructions for a web developer. This project assumes that you will be able to reproduce the basic HTML and CSS with little guidance.

The images and design spec you need to complete the project are listed below.

Images:
* Logo
* Bedford Bizarre
* Berry Blitz
* Donut
* Locations
* Background
* Myrtle Ave
* Spiced Rum
* Design Spec:

Click here to access the design spec.
![Good luck!](https://content.codecademy.com/courses/freelance-1/unit-4/img-tea-cozy-redline.jpg)

### FSE 1.6.3. Learn CSS Grid
#### Learn > Grid Essentials > Creating a Grid
4 min
To set up a grid, you need to have both a grid container and grid items. The grid container will be a parent element that contains grid items as children and applies overarching styling and positioning to them.

To turn an HTML element into a grid container, you must set the element’s display property to one of two values:

grid — for a block-level grid.
inline-grid — for an inline grid.
Then, you can assign other properties to lay out the grid to suit your needs.

#### Learn > Grid Essentials > Creating Columns
5 min
By default, grids contain only one column. If you were to start adding items, each item would be put on a new row; that’s not much of a grid! To change this, we need to explicitly define the number of rows and columns in our grid.

We can define the columns of our grid by using the CSS property grid-template-columns. Below is an example of this property in action:
```
.grid {
  display: grid;
  width: 500px;
  grid-template-columns: 100px 200px;
}
```
This property creates two changes. First, it defines the number of columns in the grid; in this case, there are two. Second, it sets the width of each column. The first column will be 100 pixels wide and the second column will be 200 pixels wide.

We can also define the size of our columns as a percentage of the entire grid’s width.
```
.grid {
  display: grid;
  width: 1000px;
  grid-template-columns: 20% 50%;
}
```
In this example, the grid is 1000 pixels wide. Therefore, the first column will be 200 pixels wide because it is set to be 20% of the grid’s width. The second column will be 500 pixels wide.

We can also mix and match these two units. In the example below, there are three columns of width 20 pixels, 40 percent, and 60 pixels:
```
.grid {
  display: grid;
  width: 100px;
  grid-template-columns: 20px 40% 60px;
}
```
Notice that in this example, the total width of our columns (120 pixels) exceeds the width of the grid (100 pixels). This might make our grid cover other elements on the page! In a later exercise, we will discuss how to avoid overflow.

#### Learn > Grid Essentials > Creating Rows
3 min
We’ve learned how to define the number of columns in our grid explicitly. To specify the number and size of the rows, we are going to use the property grid-template-rows.

This property is almost identical to grid-template-columns. Take a look at the code below to see both properties in action.
```
.grid {
  display: grid;
  width: 1000px;
  height: 500px;
  grid-template-columns: 100px 200px;
  grid-template-rows: 10% 20% 600px;
}
```
This grid has two columns and three rows. grid-template-rows defines the number of rows and sets each row’s height. In this example, the first row is 50 pixels tall (10% of 500), the second row is 100 pixels tall (20% of 500), and the third row is 600 pixels tall.

When using percentages in these two properties, remember that rows are defined as a percentage of the grid’s height, and columns are defined as a percentage of its width.

#### Learn > Grid Essentials > Grid Template
3 min
The shorthand property, grid-template, can replace the previous two CSS properties. Both grid-template-rows and grid-template-columns are nowhere to be found in the following code!
```
.grid {
  display: grid;
  width: 1000px;
  height: 500px;
  grid-template: 200px 300px / 20% 10% 70%;
}
```
When using grid-template, the values before the slash will determine the size of each row. The values after the slash determine the size of each column. In this example, we’ve made two rows and three columns of varying sizes.

The same rules from before apply; when using percentages to set rows, each row will be a percentage of the grid’s total height. Columns are still a percentage of the total width.

#### Learn > Grid Essentials > Fraction
6 min
You may already be familiar with several types of responsive units such as percentages (%), ems and rems. CSS Grid introduced a new relative sizing unit — fr, like fraction.

By using the fr unit, we can define the size of columns and rows as a fraction of the grid’s length and width. This unit was specifically created for use in CSS Grid. Using fr makes it easier to prevent grid items from overflowing the boundaries of the grid. Consider the code below:
```
.grid {
  display: grid;
  width: 1000px;
  height: 400px;
  grid-template: 2fr 1fr 1fr / 1fr 3fr 1fr;
}
```
In this example, the grid will have three rows and three columns. The rows are splitting up the available 400 pixels of height into four parts. The first row gets two of those parts, the second row gets one, and the third row gets one. Therefore the first row is 200 pixels tall, and the second and third rows are 100 pixels tall.

Each column’s width is a fraction of the available space. In this case, the available space is split into five parts. The first column gets one-fifth of the space, the second column gets three-fifths, and the last column gets one-fifth. Since the total width is 1000 pixels, this means that the columns will have widths of 200 pixels, 600 pixels, and 200 pixels respectively.

It is possible to use fr with other units as well. When this happens, each fr represents a fraction of the available space.
```
.grid {
  display: grid;
  width: 100px;
  grid-template-columns: 1fr 60px 1fr;
}
```
In this example, 60 pixels are taken up by the second column. Therefore the first and third columns have 40 available to split between them. Since each gets one fraction of the total, they both end up being 20 pixels wide.

#### Learn > Grid Essentials > Repeat
5 min
The properties that define the number of rows and columns in a grid can take a function as a value. repeat() is one of these functions. The repeat() function was created specifically for CSS Grid.
```
.grid {
  display: grid;
  width: 300px;
  grid-template-columns: repeat(3, 100px);
}
```
The repeat function will duplicate the specifications for rows or columns a given number of times. In the example above, using the repeat function will make the grid have three columns that are each 100 pixels wide. It is the same as writing:

grid-template-columns: 100px 100px 100px;

Repeat is particularly useful with fr. For example, repeat(5, 1fr) would split your table into five equal rows or columns.

Finally, the second parameter of repeat() can have multiple values.

grid-template-columns: repeat(2, 20px 50px)

This code will create four columns where the first and third columns will be 20 pixels wide and the second and fourth will be 50 pixels wide.

#### Learn > Grid Essentials > minmax
5 min
So far, all of the grids that we have worked with have been a fixed size. The grid in our example has been 400 pixels wide and 500 pixels tall. But sometimes you might want a grid to resize based on the size of your web browser.

In these situations, you might want to prevent a row or column from getting too big or too small. For example, if you have a 100-pixel wide image in your grid, you probably don’t want its column to get thinner than 100 pixels! The minmax() function can help us solve this problem.
```
.grid {
  display: grid;
  grid-template-columns: 100px minmax(100px, 500px) 100px;
}
```
In this example, the first and third columns will always be 100 pixels wide, no matter the size of the grid. The second column, however, will vary in size as the overall grid resizes. The second column will always be between 100 and 500 pixels wide.

#### Learn
Grid Essentials
Grid Gap
6 min
In all of our grids so far, there hasn’t been any space between the items in our grid. The CSS properties row-gap and column-gap will put blank space between every row and column in the grid.
```
.grid {
  display: grid;
  width: 320px;
  grid-template-columns: repeat(3, 1fr);
  column-gap: 10px;
}
```
It is important to note that grid gap properties do not add space at the beginning or end of the grid. In the example code, our grid will have three columns with two ten-pixel gaps between them.

Let’s quickly calculate how wide these columns are. Remember that using fr considers all of the available space. The grid is 320 pixels wide and 20 of those pixels are taken up by the two grid gaps. Therefore each column takes a piece of the 300 available pixels. Each column gets 1fr, so the columns are evenly divided into thirds (or 100 pixels each).

Finally, there is a shorthand CSS property, gap, that can set the row and column gap at the same time.
```
.grid {
  display: grid;
  width: 320px;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px 10px;
}
```
The example above will set the distance between rows to 20 pixels and the distance between columns to 10 pixels. Unlike other CSS grid properties, this shorthand does not take a / between values! If only one value is given, it will set the column gap and the row gap to that value.

Note: You might have seen grid-row-gap, grid-column-gap, and grid-gap in other code, but these properties are now deprecated. 

Note: CSS comments follow the C++ /* multi-line comment convention */

#### Learn > Grid Essentials > Grid Items
1 min
In this lesson, we have learned how to define a grid container. When explicitly defining a grid, you have to declare the quantity of rows and columns and their respective sizes.

In all of our examples, the items placed in the grid have always taken up exactly one square. This does not always need to be the case; we can drastically change the look of our grid by making grid items take up more than one row and one column. You can see this in the diagram to the right. Items A, B, C, and E span more than one row!

In the following exercises, you will learn CSS properties that will affect the size of the grid items and where they are displayed on the page. By manipulating both the parent and the child elements, we can create beautiful layouts with ease.

Let’s start exploring grid items!

### * Grid Essentials
#### Learn > Grid Essentials > Grid Items
1 min
In this lesson, we have learned how to define a grid container. When explicitly defining a grid, you have to declare the quantity of rows and columns and their respective sizes.

In all of our examples, the items placed in the grid have always taken up exactly one square. This does not always need to be the case; we can drastically change the look of our grid by making grid items take up more than one row and one column. You can see this in the diagram to the right. Items A, B, C, and E span more than one row!

In the following exercises, you will learn CSS properties that will affect the size of the grid items and where they are displayed on the page. By manipulating both the parent and the child elements, we can create beautiful layouts with ease.

Let’s start exploring grid items!

![CSS Grid, 4x6, left column rows 1-2: A, rows 3-4: B, columns 2-5 C, column 6 row 1: D, rows 2-4 E](https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-web-development-foundations/tracks/fscj-22-making-a-website-responsive/modules/wdcp-22-learn-css-grid-549234ef-7622-479b-8d5d-0b4c919983b8/lessons/css-grid-essentials/exercises/grid-items)

#### Learn > Grid Essentials > Multiple Row Items
6 min
Using the CSS properties grid-row-start and grid-row-end, we can make single grid items take up multiple rows. Remember, we are no longer applying CSS to the outer grid container; we’re adding CSS to the elements sitting inside the grid!
```
.item {
  grid-row-start: 1;
  grid-row-end: 3;
}
```
In this example, the HTML element of class item will take up two rows in the grid, rows 1 and 2. The values that grid-row-start and grid-row-end accept are grid lines.

Row grid lines and column grid lines start at 1 and end at a value that is 1 greater than the number of rows or columns the grid has. For example, if a grid has 5 rows, the grid row lines range from 1 to 6. If a grid has 8 rows, the grid row lines range from 1 to 9.

The value for grid-row-start should be the row at which you want the grid item to begin. The value for grid-row-end should be one greater than the row at which you want the grid item to end. An element that covers rows 2, 3, and 4 should have these declarations: grid-row-start: 2 and grid-row-end: 5.

It is possible for the value of grid-row-start to be greater than that of grid-row-end. Both properties can also each have negative values. [Consult the documentation to learn more about how to use these features.](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-row-start)

Note: for line from row 1 to row 2:
  grid-row-start: 1;
  grid-row-end: 3;
Alternatively:
  grid-row 1/3;

#### Learn > Grid Essentials > Grid Row
2 min
We can use the property grid-row as shorthand for grid-row-start and grid-row-end. The following two code blocks will produce the same output:
```
.item {
  grid-row-start: 4;
  grid-row-end: 6;
}

.item {
  grid-row: 4 / 6;
}
```
This code should look similar to the way grid-template is shorthand for grid-template-rowsand grid-template-columns. In this case, the starting row goes before the “/“ and the ending row goes after it. Again, the ending row is exclusive; this grid item will occupy rows four and five.

When an item spans multiple rows or columns using these properties, it will also include the gap if any exists. For example, if an item spans two rows of height 100 pixels and there is a ten-pixel gap, then the item will have a total height of 210 pixels.

#### Learn > Grid Essentials > Grid Column
8 min
The previous three properties also exist for columns. grid-column-start, grid-column-end and grid-column work identically to the row properties. These properties allow a grid item to span multiple columns.

When using these properties, we can use the keyword span to start or end a column or row, relative to its other end. Look at how span is used in the code below:
```
.item {
  grid-column: 4 / span 2;
}
```
This is telling the item element to begin in column four and take up two columns of space. So item would occupy columns four and five. It produces the same result as the following code blocks:
```
.item {
  grid-column: 4 / 6;
}

.item {
  grid-column-start: 4;
  grid-column-end: span 2;
}

.item {
  grid-column-start: span 2;
  grid-column-end: 6;
}
```
> span is a useful keyword, because it avoids off-by-one errors (miscalculating the ending grid line) you might make when determining the ending grid line of an element. If you know where you want your grid item to start and how long it should be, use span!

Note: span can be use in the start position:
 grid-column: span 2 / 6
 meaning take 2 columns ending at column 6, so columns 4-6.

 #### Learn > Grid Essentials > Grid Area
7 min
We’ve already been able to use grid-row and grid-column as shorthand for properties like grid-row-start and grid-row-end. We can refactor even more using the property grid-area. This property will set the starting and ending positions for both the rows and columns of an item.
```
.item {
  grid-area: 2 / 3 / 4 / span 5;
}
```
grid-area takes four values separated by slashes. The order is important! This is how grid-area will interpret those values.
```
grid-row-start
grid-column-start
grid-row-end
grid-column-end
```
In the above example, the item will start on row 2 and end on row 4, though the 4th row is not actually included, only rows 2 and 3! The item will then start on column 3 and instead of setting a number for which column to end on, we want this item to span 5 columns — this means the item will include columns 3, 4, 5, 6, and 7.

Using grid-area is an easy way to place items exactly where you want them in a grid.

#### Learn > Grid Essentials > Review
12 min
At this point, we’ve covered a great deal of different ways to manipulate the grid and the items inside it to create interesting layouts.
* grid-template-columns defines the number and sizes of the columns of the grid
* grid-template-rows defines the number and sizes of the rows of the grid
* grid-template is a shorthand for defining both grid-template-columns and grid-template-rows in one line
* row-gap puts blank space between the rows of the grid
* column-gap puts blank space between the columns of the grid
* gap is a shorthand for defining both row-gap and column-gap in one line
* grid-row-start and grid-row-end makes elements span certain rows of the grid
* grid-column-start and grid-column-end makes elements span certain columns of the grid
* grid-area is a shorthand for grid-row-start, grid-column-start, grid-row-end, and grid-column-end, all in one line

You have seen how to set up and fill in a grid and you now have one more CSS positioning technique to add to your toolkit! Let’s do some practice to solidify these skills.

#### Learn > Advanced CSS Grid > Introduction
1 min
In the previous lesson, you learned all the foundational properties necessary to create a two-dimensional grid-based layout for your web pages! In this lesson, you’ll learn the following additional properties that you can use to harness the power of CSS Grid Layout:
* grid-template-areas
* justify-items
* justify-content
* justify-self
* align-items
* align-content
* align-self
* grid-auto-rows
* grid-auto-columns
* grid-auto-flow

You will also learn about the explicit and implicit grids and grid axes.

#### Learn
Advanced CSS Grid
Grid Template Areas
16 min
The grid-template-areas property allows you to name sections of your web page to use as values in the grid-row-start, grid-row-end, grid-column-start,grid-column-end, and grid-area properties. This property is declared on grid containers.
```
<div class="container">
  <header>Welcome!</header>
  <nav>Links!</nav>
  <section class="info">Info!</section>
  <section class="services">Services!</section>
  <footer>Contact us!</footer>
</div>

.container {
  display: grid;
  max-width: 900px;
  position: relative;
  margin: auto;
  grid-template-areas: "header header"
                       "nav nav" 
                       "info services"
                       "footer footer";
  grid-template-rows: 300px 120px 800px 120px;
  grid-template-columns: 1fr 3fr; 
}

header {
  grid-area: header;
} 

nav {
  grid-area: nav;
} 

.info {
  grid-area: info;
} 

.services {
  grid-area: services;
}

footer {
  grid-area: footer;
} 
```
You may want to expand this section of the website to view the code above more clearly.
1. In the example above, the HTML creates a web page with five distinct parts.
2. In the .container ruleset, the grid-template-areas declaration creates a 2-column, 4-row layout.
3. The grid-template-rows declaration specifies the height of each of the four rows from top to bottom: 300 pixels, 120 pixels, 800 pixels, and 120 pixels.
4. The grid-template-columns declaration uses the fr value to cause the left column to use one fourth of the available space on the page and the right column to use three-fourths of the available space on the page.
5. In each ruleset below .container, we use the grid-area property to tell that section to cover the portion of the page specified. The header element spans the first row and both columns. The nav element spans the second row and both columns. The element with class .info spans the third row and left column. The element with class .services spans the third row and right column. The footer element spans the bottom row and both columns.
6. That’s it! An entire page laid out in 40 lines of code.

#### Learn > Advanced CSS Grid > Overlapping Elements
11 min
Another powerful feature of CSS Grid Layout is the ability to easily overlap elements.

When overlapping elements, it is generally easiest to use the grid-area property with grid row names. Remember that grid-area will set the starting and ending positions for both the rows and columns of an item.
```
<div class="container">
  <div class="info">Info!</div> 
  <img src="#" />
  <div class="services">Services!</div>
</div>

.container {
  display: grid;
  grid-template: repeat(8, 200px) / repeat(6, 100px);
}

.info {
  grid-area: 1 / 1 / 9 / 4;
}

.services {
  grid-area: 1 / 4 / 9 / 7;
}

img {
  grid-area: 2 / 3 / 5 / 5;
  z-index: 5;
}
```
In the example above, there is a grid container with eight rows and six columns. There are three grid items within the container — a \<div> with the class info, a \<div> with the class services, and an image.

The info section covers all eight rows and the first three columns. The services section covers all eight rows and the last three columns.

The image spans the 2nd, 3rd, and 4th rows and the 3rd and 4th columns.

> The z-index property tells the browser to render the image element on top of the services and info sections so that it is visible.

#### Learn > Advanced CSS Grid > Justify Items
7 min
We have referred to “two-dimensional grid-based layout” several times throughout this course.

There are two axes in a grid layout — the column (or block) axis and the row (or inline) axis.

The column axis stretches from top to bottom across the web page.

The row axis stretches from left to right across the web page.

In the following four exercises, we will learn and use properties that rely on an understanding of grid axes.

justify-items is a property that positions grid items along the inline, or row, axis. This means that it positions items from left to right across the web page. This property is declared on grid containers.

justify-items accepts these values:
* start — aligns grid items to the left side of the grid area
* end — aligns grid items to the right side of the grid area
* center — aligns grid items to the center of the grid area
* stretch — stretches all items to fill the grid area

There are several other values that justify-items accepts, which you can read about on the Mozilla Developer Network. The definitions for these values can also be found in the documentation. It is important to note that the page with the definitions includes some values that are not accepted in CSS Grid layout.
```
<main>
  <div class="card">Card 1</div>
  <div class="card">Card 2</div>
  <div class="card">Card 3</div>
</main>

main {
  display: grid;
  grid-template-columns: repeat(3, 400px);
  justify-items: center;
}
```
In the example above, we use justify-items to adjust the positioning of some elements on this web page.

1. There is a grid container with three columns that are each 400 pixels wide.
2. The container has three grid items that do not have a specified width.
3. Without setting the justify-items property, these elements will span the width of the column they are in (400 pixels).
4. By setting the justify-items property to center, the .card <div>s will be centered inside of their columns. They will only be as wide as necessary to contain their content (the words Card 1, etc).
5. If we specify a width for the .card elements, they will not stretch the width of their column.

#### Learn > Advanced CSS Grid > Justify Content
4 min
In the previous exercise, we learned how to position elements within their columns. In this exercise, we will learn how to position a grid within its parent element.

We can use justify-content to position the entire grid along the row axis. This property is declared on grid containers.

It accepts these values:
* start — aligns the grid to the left side of the grid container
* end — aligns the grid to the right side of the grid container
* center — centers the grid horizontally in the grid container
* stretch — stretches the grid items to increase the size of the grid to expand horizontally across the container
* space-around — includes an equal amount of space on each side of a grid element, resulting in double the amount of space between elements as there is before the first and after the last element
* space-between — includes an equal amount of space between grid items and no space at either end
* space-evenly — places an even amount of space between grid items and at either end

There are several other values that justify-content accepts, which you can read about on the Mozilla Developer Network. The definitions for these values can also be found in the documentation. It is important to note that the page with the definitions includes some values that are not accepted in CSS Grid layout.
```
<main>
  <div class="left">Left</div>
  <div class="right">Right</div>
</main>

main {
  display: grid;
  width: 1000px;
  grid-template-columns: 300px 300px;
  grid-template-areas: "left right"; 
  justify-content: center;
}
```
In the example above, the grid container is 1000 pixels wide, but we only specified two columns that are 300 pixels each. This will leave 400 pixels of unused space in the grid container.
justify-content: center; positions the columns in the center of the grid, leaving 200 pixels on the right and 200 pixels on the left of the grid.

#### Learn > Advanced CSS Grid > Align Items
4 min
In the previous two exercises, we learned how to position grid items and grid columns from left to right across the page. Now we’ll learn how to position grid items from top to bottom!

align-items is a property that positions grid items along the block, or column axis. This means that it positions items from top to bottom. This property is declared on grid containers.

align-items accepts these values:
* start — aligns grid items to the top side of the grid area
* end — aligns grid items to the bottom side of the grid area
* center — aligns grid items to the center of the grid area
* stretch — stretches all items to fill the grid area

There are several other values that align-items accepts, which you can read about on the Mozilla Developer Network. The definitions for these values can also be found in the documentation. It is important to note that the page with the definitions includes some values that are not accepted in CSS Grid layout.
```
<main>
  <div class="card">Card 1</div>
  <div class="card">Card 2</div>
  <div class="card">Card 3</div>
</main>

main {
  display: grid;
  grid-template-rows: repeat(3, 400px);
  align-items: center;
}
```
In the example above, we use align-items to adjust the positioning of some elements on this web page.

There is a grid container with three rows that are 400 pixels tall.
The container has three grid items that do not have a specified width.
Without setting the align-items property, these elements will span the height of the row they are in (400 pixels).
By setting the align-items property to center, the .card \<div>s will be centered vertically inside of their rows. They will only be as tall as necessary to contain their content (the words Card 1, etc).
> If we specify a height for the .card elements, they will not stretch the height of their row even if align-items: stretch; is set.

#### Learn > Advanced CSS Grid > Align Content
3 min
In the previous exercise, we positioned grid items within their rows. align-content positions the rows along the column axis, or from top to bottom, and is declared on grid containers.

It accepts these positional values:
* start — aligns the grid to the top of the grid container
* end — aligns the grid to the bottom of the grid container
* center — centers the grid vertically in the grid container
* stretch — stretches the grid items to increase the size of the grid to expand vertically across the container
* space-around — includes an equal amount of space on each side of a grid element, resulting in double the amount of space between elements as there is before the first and after the last element
* space-between — includes an equal amount of space between grid items and no space at either end
* space-evenly — places an even amount of space between grid items and at either end

There are several other values that align-content accepts, which you can read about on the Mozilla Developer Network. The definitions for these values can also be found in the documentation. It is important to note that the page with the definitions includes some values that are not accepted in CSS Grid layout.
```
<main>
  <div class="top">Top</div>
  <div class="bottom">Bottom</div>
</main>

main {
  display: grid;
  height: 600px;
  grid-template-rows: 200px 200px;
  grid-template-areas: "top"
                       "bottom"; 
  align-content: center;
}
```
In the example above, the grid container is 600 pixels tall, but we only specified two rows that are 200 pixels each. This will leave 200 pixels of unused space in the grid container.
align-content: center; positions the rows in the center of the grid, leaving 100 pixels at the top and 100 pixels at the bottom of the grid.

#### Learn > Advanced CSS Grid > Justify Self and Align Self
3 min
The justify-items and align-items properties specify how all grid items contained within a single container will position themselves along the row and column axes, respectively.

justify-self specifies how an individual element should position itself with respect to the row axis. This property will override justify-items for any item on which it is declared.

align-self specifies how an individual element should position itself with respect to the column axis. This property will override align-items for any item on which it is declared.

These properties are declared on grid items. They both accept these four properties: 
* start — positions grid items on the left side/top of the grid area
* end — positions grid items on the right side/bottom of the grid area
* center — positions grid items on the center of the grid area
* stretch — positions grid items to fill the grid area (default)

align-self and justify-self accept the same values as align-items and justify-items. You can read about these values on the Mozilla Developer Network. The definitions for these values can also be found in the documentation. It is important to note that the page with the definitions includes some values that are not accepted in CSS Grid layout.

#### Learn > Advanced CSS Grid > Implicit vs. Explicit Grid
2 min
So far, we have been explicitly defining the dimensions and quantities of our grid elements using various properties. This works well in many cases, such as a landing page for a business that will display a specific amount of information at all times.

However, there are instances in which we don’t know how much information we’re going to display. For example, consider online shopping. Often, these web pages include the option at the bottom of the search results to display a certain quantity of results or to display ALL results on a single page. When displaying all results, the web developer can’t know in advance how many elements will be in the search results each time.

What happens if the developer has specified a 3-column, 5-row grid (for a total of 15 items), but the search results return 30?

Something called the implicit grid takes over. The implicit grid is an algorithm built into the specification for CSS Grid that determines default behavior for the placement of elements when there are more than fit into the grid specified by the CSS.

The default behavior of the implicit grid is as follows: items fill up rows first, adding new rows as necessary. New grid rows will only be tall enough to contain the content within them. In the next exercise, you’ll learn how to change this default behavior.

#### Learn > Advanced CSS Grid > Grid Auto Rows and Grid Auto Columns
5 min
CSS Grid provides two properties to specify the size of grid tracks added implicitly: grid-auto-rows and grid-auto-columns. These properties are declared on grid containers.

grid-auto-rows specifies the height of implicitly added grid rows. grid-auto-columns specifies the width of implicitly added grid columns.

grid-auto-rows and grid-auto-columns accept the same values as their explicit counterparts, grid-template-rows and grid-template-columns:

pixels (px)
percentages (%)
fractions (fr)
the repeat() function
<body>
  <div>Part 1</div>   
  <div>Part 2</div>
  <div>Part 3</div>
  <div>Part 4</div>
  <div>Part 5</div>
</body>

body {
  display: grid;
  grid: repeat(2, 100px) / repeat(2, 150px); 
  grid-auto-rows: 50px;
}

In the example above, there are 5 <div>s. However, in the body ruleset, we only specify a 2-row, 2-column grid — four grid cells.

The fifth <div> will be added to an implicit row that will be 50 pixels tall.

If we did not specify grid-auto-rows, the rows would be auto-adjusted to the height of the content of the grid items.

#### Learn > Advanced CSS Grid > Grid Auto Flow
3 min
In addition to setting the dimensions of implicitly-added rows and columns, we can specify the order in which they are rendered.

grid-auto-flow specifies whether new elements should be added to rows or columns, and is declared on grid containers.
grid-auto-flow accepts these values:
* row — specifies the new elements should fill rows from left to right and create new rows when there are too many elements (default)
* column — specifies the new elements should fill columns from top to bottom and create new columns when there are too many elements
* dense — this keyword invokes an algorithm that attempts to fill holes earlier in the grid layout if smaller elements are added

You can pair row or column with dense, like this: grid-auto-flow: row dense;.

#### Learn > Advanced CSS Grid > Review
1 min
Great work! You have learned many new properties to use when creating a layout using CSS Grid! Let’s review:

* grid-template-areas specifies grid named grid areas
* grid layouts are two-dimensional: they have a row, or inline, axis and a column, or block, axis.
* justify-items specifies how individual elements should spread across the row axis
* justify-content specifies how groups of elements should spread across the row axis
* justify-self specifies how a single element should position itself with respect to the row axis
* align-items specifies how individual elements should spread across the column axis
* align-content specifies how groups of elements should spread across the column axis
* align-self specifies how a single element should position itself with respect to the column axis
* grid-auto-rows specifies the height of rows added implicitly to the grid
* grid-auto-columns specifies the width of columns added implicitly to the grid
* grid-auto-flow specifies in which direction implicit elements should be created

This is a great time to experiment with the code in the code editor and try any of the properties you want to practice more! When you’re ready, move on!

#### Quiz
Imagine we have a grid with 4 items in it, with the following CSS properties. What width would the 3rd column be?
````
.grid {
  grid-auto-columns: 100px 200px;
  grid-auto-flow: column;
}
````
The boxes will fill up implicitly created columns which alternate between being 100px and 200px. Only even rows will be 200px in size.

### * PupSpa
#### Objective
Web Development Foundations
PupSpa
Let’s practice what we’ve just learned about CSS Grid through building a classic, grid-based, responsive web page. Your friend has just opened a doggie daycare and grooming services shop, PupSpa. They would like a simple web page to let customers know about their services.

We currently have an HTML document styled with CSS, but every \<div> appears in its own row. Let’s add some CSS grid properties to make parts of the site appear more cohesive. Some of the properties we’ll be using include:
* display
* grid-template-rows
* grid-template-columns
* gap
* grid-column-start
* grid-column-end

We’ll also cover a couple of the shorthand properties of these as well, so let’s get started!

If you get stuck during this project or would like to see an experienced developer work through it, click “Get Unstuck“ to see a project walkthrough video.

####  PupSpa > Task 10
Lastly, the <p> elements inside of the grid boxes aren’t centered. There are some fun ways to deal with this using some advanced CSS grid properties that you’ll soon learn about. In the meantime, one way we can take care of it with knowledge we already have is to make each of the boxes its own grid! Since each \<p> element has a margin: auto declaration, they will be centered inside grid container.

To turn the boxes with the \<p> elements into grids, use the display properties in the below rulesets to turn them into grids:

* header
* .about
* .box
* .testimonial
* footer

### * CSS Grid, Task Board
#### Objective
Web Development Foundations
CSS Grid: Task Board
In this project, you will create a board of to-do items organized into columns. All of the HTML and most of the CSS have been written for you, but the grid property declarations have yet to be added.

In order to complete this project, you must know how to lay out the structure of a grid’s rows and columns and place items within that grid using CSS.

We recommend that you review our CSS Grid Essentials lesson before beginning.

The premade index.html and style.css files are displayed for you. Click this link to see the completed project in another tab. Have fun!

If you get stuck during this project or would like to see an experienced developer work through it, click “Get Unstuck“ to see a project walkthrough video.

### * CSS Grid, Bana's Travel Blog
#### Learn > Sizing Elements > Relative Measurements
1 min
Modern technology allows users to browse the Internet via multiple devices, such as desktop monitors, mobile phones, tablets, and more. Devices of different screen sizes, however, pose a problem for web developers: how can we ensure that a website is readable and visually appealing across all devices, regardless of screen size?

The answer: responsive design! Responsive design refers to the ability of a website to resize and reorganize its content based on:
1. The size of other content on the website.
2. The size of the screen the website is being viewed on.

In this lesson, we’ll size HTML content relative to other content on a website.

You’ve probably noticed the unit of pixels, or px, used in websites. Pixels are used to size content to exact dimensions. For example, if you want a div to be exactly 500 pixels wide and 100 pixels tall, then the unit of px can be used. Pixels, however, are fixed, hard coded values. When a screen size changes (like switching from landscape to portrait view on a phone), elements sized with pixels can appear too small, overflow the screen, or become completely illegible.

With CSS, you can avoid hard coded measurements and use relative measurements instead. Relative measurements offer an advantage over hard coded measurements, as they allow for the proportions of a website to remain intact regardless of screen size or layout.

####  Learn > Sizing Elements > Em
7 min
Incorporating relative sizing starts by using units other than pixels. One unit of measurement you can use in CSS to create relatively-sized content is the em, written as em in CSS.

Historically, the em represented the width of a capital letter M in the typeface and size being used. That is no longer the case.

Today, the em represents the font-size of the current element or the default base font-size set by the browser if none is given. For example, if the base font of a browser is 16 pixels (which is normally the default size of text in a browser), then 1 em is equal to 16 pixels. 2 ems would equal 32 pixels, and so on.

Let’s take a look at two examples that show how em can be used in CSS.
```
.heading {
  font-size: 2em;
}
```
In the example above, no base font has been specified, therefore the font size of the heading element will be set relative to the default font size of the browser. Assuming the default font size is 16 pixels, then the font size of the heading element will be 32 pixels.
```
.splash-section {
  font-size: 18px;
}

.splash-section h1 {
  font-size: 1.5em;
}
```
The example above shows how to use ems without relying on the default font size of the browser. Instead, a base font size (18px) is defined for all text within the splash-section element. The second CSS rule will set the font size of all h1 elements inside of splash-section relative to the base font of splash-section (18 pixels). The resulting font size of h1 elements will be 27 pixels.

#### Learn > Sizing Elements > Rem
6 min
The second relative unit of measurement in CSS is the rem, coded as rem.

Rem stands for root em. It acts similar to em, but instead of checking parent elements to size font, it checks the root element. The root element is the \<html> tag.

Most browsers set the font size of \<html> to 16 pixels, so by default rem measurements will be compared to that value. To set a different font size for the root element, you can add a CSS rule.
```
html {
  font-size: 20px;
}

h1 {
  font-size: 2rem;
}
```
In the example above, the font size of the root element, \<html>, is set to 20 pixels. All subsequent rem measurements will now be compared to that value and the size of h1 elements in the example will be 40 pixels.

One advantage of using rems is that all elements are compared to the same font size value, making it easy to predict how large or small font will appear. If you are interested in sizing elements consistently across an entire website, the rem measurement is the best unit for the job. If you’re interested in sizing elements in comparison to other elements nearby, then the em unit would be better suited for the job.

Note: Using rem units html is the root element

#### Learn > Sizing Elements > Percentages: Height & Width
7 min
To size non-text HTML elements relative to their parent elements on the page you can use percentages.

Percentages are often used to size box-model values, like width and height, padding, border, and margins. They can also be used to set positioning properties (top, bottom, left, right).

To start, let’s size the height and width of an element using percentages.
```
.main {
  height: 300px;
  width: 500px;
}
 
.main .subsection {
  height: 50%;
  width: 50%;
}
```
In the example above, .main and .subsection each represent divs. The .subsection div is nested within the .main div. Note that the dimensions of the parent div (.main) have been set to a height of 300 pixels and a width of 500 pixels.

When percentages are used, elements are sized relative to the dimensions of their parent element (also known as a container). Therefore, the dimensions of the .subsection div will be 150 pixels tall and 250 pixels wide. Be careful, a child element’s dimensions may be set erroneously if the dimensions of its parent element aren’t set first.

Note: Because the box model includes padding, borders, and margins, setting an element’s width to 100% may cause content to overflow its parent container. While tempting, 100% should only be used when content will not have padding, border, or margin.

#### Learn > Sizing Elements > Percentages: Padding & Margin
7 min
Percentages can also be used to set the padding and margin of elements.

When height and width are set using percentages, you learned that the dimensions of child elements are calculated based on the dimensions of the parent element.

When percentages are used to set padding and margin, however, they are calculated based only on the width of the parent element.

For example, when a property like margin-left is set using a percentage (say 50%), the element will be moved halfway to the right in the parent container (as opposed to the child element receiving a margin half of its parent’s margin).

Vertical padding and margin are also calculated based on the width of the parent. Why? Consider the following scenario:
1. A container div is defined, but its height is not set (meaning it’s flat).
2. The container then has a child element added within. The child element does have a set height. This causes the height of its parent container to stretch to that height.
3. The child element requires a change, and its height is modified. This causes the parent container’s height to also stretch to the new height. This cycle occurs endlessly whenever the child element’s height is changed!

In the scenario above, an unset height (the parent’s) results in a constantly changing height due to changes to the child element. This is why vertical padding and margin are based on the width of the parent, and not the height.

Note: When using relative sizing, ems and rems should be used to size text and dimensions on the page related to text size (i.e. padding around text). This creates a consistent layout based on text size. Otherwise, percentages should be used.

#### Learn > Sizing Elements > Width: Minimum & Maximum
3 min
Although relative measurements provide consistent layouts across devices of different screen sizes, elements on a website can lose their integrity when they become too small or large. You can limit how wide an element becomes with the following properties:

min-width — ensures a minimum width for an element.
max-width — ensures a maximum width for an element.
```
p {
  min-width: 300px;
  max-width: 600px;
}
```
In the example above, when the browser is resized, the width of paragraph elements will not fall below 300 pixels, nor will their width exceed 600 pixels.

When a browser window is narrowed or widened, text can become either very compressed or very spread out, making it difficult to read. These two properties ensure that content is legible by limiting the minimum and maximum widths.

Note: The unit of pixels is used to ensure hard limits on the dimensions of the element(s).

#### Learn > Sizing Elements > Height: Minimum & Maximum
1 min
You can also limit the minimum and maximum height of an element.

min-height — ensures a minimum height for an element’s box.
max-height — ensures a maximum height for an element’s box.
```
p {
  min-height: 150px;
  max-height: 300px;
}
```
In the example above, the height of all paragraphs will not shrink below 150 pixels and the height will not exceed 300 pixels.

What will happen to the contents of an element if the max-height property is set too low for that element? It’s possible that content will overflow outside of the element, resulting in content that is not legible.

#### Learn > Sizing Elements > Scaling Images and Videos
8 min
Many websites contain a variety of different media, like images and videos. When a website contains such media, it’s important to make sure that it is scaled proportionally so that users can correctly view it.
```
.container {
  width: 50%;
  height: 200px;
  overflow: hidden;
}

.container img {
  max-width: 100%;
  height: auto;
  display: block;
}
```
In the example above, .container represents a container div. It is set to a width of 50% (half of the browser’s width, in this example) and a height of 200 pixels. Setting overflow to hidden ensures that any content with dimensions larger than the container will be hidden from view.

The second CSS rule ensures that images scale with the width of the container. The height property is set to auto, meaning an image’s height will automatically scale proportionally with the width. Finally, the last line will display images as block level elements (rather than inline-block, their default state). This will prevent images from attempting to align with other content on the page (like text), which can add unintended margin to the images.

> It’s worth memorizing the entire example above. It represents a very common design pattern used to scale images and videos proportionally.
> Note that needed to set display: block on img elements

Note: The example above scales the width of an image (or video) to the width of a container. If the image is larger than the container, the vertical portion of the image will overflow and will not display. To swap this behavior, you can set max-height to 100% and width to auto (essentially swapping the values). This will scale the height of the image with the height of the container instead. If the image is larger than the container, the horizontal portion of the image will overflow and not display.

#### Learn > Sizing Elements > Scaling Background Images
2 min
Background images of HTML elements can also be scaled responsively using CSS properties.
```
body {
  background-image: url('#');
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
```
In the example above, the first CSS declaration sets the background image (# is a placeholder for an image URL in this example). The second declaration instructs the CSS compiler to not repeat the image (by default, images will repeat). The third declaration centers the image within the element.

> The final declaration, however, is the focus of the example above. It’s what scales the background image. The image will cover the entire background of the element, all while keeping the image in proportion. If the dimensions of the image exceed the dimensions of the container then only a portion of the image will display.

#### Learn > Sizing Elements > Review: Relative Measurements
1 min
Great work! You learned how to size elements on a website relative to other elements on the page.

Let’s review what you learned:
1. Content on a website can be sized relative to other elements on the page using relative measurements.
2. The unit of em sizes font relative to the font size of a parent element.
3. The unit of rem sizes font relative to the font size of a root element. That root element is the \<html> element.
4. Percentages are commonly used to size box-model features, like the width, height, padding, or margin of an element.
5. When percentages are used to size width and height, child elements will be sized relative to the dimensions of their parent (remember that parent dimensions must first be set).
6. Percentages can be used to set padding and margin. Horizontal and vertical padding and margin are set relative to the width of a parent element.
7. The minimum and maximum width of elements can be set using min-width and max-width.
8. The minimum and maximum height of elements can be set using min-height and max-height.
9. When the height of an image or video is set, then its width can be set to auto so that the media scales proportionally. Reversing these two properties and values will also achieve the same result.
10. A background image of an HTML element will scale proportionally when its background-size property is set to cover.

Relative units of measurement are a first step towards incorporating responsive design in a website. When combined with more advanced responsive techniques, you can create a seamless user experience regardless of a device’s screen size.

### FSE 1.6.4. Learn Responsive Design
#### Learn
Media Queries
Responsive Web Design
2 min
When someone visits a website, it’s possible they are viewing it on a phone, tablet, computer, or even a TV monitor. Because screen sizes can vary greatly across different devices, it’s important for websites to resize and reorganize their content to best fit screens of all sizes.

When a website doesn’t respond to different screen sizes, the website may look odd or become indecipherable on certain devices. This usually occurs on smaller screens, like phones. When a website responds to the size of the screen it’s viewed on, it’s called a responsive website.

Because websites can be displayed on thousands of different screen sizes, they must be able to respond to a change in screen size and adapt the content so that users can access it.

Nonresponsive Website
* The “Globe Book Store” title stays the same font size and collapses on top of itself when the screen becomes too narrow, making it unreadable.
* The banner image gets cut off, showing only the leftmost brown portion, and William Shakespeare is no longer visible.
* The gallery images do not shrink as the width of the browser window decreases, allowing only one image to be in each row. This causes the page to be very long.
Responsive Website
* The “Globe Book Store” title dynamically resizes the font and repositions to look better on the smaller screen.
* The banner image is resized so that William Shakespeare remains visible even when the page is smaller.
* The “Selected Title” and “Contact” headings expand to the whole width of the page on a small screen, providing clear content delineations.
* The books in the picture gallery shrink slightly so that two images can be in each row. This beneficially shortens the page.

#### Learn > Media Queries > Viewport Meta Tag
7 min
Thus far, we have been learning about creating responsive web designs with CSS. However, in order for us to enable this responsive CSS to work, we need to get familiar with the HTML viewport meta tag!

Let’s start with the viewport, which is the total viewable area for a user; this area varies depending on device. The viewport is smaller on a mobile device and larger on a desktop.

Based on the size of the viewport, the meta tag (<meta>) is used to instruct the browser on how to render the webpage’s scale and dimensions. For instance, say if a web page is 960px and the device is 320px wide. Adding the viewport meta tag will squish the content down until it is 320px — there is no need for the user to zoom out and view the whole page!

Inside the \<head> element, we will find where the \<meta> tag syntax is implemented:
```
<!DOCTYPE html> 
<html lang="en"> 
  <head> 
    ...
    <meta name="viewport" content="width=device-width, initial-scale=1">
    ...
  </head> 
```
We can break down the added \<meta> tag into the following essential components:
* the name="viewport" attribute: tells the browser to display the web page at the same width as its screen
* the content attribute: defines the values for the \<meta> tag, including width and initial-scale
* the width=device-width key-value pair: controls the size of the viewport in which it sets the width of the viewport to equal the width of the device
* the initial-scale=1 key-value pair: sets the initial zoom level (Read more about scale at MDN’s viewport documentation)

The viewport meta tag allows our web pages to be responsive and adapt a site’s contents to the users’ screen size. We’ll explore more on actually implementing this responsiveness in the later exercises, but for now, we need to first include the meta tag in our HTML file!

#### Learn > Media Queries > Media Queries
8 min
CSS uses media queries to adapt a website’s content to different screen sizes. With media queries, CSS can detect the size of the current screen and apply different CSS styles depending on the width of the screen.
```
@media only screen and (max-width: 480px) {
  body {
    font-size: 12px;
  }
}
```
The example above demonstrates how a media query is applied. The media query defines a rule for screens smaller than 480 pixels (approximately the width of many smartphones in landscape orientation).

Let’s break this example down into its parts:

1. @media — This keyword begins a media query rule and instructs the CSS compiler on how to parse the rest of the rule.
2. only screen — Indicates what types of devices should use this rule. In early attempts to target different devices, CSS incorporated different media types (screen, print, handheld). The rationale was that by knowing the media type, the proper CSS rules could be applied. However, “handheld” and “screen” devices began to occupy a much wider range of sizes and having only one CSS rule per media device was not sufficient. screen is the media type always used for displaying content, no matter the type of device. The only keyword is added to indicate that this rule only applies to one media type (screen).
3. and (max-width : 480px) — This part of the rule is called a media feature, and instructs the CSS compiler to apply the CSS styles to devices with a width of 480 pixels or smaller. Media features are the conditions that must be met in order to render the CSS within a media query.
4. CSS rules are nested inside of the media query’s curly braces. The rules will be applied when the media query is met. In the example above, the text in the body element is set to a font-size of 12px when the user’s screen is less than 480px.

#### Learn > Media Queries > Range
7 min
Specific screen sizes can be targeted by setting multiple width and height media features. min-width and min-height are used to set the minimum width and minimum height, respectively. Conversely, max-width and max-height set the maximum width and maximum height, respectively.

By using multiple widths and heights, a range can be set for a media query.
```
@media only screen and (min-width: 320px) and (max-width: 480px) {
    /* ruleset for 320px - 480px */
}
```
The example above would apply its CSS rules only when the screen size is between 320 pixels and 480 pixels. Notice the use of a second and keyword after the min-width media feature. This allows us to chain two requirements together.

The example above can be written using two separate rules as well:
```
@media only screen and (min-width: 320px) { 
    /* ruleset for >= 320px */
}


@media only screen and (min-width: 480px) { 
    /* ruleset for >= 480px */
}
```
The first media query in the example above will apply CSS rules when the size of the screen meets or exceeds 320 pixels. The second media query will then apply CSS rules when the size of the screen meets or exceeds 480 pixels, meaning that it can override CSS rules present in the first media query or apply additional CSS rules that are not already present in the first.

> Both examples above are valid, and it is likely that you will see both patterns used when reading another developer’s code.

#### Learn > Media Queries > Dots Per Inch (DPI)
6 min
Another media feature we can target is screen resolution. Many times we will want to supply higher quality media (images, video, etc.) only to users with screens that can support high resolution media. Targeting screen resolution also helps users avoid downloading high resolution (large file size) images that their screen may not be able to properly display.

To target by resolution, we can use the min-resolution and max-resolution media features. These media features accept a resolution value in either dots per inch (dpi) or dots per centimeter (dpc). Learn more about resolution measurements here.
```
@media only screen and (min-resolution: 300dpi) {
    /* CSS for high resolution screens */
}
```

The media query in the example above targets high resolution screens by making sure the screen resolution is at least 300 dots per inch. If the screen resolution query is met, then we can use CSS to display high resolution images and other media.

#### Learn > Media Queries > And Operator
4 min
In previous exercises, we chained multiple media features of the same type in one media query by using the and operator. It allowed us to create a range by using min-width and max-width in the same media query.

The and operator can be used to require multiple media features. Therefore, we can use the and operator to require both a max-width of 480px and to have a min-resolution of 300dpi.

For example:
```
@media only screen and (max-width: 480px) and (min-resolution: 300dpi) {
    /* CSS ruleset */
}
```
By placing the and operator between the two media features, the browser will require both media features to be true before it renders the CSS within the media query. The and operator can be used to chain as many media features as necessary.

#### Learn > Media Queries > Comma Separated List
4 min
If only one of multiple media features in a media query must be met, media features can be separated in a comma separated list.

For example, if we needed to apply a style when only one of the below is true:
The screen is more than 480 pixels wide
The screen is in landscape mode

We could write:
```
@media only screen and (min-width: 480px), (orientation: landscape) {
    /* CSS ruleset */
}
```
In the example above, we used a comma (,) to separate multiple rules. The example above requires only one of the media features to be true for its CSS to apply.

Note that the second media feature is orientation. The orientation media feature detects if the page has more width than height. If a page is wider, it’s considered landscape, and if a page is taller, it’s considered portrait.

#### Learn > Media Queries > Breakpoints
7 min
We know how to use media queries to apply CSS rules based on screen size and resolution, but how do we determine what queries to set?

The points at which media queries are set are called breakpoints. Breakpoints are the screen sizes at which your web page does not appear properly. For example, if we want to target tablets that are in landscape orientation, we can create the following breakpoint:
```
@media only screen and (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
    /* CSS ruleset */
}
```
The example above creates a screen size range the size of a tablet in landscape mode and also identifies the orientation.

However, setting breakpoints for every device imaginable would be incredibly difficult because there are many devices of differing shapes and sizes. In addition, new devices are released with new screen sizes every year.

Rather than set breakpoints based on specific devices, the best practice is to resize your browser to view where the website naturally breaks based on its content. The dimensions at which the layout breaks or looks odd become your media query breakpoints. Within those breakpoints, we can adjust the CSS to make the page resize and reorganize.

By observing the dimensions at which a website naturally breaks, you can set media query breakpoints that create the best possible user experience on a project by project basis, rather than forcing every project to fit a certain screen size. Different projects have different needs, and creating a responsive design should be no different.

Check out this list of breakpoints by device widths. Use it as a reference of screen widths to test your website to make certain it looks great across a variety of devices.

#### Learn > Media Queries > Review: Media Queries
1 min
Incredible work! You learned how to change the way a website appears on different screens with media queries and breakpoints

Throughout this lesson, you learned:
* When a website responds to the size of the screen it’s viewed on, it’s called a responsive website.
* You can write media queries to help with different screen sizes.
* Adding the viewport \<meta> tag to our code allows us to control the width and scaling of the viewport so that it’s sized and scaled correctly on all devices.
* Media queries require media features. Media features are the conditions that must be met to render the CSS within a media query.
* Media features can detect many aspects of a user’s browser, including the screen’s width, height, resolution, orientation, and more.
* The and operator requires multiple media features to be true at once.
* A comma separated list of media features only requires one media feature to be true for the code within to be applied.
* The best practice for identifying where media queries should be set is by resizing the browser to determine where the content naturally breaks. Natural breakpoints are found by resizing the browser.

With your knowledge of media queries and CSS, you can make websites that look great on any device, from a small phone to a huge television. By making your websites responsive, you’ll make it possible for any of your users to have a great experience.

#### Simulate Different Screen Sizes with Device Mode in Chrome DevTools
Learn how to test your website on different screen sizes.

In this article, you will learn how to simulate different screen sizes with device mode in Chrome DevTools in order to approximate how your page looks and performs on different devices. This is helpful if you want to ensure that the components of your page would be readable on mobile devices. There’s also value in seeing how your website would load on a device with a weak or non-existent connection to the network. After you finish reading the article, return to this page and complete the following assessments.

Multiple choice
Questions
What does throttling allow you to simulate?
Answer Choices
* How a website would respond to weaker, stronger, and no network connections as well as different CPU speeds.

Multiple choice
Questions
What does orientation refer to in the context of this article?
Answer Choices
* It refers to a device’s physical position with respect to gravity and how a website would look in that particular position. There are two orientations - portrait and landscape.

#### Objective > Web Development Foundations > Tsunami Coffee
Use your knowledge of relative units and responsive web design to help Tsunami Coffee make their website come to life.

Throughout this project, you’ll edit the existing Tsunami Coffee website code so that the website appears correctly on varying screen sizes. In addition, you’ll contribute styles that will make this website more visually appealing.

### FSE 1.6.5. Learn CSS, Documentation and Debugging
#### Learn > Documentation and Research > Overview
1 min
Building websites requires technical knowledge of multiple languages and frameworks. You may wonder, “How is it possible for developers to know everything there is to know about every language?” The answer is, thankfully, they don’t. One of the most essential skills of being a developer is knowing how to investigate solutions to problems you have not yet learned how to solve.

In this lesson, you will learn how to look up new ways to use previously-learned CSS properties and discover entirely new CSS properties.

On the right side of the screen is the portfolio site that you will develop into the final product. We suggest you keep this mock open in a separate tab for reference throughout the lesson.

### * Documentation and Research
#### Learn > Documentation and Research > Documentation
7 min
Every well-developed language or framework has a place where you can look up all of its features. This library of information is called a language’s documentation.

You can find the documentation for CSS at Mozilla Developer Network. In addition to CSS, The Mozilla Developer Network (referred to as MDN) contains the complete documentation for HTML, JavaScript, and many other essential tools of web development.

To see the documentation for a specific CSS property, navigate to the MDN website and search for that property in the search bar at the top of the page. Then, click on the link for that property. For example, search for the font-weight property. The list of results might appear intimidating, but you should quickly see a link starting with the description “The font-weight css property…”. This is the link we want.

Once you land on a property’s documentation page you can read all of the information about it. For example, font-weight starts with a description of the property. The “Values” section lists all of the possible values for font-weight. There are some values you already know, such as normal and bold, but there are also new values, such as lighter and bolder.

#### Learn > Documentation and Research > Google
3 min
Documentation is an essential tool to learn about properties. However, what if you don’t even know what property you need?

In situations like this, it might come as no surprise that using Google is a great way to read other developers’ solutions to problems. Googling the problem you’re trying to solve and the language you’re using will yield many useful answers.

For example, if you want to know how to change the size of text, you could google “how to change text size using CSS.” After doing this, you will receive multiple links to information about the font-size property.

#### Learn > Documentation and Research > Stack Overflow
3 min
While using Google in the previous exercise, you may have noticed a lot of links to a site called Stack Overflow.

Stack Overflow is a useful resource where developers ask and answer questions. You should use it to find answers to your questions, and learn from experienced developers.

Reading all of the top-voted answers to a Stack Overflow question can give you multiple solutions to try as well as an understanding of why one solution might be better than another. Additionally, if you can’t find a question, you can even ask it yourself and receive answers.

To search for a question on Stack Overflow, type your question and programming language into the search bar and find the question threads that seem relevant.

#### Learn > Documentation and Research > Review
<1 min
Awesome! With just a few simple searches and some research you completed the header for your portfolio site. Reading documentation and searching Google and Stack Overflow make it easy to solve development problems, even if you haven’t previously encountered the right tool for the job.

In summary:

Documentation is an easy way to view all of the information about a language or framework. The Mozilla Development Network is the source of documentation for HTML, CSS, and JavaScript.

Investigating a new language feature is as easy as typing the problem and the language into Google or Stack Overflow.

Now that you know how to find any feature and read its documentation, the sky’s the limit on what you can do. Feel free to browse MDN and Stack Overflow to find new features and try incorporating them into your header to make it look even better. Great job!

### * Off-Platform Project, Fotomatic
#### Objective
Web Development Foundations
Challenge Project: Company Home Page with Flexbox
Overview
​This project is slightly different than others you have encountered thus far on Codecademy. Instead of a step-by-step tutorial, this project contains a series of open-ended requirements which describe the project you’ll be building. There are many possible ways to correctly fulfill all of these requirements, and you should expect to use the Internet, Codecademy, and other resources when you encounter a problem that you cannot easily solve.​

Project Goals
In this project, you’ll be using flexbox to design and build the layout for a company’s homepage. You can choose to build a new homepage for an existing company or imagine your own dream company!​

Setup Instructions
If you choose to do this project on your computer instead of Codecademy, you can download what you’ll need by clicking the “Download” button below. If you need help setting up your computer, read our article about setting up a text editor for HTML/CSS development.

Prerequisites
1. To complete this project, you should have completed Codecademy’s Flexbox curriculum in any of the following:

Full-Stack Engineering Career Path
Front-End Engineering Career Path
Learn How to Build Websites Skill Path
Project Requirements
2. You’re going to build a company homepage for a real or imagined company. You’ll get to decide exactly what content to include for this company, but you should at least include:

A title and logo or splash image.
A mission statement or brief description of the company.
A list or set of images and titles representing the product or products of the company.
A section describing some of the company’s employees or teammates.
If you want, you can tour our example site for inspiration or to see how we used flexbox. Your site will probably look very different from ours, and that’s great!

3. Your project should use flexbox styling for layout. Aim to use flexbox’s advantages, such as easy horizontal and vertical positioning, flexible element flows as the page size changes, and great styling for repeated elements.

In our example project, we used flexbox to:

Create a centered navbar at the top of the page.
Create a flexible display of company products that changes from a more grid-like list to a column list as the page shrinks.
Create a flexible display of company employees.
Our example site is not an elaborate use of flexbox–we’re sure you can come up with other uses of flexbox in your layout, such as taking advantage of flex-grow or flex-shrink.

4. Your page should also use custom styles for other properties, such as colors, fonts, and other layout properties such as borders and padding.

Our example site uses:

A simple color scheme using CSS named colors, but yours can be more elaborate with hexadecimal, RGB, or HSL colors.
Fonts from the Google Fonts API.
Custom images. A great source for project images when you’re practicing web design is Unsplash.
Get creative! Customizing your site’s look and feel is one of the most exciting parts of building your own websites. You can review any of these other CSS properties in our Learn CSS course.

Project Solution
5. Great work! Visit our forums to compare your project to our sample solution code. You can also learn how to host your own solution on GitHub so you can share it with other learners!

Remember, this is just one possible solution. Your own project may be coded totally differently, have more or less content, and look totally different! We’re providing our solution for you get a sense of one way to flexbox to help with page layout. There are multiple ways to solve these projects, and you’ll learn more by seeing others’ code.

### FSE 1.6.6. Challenge Project, Company Home Page

#### Objective > Web Development Foundations > Challenge Project: Company Home Page with Flexbox
Overview
​This project is slightly different than others you have encountered thus far on Codecademy. Instead of a step-by-step tutorial, this project contains a series of open-ended requirements which describe the project you’ll be building. There are many possible ways to correctly fulfill all of these requirements, and you should expect to use the Internet, Codecademy, and other resources when you encounter a problem that you cannot easily solve.​

Project Goals
In this project, you’ll be using flexbox to design and build the layout for a company’s homepage. You can choose to build a new homepage for an existing company or imagine your own dream company!​

Setup Instructions
If you choose to do this project on your computer instead of Codecademy, you can download what you’ll need by clicking the “Download” button below. If you need help setting up your computer, read our article about setting up a text editor for HTML/CSS development.

Download
Tasks
5/5 complete
Mark the tasks as complete by checking them off
Prerequisites
1. To complete this project, you should have completed Codecademy’s Flexbox curriculum in any of the following:

* Full-Stack Engineering Career Path
* Front-End Engineering Career Path
* Learn How to Build Websites Skill Path

Project Requirements
2. You’re going to build a company homepage for a real or imagined company. You’ll get to decide exactly what content to include for this company, but you should at least include:

* A title and logo or splash image.
* A mission statement or brief description of the company.
* A list or set of images and titles representing the product or products of the company.
* A section describing some of the company’s employees or teammates.
If you want, you can tour our (example site)[https://content.codecademy.com/PRO/independent-practice-projects/flexbox-business-site/example-site/index.html] for inspiration or to see how we used flexbox. Your site will probably look very different from ours, and that’s great!

3. Your project should use flexbox styling for layout. Aim to use flexbox’s advantages, such as easy horizontal and vertical positioning, flexible element flows as the page size changes, and great styling for repeated elements.

In our example project, we used flexbox to:

* Create a centered navbar at the top of the page.
* Create a flexible display of company products that changes from a more grid-like list to a column list as the page shrinks.
* Create a flexible display of company employees.
Our example site is not an elaborate use of flexbox–we’re sure you can come up with other uses of flexbox in your layout, such as taking advantage of flex-grow or flex-shrink.

4. Your page should also use custom styles for other properties, such as colors, fonts, and other layout properties such as borders and padding.

Our example site uses:

* A simple color scheme using CSS named colors, but yours can be more elaborate with hexadecimal, RGB, or HSL colors.
* Fonts from the Google Fonts API.
* Custom images. A great source for project images when you’re practicing web design is Unsplash.
Get creative! Customizing your site’s look and feel is one of the most exciting parts of building your own websites. You can review any of these other CSS properties in our Learn CSS course.

Project Solution
5. Great work! Visit our forums to compare your project to our sample solution code. You can also learn how to host your own solution on GitHub so you can share it with other learners!

Remember, this is just one possible solution. Your own project may be coded totally differently, have more or less content, and look totally different! We’re providing our solution for you get a sense of one way to flexbox to help with page layout. There are multiple ways to solve these projects, and you’ll learn more by seeing others’ code.

### FSE 1.6.7. Challenge Project, Responsive Club Website

### FSE 1.6.8. Review, Making a Website Responsive

#### Review: Making a Website Responsive
In this unit, you learned about responsive web design practices.

Congratulations! The goal of this unit was to establish a foundation in responsive web design and give you the tools to create websites that use different layouts which work on a variety of devices.

Having completed this unit, you are now able to:
* Understand responsive web design
* Use CSS Grid and Flexbox for layout, positioning, and responsiveness
* Use media queries

If you are interested in learning more about these topics, here are some additional resources:
* Resource: [Grid Garden](https://codepip.com/games/grid-garden/)
* Article: [Responsive Web Design](https://www.smashingmagazine.com/2011/01/guidelines-for-responsive-web-design/)
* Article: [You Don’t Need a Framework: Understanding the Fundamentals of Responsive Design](https://www.taniarascia.com/you-dont-need-a-framework/)
* Article: [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

Learning is social. Whatever you’re working on, be sure to connect with the Codecademy community in the forums. Remember to check in with the community regularly, including for things like asking for code reviews on your project work and providing code reviews to others in the projects category, which can help to reinforce what you’ve learned.