Readme for Quote Generator
This code generates a random quote from an array of pre-defined quotes when the button is clicked.

HTML File
The HTML file contains a button and a paragraph element for displaying the quote. It also includes a reference to an external CSS file.

CSS File
The CSS file defines the style for the button and the paragraph element.

JavaScript File
The JavaScript file defines an array of quotes and a function for changing the quote displayed in the paragraph element. When the button is clicked, the function selects a random quote from the array and displays it in the paragraph element.

Variables
p: represents the paragraph element where the quote is displayed
btn: represents the button element
quotes: an array containing pre-defined quotes
Functions
change(): a function that generates a random number and uses it to select a quote from the quotes array. The selected quote is then displayed in the p element.
Event Listener
addEventListener(): listens for the click event on the btn element and calls the change() function to generate a new quote.