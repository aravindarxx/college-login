# Adhiparasakthi Engineering College Login Page

A responsive, single-page college portal login interface built with HTML, CSS, and JavaScript. It presents a branded welcome panel and a login form with Student, Faculty, and Admin user types.

## Features

- Responsive two-panel layout that stacks on smaller screens
- College logo displayed from `college-logo.png`
- User type selector that updates the username label and placeholder
- Username and password fields with basic required-field validation
- Demo login message, Google sign-in placeholder, and account-creation placeholder

## Run locally

No build tools or dependencies are required. Keep `index.html` and `college-logo.png` in the same folder, then open `index.html` in a web browser. Alternatively, serve the folder with any static web server.

## Demo behavior

The login form only displays a success message when both fields contain values. It does not authenticate credentials or connect to a college portal. Google sign-in and account creation show placeholder alerts and are not connected to authentication or registration services.

The decorative background uses an image hosted by Unsplash, so that image requires an internet connection. The college logo is loaded locally from `college-logo.png`.
