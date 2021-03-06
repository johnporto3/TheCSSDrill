# TheCSSDrill

The CSS Drills
Covalence

Objective
Practice using the fundamentals of CSS that were explored in lecture.

Setup
Create a new project folder and connect it to a github repository. Copy this README.md file into it.

Create an index.html file and a styles.css file

In the head element, link the two files together by using the link tag:

Build the HTML Structure
In the body element, create a div with an id of "container"
Add 4 div elements with a class name of "boxes" and a unique id (box1, box2, boxn) inside the container div. Each added div will be a child of the container div and a sibling to each other
Create a h2, p, and an anchor element inside of each of the 4 div's
h2: A story title
p: A story description
a: Read Me
Add some text for the heading, paragraph, and anchor elements
Now, Lets style!
Assign a global font family
Here is a list of some Web Safe Fonts: https://www.w3schools.com/cssref/css_websafe_fonts.asp

You could also play around with Google Fonts: https://fonts.google.com/

{ font-family: "Palatino Linotype", "Book Antiqua", Palatino, serif; }
Change the background color for the body element: *the two forward slashes indicate a comment. The HEX value (#XXXXXX) is the HEX equilvalent to lightgray. *you can use either one in this drill.
Use a multiple selector rule set to center the text for all h2, p, and a elements
Use an element selector to remove the default underline styles for a anchor element and change the font color:
*When you refresh your browser you'll notice that the link is not centered like the h2 and p elements. This is because text-align will center the element based on the width assigned to it. If you apply a border to the link tag, you'll see that the link is centered inside the anchor element. The best way to center the link, relative to its parent element, is to enclose it inside of a div element.

Wrap the anchor element inside of the div and give the div a class name of "readme-wrapper":
Replace the a in the multiple selector rule with .readme-wrapper
Now refresh and you'll see the link is centered as we expected it
Use a class selector to target the .boxes class:
Change the display to inline-block
add margin
add padding
add a solid border
add a border radius to round the edges of the border
Add a CSS :hover selector so that when the link is moused over the cursor changes to a pointer, the font is bold, and text color changes:
Wrap a single word in each paragraph element inside of a span element and assign it a new font color and font weight:
Change the display to block in the class selector named .boxes
When you refresh the page, you'll see each div now takes up the entire row
Add a width of 20% to each div
Use an id selector to add an unique background color to each div
Change the position of the second div to be relative to its parent
Position the second div so that it is next to the first div
Change the position to absolute
Position the second div to the top right corner
Remove the position styles for the second div
The second div should now be returned to the normal flow
Add a new div element as a child inside each of the 4 div elements
we'll use this div to represent an image
Give the new div a class name
Assign a width, height, and background color to the div
Position the div so its inline and to the left of the header
Styling Specificity
Insert 3 h1 tags into the html document, give each text for your favorite tv shows.
Apply styling so that any and all h1’s have a font color of your choice.
Add 2 more h1’s with 2 other tv shows, what immediately happens to their font color when you refresh the html doc?
Give the original 3 h1’s all the same class.
Give the additional 2 h1’s the same class (have it be different than the other 3)
Apply styling by class name, have the first 3 h1’s get a new font color, don’t delete or comment out the original styling. Once you apply a new font color by class, refresh the page and see what it does.
Do the same thing for the added 2 h1’s, give them a different font color by class name.
Take note at what styling applied to a class does to what was already applied to ALL of the elements before.
Rank each tv show you have (so all 5 h1’s), a rank of show1 would be the best. Have the rank be the id of each h1. At this point every h1 should have a class AND an id attribute.
Apply styling using the id of each h1, give each a different color. Refresh the document and see how this type of styling changes what was already applied. Create 3 unordered lists each with 5 items, have the first list be 5 friends names, have the next be 5 places you want to travel to, and have the last list be your favorite restaurants.
Apply the same steps covered in the directions to play with the specificity of styling on each of these lists.
Wrap each list in a div, give the div a border that is 2 pixels thick, have it be solid and the color be black.