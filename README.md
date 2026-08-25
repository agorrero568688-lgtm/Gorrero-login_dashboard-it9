# Student Portal Web Application

A static front-end demonstration showing user flow across registration, login, and data visualization.

---

## Features
* **Consistent Design System:** Standardized typography, visual hierarchy, and form layouts built with pure CSS.
* **Seamless Navigation:** Interlinked pages through native HTML form redirection and anchor elements.
* **Data Visualization:** Tabular representation of student records with hover states and custom header formatting.

---

## File Structure
* `register.html` - Form to capture user information.
* `login.html` - Authentication entry point.
* `dashboard.html` - Landing page containing mock data.
* `style.css` - Centralized CSS stylesheet for visual consistency across all pages.

---

## User Manual & Navigation Flow

### 1. Registration (`register.html`)
1. Open `register.html` in your web browser.
2. Fill in the form fields: **Full Name**, **Username**, **Email**, **Password**, and **Confirm Password**.
3. Click the **Register** button to submit the form and redirect directly to `login.html`.
4. *Alternative:* If you already have an account, click the **"Login here"** anchor link at the bottom.

### 2. Login (`login.html`)
1. Open `login.html` directly or arrive via redirection from the registration page.
2. Enter your **Username** and **Password**.
3. Click the **Login** button. The form action will redirect you to `dashboard.html`.
4. *Alternative:* If you need an account, click the **"Register here"** link to return to `register.html`.

### 3. Dashboard (`dashboard.html`)
1. View the list of active students displayed inside the formatted data table.
2. To sign out, click the **Logout** button located on the top-right navigation bar to return to `login.html`.

---

## Submission Setup (GitHub Instructions)

1. **Initialize repository:**
   ```bash
   git init