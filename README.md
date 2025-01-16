# Uncommon HTML Error: Accessing Non-Existent Attribute

This repository demonstrates an uncommon error in HTML that occurs when attempting to access a non-existent attribute of an HTML element using JavaScript.  This is not a syntax error but rather a runtime error that can be difficult to debug if not carefully considered.

## Description
The `bug.html` file contains the erroneous code.  It attempts to access the attribute `myNonExistentAttribute` of an element with the ID `myDiv`.  Since this attribute doesn't exist, the JavaScript code throws a `TypeError`.  The `bugSolution.html` file provides a corrected version of the code.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Open your browser's developer console (usually by pressing F12).
4. Observe the error message indicating that the attribute could not be found.

## Solution
The `bugSolution.html` file demonstrates how to avoid this error.  Always check for the existence of an attribute before accessing it to prevent such runtime exceptions.