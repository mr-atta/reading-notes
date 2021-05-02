#  HTML Tables <dr><br> `<table>` <br>

![Tables](https://cdn.educba.com/academy/wp-content/uploads/2019/10/HTML-Table-Tags.png)
### What's a Table? ??
> A table represents information in a grid format.

### How to create tables ??
1.  `<table>` 
2.  `<tr>`
3.  `<td>` 
   * ![ HTML Tables](https://flaviocopes.com/html-tables/no-styling.png)
> In the **`<table>`** we have **`<tr>`** it is the row.And inside the `<tr>` have **`<td>`** had the data. One piece of the row is called a cell.

> You can add css to the Table (inside or outside "better") to add lines.such as : border , width (to rows) , color ...


#### There are characteristics of another, like:
   - `<caption>` , described the table , be after the `<table>` tag.
   - `<th>` , is changing the cell to the default title(centered , bold).
   - `<thead>` , table head for groups of `<td>`.
   - `<tfoot>` , table footer for groups of `<td>`.

   * ![`<table>` ](https://i.imgur.com/uIwzEfS.png)

### Spanning ColumnS
> to stretch across more than one column , `<th>``</th>` or `<th></th>`

#### Summary 
 1. The `<table>` element is used to add tables to a web page.
 2. A table is drawn out row by row. Each row is created with the `<tr>` element.
 3. Inside each row there are a number of cells represented by the `<td>` element (or `<th>` if it is a header).
 4. You can make cells of a table span more than one row or column using the rowspan and colspan attributes.
 5. For long tables you can split the table into a `<thead>`, `<tbody>`, and `<tfoot>`.

 # JS  Objects <dr><br> 
 ![js ](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQd-mbfdUrmeRr00MPj0rbbmO2rEnIwwiVkLQ&usqp=CAU)
### creating an Object: **constructor notation** 
![constructor](https://image.slidesharecdn.com/extendingbuilt-inobjects-150317132558-conversion-gate01/95/extending-built-in-objects-6-638.jpg?cb=1426683966)
<br>

> constructor should make our live a piece of cake.
- when we have very much objects , And we need to make change on them, we can not old way to creating an Object (use constructor).
- used Method (or function).
- It is easy to change the code.
- On the right, an empty object called hote 1 is created using the constructor function. Once it has been created, three properties and a method are then assigned to the object. ( If the object already had any of these properties, this would overwrite the values in those properties.) To access a property of this object, you can use dot notation,just as you can with any object. For example, to get the hotel's name you could use: hotel .name
![constructor ](https://miro.medium.com/max/560/1*DnOmZR328jCXUAXjR6-Alg.jpeg)

### Example
`function Hotel (name, rooms, booked) {`
`this .name = name;`
`this.rooms = rooms;`
`this.booked = booked;`
`this.checkAvailability = function()`
`return this.rooms - this.booked;`
`} ;`
`var quayHotel`
`var parkHotel`
`new Hotel('Quay', 40, 25);`
`new Hotel( ' Park', 120, 77);`
`var details!= quayHotel .name + ' rooms : ';`
`detailsl += quayHotel.checkAvailability();`
`var elHotell = docurnent.getElementByid('hotell');`
`elHotell.textContent =details!;`
`var details2 = parkHotel .name+ ' rooms: ';`
`detai l s2 += parkHotel.checkAvailability();`
`var e1Hotel2 = document.getEl ementByid('hotel2');`
`elHotel2.textContent = details2;`

![this](https://miro.medium.com/max/1838/1*ofrtrTxhyh6zNNPZ9zJLSA.jpeg)

#### ADDING AND REMOVING PROPERTIES
* You do this using the dot notation that you saw for adding properties to objects
* To delete a property, you use the keyword delete, and then
use dot notation to identify the property or method you want to remove from the object.

* Arrays are objectives , they hold a related set of key/value pairs.
* In JavaScript, an array can hold different types of data types in a single slot, which implies that an array can have a string, a number or an object in a single slot.

   * ![objecte type](https://image.slidesharecdn.com/byvalueversusbyreference-170310033218/95/js-basic-by-value-versus-by-reference-9-638.jpg?cb=1489132241)

* **The built-in objects** are Date, Math, String, Array, and Object. Each is used in a unique and not-quite-consistent way.
   * ![built-in object](https://i.imgur.com/J3ETg5D.png)

![OBJECT MODEL](https://miro.medium.com/proxy/0*Tk4fTMbOEOmGX_nU.png)

  ### THE BROWSER OBJECT MODEL:THE WINDOW OBJECT
   * The window object represents the current browser window or tab. It is the topmost object in the Browser Object Model, and it contains other objects that tell you about the browser. 
  ### THE DOCUMENT OBJECT MODEL
    * The topmost object in the Document Object Model (or DOM) is the document object. It represents the web page loaded into the current browser window or tab.

  ### GLOBAL OBJECTS: STRING OBJECT
   * Whenever you have a value that is a string, you can use the properties and methods of the String object on that valu e. This  xample stores the phrase "Home sweet home " in a variable.

   ### MATH OBJECT TO CREATE RANDOM NUMBERS
    * To get a random whole number between 1 and 10, you need to multiply the randomly generated number by 10. This number will still have many decimal places, so you can round it down to the nearest integer.