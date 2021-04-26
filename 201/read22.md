# HTML 
## Text 
![Text](https://miro.medium.com/max/5376/1*vTmkPWNzpwrQ7x1GAr2MEg.jpeg)
### Headings
  * from h1 to h6
  > `<h1>` .... `<h6>`
  * h1 is the main heading, then we have subheadings.
  * ` If there are further sections under the subheadings then the element is used this element `

### Paragraphs 
  * `<p>`  , consists of one or more sentences.
### Bold & Italic
  * `<b>`
  * `<i>`
  * used in the Paragraph

### Superscript & Subscript 
  * `<sup>`  , used : power number
  * `<sub>`  , used : foot notes or chemical formulas

* In code the White Space  (more than one) is not eficted on the output, `This is known as white space collapsing`.

### Line Breaks & Horizontal Rules
* `<br />` add a line break inside the paragraph. " Line Breaks "
* `<hr />` add a horizontal rule between sections. " Horizontal Rules "

## Visual Editors & Their Code views
- `Visual Editors : often resemble word processors, If you copy and paste text from a program that allows you to format text.`
- `Code views : show you the code created by the visual editor so you can manually edit it, or so you can just enter new code yourself.`

### Strong & Emphasis
* `<strong>`  for importance content, the content will be bold.
* `<em>` "emphasis" changed the content , the content will be italic.
* used in Paragraph

### Quotations 
* `<q>` used for short quotation, in Paragraph.
* `<blockquote>`  when all the Paragraph was a quotation.

### Abbreviations
* for html5
* `<abbr>` When the mouse stopped on the word to make you the text of the title.
### Citations & Definitions
* `<cite>`  Citation
* `<dfn>`  Definition
*  used in Paragraph

### Author Details
* contact author details, like:physical address,phone number,email address.
* `<address>` 

### Changes to Content
* `<ins>`  insert, underline 
* `<del>`  delete 
* `<s>`  strikethrough 

# CSS 
> What CSS does??  CSS will treat each element as if it lives inside its own box

![html css](https://i2.wp.com/xomisse.com/wp-content/uploads/2016/02/difference-between-html-and-css.png?resize=800%2C301&ssl=1)

## BLOCK & INLINE ELEMENTS 
> "In this example, block level elements are shown with red borders, and inline elements have green borders. The `<body>` element creates the first box, then the `<h1>`, `<h2>`, `<p>`, `<i>`, and `<a>` elements each create their own boxes within it.
Using CSS, you could add a border around any of the boxes".

* Example of what you can do with Boxes: Width and height , Background color , Borders (color, width, and style) , Position in the browser window
* Example of what you can do with Text: Typeface , Size , Color ,Italics, bold, uppercase, lowercase, small-caps .

## CSS Associates Style rules with HTML elements 
> CSS `works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.`
![css1](https://images.slideplayer.com/32/9811421/slides/slide_5.jpg)

### How Elements Are Displayed
> CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon.
![css2](https://cf.ppt-online.org/files/slide/d/Dy0uOmegJq5ExPrNzKUj2QStWlGRwHYA4Zkas1/slide-2.jpg)

## Using External CSS 
* special file for css , linked to HTML file in head.
![css link](https://matthewjamestaylor.com/img/illustrations/large/adding-css-to-html-with-link-embed-inline-and-import.jpg)

* three attributes: href , type , rel 
 ## Using Internal CSS
* write in the head by `<style>`
* just one file 

## CSS Selectors 
> There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document.
* Class Selector : mentioned using . , in style  
* ID Selector : mentioned using #  , in style 

## Why use External Style Sheets?
* All pages of your web can share the same style sheet, by using link.
* If you want to make a change to how your site appears, you only need to edit the one CSS file.
* The HTML code will be easier to read and edit.

# JS
## STATEMENTS 
> `A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement.`
* Example: 
> var today= new Date{); 
> var hourNow = today.getHours{) ; 
> var greeting;

## COMMENTS 
* used to explain what your code does.
* Just the programer can see it
* /* the COMMENT */  , multiline
* // the COMMENT   , single line

## WHAT IS A VARIABLE? 
* Is the pocket we put something in it. It can differentiate between data types and the value. 
* var  quantity ;

* var  quantity = 3 ;
or 
* var  quantity = '3' ;

### DATA TYPES 
1. NUMERIC
2. STRING
3. BOOLEAN

![var](https://simplesnippets.tech/wp-content/uploads/2018/10/variables-and-datatypes-in-JavaScript-featured-image.jpg)
* we can created an Array


# Operators
![Operators](https://simplesnippets.tech/wp-content/uploads/2018/03/operators-in-cprogramming-featured-image.jpg)
* We have many Operators 
  - *
  - +
  - -
  - /
  - ==
  - !=
  - !==
  - ===
  - <
  - >
  - <=
  - >=
* The priority of parentheses must be observed'()'
* from left to right
### AND , OR , not
>like: (var == '1' && var < '10')

![AND , OR , not](https://i.pinimg.com/originals/79/ed/b1/79edb138611e6bc382066860c6fa3d2b.jpg)


## Loops
![loop](https://image.shutterstock.com/image-vector/loop-logo-vector-ribbon-lettering-260nw-1425991553.jpg)
* It works on checking the condition if it is true entry into the block.
* type of loops:
  - for 
  - while
  - do  while

### for
* when you have a specific number of runs.
* The most common.
* The counter(var) often starts at zero.
* Every time one counter increases.
* When the condition becomes "f" out of the block.
![for](https://www.javascripttutorial.net/wp-content/uploads/2020/01/JavaScript-for-Loop.png)

### while 
* The meter usually starts with 1.
* The increase over the counter is in the block.
* Statement 1: '= +' Used to add new content to var 'msg' every run.
* Statement 2: Increase counter variable by 1.
![if](https://cdn-media-1.freecodecamp.org/images/1*XJvkwoG4BLFnx6tpfzPZQQ.jpeg)

* Make sure not to fall into a trap of the infinity loop.&#127773;
![infinity loop](https://i.pinimg.com/236x/4f/ba/10/4fba1042ff907e92f84a60fef19d57e4--housewife-humor-pie-charts.jpg)

