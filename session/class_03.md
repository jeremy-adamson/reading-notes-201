# HTML Lists, Control Flow with JS, and the CSS Box Model

## HTML

* When should use use an `unordered list` in your HTML document?
  * When order doesn't matter (as the name implies) such as simply indicating a grouping of... things
* How do you change the `bullet style` of unordered list items?
  * type
    * Can be defined as either a `circle`, `disc`, or `square`
* When should use use an `ordered list` vs an `unordered list` in your HTML document?
  * When there are steps or as the name describes, a list where the order of the elements matters (decreasing lists, increasing lists, chapters in a book)
* Describe two ways you can change the numbers on `list items` provided by an `ordered list`?
  * `start` can define the starting value for an ordered list
  * `type` can define the numbering type
    * `a` for lower case letters (upper case too with `A`)
    * `i` for lower case roman numerals
    * `1` for numbers (default)

## CSS

* Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: "The Box Model?"
  * Not sure how to write a story but if a toddler is dressing for warm weather and is wearing layers, the kid would be the content, the trapped air between the person and the snow jacket would be the padding, the snow jacket itself would be the border, and the margin is how far the kid is flailing their arms so no one else can get close enough to put gloves on the kid.
* List and describe the four parts of an HTML elements box as referred to by the `box model`.
  * Content - The actual content you're trying to display (ie. text or picture)
  * Padding - The empty space between the content and the border
  * Border - Can typically be viewed as a line which separates the padding from the margin
  * Margin - The size of the empty space or buffer outside of the border

## Learn JS

* What `data types` can you store inside of an `Array`?
  * I am uncertain on if there is a limit to what CAN be stored in an array in terms of data types (assuming enough system resources)
* Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?
  * Yes it is valid since arrays can contain arrays.  To access a particular element you would have to write `people[x][y]` where x indicates which sub array to select and y inidcates which element in the sub array.
* List five shorthand operators for assignment in javascript and describe what they do.
  * `+=` adds whatever is to the right to the variable on the left and stores the result in the variable on the left
  * `-=` subtracts whatever is to the right to the variable on the left and stores the result in the variable on the left
  * `*=` multiplies whatever is to the right to the variable on the left and stores the result in the variable on the left
  * `/=` divides whatever is to the right to the variable on the left and stores the result in the variable on the left
  * `%=` takes the modulus (remainder) after dividing the variable on the left by the value on the right and stores the result in the variable on the left
* Read the code below and evaluate the last `expression` and explain what the result would be and why.
  * 10dog - The first operation is adding an integer to a boolean which would convert the boolean `false` into a 0 making the sum 10.  However the next operation is attempting to add an integer to a string so the integer gets converted into a string and the two strings are concatenated leaving `10dog`
* Describe a real world example of when a conditional statement should be used in a JavaScript program.
  * If a person does not have sufficient funds in their account, the transaction will be declined.  For online banking, pretty sure they'd check that in their coding.
* Give an example of when a `Loop` is useful in JavaScript.
  * Iterating through an array to see if a given elements exists in it.

## Readings

Alternative reading option would be:

* Duckett HTML Chapter 3: Lists (p.62-73)
* Duckett HTML Chapter 13: Boxes (p.300-329)
* Duckett JS Chapter 2: Basic JavaScript (p.70-73)
* Duckett JS Chapter 4: Decisions and Loops (p.162-182)

Main reading:

* [Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [Ordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
* [Unordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
* [Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
* [The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
* [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
* [Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
* [Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
* [Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
* [Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

## Additional Reading

* [Lists](https://www.w3schools.com/html/html_lists.asp)
* [Box Model](https://www.w3schools.com/css/css_boxmodel.asp)
* [JS](https://www.w3schools.com/js/default.asp)
* [Arrays](https://www.w3schools.com/js/js_arrays.asp)
* [Loops](https://www.w3schools.com/js/js_loop_for.asp)
