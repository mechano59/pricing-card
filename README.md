
# Subscription Plans Webpage

## Overview
This project is a responsive webpage designed to showcase premium subscription plans using HTML, CSS, and JavaScript. It features three subscription tiers (Basic, Standard, and Premium) with interactive card elements, hover effects, and a selection mechanism. The design leverages Bootstrap for layout and responsiveness, Font Awesome for icons, and Google Fonts for typography.

## Features
- **Responsive Design**: Adapts to various screen sizes using Bootstrap's grid system and custom media queries.
- **Interactive Cards**: Subscription cards with hover effects, animated gradient borders, and a selection state that changes styling.
- **Custom Styling**: Utilizes CSS custom properties (variables), gradients, and animations for a modern look.
- **Plan Selection**: JavaScript enables users to select a plan, updating card appearance (background, button, badge, and text colors).
- **External Libraries**:
  - Bootstrap 5.3.0-alpha1 for layout and components.
  - Font Awesome 6.0.0 for icons.
  - Google Fonts (Poppins) for typography.

## File Structure
- `index.html`: The main HTML file containing the webpage structure, styles, and scripts.
- Inline CSS within `<style>` tags for custom styling.
- Inline JavaScript for card selection functionality and DOM manipulation.

## Installation
1. **Clone or Download**: Obtain the project files.
2. **Open `index.html`**: Use a web browser to view the webpage locally. No server setup is required since it uses CDN-hosted libraries.
3. **Dependencies**: Ensure an internet connection to load external resources:
   - Bootstrap CSS and JS (via cdn.jsdelivr.net).
   - Font Awesome (via cdnjs.cloudflare.com).
   - Google Fonts (via fonts.googleapis.com).

## Usage
- Open `index.html` in a browser to view the subscription plans.
- Hover over cards to see animated border and shadow effects.
- Click a card to select it, which applies a gradient background, updates the button and badge styles, and adjusts text colors.
- The page is responsive and works on desktop, tablet, and mobile devices.

## Customization
To modify the webpage:
- **Content**: Edit plan details (names, prices, features) in the HTML `<div class="card-body">` sections.
- **Styling**: Adjust CSS variables in `:root` (e.g., `--primary-color`, `--accent-color`) or other styles in the `<style>` section.
- **Functionality**: Modify the JavaScript in the `<script>` tag to change selection behavior or add new interactions.
- **External Libraries**: Update CDN links to newer versions or replace with local files if offline support is needed.

## Notes
- The webpage includes a Cloudflare challenge script for security, which may require an internet connection to function properly.
- The design is optimized for modern browsers (Chrome, Firefox, Edge, Safari).
- For production use, consider hosting the external libraries locally to improve performance and reliability.

## License
This project is for educational purposes and can be modified or distributed freely, provided the original CDN-hosted libraries comply with their respective licenses.

