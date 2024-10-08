# Form Validation

This project is a simple contact form with client-side validation using HTML, CSS, and JavaScript. The form validates user input for name, phone number, email address, and message fields. Errors are displayed dynamically, and successful validation shows a checkmark icon.

## Features

- **Full Name Validation**: Ensures that the name is entered in full (first and last names) using regex.
- **Phone Number Validation**: Only accepts a 10-digit numeric phone number.
- **Email Validation**: Validates the email format to ensure correct entry.
- **Message Validation**: Requires a minimum of 30 characters in the message field.
- **Real-Time Feedback**: Error messages are shown immediately as the user types, with icons displayed for successful input.

## File Structure

```
├── index.html          # Main HTML file
├── style.css           # CSS file for styling
└── script.js           # JavaScript file for form validation
```

## How to Use

1. Clone or download this repository.
2. Open the `index.html` file in your browser.
3. Fill out the form, and the form validation will provide real-time feedback on each input field.
4. Once all fields are valid, the form can be submitted (functionality can be extended).

## Example of Validations

- **Full Name**: Must include first and last names (e.g., John Doe).
- **Phone Number**: Must be exactly 10 digits (e.g., 1234567890).
- **Email**: Must follow the format (e.g., example@mail.com).
- **Message**: Must be at least 30 characters long.
