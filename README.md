# [Typesetting on the web](http://scottdejonge.com/typesetting)

This example should prove that through using simple <abbr title="Cascading Style Sheets">CSS</abbr>, and semantic <abbr title="Hypertext Text Markup Language">HTML</abbr>, along with effective typesetting design content can be visually appealing whilst also being natively accessible, responsive, and performant.

* * *

## <small>Chapter 1:</small> Problem space

In order to properly define the problem space we will set design limitations to ensure there are objective outcomes to the design process. These design limitations are as follows:

1.  _Less is more:_ the download payload for all styles, assets, and markup should be minised as much as possible.
2.  _Keep it simple:_ all styles should be defined using simple, modern, and understandable <abbr title="Cascading Style Sheets">CSS</abbr> properties, this means no opinionated development workflows such as Sass, Less etc.
3.  _Effecient design is good design:_ whilst we should minimise technical understanding, this should not interfere with reusable well defined code, therefore we will utlilise PostCSS, Autoprefixer and CSSNext to automate cross-browser compatiblity.
4.  _Legibility is key:_ we will use a well structured typeface ([<abbr title="Edward Tufte">ET</abbr> Book](https://edwardtufte.github.io/et-book/)) along with formatted <abbr title="Hypertext Text Markup Language">HTML</abbr> tags to emphasis content.
5.  _Easy reading:_ we will use a high contrast color palette (<abbr title="Web Content Accessibility Guidelines 2.0 AAA">WCAG 2.0 AAA</abbr>) and scaling vertical rythym to provide a clear visual heriarchy context.

* * *

## <small>Chapter 2:</small> Objectives

To better measure the success of typesetting design on the web we will set the objectives of this example as the following:

*   _Clarity:_ we will measure the clarity of the typographic design through automatic accessibility testing, ensuring culor contrast and <abbr title="Document Object Model">DOM</abbr> tree heriarchy pass <abbr title="Web Content Accessibility Guidelines 2.0 AAA">WCAG 2.0 AAA</abbr> guidelines
*   _Consistancy:_ we will ensure the consistant rendering of the design across browsers, mediums (screens and print), and devices.

* * *

## <small>Chapter 3:</small> Challenges

<q>Lets move away from the learnt habits</q> I thought to myself,

* * *

## <small>Chapter 4:</small> Fonts

<q>Lets move away from the learnt habits</q> I thought to myself,

* * *

## <small>Chapter X:</small> The cascade

Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Cras justo odio, dapibus ac facilisis in, egestas eget quam. Vestibulum id ligula porta felis euismod semper. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Curabitur blandit tempus porttitor. Maecenas faucibus mollis interdum.

> Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Maecenas faucibus mollis interdum.
> 
> <cite>John Doe</cite>

Aenean eu leo quam. Pellentesque ornare sem lacinia quam venenatis vestibulum. Cras justo odio, dapibus ac facilisis in, egestas eget quam. Vestibulum id ligula porta felis euismod semper. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus. Curabitur blandit tempus porttitor. Maecenas faucibus mollis interdum.

* * *

## <small>Chapter X:</small>Markup & styles

Predicatable and reusable. Use the correct markup

### Headings

# Heading 1 <small>Heading 1 small</small>

## Heading 2 <small>Heading 2 small</small>

### Heading 3 <small>Heading 3 small</small>

#### Heading 4 <small>Heading 4 small</small>

##### Heading 5 <small>Heading 5 small</small>

###### Heading 6 <small>Heading 6 small</small>

### Paragraph

An example of paragraph content that is sizes at 1em of the root font size of the document.

### Link

[link](#)

### Strong

**strong**

### Emphasis

_emphasis_

### Abbreviation

<abbr title="In case you missed it">ICYMI</abbr>

### Small

<small>small</small>

### Horizontal Rule

* * *

### Quote

<q>A quote</q>

### Blockquote

> A blockquote

### Cite

<cite>A citation</cite>

### List

*   Unordered list

1.  Ordered List

### Definition List

<dl>
<dt>Definition term</dt>
<dd>Definition</dd>
</dl>

### Code

`code`

### Pre

    Hello World

### Kbd

<kbd>ctrl</kbd> + <kbd>s</kbd>

### Mark

<mark>mark</mark>

* * *