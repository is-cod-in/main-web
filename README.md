# is-cod.in

<div align="center">
  <img src="assets/logo.png" alt="is-cod.in Logo" width="200"/>

  **Free Subdomain Service for Everyone**

  [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
  [![Website](https://img.shields.io/website?url=https%3A%2F%2Fis-cod.in)](https://is-cod.in)
  [![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black)](https://vercel.com)
</div>

---

## Table of Contents

- [About](#about)
- [Features](#features)
- [Live Demo](#live-demo)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Local Development](#local-development)
- [Usage](#usage)
  - [For Users](#for-users)
  - [For Contributors](#for-contributors)
- [Project Structure](#project-structure)
- [Technology Stack](#technology-stack)
- [Registration Process](#registration-process)
- [Contributing](#contributing)
- [Team](#team)
- [License](#license)
- [Support](#support)

---

## About

**is-cod.in** is a free subdomain service that allows users to claim their own custom subdomains under the `is-cod.in` domain. Whether you're a developer, hobbyist, or someone looking to host a personal project, is-cod.in provides an easy and accessible way to get your own subdomain completely free of charge.

Our mission is to make web hosting more accessible by providing free subdomains to anyone who needs them. Join our growing community and claim your subdomain today!

---

## Features

- **Free Subdomain Registration** - Get your own subdomain at no cost
- **Simple Registration Process** - Register via GitHub or Discord
- **Modern UI** - Clean, responsive design with smooth animations
- **Instant Subdomain Preview** - Check if your desired subdomain is available
- **Community Driven** - Open-source project with active development
- **Fast Deployment** - Hosted on Vercel for optimal performance
- **Mobile Responsive** - Works seamlessly on all devices
- **SEO Optimized** - Proper meta tags and Open Graph support

---

## Live Demo

Visit our website: [https://is-cod.in](https://is-cod.in)

Check out the team page: [https://is-cod.in/team](https://is-cod.in/team)

---

## Getting Started

### Prerequisites

To run this project locally, you only need a web browser and a simple HTTP server. No build tools or package managers are required.

- **Web Browser** (Chrome, Firefox, Safari, Edge, etc.)
- **HTTP Server** (optional, for local development)

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/is-cod-in/main-web.git
cd main-web
```

2. **That's it!** The project uses vanilla HTML, CSS, and JavaScript with no build process required.

### Local Development

You can open the `index.html` file directly in your browser, or use a simple HTTP server for a better development experience:

**Option 1: Using Python**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Option 2: Using Node.js (http-server)**
```bash
npx http-server
```

**Option 3: Using VS Code Live Server**
- Install the "Live Server" extension in VS Code
- Right-click on `index.html` and select "Open with Live Server"

Then navigate to `http://localhost:8000` (or the port your server is using) in your browser.

---

## Usage

### For Users

1. **Visit the Website**: Go to [https://is-cod.in](https://is-cod.in)

2. **Choose Your Subdomain**: Enter your desired subdomain name in the input field

3. **Check Availability**: Click "Claim Subdomain" to verify if the subdomain is available

4. **Register**: Complete the registration process through:
   - **GitHub**: [Register with GitHub](https://github.com/is-cod-in/register)
   - **Discord**: [Join our Discord](https://discord.gg/zEVFx2Vdq5)

5. **Wait for Approval**: Our team will review and approve your subdomain request

6. **Start Using**: Once approved, your subdomain will be active and ready to use!

### For Contributors

If you want to contribute to the project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test your changes locally
5. Commit your changes (`git commit -m 'Add some amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

---

## Project Structure

```
main-web/
├── assets/              # Static assets
│   └── logo.png        # Project logo
├── team/               # Team page
│   └── index.html      # Team members showcase
├── index.html          # Main landing page
├── vercel.json         # Vercel deployment configuration
├── LICENSE             # GPL v3 License
└── README.md           # Project documentation
```

### Key Files

- **index.html**: Main landing page with subdomain registration interface
- **team/index.html**: Team members page showcasing contributors
- **vercel.json**: Configuration for Vercel deployment (enables clean URLs)
- **assets/logo.png**: Project logo and branding

---

## Technology Stack

- **HTML5** - Modern semantic markup
- **CSS3** - Advanced styling with gradients, animations, and responsive design
- **JavaScript (Vanilla)** - Client-side interactivity with no frameworks
- **Font Awesome** - Icon library for social media icons
- **Google Fonts** - Silkscreen font for unique typography
- **Vercel** - Hosting and deployment platform

**Why Vanilla JavaScript?**

We chose to build this project without frameworks to:
- Keep the project lightweight and fast
- Minimize dependencies
- Make it easy for beginners to contribute
- Ensure maximum compatibility across browsers

---

## Registration Process

### Step-by-Step Guide

1. **Choose Your Subdomain**
   - Enter a valid subdomain (lowercase letters, numbers, and hyphens only)
   - Format: `your-subdomain.is-cod.in`

2. **Submit Registration**
   - Visit the [GitHub repository](https://github.com/is-cod-in/register)
   - Or join our [Discord server](https://discord.gg/zEVFx2Vdq5)

3. **Provide Required Information**
   - Subdomain name
   - Target URL or server details
   - Contact information

4. **Wait for Approval**
   - Our team reviews all requests
   - Approval typically takes 24-48 hours

5. **Subdomain Activation**
   - Once approved, DNS records are configured
   - Your subdomain becomes active

### Subdomain Guidelines

- Must be alphanumeric with hyphens (no special characters)
- Cannot contain offensive or inappropriate content
- Must not infringe on trademarks or copyrights
- Should not be used for illegal activities
- One subdomain per user/project

---

## Contributing

We welcome contributions from the community! Here's how you can help:

### Ways to Contribute

- **Report Bugs**: Open an issue if you find a bug
- **Suggest Features**: Share your ideas for new features
- **Improve Documentation**: Help us make the docs better
- **Submit Pull Requests**: Contribute code improvements
- **Spread the Word**: Share is-cod.in with others

### Development Workflow

1. **Fork the Repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/main-web.git
   ```

2. **Create a Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Your Changes**
   - Follow existing code style
   - Test thoroughly
   - Keep changes focused and atomic

4. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "feat: add your feature description"
   ```

5. **Push to Your Fork**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Open a Pull Request**
   - Describe your changes clearly
   - Reference any related issues
   - Wait for review

### Code Style Guidelines

- Use consistent indentation (spaces, not tabs)
- Write descriptive variable and function names
- Add comments for complex logic
- Keep functions small and focused
- Test your changes across different browsers

### Commit Message Conventions

We follow conventional commit messages:

- `feat:` - New feature
- `fix:` - Bug fix
- `docs:` - Documentation changes
- `style:` - Code style changes (formatting, etc.)
- `refactor:` - Code refactoring
- `test:` - Adding or updating tests
- `chore:` - Maintenance tasks

---

## Team

Meet the amazing people behind is-cod.in:

| Name | Role | Description |
|------|------|-------------|
| **Araan** | Lead | Project founder and lead developer |
| **Axiom** | Co-Lead | Co-leader and core contributor |
| **Mopizify** | Collaborator | Active contributor |
| **TheBoys** | Collaborator | Development support |
| **Hari** | Partner | Strategic partner |
| **Jay** | Collaborator | Community support |

Want to meet the team? Visit our [Team Page](https://is-cod.in/team)!

---

## License

This project is licensed under the **GNU General Public License v3.0** - see the [LICENSE](LICENSE) file for details.

### What This Means

- You can freely use, modify, and distribute this software
- Any modifications must also be open-source under GPL v3
- You must include the original copyright notice
- No warranty is provided

---

## Support

Need help or have questions? We're here to help!

### Contact Us

- **GitHub Issues**: [Report a bug or request a feature](https://github.com/is-cod-in/main-web/issues)
- **Discord Community**: [Join our Discord server](https://discord.gg/zEVFx2Vdq5)
- **Website**: [https://is-cod.in](https://is-cod.in)

### Frequently Asked Questions

**Q: Is this service really free?**
A: Yes! is-cod.in is completely free to use.

**Q: Can I use my subdomain for commercial purposes?**
A: Yes, you can use your subdomain for any legal purpose, including commercial projects.

**Q: How long does approval take?**
A: Most requests are approved within 24-48 hours.

**Q: Can I have multiple subdomains?**
A: Generally, we allow one subdomain per user. Contact us if you need multiple subdomains for different projects.

**Q: What if my desired subdomain is taken?**
A: Try a different name or variation. Subdomains are assigned on a first-come, first-served basis.

**Q: Can I transfer my subdomain to someone else?**
A: Please contact us on Discord to discuss subdomain transfers.

---

## Acknowledgments

- Thanks to all our contributors and community members
- Built with passion for the open-source community
- Hosted on Vercel's amazing platform
- Icons by Font Awesome
- Fonts by Google Fonts

---

<div align="center">
  Made with ❤️ by the is-cod.in team

  [Website](https://is-cod.in) • [GitHub](https://github.com/is-cod-in) • [Discord](https://discord.gg/zEVFx2Vdq5)
</div>
