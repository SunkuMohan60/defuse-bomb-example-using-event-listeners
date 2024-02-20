HTML (HyperText Markup Language):

Used for structuring the content of the webpage.
Includes elements such as <html>, <head>, <body>, <div>, <input>, <img>, and <p>.
CSS (Cascading Style Sheets):

External CSS file (file.css) is linked to the HTML file.
Bootstrap library is included via a CDN link for styling (buttons, containers, etc.).
The provided Bootstrap version is 4.5.2.
JavaScript:

External JavaScript file (project.js) is linked to the HTML file.
Used for dynamic behavior and interactivity on the webpage.
The script includes logic for a countdown timer and bomb defusing functionality.
The setInterval() function is used to decrement the countdown timer every second.
Event listeners are employed:
keydown event listener on the input field (defuserEl) listens for the "Enter" key press.
If the entered text is "defuse" and the countdown is not zero, the timer stops, and a success message is displayed.
DOM manipulation to update the timer display and respond to user input.
External Libraries:

jQuery library is included via CDN for simplifying DOM manipulation (jquery-3.5.1.slim.min.js).
Popper.js library is included via CDN for Bootstrap's dropdowns, popovers, and tooltips (popper.js).
Bootstrap:

Used for styling and layout of HTML elements.
Classes such as timer-container, user-input, bomb-image, etc., are Bootstrap classes.
Responsive design components are utilized, ensuring the webpage looks good on various devices.
Overall, the provided code uses HTML for structure, CSS for styling, JavaScript for dynamic behavior, and Bootstrap for styling and layout. It employs libraries like jQuery and Popper.js for enhanced functionality. The webpage features a countdown timer with bomb defusing functionality, providing an interactive experience for users.
