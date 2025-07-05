# W3C Credentials Community Group Website

The official website for the W3C Credentials Community Group, built with
[Eleventy (11ty)](https://www.11ty.dev/) and deployed automatically via GitHub
Actions.

## 🚀 Quick Start

### Prerequisites
- Node.js (version 22 or higher)
- npm or yarn

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/w3c-ccg/w3c-ccg.org
   cd w3c-ccg.org
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start development server:**
   ```bash
   npm start
   ```

4. **Build for production:**
   ```bash
   npm run build
   ```

The site will be available at `http://localhost:8080` during development.

## 🛠️ Development

### Available Scripts

- `npm start` - Start development server with live reload
- `npm run build` - Build the site for production
- `npm run clean` - Clean the build directory

### Adding New Pages

1. Create a new Markdown file in the `src/` directory
2. Add front matter with layout and metadata:
   ```yaml
   ---
   layout: base.njk
   title: "Your Page Title"
   description: "Page description for SEO"
   ---
   ```
3. Write your content in Markdown, HTML, or Nunjucks

### Modifying Styles

Edit `src/css/style.css` to customize the appearance. The CSS includes:
- Responsive design for all screen sizes
- Accessibility features (focus states, ARIA support)
- Modern design with W3C-appropriate styling
- Mobile-first approach

### JavaScript Features

The site includes interactive features in `src/js/main.js`:
- Mobile navigation toggle
- Dropdown menu support
- Smooth scrolling
- Keyboard navigation
- Accessibility enhancements

## 🚀 Deployment

### Automatic Deployment

The site automatically deploys to GitHub Pages when you push to the `main` branch. The GitHub Actions workflow:

1. Checks out the code
2. Sets up Node.js
3. Installs dependencies
4. Builds the site
5. Deploys to GitHub Pages

### Manual Deployment

To deploy manually:

1. Build the site: `npm run build`
2. The built site will be in the `_site/` directory
3. Deploy the contents of `_site/` to your hosting provider

## 🤝 Contributing

We welcome contributions from the community! Here's how to get involved:

### Submitting Changes

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Make your changes
4. Test thoroughly
5. Commit with clear messages
6. Push to your fork
7. Create a Pull Request

## 📚 Resources

### W3C Credentials Community Group

- **W3C Community Page**: https://www.w3.org/community/credentials/
- **Mailing List**: public-credentials@w3.org
- **GitHub**: https://github.com/w3c-ccg
- **Meeting Info**: Every Tuesday at 12:00 PM ET

### Development Resources

- [Eleventy Documentation](https://www.11ty.dev/docs/)
- [Nunjucks Templating](https://mozilla.github.io/nunjucks/)
- [GitHub Actions Guide](https://docs.github.com/en/actions)

## 📄 License

This project is licensed under the [W3C Software and Document License](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document).

## 🙏 Acknowledgments

- The W3C Credentials Community Group members
- Contributors to the Eleventy framework
- The broader digital identity community
- All community members who provide feedback and contributions

---

## 🔗 Quick Links

- [Join our mailing list](mailto:public-credentials-request@w3.org?subject=subscribe)
- [Weekly meetings](https://meet.jit.si/w3c-ccg)
- [GitHub organization](https://github.com/w3c-ccg)
- [W3C Community Group page](https://www.w3.org/community/credentials/)

**Built with ❤️ by the W3C Credentials Community Group**
