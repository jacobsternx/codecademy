
:: Terminology
Inner Loop: Focus zone where are productive, no distractions. Coding zone.

10x talent, as the label implies, is able to deliver ten times more than is expected, but what makes them so valuable is that they are multidimensional. They are smart, good communicators, and have interests beyond their core specialty. Their curiosity and love of learning drives them to do more and do it better.

Bus Factor: If one team member got hit by bus, how would project continue?

Bikeshedding: Focusing on trivial, mundane, low impact issues. The term originates from a fictional scenario where a committee tasked with approving plans for a nuclear power plant spends a significant amount of time discussing the design and color of a simple bikeshed on the plant premises while barely touching upon the complex technical aspects of the nuclear facility. Bikeshedding highlights the human tendency to focus on easily understandable or relatable topics, even if they have minimal impact or relevance to the overall objective. This phenomenon can hinder productivity, waste resources, and lead to misallocation of attention and effort. Understanding and mitigating bikeshedding can improve decision-making and project management in organizations.

---

CSS Flexbox Cheat Sheet (currently disorganized)

`flex`

`flex-flow`

`align-content`:
`flex-start` — all rows of elements will be positioned at the top of the parent container with no extra space between.
`flex-end` — all rows of elements will be positioned at the bottom of the parent container with no extra space between.
`center` — all rows of elements will be positioned at the center of the parent element with no extra space between.
`space-between` — all rows of elements will be spaced evenly from the top to the bottom of the container with no space above the first or below the last.
`space-around` — all rows of elements will be spaced evenly from the top to the bottom of the container with the same amount of space at the top and bottom and between each element.
`stretch` — if a minimum height or no height is specified, the rows of elements will stretch to fill the parent container from top to bottom (default value).

`align-items`: property is used to space flex items on the cross axis. Both `align-items` and `align-content` align items vertically, but the key difference is that the `align-items` property is used to align items within a single row, whereas the `align-content` property is used for multiple rows.
`flex-start` — all rows of elements will be positioned at the top of the parent container with no extra space between.
`flex-end` — all rows of elements will be positioned at the bottom of the parent container with no extra space between.
`center` — all rows of elements will be positioned at the center of the parent element with no extra space between.
`baseline` 
`stretch` — if a minimum height or no height is specified, the rows of elements will stretch to fill the parent container from top to bottom (default value).


`align-self`: 

`flex-wrap`

`flex-direction`:

`order`:

`justify-content`:

`flex`:

`flex-flow`: property is used to declare both the flex-wrap and flex-direction properties in one line.

`flex-basis` is limited by both max-width/max-height and min-width/min-height
When declared, flex-basis will override the width/height property set on a flex container
If no `flex-basis` is specified the default is the set width/height value, if width/height isn’t specified the default is the width/height of the content
When there is not enough space for our flex items our items will shrink at an even rate to fit within the container by default

`display: flex` changes an element to a block-level container with flex items inside of it.
`display: inline-flex` allows multiple flex containers to appear inline with each other.
`justify-content` is used to space items along the main axis.
`align-items` is used to space items along the cross axis.
`flex-grow` is used to specify how much space (and in what proportions) flex items absorb along the main axis.
`flex-shrink` is used to specify how much flex items shrink and in what proportions along the main axis.
`flex-basis` is used to specify the initial size of an element styled with flex-grow and/or flex-shrink.
`flex` is used to specify flex-grow, flex-shrink, and flex-basis in one declaration.
`flex-wrap` specifies that elements should shift along the cross axis (to next row) if the flex container is not large enough.
`align-content` is used to space rows along the cross axis.
`flex-direction` is used to specify the main and cross axes.
`flex-flow` is used to specify `flex-wrap` and `flex-direction` in one declaration.
Flex containers can be nested inside of each other by declaring `display: flex` or `display: inline-flex` for children of flex containers.

The `flex-direction` property can accept four values:
`row` — elements will be positioned from left to right across the parent element starting from the top left corner (default).
`row-reverse` — elements will be positioned from right to left across the parent element starting from the top right corner.
`column` — elements will be positioned from top to bottom of the parent element starting from the top left corner.
`column-reverse` — elements will be positioned from the bottom to the top of the parent element starting from the bottom left corner.

> The main axis is used to position flex items with the following properties:
`justify-content`
`flex-wrap`
`flex-grow`
`flex-shrink`

> The cross axis is used to position flex items with the following properties:
`align-items`
`align-content`



Descendant selector (space)
Child selector (>)
Adjacent sibling selector (+)
General sibling selector (~)