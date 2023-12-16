# Labelling-Form-Controls

<label>
When introducing form controls, the code was kept simple by indicating the purpose of each one in text next to it. However, each form control should have its own <label> element as this makes the form accessible to vision-impaired users.The <label> element can be used in two ways. It can:
1. Wrap around both the text description and the form input (as shown on the first line of the example to your right).
2. Be kept separate from the form control and use the forattribute to indicate which form control it is a label for (as shown with the radio buttons).

for
The for attribute states which form control the label belongs to. Note how the radio buttons use the id attribute. The value of the id attribute uniquely identifies an 
element from all other elements on a page. (The id attribute is covered on page 183.)The value of the for attribute matches that of the id attribute on the form control it is labelling.This technique using the for and id attributes can be used on any form control. When a <label>element is used with a checkbox or radio button, users can click on either the form control or the label to select. The expanded clickable area makes the form easier to use. The position of the label is very important. If users do not know where to enter information or what information to enter, they are less likely to use the form correctly. 

As a rule of thumb, here are the best places to place labels on form controls.
Above or to the left:
● Text inputs
● Text areas
● Select boxes
● File uploads
To the right:
● Individual checkboxes
● Individual radio buttons


<label>Age: <input type="text" name="age" /></label>
<br/ >
Gender:
<input id="female" type="radio" name="gender"
 value="f">
<label for="female">Female</label>
<input id="male" type="radio" name="gender" 
 value="m">
<label for="male">Male</label>
