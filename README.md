
Built by https://www.blackbox.ai

---

```markdown
# SecRoster

## Project Overview
SecRoster is a web-based application designed for security personnel and their employers. It provides a streamlined interface for various user types to manage their accounts, allowing companies and guards to sign up, log in, and access essential functionalities. 

## Installation
To run this project locally, you can simply clone the repository and open the `index.html` file in your web browser. Follow these steps:

1. Clone the repository:
   ```bash
   git clone https://your-repository-url.git
   ```
2. Navigate into the project directory:
   ```bash
   cd your-project-directory
   ```
3. Open the `index.html` file in your preferred web browser.

## Usage
You can start using the application by visiting the main page (`index.html`). From there, you have the option to sign up as either a company or a guard. 

### Account Types
1. **Company Signup**: Fill in the required fields to create a company account.
2. **Guard Signup**: Fill in the necessary details to register as a guard.
3. **Login**: Access your account by entering your email and password.

## Features
- **Responsive Design**: The application is styled with Tailwind CSS, ensuring a mobile-friendly experience.
- **User Account Management**: Companies and guards can easily sign up and log in.
- **Admin Dashboard**: For managing registered guards, including verification and access to multiple functions.
- **User-Friendly Interface**: Easy navigation and prompt feedback on form submissions.

## Dependencies
The project primarily uses:
- **Tailwind CSS**: This framework is included via CDN for styling and responsive design.
- **Font Awesome**: For icons, included via CDN.

No additional packages or libraries were found in a `package.json` file as this project is purely HTML/CSS/JavaScript-based and does not require a Node.js environment.

## Project Structure
Here's the basic structure of the project:
```
secRoster/
│
├── index.html             # Main landing page for choosing account type
├── company-signup.html    # Signup page for company users
├── guard-signup.html      # Signup page for guard users
├── login.html             # Login page for all users
├── admin-dashboard.html    # Admin dashboard for company managing guards
```

### Styling
The styling for the application is managed through:
- Tailwind CSS for utility-first styling.
- Custom fonts from Google Fonts.

### Script Functionality
JavaScript functions are used to manage form submissions and basic interactivity:
- Form validations.
- Dropdown management in the admin dashboard.
- Tab switching functionality for organizing tasks.

## Conclusion
SecRoster provides an elegant and functional approach to managing security personnel and their registrations. Feel free to contribute to the project or use it as a foundation for your own applications!
```