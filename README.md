# JavaScript Practice Tasks
This repository contains solutions to a series of JavaScript exercises aimed at building practical programming skills. Below is a brief description of each task.
![Example Image](https://github.com/Ammar-Alkhalidi/JS-Try-Await/blob/main/error-preview.png))
![Example Image](https://github.com/Ammar-Alkhalidi/JS-Try-Await/blob/main/success-preview.png))

- Task 1: Style a Paragraph on Button Click
Objective:
Change the style of a paragraph dynamically when a button is clicked.

# Functionality:
When the button is clicked, the paragraph:
Changes color to red.
Uses the monospace font-family.
Has a font size of 4em.
Solution:
The addEventListener method is used to attach a click event to the button. The paragraph's styles are updated using JavaScript’s style property.

- Task 2: Highlight a Navigation Link
Objective:
Select and highlight the first link in a navigation bar.

# Functionality:
Print the text of the first link (Home) to the console.
Add the active class to the link to visually highlight it.
Solution:
The querySelector method is used to select the first navigation link. The classList.add method is used to apply the active class.

- Task 3: Dynamically Create a Styled Div
Objective:
Create a div element dynamically and add it to the body.

# Functionality:
The created div has:
A box class.
Predefined styles such as a teal background and fixed dimensions.
Solution:
The createElement method is used to create the div. The classList.add method assigns the box class, and appendChild appends it to the body.

- Task 4: Cross Out Tasks on Click
Objective:
Toggle the line-through style on a task when it is clicked.

# Functionality:
Clicking a task crosses it out or removes the cross-out effect.
This is achieved by toggling the text-decoration style or a CSS class.
Solution:
Each task is assigned a click event listener using forEach on a list of task elements. The classList.toggle method is used to apply a crossed-out class, which contains the required styles.

- Task 5: Form Validation with Success and Error Messages
Objective:
Validate a form upon submission and display appropriate feedback.
![Example Image](https://github.com/Ammar-Alkhalidi/JS-Try-Await/blob/main/error-preview.png))

# Functionality:
Check if the email and password fields are filled.
Display a success message with a green background if both fields are filled.
Display an error message with a red background if either field is empty.
Ensure the message div never contains both success and error classes.
Solution:
The addEventListener method is used to attach a submit event to the form. Validation logic is encapsulated in a function, which updates the message and styles dynamically. In the alternate version, validation is handled using Promises to simulate asynchronous processes.
![Example Image](https://github.com/Ammar-Alkhalidi/JS-Try-Await/blob/main/success-preview.png))

# Technologies Used
* HTML: Structure of the tasks and elements.
* CSS: Styling of elements (e.g., hover effects, classes like error and success).
* JavaScript: Logic for interactivity, DOM manipulation, and event handling.

# How to Run
Clone this repository.
Open the HTML files in any browser.
Interact with the page to see the JavaScript functionality in action.
Lessons Learned
Dynamic DOM manipulation using JavaScript.
Event handling with addEventListener.
Styling elements programmatically with style and classList.
Form validation and providing user feedback.
Using Promises for asynchronous operations.
