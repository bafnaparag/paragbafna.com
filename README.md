# ParagBafna Apps - Official Website

This repository contains the source code for the official ParagBafna Apps website, which is hosted on GitHub Pages. The website serves as a status page and documentation hub for our macOS and iOS applications.

## 🌐 Website Structure

The website includes:

- **Status Page**: Real-time status information for all our applications
- **Privacy Policies**: Detailed privacy policies for each application
- **Terms of Use**: Terms and conditions for using our applications
- **Support Resources**: Links to support documentation and contact information

## 📁 Repository Structure

```
├── index.html              # Main landing page
├── css/                    # CSS styles
├── js/                     # JavaScript files
├── apps/                   # Individual app pages
│   ├── unwind/             # Unwind app specific pages
│   │   ├── index.html      # App landing page
│   │   ├── privacy.html    # Privacy policy
│   │   └── terms.html      # Terms of use
│   └── [other-apps]/       # Other app directories
├── privacy/                # Main privacy policy directory
├── terms/                  # Main terms of use directory
└── support/                # Support resources
```

## 🚀 Deployment

This website is automatically deployed to GitHub Pages whenever changes are pushed to the `main` branch. The live site can be accessed at [https://paragbafna.github.io](https://paragbafna.github.io) or at your custom domain once configured.

## 🔧 Development

### Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript
- Git installed on your local machine

### Local Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/paragbafna/paragbafna.github.io.git
   cd paragbafna.github.io
   ```

2. Make your changes to the files as needed

3. Test locally by opening the HTML files in a browser

4. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Description of changes"
   git push origin main
   ```

## 📝 Adding a New App

To add a new application to the website:

1. Create a new directory in the `apps/` folder with your app name
2. Copy the template files from another app directory
3. Update the content to reflect the new application
4. Add the app to the status cards section in `index.html`

## 🔒 Custom Domain Setup

To use a custom domain with GitHub Pages:

1. Go to the repository settings on GitHub
2. Scroll to the "GitHub Pages" section
3. Enter your custom domain in the "Custom domain" field
4. Add the appropriate DNS records with your domain registrar:
   - Type: A Record, Host: @, Value: 185.199.108.153
   - Type: A Record, Host: @, Value: 185.199.109.153
   - Type: A Record, Host: @, Value: 185.199.110.153
   - Type: A Record, Host: @, Value: 185.199.111.153
   - Type: CNAME, Host: www, Value: paragbafna.github.io

## 📄 License

© 2025 ParagBafna Apps. All rights reserved.

## 📞 Contact

For questions or concerns about this website, please contact [support@paragbafna.com](mailto:support@paragbafna.com).
