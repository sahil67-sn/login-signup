# Sign-Up & Login Pages

A simple two-page front-end project built with plain HTML and CSS. It includes a **Sign-up** form and a **Log-in** form that share the same sky-blue-to-purple gradient theme and link to each other.

## Files

| File | Description |
|------|-------------|
| `index.html` | Sign-up page (default landing page) |
| `login.html` | Log-in page |

## Features

### Sign-up page (`index.html`)
- Fields: Name, Last Name, DOB (date picker), Gender (Male / Female), Mobile No., Email, Confirm Email, Password, Confirm Password
- "Terms & Condition" checkbox
- Submit button with gradient styling
- "Already a member? Login" link to `login.html`

### Log-in page (`login.html`)
- Email and Password fields with placeholders
- "Forget Password?" text
- Login button with gradient styling
- "Not a Member? Sign UP" link to `index.html`

## Getting Started

No installation or build step is needed.

1. Download or clone the project and keep both files in the same folder.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Use the links at the bottom of each form to switch between pages.

## Project Structure

```
.
├── index.html   # Sign-up page
├── login.html   # Log-in page
└── README.md
```

## Tech Stack

- HTML5
- CSS3 (embedded in `<style>` tags, using flexbox and `linear-gradient`)

## Current Limitations

- The forms are front-end only: there is no JavaScript and no backend, so submitting does not save or authenticate anything.
- No input validation beyond the browser's built-in `type` checks (email, tel, date).
- Layout uses percentage-based sizes and `&nbsp;` spacing, so it is best viewed on a desktop screen and is not fully responsive.
- "Forget Password?" is plain text and not yet linked to anything.

## Possible Improvements

- Add JavaScript validation (matching email/password confirmation, required fields)
- Connect the forms to a backend or authentication service
- Replace `&nbsp;` spacing with CSS for aligned labels and inputs
- Associate each `<label>` with its input using `for`/`id`
- Make the layout responsive with media queries
- Move the shared CSS into a separate stylesheet
- Add a real "Forgot Password" flow and a link to the Terms & Conditions

## License

Add a license of your choice (e.g., MIT) if you plan to share this project.
