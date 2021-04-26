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
   
      