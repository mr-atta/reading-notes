# 15 : Layout <dr><br>

### Building Blocks 
<br>

> CSS and HTML element are be in boxs. This box wil be a block-level box or an inline box.

![inline and block](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/06/Block-level-Inline-elements-in-html-df.jpg)
> Block-level elements start on a new line 
* Examples include:
     * `<h1> <p> <ul> <li>`

> Inline elements flow in between surrounding text
 * Examples include:
     * `<img> <b> <i>`


* "CSS has the following **positioning schemes** that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property."
 * ![positioning schemes](https://www.internetingishard.com/html-and-css/advanced-positioning/css-positioning-schemes-summary-d7f831.png)
   * Normal flow    
   * Relative Positioning
   * Ab solute positioning

* box offset 
  ![box offset ](https://i1.wp.com/css-tricks.com/wp-content/uploads/2019/06/after_hov.png?ssl=1)
  * to tell the browser how far from the top or bottom and left or right it should be placed. (will help in css)

* normal flow
  * position:static
* Relative positioning
  * position:relative
* Absolute Positioning    
  * position:absolute
*   Fixed Positioning
  * position:fixed
* Articlapping Elements
  * z-index
* Floating Elements  
  * float 
* Clearing Floats
  * clear
    * left , right , both , none
  


## Screen Sizes
![ Screen Sizes](https://www.airscreen.com/fileadmin/_processed_/8/b/csm_AIRSCREEN_Size-Overview_new_4018a50f7d.jpg)
* Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

### Screen Resolution
![Resolution](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzaB5H-ZW23hX8RTCAIWQbLQB_8pBN-AqgiA&usqp=CAU)
* Resolution refers to the number of dots a screen shows per inch.

## Fixed Width Layouts 
* Fixed width layout designs do not change size as the user increases or decreases the size of their browser window.
- advantages of fixed-width design:
   - The basic layout of the page remains the same regardless of canvas size.
   - Fixed-width pages and columns provide better control over line lengths
   - Elements may shift unpredictably if the font size in the browser is larger or smaller than the font size used in the design process.

- disadvantages of fixed-width design:
   - You can end up with big gaps around the edge of a page.
   - If a user increases font sizes, text might not fit into the allotted spaces.
   - The design works best on devices that have a site or resolution similar to that of desktop or laptop computers.
![Fixed Width Layouts ](https://internetingishard.netlify.app/fixed-width-vs-fluid-layouts-258df9.e0ad9d98.png)


## Liquid Layouts
* Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window.
![Liquid Layouts](https://3wga6448744j404mpt11pbx4-wpengine.netdna-ssl.com/wp-content/uploads/2014/07/liquid.png)