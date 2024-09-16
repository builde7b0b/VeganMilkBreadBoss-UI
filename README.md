# Vegan Milk Bread Boss

Welcome to the Vegan Milk Bread Boss website! This project is an e-commerce platform for ordering various vegan milk bread products. The site is built using HTML, Bootstrap, and custom JavaScript for interactivity and user-friendly shopping experience.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Testing](#testing)
- [Private Code](#private-code)
- [License](#license)

## Project Overview

This website provides a comprehensive ordering system for vegan milk bread. Users can browse through different products, view details, add items to their cart, and place orders via a contact form. The checkout system integrates with a Google Form to handle customer orders.

## Technologies Used

- HTML5
- CSS3 with Bootstrap 5 for responsive design
- JavaScript for interactive features and form validation
- Google Forms for order submission
- Font Awesome for icons
- Custom fonts and styles in `styles.css`

## Setup Instructions

1. **Clone the Repository:**
    ```bash
    git clone <repository-url>
    ```

2. **Navigate to the Project Directory:**
    ```bash
    cd vegan-milk-bread-boss
    ```

3. **Install Dependencies (if applicable):**
    Since this is a static website, there are no backend dependencies to install. However, you can serve the website locally using a simple HTTP server.
    ```bash
    # Using Python's built-in HTTP server
    python -m http.server
    ```
    The website will be available at `http://localhost:8000`.

4. **Open the Website:**
    Open `index.html` in your preferred web browser to view the website.

## Testing

This project includes some basic tests for JavaScript functionality, such as form validation and cart updates. The tests use vanilla JavaScript for simplicity.

1. **Form Validation Test:**
    - Ensure that the checkout form requires all fields (name, email, phone) before submission.
    - Invalid entries (e.g., invalid email format) should prevent form submission.

2. **Cart Functionality Test:**
    - Add items to the cart and verify they appear in the cart summary.
    - Remove items and ensure the cart updates correctly.
    - Check that the total cost is updated when items are added or removed.

### Adding Custom Tests

To add more tests, you can create a `test.js` file with JavaScript test functions. Import this script into `index.html` for browser testing.

## Private Code

Some parts of the code, such as order submission logic and cart processing, are intended to be private. If you plan to integrate sensitive logic (e.g., payment processing, inventory management) in the future, consider implementing these components on a secure backend server rather than in the frontend codebase.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please contact the website owner at `info@veganmilkbreadboss.com`.
