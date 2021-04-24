# *HTML* 
  ** (Hyper Text Markup Language) **

  ![HTML](https://cdn.lynda.com/course/170427/170427-637363828865101045-16x9.jpg)

## How to build HTML Structure ??
 * HTM L Us es El ements to Describe the Structure of Pages.
 * Each element has an opening tag and a closing tag.

## ***Tags***
   ![Tags](https://miro.medium.com/max/834/1*btGyl3NCaO-QKLxq8KEDCA.png)
 * tags are like command in HTML, its have an opening tag and ending tag.
 * The characters in the brackets indicate the tag's purpose.

![Tag](https://tutorial.techaltum.com/images/element.png)

- *Attributes Tell Us More Extra Information*
  - It should be  written in lowercase
  - The value is the information, It should be placed in double quotes
  - like : lang
    -  > To denote the language used 
 ![lang](https://cms-assets.tutsplus.com/uploads/users/30/posts/31961/preview_image/lang-pre.png)
 - The majority of attributes can only be used on certain elements

![html tag](https://i.pinimg.com/originals/c3/16/b8/c316b804abc25e9b1c509b1a96d5c9f6.jpg)

* In HTML5 you should include DOCTYPEs in the first , as 
  - <!DOCTYPE html> 
* Comments in HTML 
  - <!-- the comment be here -->
  * the comment will not be visible to user's
* ID in HTML 
  - for one element 
  - to identify special element from other elements
  - to do special css 
* Class in HTML
  - like id, but to more than one element
* Block Elements
  - start on a new line in the browser window, when we have many statements
  - Examples : `<h1>`, `<p>`, `<ul>`, `<li>`
* Inline Elements
  - Some elements be on the same line
  - Examples : `<a>`, `<b>`, `<em>`, `<img>`

* `<div>` , Grouping Text & Elements In a Block
 > group elements together in block 
* `<span>` , Grouping Text & Elements Inline
* IFrames
  - a little window in your page, in that window you can see another page.
  - you will need 
    - src
    - height
    - width

* Information About Your Page
  * ` <meta> `
  * inside the ` <head> `
  * not visible to users

# __HTML5 Layout __
   ![HTML4,5](https://coursework.vschool.io/content/images/2018/01/html5_sectioning_high_level.jpg)
    > what is the difference ?? 
 ## `<header>` `<footer>`
 *  The main header or footer that appears      at the *top* or *bottom* of every page on       the site.
 * header using h : __h1 to h6__

## Navigation  `<nav>`
* The <nav> element is used to contain the     major navigational blocks on the site such   as the primary site navigation. 
* usually contain **: ul : li : a**

## Articles  `<article>`
* The <article> element acts as a container    for any section of a page that could stand   alone and potentially be syndicated.
* If a page contains several articles (or      even summaries of several articles), then    each individual article would live inside    its own `<article>` element.
## Article  `<aside>` 
* The element has two `<aside>` purposes, depending on whether it is inside an `<article>` element or not.
* When the `<aside>` element is used inside an `<article>` element, it should contain information that is related to the article.
* When the `<aside>` element is used outside of an `<article>` element, it acts as a container for content that is related to the entire page.

## Sections `<section>`
* The <section> element groups related content together, and typically each section would have its own heading.
## Heading Groups `<hgroup>`
* The purpose of the `<hgroup>` element is to group together a set of one or more `<h1>` through <h6> elements so that they are treated as one single heading.

## Figures `<figure>` `<figcaption>`
* It is important to note that the article should still make sense if the content of the `<figure>` element were moved (to another part of the page, or even to a different page altogether).
* Examples of usage include:
  * Images
  * Videos
  * Graphs
  * Diagrams
  * Code samples
  * Text that supports the main
  * body of an article
* The `<figure>` element should also contain   a `<figcaption>` element which provides a    text decription for the content of the       `<figure>` element.
## Sectioning Elements  `<div>`
* It may seem strange to follow these new      elements by revisiting the `<div>` element   again.
*  the `<div>` element will remain an           important way to group together related      elements
* The new elements provide clearer code (compared with using multiple `<div>` elements).

&nbsp &nbsp 

* ___ Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements. ___
# Process & Design
* Example Site Map : 

output: &nbsp ___HTML & CSS: Design and Build Web Sites___
  bookdown::https://documentcloud.adobe.com/link/review?uri=urn:aaid:scds:US:25671887-83dc-4fff-81c7-469ffdd4112e: default