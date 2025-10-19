# Supreme Court Verdict Page: Electoral Bonds Case

This project is a single-page web application that presents a detailed overview of the Indian Supreme Court's landmark verdict on the Electoral Bonds case. It is designed to be clean, modern, and easy to read, with a focus on presenting legal information in a structured and accessible format.

## Features

- **Responsive Design**: The layout is optimized for both desktop and mobile viewing.
- **Light & Dark Mode**: Automatically detects the user's device preference and provides a toggle for manual switching.
- **Frosted Glass Navigation**: A semi-transparent top navigation bar that provides a modern look.
- **Interactive Timeline**: A vertical timeline that walks through the key events of the case.
- **Structured Content**: The verdict is broken down into clear sections, including arguments, court analysis, the final verdict, and the *ratio decidendi*.
- **Zero Dependencies**: The entire page is built with vanilla HTML, CSS, and JavaScript. No external libraries are needed.

## Screenshots

Here are some screenshots of the page in action:

### Arguments Section
![Arguments Section](image1)

### Case Progression Timeline
![Case Progression Timeline](image2)

## How to Use

1.  **Download the files**: Save the `index.html` file to your local machine.
2.  **Open in a browser**: Open the `index.html` file in any modern web browser like Chrome, Firefox, or Safari.

That's it! The page is self-contained and ready to run without any additional setup.

## File Structure

- `index.html`: The main file containing all the HTML structure, CSS styles, and JavaScript functionality.

## Customization

You can easily customize the content and styling:

- **Content**: All the text is located directly in the `index.html` file within the `<body>` tag. You can edit the headings, paragraphs, and timeline events to fit your needs.
- **Styling**: The CSS is located within the `<style>` tags in the `<head>` of the `index.html` file. You can change colors, fonts, and layout by modifying the CSS variables and rules.
    - **Colors**: Theming is controlled by CSS variables at the top of the style block. You can change the `--bg-color`, `--text-color`, `--link-color`, etc., for both light and dark modes.
    - **Fonts**: The page uses the 'Inter' font from Google Fonts. You can change this by updating the `<link>` in the `<head>` and modifying the `font-family` property in the `body` style.
