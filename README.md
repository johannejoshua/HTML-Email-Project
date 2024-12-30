# Responsive HTML Email Template

## Overview
This repository contains a **responsive HTML email template** designed with modern HTML and CSS. The template is compatible with over **88 email clients**, including popular platforms like Gmail, Outlook, Apple Mail, and Yahoo Mail. Additionally, it supports **dark mode** rendering, ensuring optimal viewing in both light and dark themes.

## Features
- **Fully Responsive Design:** Adapts seamlessly to different screen sizes, from desktops to mobile devices.
- **Wide Compatibility:** Tested across 88+ email clients for consistent rendering.
- **Dark Mode Support:** Provides a visually pleasing experience in dark mode.
- **Clean and Modular Code:** Easy to understand and customize.
- **Inline CSS:** Ensures maximum compatibility with email clients.

## Preview
### Light Mode
![Light Mode Preview](./assets/light-mode-preview.png)

### Dark Mode
![Dark Mode Preview](./assets/dark-mode-preview.png)

> **Note:** Screenshots are included in the `assets/` directory for a quick visual reference.

## Getting Started

### Prerequisites
To use or customize this template, you'll need:
- A text editor (e.g., VS Code, Sublime Text)
- Basic knowledge of HTML and CSS

### Files Included
- `index.html`: Main HTML file containing the email structure.
- `styles.css`: CSS file with inline styles embedded in the HTML (for email client compatibility).
- `assets/`: Directory containing images and preview screenshots.

### How to Use
1. Clone or download the repository:
   ```bash
   git clone https://github.com/YourUsername/Email-Template.git
   ```
2. Open `index.html` in your text editor to review the code.
3. Customize the template:
   - Replace placeholder text and images with your own content.
   - Modify colors, fonts, or layout as needed.
4. Test the template:
   - Use an email testing tool like [Litmus](https://litmus.com/) or [Email on Acid](https://www.emailonacid.com/) to preview the design in various email clients.
   - Send test emails using an SMTP server or services like Gmail.

## Customization Guide

### Updating Colors
The template uses CSS variables for easy customization. Update the following variables in the `<style>` section:
```css
:root {
  --primary-color: #4CAF50;
  --secondary-color: #FFFFFF;
  --background-light: #F5F5F5;
  --background-dark: #121212;
  --text-light: #000000;
  --text-dark: #FFFFFF;
}
```

### Adding Images
Replace the `src` attribute in the `<img>` tags with your image URLs. Ensure the images are hosted on a reliable CDN for optimal loading times.

### Modifying Layout
The layout is built using tables for email compatibility. Adjust table rows (`<tr>`) and columns (`<td>`) to make structural changes.

## Testing and Compatibility
This template has been tested and verified with:
- **Desktop Clients:** Outlook 2016, Outlook 365, Apple Mail, Thunderbird.
- **Web Clients:** Gmail, Yahoo Mail, Outlook.com.
- **Mobile Clients:** Gmail App, Apple Mail App, Samsung Email.

Dark mode has been tested on:
- **Gmail (Desktop and Mobile)**
- **Apple Mail (Desktop and Mobile)**
- **Outlook (Dark mode-aware clients)**

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add feature name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For questions or feedback, feel free to reach out:
- Email: [your.email@example.com](mailto:your.email@example.com)
- GitHub: [YourUsername](https://github.com/YourUsername)

---

Thank you for checking out this project! I hope this template meets your needs.
