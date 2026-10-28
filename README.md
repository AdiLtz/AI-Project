# Northstar Internal Hackathon

A responsive front-end demo for the Northstar Internal Hackathon. It includes a participant sign-in page and an event page with event details and a demo registration form.

## Pages

- `index.html` — participant sign-in page.
- `hackathon.html` — event information, theme toggle, and registration form. The page is available after signing in.

## Run locally

No dependencies or build step are required. Open `index.html` in a browser, or serve the project directory with a local static web server and visit the address it provides.

## Demo sign-in

- **Student email or ID:** `student@northstar.edu`
- **Password:** `CampusDemo123`

Successful sign-in opens `hackathon.html`. The demo sign-in state is stored in the browser's session storage.

## Demo limitations

This project is a front-end demonstration only. It has no backend or real authentication. The registration form displays an on-page confirmation but does not send or save the submitted information. The theme preference is stored in the browser's local storage.
