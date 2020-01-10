### Detect the key sequence

This exercize thought me how to look if there is a certain key sequence that the user has typed.

First, we add an event listener to the window that listens for a keyup event. 

The keys get pushed into an empty array we created. We also need a variable with the string we're looking for.

We then splice the array starting from the end, which means negative string length.

We trim this array by the number we get after deductiong the string length from the typed array length.

The elements of the array need to be converted into a string, in order to see if it includes our string.

If it does, you will see a unicorn or a rainbow show up on the page :)

Thanks to a library called cornify.js you may find here: https://www.cornify.com/js/cornify.js.


