# Links
![Links](https://www.litmus.com/wp-content/uploads/2020/04/the-ultimate-guide-to-removing-blue-links-in-email.png)

* Links, allow you to move from one web page to another
* Browsers show links in blue with an underline by default.
* types:
  * Links from one website to another
  * Links from one page to another on the same website
  * Links from one part of a web page to another part, same page
  * Links that open in a new browser window
  * Links that start up your email and address a new email to someone

### Writing Links
* using `<a>` tage 
* `<a href="the link here">the click</a>`
![link](https://i0.wp.com/digitalfortress.tech/wp-content/uploads/2018/05/mail-to.png?resize=672%2C377&ssl=1)
* The text between the opening and closing tag is known as link text.
* "To write good link text, you can think of words people might use when searching"

## Linking to Other Sites
* href be in the opening tag 
* " The value of the href attribute is the page that you want people to go to when they click on the link."(href content the full web address for the site "absolute URL").
* the link be between the opening `<a>` tag and the closing `</a>`

## Linking to Other Pages on the Sa me Site
* using a shorthand " relative URL "
![URL](https://www.87android.com/wp-content/uploads/2014/02/absolut-relative-url-html.png)


### Directory Structure
![Directory Structure](https://static.packt-cdn.com/products/9781783552092/graphics/2092OT_01_07.jpg)
* " FolderName " / " FileName "

### folders
> index.html  is the homepage


### Relative Link Type
 * Same folder: href="reviews.html"
 * Child Folder: href="music/listings.html"
 * Grandchild Folder: href="movies/dvd/reviews.html"
 * Parent Folder: href="../index.html"
 * GrandParent Folder: href="../../index.html"

## Email Links 
* mailto: href="mailto:jon@example.org"

## Opening Links in a New Window 
* target: href="http://www.imdb.com"

## Linking to a Specific Part of the Same Page
* " At the top of a long page you might want to add a list of contents that links to the corresponding sections lower down. Or you might want to add a link from part way down the page back to the top of it to save users from having to scroll back to the top."

## Linking to a Specific Part of Another Page
* If you want to link to a specific part of a different page you can use a similar technique.

![Links](https://i1.wp.com/css-tricks.com/wp-content/uploads/2018/09/nested-links.png?ssl=1)



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

   ![computer](https://clever-solution.com/wp-content/uploads/2020/02/55%D0%9C%D0%BE%D0%BD%D1%82%D0%B0%D0%B6%D0%BD%D0%B0%D1%8F-%D0%BE%D0%B1%D0%BB%D0%B0%D1%81%D1%82%D1%8C-4.png)
   
# js 
## This chapter is divided into three sections that introduce:
* FUNCTIONS & METHODS :"consist of a series of statements together because they perform a specific task."
* BUILT-IN OBJECTS :use to create models of the world using data
* OBJECTS :"The browser comes with a set of objects that act like a toolkit for creating interactive web pages."

![FUNCTION](https://www.freecodecamp.org/news/content/images/size/w2000/2021/03/javascript-map-function.png)
## * WHAT IS A FUNCTION? *
> Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of st atements).

* we ** call ** the function when we want it to make the sentences.
* When we want the Function to be flexible, we use the **parameters**.
* When we want the return something to use, we use the **Return**.

## Declaring a function
![Declaring a function](https://scriptverse.academy/img/tutorials/js-nested-functions.png)
* when we need to call function we will use the * '**name**+**(**parameters"if there are"**)**' *.
