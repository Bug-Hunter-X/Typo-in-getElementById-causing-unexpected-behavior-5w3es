# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle bug that can occur in HTML when there is a typo in the `getElementById` function used to manipulate the DOM.

## Bug Description

The bug lies in a simple typo in the JavaScript code. Instead of `getElementById`, `getElementByIdx` is used, resulting in a runtime error without any visible error messages in the console. This makes the bug difficult to debug. The intended behavior was to modify the innerHTML of the div with id "myDiv".

## Solution

The solution involves correcting the typo in the script, using the correct `getElementById` method to access the element and modify its innerHTML.