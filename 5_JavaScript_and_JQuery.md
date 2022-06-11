## Javascript

- Also began in the mid 90s as Netscape's scripting technology
  - Microsoft used JScript and VBScript
  - Adobe used ActionScript in flash
- Standardized in the mid-00s as the dominant client-side scripting language in browsers
  - Allows manipulation of the DOM
- Also available for server-side scripting in NODE.js
- Open Source - This is good. It is not subject to the whims of a single company
- Object Oriented - EVERYTHING in JavaScript is an object. Even functions
- Event Driven - Much of the JavaScript code that you write will be event handlers

#### How do we access the DOM?
- Every browser makes the DOM accessible through the document object
- The document object is available to all JavaScript code
- document.head or document.body to reference the head or body
- Children of the body are an array of HTML elements
  - document.body.children[2] to reference the third child element of the body
  - document.body.children[2].children[1] to reference the second child of the third child of the body

#### Acessing the DOM
- colorlist = document.body.children[1].children[0]
- animallist = document.body.children[1].children[1]
- firstanimallist = document.body.children[1].children[1].children[0]

