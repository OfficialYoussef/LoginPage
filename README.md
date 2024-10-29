# LoginPage
# Login Page | Youssef

This document describes the structure and functionality of a simple login page built using HTML and CSS.

## Overview

This login page includes a clean and modern interface with fields for email/phone, password, and options for user convenience and accessibility. 

## Structure

1. **Head Section**:
   - Sets the document character encoding to UTF-8.
   - Includes a viewport meta tag to ensure responsiveness on different screen sizes.
   - Links an external stylesheet, `style.css`, for custom design.

2. **Navigation (`<nav>`)**:
   - Contains a logo image (located at `images/logo.svg`).
   - The logo is clickable and can link back to the homepage or any designated URL.
![Screenshot from 2024-10-29 11-13-13](https://github.com/user-attachments/assets/b6e6635d-0ad7-40c2-8799-9469cf1bb1b0)


3. **Form Wrapper (`<div class="form-wrapper">`)**:
   - Wraps the form with a visually distinct container.
   - Contains a heading (`<h2>Sign In`) to identify the page as a login interface.

4. **Login Form**:
   - Consists of two main input fields:
     - **Email or Phone Number**: text input field, required.
     - **Password**: password input field, required.
   - Each input is within a `form-control` div for organized styling and alignment.
   - **Remember Me** checkbox with an associated label, allowing users to stay signed in.
   - "Need help?" link for users requiring assistance.

5. **Buttons and Links**:
   - **Sign In Button**: the primary button for form submission.
   - **Sign Up Link**: offers new users a way to register by linking to a signup page.
   - **Google reCAPTCHA Notice**: informs users of bot protection, with a "Learn more" link for additional details.

## Example HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<!-- HTML code here -->
</html>
