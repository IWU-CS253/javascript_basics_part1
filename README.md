# JavaScript Basics Assignment: Interactive Web Page

## Objective:
Create a simple, interactive webpage using JavaScript that demonstrates an understanding of fundamental JavaScript concepts, including variables, functions, DOM manipulation, event handling, control structures, and form validation.

## Assignment Description:
Students will build a single HTML page that includes a JavaScript file. The page should contain the following elements:
1. A heading (`<h1>`) introducing the webpage.
2. A button that triggers an alert message.
3. A section displaying dynamic content modified using JavaScript.
4. A form with at least two input fields and a submit button.
5. JavaScript functionality that validates the form inputs before submission.

## Instructions:

### 1. Setting Up the HTML Page
- Create an HTML file (`index.html`).
- Include a `<script>` tag linking to an external JavaScript file (`script.js`).
- Add a heading (`<h1>`) and a paragraph (`<p>`) with an initial message.
- Add a button with an `id` of `alertButton` that, when clicked, displays an alert message.
- Add a `<div>` with an `id` of `content` where JavaScript will dynamically insert text.
- Add a simple form with:
  - A text input field for the user's name (`id="nameInput"`).
  - A number input field for the user's age (`id="ageInput"`).
  - A submit button (`id="submitButton"`).

### 2. Writing JavaScript Code (script.js)

#### a. Displaying an Alert Message
- Select the button using `document.querySelector`.
- Attach an event listener that displays an alert when the button is clicked.

#### b. Changing Content Dynamically
- Select the `<div>` with `id="content"`.
- Create a function that changes the text inside this `<div>` when the button is clicked.

#### c. Working with Variables and Functions
- Declare variables using `let` and `const`.
- Create a function that updates the content dynamically.
- Call the function inside an event listener when a button is clicked.

#### d. Handling User Input and Validation
- Select the form inputs and submit button using `document.querySelector`.
- Add an event listener to the submit button to capture user input.
- Validate input to ensure the name is not empty and age is a positive number.
- Display an error message if validation fails, otherwise display a success message.

### 3. Implementing Control Structures
- Use an `if-else` statement to check input validity.
- Use a `for` or `while` loop to iterate through form fields if needed.

## Submission Requirements:
- Upload `index.html` and `script.js` files.
- Ensure proper indentation and comments in JavaScript code.


