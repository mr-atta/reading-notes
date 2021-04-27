# HTML 
## Lists
![Lists](https://media.gcflearnfree.org/content/5e46ef60397c182fec255f32_02_14_2020/lists.png)
* there are three types of list:
   ### Ordered lists  
   * each item has a number 
    - `<ol>`
       -  `<li>`
   * Each item in the list is placed between an opening "li" tag, and all "li" tags be inside "ol" tag.

  ### Unordered lists  
  * with a bullet point
   - `<ul>`
       -  `<li>`
   * Each item in the list is placed between an opening "li" tag, and all "li" tags be inside "ul" tag.

  ### Definition lists  
  * terms with the definition for each term
  - `<dl>`
       -  `<dt>`  , being defined
       -  `<dd>`  , contain the definition
    * Each item in the list is placed between an opening "dt" tag and "dd" tag, and all "li" tags be inside "dl" tag.

 ### And Nested Lists 
 * "You can put a second list inside an `<li>` element to create a sublist or nested list."

# CSS
## Boxes
### Box Dimensions 
* width, height 
* using pixels, percentages, or ems.

### Limiting Width
* min-width, max-width 
* user's screen
* min-width : smallest size a box can be displayed
* max-width : maximum width a box

### Limiting Height
* min-height, max-height
* height or minmum limit properties. 

### Overflowing Content 
![Overflowing Content ](https://www.tutorialandexample.com/wp-content/uploads/2020/10/CSS-Overflow.png)
* overflow 
   * hidden " This property simply hides any extra content that does not fit in the box "
   * scroll " This property adds a scrollbar to the box so that users can scroll to see the missing content. " 

## Border, Margin & Padding 
![Border, Margin & Padding](https://www.differencebetween.com/wp-content/uploads/2014/12/Difference-Between-Margin-and-Padding.png)
* Border
  * " Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another."
* Margin 
  * Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.
* Padding
  * Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.

### Border Width
* border-width 
* values: thin ,  medium , thick
* control size like :
    * border-top-width
    * border-right-width
    * border-bottom-width
    * border-left-width

### Border Style
* border-style  , solid or dotted or dashed or double or groove or ridge or inset or outset or hidden / none 

### Border Color 
* border-color  , and pick the color 

### Shorthand
* border 
* allows you to specify the width, style and color of a border in one property 

### padding 
* "padding  , allows you to specify how much space should appear between the content of an element and its border."

### margin 
* "The margin property controls the gap between boxes. Its value is commonly given in pixels, although you may also use percentages or ems."

### centering content 
* text-align: center;

### display
* display
  * inline
  * block 
  * inline-block
  * none

### Hiding Boxes
* visibility 
   * hidden
   * visible

## CSS3: Border Images
* border-image
   * stretch 
   * repeat 
   * round 

* box-shadow 
   * Horizontal offset 
   * Vertical offset
   * Blur distance
   * Spread of shadow   

* border-radius
   * border-top-right-radius
   * border-bottom-right-radius
   * border-bottom-left-radius
   * border-top-left-radius   

* border-radius 
   * To create more complex shapes
   

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
* var  quantity = value ;


### DATA TYPES 
1. NUMERIC
2. STRING
3. BOOLEAN

![var](https://simplesnippets.tech/wp-content/uploads/2018/10/variables-and-datatypes-in-JavaScript-featured-image.jpg)
* we can created an Array


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

      