# Haikal's Portfolio

A highly configurable, responsive personal portfolio website built with HTML, CSS, and JavaScript. This project is designed to be easily customizable via YAML configuration and Markdown content files.

## 🚀 Live Demo

Check out the live version here: [haikalimamridha.github.io](https://haikalimamridha.github.io/haikalswag.github.io/)

## ✨ Features

- **YAML-Powered Configuration**: Easily update your site's title, navigation, social links, and section icons without touching HTML.
- **Dynamic Markdown Content**: Manage your content using simple Markdown files.
- **Responsive Design**: Built with Bootstrap 5 and custom CSS to look great on all devices.
- **Math Support**: Integrated with MathJax for beautiful mathematical notation.
- **Interactive Project Gallery**: Showcase your work with responsive image galleries.
- **Test Suite**: Includes automated tests to ensure template quality and functionality.

## 🛠️ Project Structure

```text
├── contents/               # Configuration and content files
│   ├── config.yml          # Main site configuration
│   ├── home.md             # Biography and contact info
│   ├── projects.md         # Detailed project showcase
│   ├── services.md         # Experience and services
│   └── journal.md          # Academic papers and journals
├── static/                 # Static assets
│   ├── assets/             # Images, PDFs, and favicons
│   ├── css/                # Custom and Bootstrap styles
│   └── js/                 # Site logic and dependencies
├── tests/                  # Test scripts
├── index.html              # Main landing page
└── LICENSE                 # MIT License
```

## ⚙️ Customization

### 1. Main Configuration
Modify `contents/config.yml` to update:
- Site Title and Navbar Brand
- Social Media Links (LinkedIn, GitHub, Instagram, etc.)
- CV/Resume Link
- Section definitions (ID, Title, Icon, Navigation text)

### 2. Updating Content
Edit the `.md` files in the `contents/` directory to update your information. The site automatically parses these files and injects the HTML into the corresponding sections.

### 3. Adding Projects
The `projects.md` file supports a custom `<div class="project-gallery">` to display multiple screenshots for each project.

## 🧪 Running Tests

The project includes tests to ensure everything is working correctly. You can run them using Node.js:

```bash
node tests/template-quality.test.js
node tests/background-selection.test.js
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ✍️ Author

**Haikal Imam Ridha**
- GitHub: [@haikalimamridha](https://github.com/haikalimamridha)
- LinkedIn: [Haikal I Ridha](https://www.linkedin.com/in/haikal-i-ridha-817869326)
