# 📋 Form Validator

A clean, responsive, client-side Form Validation application (and Chrome Extension popup) that validates user registration details in real-time. It checks for required fields, string length constraints, email formatting, and password matching with clear visual indicators[cite: 5, 7, 8].

---

## ✨ Features

- **Field Validation**: Ensures all required fields (Username, Email, Password, Confirm Password) are non-empty[cite: 5, 7].
- **Length Constraints**:
  - **Username**: Must be between 3 and 15 characters long.
  - **Password**: Must be between 6 and 25 characters long[cite: 7].
- **Email Regex Validation**: Verifies that the entered email conforms to valid email address formats[cite: 7].
- **Password Matching**: Validates that the "Confirm Password" input matches the primary password field[cite: 5, 7].
- **Visual Feedback**: Dynamic input borders and inline error messages (red for errors, green for valid inputs)[cite: 7, 8].
- **Form Reset**: Automatically resets all input fields and styling upon successful submission[cite: 7].

---

## 🛠️ Project Structure

```text
form-validator/
├── index.html     # HTML structure containing the registration form
├── style.css      # Layout styling, error/success states, and animations
├── script.js      # Form validation logic, event handlers, and helpers
├── manifest.json  # Chrome Extension configuration file (Manifest V3)
└── icon.png       # Application / Extension icon graphic
