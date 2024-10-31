# About Spain! 🌞🇪🇸

## Description
**About Spain!** is a webpage that provides information about Spain, including its nature, history, and national symbols. It includes a user feedback form, the option to switch to night mode, and simple user authentication.

## Features
### 1. User Authentication
- Users can enter their name to authenticate.
- Once the name is entered, a welcome message is displayed, and the form hides.
- The user data is stored in `localStorage` to persist the welcome message even after page reloads.
- Users can log out by clicking the **Logout** button.

### 2. Dark Mode 🌙
- The **Toggle Theme** button switches the page between light and dark modes.
- Theme preferences are saved in `localStorage` so that the selected mode persists even after refreshing the page.

### 3. Feedback Form
- The form includes fields for name, last name, gender, and opinions about Spain.
- Simple form validation ensures that required fields are filled out before submission.
- If fields are empty, the user sees corresponding error messages.
- Upon successful submission, the message **Form submitted successfully!** appears.

