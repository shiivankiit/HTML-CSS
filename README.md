# Lectures Brief.

# HTML Basics Example

This file demonstrates some basic HTML elements:

- A button element
- A p paragraph element
- An anchor tag for creating links

----------------------------------------------------------------------------------------

# CSS Buttons UI Project [02]

This file demonstrates how to style buttons using CSS.

It includes:

- Custom button design
- Hover effects
- Active click effects
- CSS transitions
- Box shadows

Preview Features

- Subscribe Button → changes color and opacity on hover/click
- Join Button → outlined button with smooth background transition
- Tweet Button → shadow effect on hover

----------------------------------------------------------------------------------------

# CSS Box Model & Button Styling

This file demonstrates:

- Chrome Developer Tools basics
- CSS Button Styling
- CSS Box Model
- Padding and Margin usage
- Smooth UI styling with CSS

------------------------------------------------

The webpage contains three styled buttons:

- Subscribe Button
- Join Button
- Tweet Button

The project mainly focuses on understanding the CSS Box Model and how spacing works in web design.

------------------------------------------------

It consists of:

- Content → Actual text or element
- Padding → Space inside the element
- Border → Outline around the element
- Margin → Space outside the element
---------------------------------------------------------------------------------------
# Text-Styles[04_text.html]

This code demonstrates how to style text using HTML and CSS.
It recreates a simple YouTube-style text layout and a promotional banner.

 ## The Web-page contains:

A video title
Video statistics
Channel information
Video description
A promotional banner with a hoverable "Shop now" text

## By bulding this page I learned a concept
By building this project, you practiced:
HTML paragraphs
CSS classes
Font styling
Margins & padding
Inline vs block elements
Hover effects
Span usage
Text alignment
Basic UI styling

-------------------------------------------------------------------------------------------
# 06[HTML-Structure]
# HTML Structure and Basic Buttons

## Overview
In this lesson, we learn about the basic structure of an HTML document and how different HTML tags divide a webpage into different sections.
We also learn how to create and style buttons using CSS properties like background color, padding, border radius, hover effects, and transitions.
---
# HTML Document Structure
A basic HTML document is divided into three main sections:

1. HTML Tag
2. Head Tag
3. Body Tag
## 1. HTML Tag (`<html>`)
The `<html>` tag represents the complete webpage.
It is the root element of an HTML document and contains all other HTML elements.
Example:
```html
<html>
   ...
</html>
```
Everything inside the webpage exists inside this tag.
---
## 2. Head Tag (`<head>`)
The `<head>` tag contains information about the webpage that is not directly visible on the browser page.
It stores metadata and resources required by the webpage.
Common elements inside the head section:

- `<title>` - Defines the webpage title
- `<meta>` - Provides metadata information
- `<link>` - Connects external files like CSS

Example:
```html
<head>
  <title>Buttons</title>
</head>
```
## 3. Body Tag (`<body>`)
The `<body>` tag contains all the content that is visible on the webpage.
Examples:
- Text
- Images
- Buttons
- Forms
- Videos
- Other HTML elements
Example:
```html
<body>
   <button>Subscribe</button>
</body>
```
# CSS Styling
CSS is used to design and style HTML elements.
In this project, CSS is used to create YouTube-style buttons.
# Button Components

## 1. Subscribe Button:

Features:
- Red background
- White text
- Rounded corners
- Hover opacity effect
- Cursor changes on hover
CSS properties used:

```css
background-color
color
border
padding
border-radius
cursor
transition
```
## 2. Join Button

Features:

- White background
- Blue border
- Blue text
- Changes color when hovered

Hover effect:

- Background becomes blue
- Text becomes white

---

## 3. Tweet Button

Features:

- Blue background
- Rounded shape
- Bold text
- Shadow effect on hover

CSS properties used:

```css
font-weight
box-shadow
transition
```

# CSS Concepts Learned

## 1. Class Selector

Classes are used to apply styles to specific HTML elements.
Example:

```html
<button class="subscribe-btn">
```
CSS:
```css
.subscribe-btn {
   background-color: red;
}
```
## 2. Hover Effect
The `:hover` pseudo-class applies styles when the mouse pointer moves over an element.
Example:

```css
button:hover {
   opacity:0.7;
}
```
## 3. Transition

The `transition` property creates smooth animation between two states.
Example:

```css
transition: opacity 0.15s;
```
# Project Structure

```
HTML-CSS-Learning/
│
├── index.html
└── README.md
```
# Key Learning Points

- Learned the basic structure of an HTML document.
- Understood the difference between HTML, Head, and Body tags.
- Learned how CSS styles HTML elements.
- Learned how to create reusable button styles using classes.
- Learned hover effects and smooth transitions.

# Technologies Used

- HTML5
- CSS3
# Output

A webpage containing three styled buttons:
- Subscribe Button
- Join Button
- Tweet Button
---------------------------------------------------------------------------------------
# [07-08]
# YouTube Clone - Basic HTML & CSS Structure

## Overview

In this lesson, we start building a basic YouTube clone interface using HTML and CSS.

We learn how to add images, create search bars, and structure video information like title, author, and views.

---
# Concepts Learned

## 1. Image Element (`<img>`)
The `<img>` tag is used to display images on a webpage.

Example:
```html
<img class="thumbnail" src="Images/thumbnail-1.webp">
```
-----------------------------------------------------------------------------------------
# [09-How div works]
# YouTube Clone - Video Preview Layout

## Overview

In this lesson, we start creating a basic YouTube clone interface using HTML and CSS.
The main focus of this project is understanding how webpages are structured using containers and how multiple elements can be arranged using CSS display properties.

This lesson introduces:
- Div elements
- Block elements
- Inline elements
- Inline-block elements
- Basic webpage layout creation
---

## HTML Concepts Learned

### 1. Div Element (`<div>`)

The `<div>` element is a container used to group multiple HTML elements together.
It does not create any visual change by itself but helps in organizing and controlling sections of a webpage.
Example:
```html
<div class="video-preview">
    <img>
    <p></p>
</div>
```
In this project, each video preview is wrapped inside a div container so that multiple videos can be styled and positioned together.
---

### 2. Image Element (`<img>`)
The image tag is used to display thumbnails on the webpage.
Example:
```html
<img class="thumbnail" src="Images/thumbnail-1.webp">
```
The `src` attribute specifies the location of the image.

---

## CSS Concepts Learned
### 1. Display Property
The `display` property controls how an element appears on the webpage.
Example:

```css
.video-preview {
    display: inline-block;
}
```
By default, a div behaves like a block element. Using `inline-block` allows multiple video containers to appear in the same row.

---

### 2. Inline-Block Layout

Inline-block elements:

- Take only the required width
- Allow other elements to appear beside them
- Support width and height properties

This property is useful for creating layouts like:

- YouTube video grids
- Product cards
- Image galleries

---

### 3. Margin Spacing
The `margin-right` property creates space between elements.

Example:

```css
margin-right: 15px;
```
It adds spacing between video previews.

---

## Element Types Learned

### Block Elements
Block elements take the full available width and start from a new line.

Examples:

- `<div>`
- `<p>`
- `<h1>`

---

### Inline Elements:-
Inline elements stay within the same line and only take required space.

Examples:

- `<strong>`
- `<span>`

---

### Inline-Block Elements

Inline-block elements combine properties of both block and inline elements.
They:
- Stay in the same line
- Allow width and height control
---

## Project Structure
```
YouTube-Clone/
│
├── index.html
├── Images/
│   ├── thumbnail-1.webp
│   └── thumbnail-2.webp
└── README.md
```

---
## Key Learning Points

- Learned how to use div as a container.
- Understood different types of HTML elements.
- Learned how to create reusable UI components.
- Learned how CSS display property controls layouts.
- Created a basic YouTube-style video preview section.

---
## Technologies Used

- HTML5
- CSS3

---
## Output
A basic YouTube clone layout containing:
- Search bar
- Video thumbnails
- Video titles
- Video authors
- Video statistics
Multiple video cards are displayed horizontally using CSS inline-block layout.
-----------------------------------------------------------------------------------------------------
# 10_youtube.html

# YouTube Clone - Nested Layouts Technique

## Overview

In this project, we continue building a YouTube clone interface using HTML and CSS.
The main focus of this lesson is learning the **Nested Layouts Technique**, where smaller layouts are combined together to create complex webpage structures.
A modern website is usually built by combining:

- Vertical layouts
- Horizontal layouts
- Grid layouts
- Flexbox layouts
- Nested containers

In this project, we create a complete YouTube-style page containing:

- Header navigation bar
- Sidebar navigation
- Search section
- Video grid
- Video cards
- Channel information
- Video duration labels
- Responsive layout

---

# Concepts Learned

## 1. Nested Layouts Technique

Nested layouts mean placing one layout inside another layout to create complex designs.
Example:
```html
<div class="video-preview">

    <div class="thumbnail-row">
        Image section
    </div>

    <div class="video-info-grid">
        Video information section
    </div>

</div>
```
Here:

- The main `video-preview` works as a container.
- Inside it, the thumbnail and video information are separate layouts.

This technique is widely used in real-world websites.

---
# Layout Types Learned

## 1. Vertical Layout
Vertical layouts arrange elements from top to bottom.
Example:

```html
<div class="thumbnail-row">
    <img>
</div>

<div class="video-info">
    <p>Title</p>
    <p>Author</p>
</div>
```
Used for:
- Thumbnail section
- Video details section
---

## 2. Horizontal Layout
Horizontal layouts arrange elements side by side.
Example:

```css
.video-info-grid {
    display: grid;
    grid-template-columns: 50px 1fr;
}
```
This creates:
```
Profile Picture | Video Information
```
Used for:
- Channel image
- Video title and details

---
# HTML Concepts Learned

## 1. Header Structure

The header is divided into three sections:
```html
<div class="header">

    <div class="left-section">
    </div>

    <div class="middle-section">
    </div>

    <div class="right-section">
    </div>

</div>
```

### Left Section

Contains:
- Hamburger menu
- YouTube logo
---

### Middle Section

Contains:
- Search input
- Search button
- Voice search button

---

### Right Section

Contains:
- Upload icon
- YouTube apps icon
- Notifications
- User profile

---

# 2. Sidebar Layout

The sidebar contains navigation links.

Example:
```html
<div class="sidebar-link">
    <img src="Images/home.svg">
    <div>Home</div>
</div>
```

Each sidebar item contains:
- Icon
- Text label

---
# 3. Video Card Component

Each video is created as a reusable component.
Structure:

```
Video Preview
│
├── Thumbnail
│
├── Video Duration
│
├── Channel Picture
│
├── Video Title
│
├── Author Name
│
└── Views and Date
```

---

# CSS Concepts Learned

## 1. CSS Grid

CSS Grid is used to create two-dimensional layouts.
Example:

```css
.video-grid {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
}
```
Creates:

```
Video 1 | Video 2 | Video 3
Video 4 | Video 5 | Video 6
```

---
## 2. Responsive Grid Layout

Media queries are used to change the number of columns according to screen size.

Example:

```css
@media(max-width:750px){
    .video-grid{
        grid-template-columns:1fr 1fr;
    }
}
```
The layout automatically adjusts for:

- Mobile screens
- Tablets
- Desktop screens

---
# 3. Flexbox Layout

Flexbox is used for arranging elements in a row.
Example:

```css
.header {
    display:flex;
    justify-content:space-between;
}
```

Used for:
- Header sections
- Navigation alignment
- Icon positioning

---
# 4. Position Property

The `position` property is used to place elements precisely.
Examples:
## Fixed Header

```css
.header {
    position:fixed;
    top:0;
}
```
Keeps the header visible while scrolling.

---
## Video Duration Overlay

```css
.video-time {
    position:absolute;
    bottom:8px;
    right:5px;
}
```
Places the time label over the thumbnail.

---

# 5. Tooltip Feature

Tooltips display extra information when hovering over icons.
Example:

```html
<div class="tooltip">
Search
</div>
```

CSS controls visibility:

```css
.tooltip{
    opacity:0;
}

button:hover .tooltip{
    opacity:1;
}
```

---

# 6. Google Fonts Integration

The project uses the Roboto font from Google Fonts.

Example:
```html
<link href="https://fonts.googleapis.com/css2?family=Roboto">
```
This improves typography and makes the UI closer to the original YouTube design.

---
# Important CSS Properties Used

| Property | Purpose |
|---|---|
| display:flex | Creates flexible layouts |
| display:grid | Creates grid layouts |
| grid-template-columns | Defines grid columns |
| position:fixed | Fixes elements on screen |
| position:absolute | Positions elements relative to parent |
| z-index | Controls layer priority |
| border-radius | Creates rounded shapes |
| transition | Creates smooth animations |
| cursor:pointer | Changes mouse cursor |
| media queries | Creates responsive designs |

---
# Responsive Design
The website adapts according to screen width.

Layouts:

### Small Screen
```
Video 1 | Video 2
```
### Medium Screen
```
Video 1 | Video 2 | Video 3
```
### Large Screen
```
Video 1 | Video 2 | Video 3 | Video 4
```

---
# Project Structure
```
YouTube-Clone/
│
├── index.html
│
├── 10_youtube.css
│
├── Images/
│   ├── youtube-logo.svg
│   ├── hamburger-menu.svg
│   ├── search.svg
│   ├── thumbnails
│   ├── channel images
│   └── icons
│
└── README.md
```
---

# Key Learning Points

- Learned how real websites are structured using nested layouts.
- Understood how multiple layouts combine to create complex UI.
- Learned the difference between vertical and horizontal layouts.
- Used CSS Grid for video arrangement.
- Used Flexbox for navigation layouts.
- Created reusable video card components.
- Learned responsive design using media queries.
- Added tooltips and overlay elements.
- Created a YouTube-style interface from scratch.

---
# Technologies Used

- HTML5
- CSS3
- CSS Grid
- Flexbox
- Google Fonts

---
# Output

A responsive YouTube clone interface containing:

- Fixed navigation header
- Sidebar menu
- Search functionality design
- Video grid layout
- Video thumbnails
- Channel pictures
- Video information
- Duration labels
- Hover tooltips

The project demonstrates how professional websites are created using nested layouts and modern CSS techniques.
----------------------------------------------------------------------------------------------------------------------------
# [11_grid.html]

# CSS Grid Layout Practice

## Overview
In this lesson, we learn about **CSS Grid Layout**, which is used to create complex webpage layouts using rows and columns.
Before CSS Grid, layouts were often created using `inline-block`, but it had alignment issues. CSS Grid provides a cleaner and more powerful way to arrange elements.

This lesson covers:-

- Introduction to CSS Grid
- Grid containers and grid items
- Rows and columns
- `grid-template-columns`
- Fraction units (`fr`)
- Column and row gaps
- Creating two-dimensional layouts

---
# Why CSS Grid?

`inline-block` can be used to place elements side by side, but it creates alignment problems because elements may not line up properly.
CSS Grid solves these problems by providing a structured layout system.
Grid allows developers to easily create layouts with:

- Multiple rows
- Multiple columns
- Precise sizing
- Better alignment

---
# CSS Grid Layout
CSS Grid is a **two-dimensional layout system**.

It works with:
- Rows
- Columns

Example:
```
Column 1 | Column 2 | Column 3
---------|----------|---------
 Item 1  |  Item 2  |  Item 3
 Item 4  |  Item 5  |  Item 6
```

---
# Grid Container

A grid container is the parent element where we apply:
```css
display: grid;
```
Example:
```css
.container {
    display: grid;
}
```
All direct children of the grid container automatically become **grid items**.

---
# Grid Items:-

Grid items are the direct children of a grid container.
Example:
```html
<div class="container">

    <div>Item 1</div>

    <div>Item 2</div>

</div>
```
Here:
- Parent div → Grid container
- Child divs → Grid items
---

# Grid Columns:-

## grid-template-columns
The `grid-template-columns` property defines:

- Number of columns
- Width of each column

Example:-
```css
grid-template-columns: 100px 100px;
```
Creates:
```
| 100px | 100px |
```
Two columns are created.
---
## Multiple Columns

Example:

```css
grid-template-columns: 100px 100px 200px;
```
Creates:

```
|100px|100px|200px|
```
Each value represents one column.

---

# Fraction Unit (`fr`)

The `fr` unit represents a fraction of available space.

Example:
```css
grid-template-columns: 1fr 1fr;
```
The available space is divided equally.
Layout:
```
| 50% | 50% |
```
---

Example:
```css
grid-template-columns: 1fr 2fr;
```

Layout:
```
| 1 part | 2 parts |
```
The second column receives twice the space of the first column.
---

# Combining Fixed and Flexible Columns
Example:

```css
grid-template-columns: 100px 1fr;
```
Meaning:
- First column → fixed 100px
- Second column → takes remaining space
  
Layout:

```
|100px| Remaining Space |
```

---

# Grid Rows

CSS Grid can also control rows.
Property:

```css
grid-template-rows
```
It defines:-
- Number of rows
- Height of rows
  
Example:

```css
grid-template-rows: 100px 200px;
```

Creates:

```
Row 1 → 100px
Row 2 → 200px
```
---
# Grid Gaps

Grid provides spacing between items using gap properties.

## Column Gap

Creates horizontal spacing.

Example:

```css
column-gap:20px;
```

Output:

```
Item 1   20px   Item 2
```

---
## Row Gap

Creates vertical spacing.
Example:

```css
row-gap:20px;
```

Output:

```
Item 1

20px gap

Item 2
```

---
# Difference Between Flexbox and Grid

| CSS Grid | CSS Flexbox |
|---|---|
| Two-dimensional layout | One-dimensional layout |
| Works with rows and columns | Works with row OR column |
| Used for complex layouts | Used for smaller component layouts |
| Controls entire page structure | Controls individual sections |

---
# Grid Structure

Example:

```css
.container {
    display:grid;
    grid-template-columns:1fr 1fr 1fr;
}
```
Creates:
```
--------------------------------
| Item 1 | Item 2 | Item 3 |
--------------------------------
| Item 4 | Item 5 | Item 6 |
--------------------------------
```
---
# Important CSS Grid Properties

| Property | Purpose |
|---|---|
| display:grid | Creates a grid container |
| grid-template-columns | Defines column count and width |
| grid-template-rows | Defines row count and height |
| grid-template-areas | Defines named grid sections |
| column-gap | Adds space between columns |
| row-gap | Adds space between rows |
| gap | Adds space between rows and columns |

---
# Code Examples Covered
## Equal Columns

```css
grid-template-columns:1fr 1fr 1fr;
```

Creates three equal columns.

---
## Different Column Sizes

```css
grid-template-columns:100px 1fr 2fr;
```
Creates:

- Fixed column
- Flexible column
- Double-sized flexible column

---
## Grid With Spacing

```css
grid-template-columns:1fr 1fr 1fr;
column-gap:20px;
row-gap:20px;
```
Creates equal columns with spacing between items.

---
# Key Learning Points

- Learned why CSS Grid is preferred over inline-block for layouts.
- Understood grid containers and grid items.
- Learned how rows and columns work.
- Learned how to define column sizes.
- Learned the use of `fr` units.
- Learned how to create responsive layouts using grid.
- Learned how to control spacing using gaps.
- Understood the difference between CSS Grid and Flexbox.

---
# Technologies Used

- HTML5
- CSS3
- CSS Grid Layout

---
# Output

A practice webpage demonstrating different CSS Grid layouts:

- Fixed-width columns
- Flexible columns using `fr`
- Multiple column structures
- Equal grid layouts
- Row and column spacing

This lesson builds the foundation for creating modern website layouts using CSS Grid.

--------------------------------------------------------------------------------------------------------
# 12_Flexbox.html

# CSS Flexbox Practice

## Overview
In this lesson, we learn about **CSS Flexbox (Flexible Box Layout)** and how it is used to arrange elements inside a container.
Flexbox provides an easier way to create layouts compared to traditional methods like `inline-block`.

The main focus of this lesson is understanding:

- Flex containers
- Flex items
- Row layouts
- Flexible sizing
- Content alignment
- Space distribution
- Vertical alignment

---

# What is CSS Flexbox?

Flexbox is a CSS layout system used to arrange elements inside a container.
It helps developers easily create:
- Horizontal layouts
- Vertical layouts
- Responsive designs
- Proper alignment between elements

Flexbox is a **one-dimensional layout system**, meaning it works with either:
- Rows
- Columns

Example:
```
Item 1 | Item 2 | Item 3
```
---

# Flex Container
A flex container is created by applying:

```css
display: flex;
```

Example:
```css
.container {
    display:flex;
}
```

All direct children of the container automatically become **flex items**.
---

# Flex Direction:-
The `flex-direction` property defines the direction in which flex items are arranged.

## Row Direction

Default behavior:
```css
flex-direction: row;
```
Elements are placed horizontally.
Example:

```
| Item 1 | Item 2 | Item 3 |
```
---

## Column Direction

Elements can also be arranged vertically:
```css
flex-direction: column;
```

Example:
```
Item 1

Item 2

Item 3
```

---

# Flex Property

## flex: 1
The `flex` property controls how much space an item takes inside the container.

Example:
```css
.second-box {
    flex:1;
}
```
Meaning:

- The element takes all available remaining space.
- Other fixed-width elements keep their size.

Example:
```html
<div style="width:100px">
</div>

<div style="flex:1">
</div>
```
Output:

```
|100px| Remaining Space |
```

---
# Justify Content

The `justify-content` property controls the alignment of items along the main axis.

---
## Center Alignment
Example:

```css
justify-content:center;
```

Output:
```
      Item 1 Item 2 Item 3
```

Items move to the center of the container.

---

## Space Between

Example:

```css
justify-content:space-between;
```

The first item stays at the start, the last item stays at the end, and equal space is added between items.
Output:

```
Item 1        Item 2        Item 3
```

---
# Align Items

The `align-items` property controls alignment along the cross axis.

Example:

```css
align-items:center;
```
It vertically centers items inside the container.

Example:

```
-----------------
|               |
| Item  Item    |
|               |
-----------------
```

---

# Flexbox vs CSS Grid

| Flexbox | CSS Grid |
|---|---|
| One-dimensional layout | Two-dimensional layout |
| Works with rows OR columns | Works with rows AND columns |
| Best for components | Best for complete page layouts |
| Easier alignment | More control over complex structures |

---

# Important Flexbox Properties

| Property | Purpose |
|---|---|
| display:flex | Creates a flex container |
| flex-direction | Defines row or column direction |
| flex | Controls item size flexibility |
| justify-content | Aligns items horizontally |
| align-items | Aligns items vertically |
| gap | Creates spacing between items |

---

# Examples Covered

## Basic Flex Layout

```css
display:flex;
flex-direction:row;
```

Creates a horizontal arrangement.
---

## Flexible Item

```css
flex:1;
```

Allows an element to occupy remaining space.

---

## Centering Items

```css
justify-content:center;
```

Places items in the center of the container.

---

## Equal Spacing

```css
justify-content:space-between;
```

Creates equal space between flex items.

---

## Vertical Alignment

```css
align-items:center;
```

Centers items vertically inside the container.

---

# Key Learning Points

- Learned the basics of CSS Flexbox.
- Understood flex containers and flex items.
- Learned how to arrange elements horizontally.
- Learned how `flex:1` distributes available space.
- Learned horizontal alignment using `justify-content`.
- Learned vertical alignment using `align-items`.
- Understood the difference between Flexbox and CSS Grid.

---

# Technologies Used

- HTML5
- CSS3
- CSS Flexbox

---

# Output

A practice webpage demonstrating different Flexbox layouts:
- Basic row layout
- Flexible width elements
- Center-aligned items
- Space-between alignment
- Vertically centered elements
This lesson builds the foundation for creating modern responsive layouts using CSS Flexbox.
------------------------------------------------------------------------------------------------------------
# [Lecture 15-16] contains Positioning.

# CSS Positioning

## Overview:-
In this lesson, we learn about **CSS Positioning**, which is used to control how elements are placed on a webpage.
CSS positioning allows developers to move elements, create overlays, fix elements on the screen, and build complex layouts.

The main topics covered in this lesson are:

- Static positioning
- Relative positioning
- Absolute positioning
- Fixed positioning
- Sticky positioning
- Position offsets
- Layering using z-index

---
# What is CSS Positioning?

CSS positioning defines how an element is placed inside a webpage.
The `position` property controls the positioning behavior of an element.

Syntax:
```css
.element {
    position: value;
}
```
CSS provides five main position values:

1. Static
2. Relative
3. Absolute
4. Fixed
5. Sticky

---
# 1. Static Positioning

## `position: static`
Static is the default position of every HTML element.
Example:

```css
div {
    position: static;
}
```
Characteristics:

- Elements follow the normal document flow.
- `top`, `right`, `bottom`, and `left` properties do not work.
- Elements appear according to their normal HTML order.
- 
Example:
```
Element 1

Element 2

Element 3
```
---
# 2. Relative Positioning

## `position: relative`
Relative positioning moves an element relative to its original position.

Example:
```css
.box {
    position: relative;
    top: 20px;
    left: 30px;
}
```

The element moves:
- 20px downward
- 30px to the right

Important:

The original space of the element is still preserved.
Example:

Before:
```
Box
```

After
```
        Box
```

The empty original position remains.
---

# 3. Absolute Positioning

## `position: absolute`

Absolute positioning removes an element from the normal document flow.
The element is positioned relative to its nearest positioned parent.

Example:

```css
.child {
    position:absolute;
    top:0;
    right:0;
}
```
Common usage:

- Badges
- Icons
- Overlays
- Image labels

Example:
```
-------------------
|             X   |
|                 |
|     Image       |
|                 |
-------------------
```

---

# Parent-Child Relationship in Absolute Positioning

Usually, the parent is given:
```css
.parent {
    position:relative;
}
```

The child uses:
```css
.child {
    position:absolute;
}
```

Example:
```html
<div class="parent">

    <div class="child">
        Text
    </div>

</div>
```

CSS:
```css
.parent {
    position:relative;
}

.child {
    position:absolute;
    right:10px;
}
```

The child is positioned inside the parent container.

---

# 4. Fixed Positioning

## `position: fixed`

Fixed positioning attaches an element to the browser window.
The element stays in the same place even while scrolling.

Example:
```css
.header {
    position:fixed;
    top:0;
}
```
Common examples:

- Navigation bars
- Chat buttons
- Floating buttons

Example:

```
----------------
 Header
----------------


Content


Content
```

The header remains visible.

---

# 5. Sticky Positioning

## `position: sticky`

Sticky positioning is a combination of:

- Relative positioning
- Fixed positioning

The element behaves normally until a scrolling limit is reached, then it sticks.
Example:

```css
.sidebar {
    position:sticky;
    top:0;
}
```
Common usage:

- Sticky navigation
- Table headers
- Sidebars

---
# Position Offset Properties

Positioned elements can be moved using:

## Top

Moves element downward.
```css
top:20px;
```

---
## Bottom

Moves element upward.

```css
bottom:20px;
```

---
## Left

Moves element right.

```css
left:20px;
```

---
## Right

Moves element left.

```css
right:20px;
```

---
# Z-Index

## Layer Control

`z-index` controls which element appears above another element.

Example:

```css
.header {
    z-index:100;
}
```
Higher z-index elements appear on top.

Example:

```
z-index:10

Image


z-index:100

Header
```
Header appears above the image.

---
# Positioning Example

## Image With Text Overlay
HTML:

```html
<div class="container">

<img src="image.jpg">

<div class="text">
10:30
</div>

</div>
```

CSS:

```css
.container {
    position:relative;
}

.text {
    position:absolute;
    bottom:10px;
    right:10px;
}
```

Output:

```
----------------
|              |
|    Image     |
|          10:30|
----------------
```
---

# Common Real-World Uses

## Fixed Header

Used in websites like YouTube.

```css
.header {
    position:fixed;
    top:0;
}
```
---

## Video Duration Label

Used on video thumbnails.

```css
.time {
    position:absolute;
    bottom:5px;
    right:5px;
}
```

---

## Notification Badge

Example:

```css
.notification {
    position:absolute;
    top:-5px;
    right:-5px;
}
```

---

## Floating Buttons

Example:

```css
.button {
    position:fixed;
    bottom:20px;
    right:20px;
}
```

---

# Difference Between Position Types

| Position | Description |
|---|---|
| Static | Default position |
| Relative | Moves from original location |
| Absolute | Positioned relative to parent |
| Fixed | Attached to browser window |
| Sticky | Sticks during scrolling |

---

# Important CSS Properties

| Property | Purpose |
|---|---|
| position | Defines positioning method |
| top | Moves element downward |
| bottom | Moves element upward |
| left | Moves element right |
| right | Moves element left |
| z-index | Controls element stacking order |

---

# Key Learning Points

- Learned how CSS positioning works.
- Understood different position values.
- Learned how relative and absolute positioning work together.
- Learned how fixed elements stay visible while scrolling.
- Learned how sticky elements behave during scrolling.
- Learned how to control element layering using z-index.
- Learned how positioning is used in real-world websites.

---

# Technologies Used

- HTML5
- CSS3

---

# Output

After completing this lesson, you can create:

- Fixed navigation bars
- Overlay text on images
- Notification badges
- Floating buttons
- Layered UI components
- Advanced webpage layouts

CSS positioning is an essential concept for building modern responsive websites.
