# Calender_js
# Hosted Link:-https://tulasidurga1.github.io/Calender_js/

### This is an HTML and JavaScript code for creating a simple calendar web application. Let's go through the code step by step:

# HTML Structure:

- The HTML file starts with the usual document type declaration and sets the document's language to English.
- It includes meta tags for character encoding, compatibility settings, and viewport settings.
- The title of the web page is set to "Calendar."
- The page loads an external JavaScript file called "script.js" using the <script> tag with the defer attribute.
- It also loads an external CSS file called "style.css" using the <link> tag.
### HTML Body:

-  content of the page is wrapped inside a <div class="main"> container, which is centered on the page using CSS.
- Inside the main container, there is another <div class="container"> for the calendar content.
- The calendar content is divided into three sections: month-year, calendar, and date.
### Month and Year Selection:

- In the month-year section, there are two <select> elements for selecting the month and year.
- Month options range from January to December, and year options are dynamically filled from 1900 to 2099 in the JavaScript code.
### Calendar Display:

- The calendar section consists of two lists: ul.week for displaying the days of the week and ul.day for displaying the calendar days.
- The days of the week are displayed as list items (<li>).
- Calendar days are initially empty and are filled dynamically using JavaScript.
### Date Input Form:

- Below the calendar, there is a <form> with an input field (<input type="number">) for entering a specific date.
- Users can enter a date between 1 and 31, and there is a "Submit" button (<input type="submit">) to submit the date.
### CSS Styling:

- CSS styles are defined in the "style.css" file.
- The styling includes background images, colors, fonts, and layout adjustments to create an aesthetically pleasing calendar interface.
- Various classes are used to style different elements within the HTML structure.
  ### JavaScript Functionality (in "script.js"):

- The JavaScript code at the bottom of the HTML file provides functionality to the calendar.
- It initializes the calendar by determining the current date and populates the days of the month accordingly.
- The dateOfFirstDay() function calculates and displays the days of the month based on the selected month and year.
- The fillDates() function fills the calendar with days based on the month's number of days.
- The highlightColor() function highlights the current date in the calendar.
- The fillingYears() function populates the year selection dropdown.
- Event listeners are added to the month and year dropdowns to update the calendar when the user makes a selection.
- The ValidateDate() function is called when the user submits a specific date and highlights that date in the calendar.
