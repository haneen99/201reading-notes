# HTML lists allow web developers to group a set of related items in lists.

* Unordered HTML List
An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.

* The list items will be marked with bullets (small black circles) by default:

* Example
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
## The CSS Box Model
In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:
![box](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.geeksforgeeks.org%2Fcss-box-model%2F&psig=AOvVaw2SwjE80fklNbVLDkwgDyAs&ust=1624462868486000&source=images&cd=vfe&ved=0CAoQjRxqFwoTCLi8ivbJq_ECFQAAAAAdAAAAABAD)
### Control flow
The control flow is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops. 

For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:

if (field==empty) {
    promptUser();
} else {
    submitForm();
}