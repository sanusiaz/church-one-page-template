# Church One-Page Template

A modern, responsive, and beautifully designed single-page website template for churches. Built with HTML5, Tailwind CSS (via CDN), and Vanilla JavaScript.

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices.
- **Modern Aesthetics**: Incorporates a sophisticated color palette (Navy and Champagne/Bronze), glassmorphism effects, and smooth scroll animations.
- **Dynamic Video Modal**: Includes a "Watch Live" feature that opens a professional video modal to play embedded YouTube videos dynamically.
- **Sections Included**:
  - Hero Section (with parallax background and animations)
  - Service Times & Information
  - About / Mission Statement
  - Sermon Library Preview
  - Ministries & Groups
  - Upcoming Events
  - Online Giving Form (UI only)
  - Contact Information & Form

## Technologies Used

- **HTML5**: Semantic structure.
- **Tailwind CSS (CDN)**: Rapid UI development and responsive utility classes.
- **Vanilla CSS**: Custom animations, gradients, scrollbar styling, and modal overlay effects.
- **Vanilla JavaScript**: Handles mobile menu toggling, smooth scrolling, intersection observers for scroll reveals, number count-up animations, and the dynamic video modal logic.
- **Google Fonts**: Utilizes *Playfair Display*, *Inter*, and *Cormorant Garamond* for elegant typography.

## How to Use

1. **Clone or Download**: Clone this repository or download the ZIP file to your local machine.
2. **Open the File**: Simply open the `index.html` file in any modern web browser. No build steps, servers, or `npm` installations are required since Tailwind is imported via CDN.

## Customization

- **Colors**: The primary colors (Navy and Champagne/Bronze) are defined in the Tailwind configuration block inside the `<head>` of `index.html`, and can be easily adjusted.
- **Videos**: To change the YouTube videos that play in the "Watch Live" modal, modify the `videoIds` array in the JavaScript section near the bottom of the document.
