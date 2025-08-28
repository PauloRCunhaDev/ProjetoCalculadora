# React Calculator

A simple calculator application built with React.js, styled with Tailwind CSS, and utilizing modern JavaScript with Babel for JSX transformation. The project includes a calculator interface for basic arithmetic operations and a history panel to display past calculations.

## Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [Setup](#setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features
- Basic arithmetic operations (addition, subtraction, multiplication, division).
- Clear (C) and Clear Entry (CE) functionality.
- Display of current operation and result.
- Operation history panel to track previous calculations.
- Responsive design for both desktop and mobile devices.
- Styled with Tailwind CSS and custom fonts (Rubik).

## Technologies
- **React.js**: For building reusable UI components.
- **Tailwind CSS**: For styling the application with a utility-first approach.
- **Babel**: For JSX transformation in the browser.
- **HTML5**: For the application structure.
- **Google Fonts (Rubik)**: For typography.

## Setup
1. **Clone or Download the Project**:
   - Copy the provided `index.html` file into your project directory.
   - No additional dependencies are required since all libraries are loaded via CDN.

2. **Serve the Application**:
   - Open the `index.html` file in a web browser directly, or
   - Use a local server (e.g., `npx live-server` or any static file server) to serve the file for a better development experience.

3. **Ensure Internet Access**:
   - The application relies on CDNs for React, ReactDOM, Babel, and Tailwind CSS. Ensure you have an active internet connection.

## Usage
- **Calculator Interface**:
  - Click the number buttons (0-9) to input numbers.
  - Use operation buttons (+, -, ×, ÷) to perform calculations.
  - Press `=` to compute the result.
  - Use `C` to clear the entire operation or `CE` to clear the last entry.
  - The decimal point (`,`) button allows for decimal numbers.

- **Operation History**:
  - The history panel on the right (or below on mobile) displays previous calculations.
  - Currently, the history is static but can be extended to dynamically update with user interactions.

## Project Structure
