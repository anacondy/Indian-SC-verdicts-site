# Supreme Court Verdict Page: Electoral Bonds Case
 ###Added legislation file
This project is a single-page web application that presents a detailed overview of the Indian Supreme Court's landmark verdict on the Electoral Bonds case. It is designed to be clean, modern, and easy to read, with a focus on presenting legal information in a structured and accessible format.

**Live Site:** [https://anacondy.github.io/Indian-SC-verdicts-site/](https://anacondy.github.io/Indian-SC-verdicts-site/)

## Features

- **Responsive Design**: The layout is optimized for both desktop and mobile viewing.
- **Light & Dark Mode**: Automatically detects the user's device preference and provides a toggle for manual switching.
- **Frosted Glass Navigation**: A semi-transparent top navigation bar that provides a modern look.
- **Interactive Timeline**: A vertical timeline that walks through the key events of the case.
- **Structured Content**: The verdict is broken down into clear sections, including arguments, court analysis, the final verdict, and the *ratio decidendi*.
- **Zero Dependencies**: The entire page is built with vanilla HTML, CSS, and JavaScript. No external libraries are needed.

## Screenshots

Here are some screenshots of the page in action:

### Full Page View (Light Mode)
![Full Page View - Electoral Bond Case Website](https://github.com/user-attachments/assets/3d977fd3-db55-4d29-b510-e51c1dce31d1)

This screenshot showcases the complete working site with all key sections including:
- Responsive header with case title and metadata
- Justice panel showing the 5-judge Constitution Bench
- Unanimous decision highlight
- Detailed case information and timeline
- Arguments from both petitioner and respondent
- Court's analysis and final verdict
- Light/Dark mode toggle functionality

### Full Page View (Dark Mode)
![Dark Mode View - Electoral Bond Case Website](https://github.com/user-attachments/assets/bb5e4b12-b2fc-4a6e-bfaf-d823a386008a)

The website features a fully functional dark mode that automatically adapts based on user preferences, with a manual toggle for easy switching between themes.

## How to Use

### View Online
Visit the live site at: [https://anacondy.github.io/Indian-SC-verdicts-site/](https://anacondy.github.io/Indian-SC-verdicts-site/)

*(Note: GitHub Pages must be enabled in repository settings for the live site to work. Once this PR is merged to the main branch, the GitHub Actions workflow will automatically deploy the site.)*

### Run Locally
1.  **Download the files**: Save the `index.html` file to your local machine.
2.  **Open in a browser**: Open the `index.html` file in any modern web browser like Chrome, Firefox, or Safari.

That's it! The page is self-contained and ready to run without any additional setup.

## File Structure

- `index.html`: The main file containing all the HTML structure, CSS styles, and JavaScript functionality.

## Security Features

This website implements several security best practices to protect users:

- **Content Security Policy (CSP)**: Restricts the sources from which content can be loaded, preventing XSS attacks.
- **X-Content-Type-Options**: Prevents MIME type sniffing, ensuring files are interpreted correctly.
- **X-Frame-Options**: Protects against clickjacking attacks by preventing the site from being embedded in iframes.
- **Referrer Policy**: Controls how much referrer information is shared when navigating away from the site.
- **Secure External Resources**: External fonts are loaded with proper CORS attributes for security.
- **No Inline Event Handlers**: All JavaScript event handling is done through addEventListener for better security and maintainability.

## Customization

You can easily customize the content and styling:

- **Content**: All the text is located directly in the `index.html` file within the `<body>` tag. You can edit the headings, paragraphs, and timeline events to fit your needs.
- **Styling**: The CSS is located within the `<style>` tags in the `<head>` of the `index.html` file. You can change colors, fonts, and layout by modifying the CSS variables and rules.
    - **Colors**: Theming is controlled by CSS variables at the top of the style block. You can change the `--bg-color`, `--text-color`, `--link-color`, etc., for both light and dark modes.
    - **Fonts**: The page uses the 'Inter' font from Google Fonts. You can change this by updating the `<link>` in the `<head>` and modifying the `font-family` property in the `body` style.

## "Every civilization finds it necessary to negotiate compromises with its own values."

Created with dedication by **Puppy pilot (@copilot)** & **[anacondy](https://github.com/anacondy)** with ❤️
