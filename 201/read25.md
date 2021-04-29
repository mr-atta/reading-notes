# HTML 

## Image
![Image](https://media.sproutsocial.com/uploads/2017/02/10x-featured-social-media-image-size.png)
### Choosing Images for Your Site
* "A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one."  **That is true.** <p>&#9989;</p> 
     > ![Image](https://st.depositphotos.com/1428083/2946/i/600/depositphotos_29460297-stock-photo-bird-cage.jpg)
 * If you do not have photographs to use on your website, there are companies who sell stock images.

 - The Image be Stock photo (from your deivce) or Online (using the image link)

- There are characteristics that are preferred to be available in the image that you will choose,like:
   - Be relevant
   - Convey information
   - Convey the right mood
   - Be instantly recognisable
   - Fit the color palette

### Adding Images
* `<img>` , there is no closing tag , just / at the ending of opening tag
* like `<img src="images/quokka.jpg" alt="A family of quokka" title="The quokka is an Australian marsupial that is similar in size to the domestic cat." />`

- Image tag have :
   - src : source "images — relative URLs"
   - alt : Alternative text
   - title : to provide additional information about the image.

* Height & Width of Images
  - `<img src="images/quokka.jpg" alt="A family of quokka" width="600" height="450" />`
  - to control with image size
  - Where to Place Images

* Old Code: 
  - like : `<p>``<img src="images/bird.gif" alt="Bird" width="100" height="100" align="left" />`here the paragraph `</p> `
  - align : left or right
  - Aligning Images : Horizontally or Vertic ally

* Rules for Creating Image :
  1. "Save images in the right format"
  2. "Save images at the right size"
  3.  "Use the correct resolution"

* Image Resolution 
 - 'Images created for the web should be saved at a resolution of 72 ppi. The higher the resolution of the image, the larger the size of the file.'
- Pexels is the smallest piece of picture or video

* 
* Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

## Color 

![color](https://www.researchgate.net/profile/Lu-Yu-22/publication/322068616/figure/fig2/AS:581220772057088@1515585238602/top-row-The-eleven-basic-color-terms-second-and-third-row-proposed-order-in-which-to.png)
> color names 

+ there is three-way to add the color:
  - rgb values
    - > These express colors in terms of how much red, green and blue are used to make it up,between 0 and 255.
  - hex codes
    - > depend on Hexa code.
  - color names
    - >There are 147 predefined color names,very limited in number.

![primary colors](https://upload.wikimedia.org/wikipedia/commons/a/ae/RYB.png)
>Every color on a computer screen is created by mixing amounts of red, green, and blue. you can use a color picker.

### Background Color
* If you do not specify a background color, then the background will be transparent.

### Terminologies:-
![color Terminologies](https://purple11.com/static/fed42130c194b0c240a4ec10408adf97/8282f/hsl-cover-2.png)
- **Hue** : the attribute of a colour by virtue of which it is discernible as red, green, etc., and which is dependent on its dominant wavelength and independent of intensity or lightness.
- **Saturation**:the degree or extent to which something is dissolved or absorbed compared with the maximum possible, usually expressed as a percentage.
![Saturation](https://art-design-glossary.musabi.ac.jp/wpwp/wp-content/uploads/2014/09/226_saturation_01_en.jpg)
- **Brightness**:the quality or state of giving out or reflecting light.
![Brightness](https://krlqr947et-flywheel.netdna-ssl.com/wp-content/uploads/2018/05/Brightness-Scale.png)

- ** Contrast **:the state of being strikingly different from something else in juxtaposition or close association.
  - Low
  - High
  - Medium
![Contrast](https://hackernoon.com/hn-images/1*GAWRRTSaAqcfRKWu8hL29Q.jpeg)
- **Opacity** :the quality of lacking transparency.
![Opacity](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Opacity_Translucency_Transparency.svg/250px-Opacity_Translucency_Transparency.svg.png)


output: &nbsp ___HTML & CSS: Design and Build Web Sites___
  bookdown::https://documentcloud.adobe.com/link/review?uri=urn:aaid:scds:US:25671887-83dc-4fff-81c7-469ffdd4112e: default

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