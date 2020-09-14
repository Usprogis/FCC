# Survey form

This project is a survey form for Erasmus students coming to Latvia.
Page is made by completing the given user stories:

User Story #1: I can see a title with id="title" in H1 sized text.

User Story #2: I can see a short explanation with id="description" in P sized text.

User Story #3: I can see a form with id="survey-form".

User Story #4: Inside the form element, I am required to enter my name in a field with id="name".

User Story #5: Inside the form element, I am required to enter an email in a field with id="email".

User Story #6: If I enter an email that is not formatted correctly, I will see an HTML5 validation error.

User Story #7: Inside the form, I can enter a number in a field with id="number".

User Story #8: If I enter non-numbers in the number input, I will see an HTML5 validation error.

User Story #9: If I enter numbers outside the range of the number input, which are defined by the min and max attributes, I will see an HTML5 validation error.

User Story #10: For the name, email, and number input fields inside the form I can see corresponding labels that describe the purpose of each field with the following ids: id="name-label", id="email-label", and id="number-label".

User Story #11: For the name, email, and number input fields, I can see placeholder text that gives me a description or instructions for each field.

User Story #12: Inside the form element, I can select an option from a dropdown that has a corresponding id="dropdown".

User Story #13: Inside the form element, I can select a field from one or more groups of radio buttons. Each group should be grouped using the name attribute.

User Story #14: Inside the form element, I can select several fields from a series of checkboxes, each of which must have a value attribute.

User Story #15: Inside the form element, I am presented with a textarea at the end for additional comments.

User Story #16: Inside the form element, I am presented with a button with id="submit" to submit all my inputs.

Project contains these files:
- index.html - forms backbone
- style.scss - styling writed in scss for better usage

---
Index.html and style.scss files are verified by the W3c validators.
Files are short in code line count so there are little comments.

### Usage

Pull the repo and index.html and style.scss files in one directory. You can use a online SCSS to CSS converter or use ruby Compass (http://compass-style.org/) to convert the code. After that, use a web browser to open the index.html file and see the page.
The Tribute Page is also available at CodePen.io. Link: https://codepen.io/USprogis/pen/YzqvJYj

For user story verification the index.html file contains FCC external script that checks if the user stories are completed.

To use the checker, click a button that appears in the top left corner and select the survey form page test suite from dropdown menu and click button "Run Tests".