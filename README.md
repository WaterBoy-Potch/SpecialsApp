# Water Boy Monthly Specials

A responsive web application designed to showcase Water Boy's monthly specials and coupons. The app features a promotional video overlay, a sign-up form for exclusive offers, and social media links. It is built with HTML, CSS, and JavaScript, utilizing external libraries for enhanced functionality.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Setup](#setup)
- [File Structure](#file-structure)
- [Usage](#usage)
- [Customization](#customization)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project is a "Coming Soon" page for Water Boy's monthly specials web app. It aims to engage users with a video overlay on page load, provide information about past and current specials, and encourage sign-ups for exclusive offers. The design is mobile-friendly and includes a clean, modern aesthetic with a gradient background.

## Features
- **Video Overlay**: A promotional video appears at the top of the page (7/24 of viewport height) on load, with a close button.
- **Responsive Design**: Adapts to various screen sizes, with a larger logo and adjusted layouts for mobile devices.
- **Sign-Up Form**: Users can indicate if they are existing customers, triggering a SweetAlert2 popup and redirecting to Google Forms.
- **Specials Dropdowns**: View past and current specials (past specials are read-only).
- **Social Media & Contact Links**: Footer includes links to Facebook, Instagram, email, and phone, separated by a horizontal line.
- **Custom Styling**: Uses Montserrat and Open Sans fonts, with a blue gradient background.

## Setup
To run this project locally, follow these steps:

1. **Clone or Download**:
   - Clone this repository: `git clone <repository-url>`
   - Or download the ZIP file and extract it.

2. **Open the Project**:
   - Navigate to the project folder.
   - Open `index.html` in a web browser (e.g., Chrome, Firefox) to view the page locally. No server is required as it’s a static site.

3. **Ensure Internet Access**:
   - The project relies on external CDNs for Font Awesome, Google Fonts, and SweetAlert2. An internet connection is needed unless you host these locally.

4. **Optional: Local Server**:
   - For a more robust local setup, use a tool like `live-server` (via npm) or Python’s HTTP server:
     - `npx live-server`
     - `python -m http.server 8000`

## File Structure