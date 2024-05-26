## User Registration Form

This project is a user registration form created using HTML, CSS, and JavaScript. It includes various input fields and features designed to enhance user experience, such as password visibility toggling and form validation. Upon successful submission, a pop-up message informs the user that their registration was successful.

### Features

- **Username Field:** Users can enter their full name.
- **Email Field:** Accepts the user's email address.
- **Password Field:** Includes a "Show Password" button to toggle password visibility.
- **Birthdate Field:** Allows users to select their birthdate.
- **Address Field:** Users can enter their address.
- **Form Validation:** The "Register" button is disabled until all fields are filled.
- **Submission Alert:** Displays a pop-up message indicating successful registration upon form submission.

### Files

- **index.html:** Contains the HTML structure of the registration form.
- **style.css:** Includes CSS styles for form elements and button states.
- **script.js:** Implements JavaScript functionality for form validation and password visibility toggling.

### CSS Styles

The CSS styles improve the form's appearance and usability. The `#show-password-button` changes background color on hover, and the `#register-button` is styled to indicate its disabled state when fields are empty.

### JavaScript Functionality

JavaScript functionality includes:
- Toggling password visibility using the "Show Password" button.
- Enabling the "Register" button only when all form fields are filled.
- Displaying an alert message upon successful form submission.

### How It Works

The form uses `required` attributes to ensure all fields are filled before submission. JavaScript checks the form fields and enables the "Register" button only when all fields are filled. On submission, an alert notifies the user of successful registration without reloading the page.

### License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
