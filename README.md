## SURVEY-FORM

  * I created a survey form page by using HTML, Bootstrap, and CSS.

  * The survey form is in the file name [survey-form](index.html).

**Description**
  
   * Form Layout: The form is wrapped in a <form> tag and divided into several sections using <div> tags with Bootstrap classes for spacing `(.   margin)` and layout `(.row, .col-3, .col-6)`.

   * Personal Details Section: Collects the user's name (first and last) and email address.Uses Bootstrap’s grid system `(.row, .col-3, .col-6) `for layout and form control classes `(.form-control)` for input styling.
     
   * Experience Rating Section: Users rate their experience with a series of stars, styled with custom CSS for hover effects and selection states.The `.star` class defines the star shape using CSS clip-path and background color, while `.selected` changes the color when a star is selected.

   * Satisfaction and Likelihood Ratings: Collects feedback on various aspects (purchase, service, overall company) using radio buttons. Each aspect is presented in a table with headings for different satisfaction levels.Radio buttons are grouped and styled using Bootstrap's `.form-check` and input classes.
 
   * Additional Comments Section: Provides a text area for users to add any additional comments or suggestions.Uses Bootstrap's `.form-control `class for consistent styling.

   * Submit Button: A simple submit button at the end of the form to capture the user's input.
