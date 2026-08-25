# Student List Web Application

A static front-end demonstration showing user flow across registration, login, and data visualization.

---

## Features
* **Consistent UI Design:** Clean, uniform typography and form layouts powered by a shared CSS stylesheet.
* **Page Navigation:** Smooth redirection across pages using standard HTML forms and hyperlinked text.
* **Data Display:** Structured table showing mock student data with customized headers and row styling.

---

## File Structure
* `register.html` - Account creation form
* `login.html` - User authentication page
* `dashboard.html` - Main overview page displaying student data
* `style.css` - External stylesheet for global styling

---

## User Manual & Navigation Flow

### 1. Registration (`register.html`)
1. Open `register.html` in your web browser.
2. Fill in the form fields: **Full Name**, **Username**, **Email**, **Password**, and **Confirm Password**.
3. Click the **Register** button to submit the form and redirect directly to `login.html`.
4. If you already have an account, click the **"Login here"** anchor link at the bottom.

### 2. Login (`login.html`)
1. Open `login.html` directly or arrive via redirection from the registration page.
2. Enter your **Username** and **Password**.
3. Click the **Login** button. The form action will redirect you to `dashboard.html`.
4. If you need an account, click the **"Register here"** link to return to `register.html`.

### 3. Dashboard (`dashboard.html`)
1. View the list of active students displayed inside the formatted data table.
2. To sign out, click the **Logout** button located on the top-right navigation bar to return to `login.html`.

---
