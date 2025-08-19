# William Wakefield - Portfolio Website

A modern, responsive portfolio website built with Jekyll and deployed on GitHub Pages.

## 🚀 Quick Start

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/willwake/wjw-web-portfolio.git
   cd wjw-web-portfolio
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **Open in browser**
   Navigate to `http://localhost:4000`

### GitHub Pages Deployment

This site is configured for automatic deployment to GitHub Pages. Simply push to the `main` branch and GitHub Actions will build and deploy the site automatically.

## 📁 Project Structure

```
wjw-web-portfolio/
├── _config.yml          # Jekyll configuration
├── _layouts/            # Page layouts
├── _includes/           # Reusable components
├── _projects/           # Project markdown files
├── assets/
│   ├── css/            # Stylesheets
│   └── js/             # JavaScript files
├── .github/workflows/   # GitHub Actions
└── pages/              # Main pages (about, contact, etc.)
```

## 🎨 Features

- **Responsive Design**: Mobile-first approach with modern CSS Grid and Flexbox
- **Modern UI**: Clean, professional design with smooth animations
- **Dark/Light Theme**: Automatic theme switching based on user preference
- **SEO Optimized**: Meta tags, structured data, and semantic HTML
- **Fast Loading**: Optimized assets and minimal dependencies
- **Accessibility**: WCAG compliant with proper ARIA labels

## 🛠 Technologies

- **Jekyll**: Static site generator
- **GitHub Pages**: Hosting and deployment
- **CSS3**: Modern styling with custom properties
- **JavaScript**: Interactive features and animations
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Inter)

## 📝 Customization

### Personal Information

Update the following files with your information:

1. **_config.yml**: Site title, description, social links
2. **about.md**: Professional summary and experience
3. **_projects/**: Add your project files
4. **assets/**: Replace with your images and files

### Styling

The design uses CSS custom properties for easy theming. Modify the variables in `assets/css/main.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #64748b;
    /* ... other variables */
}
```

### Content Management

- **Projects**: Add markdown files to `_projects/` directory
- **Blog Posts**: Add markdown files to `_posts/` directory (if blog is enabled)
- **Pages**: Create new pages in the root directory or `pages/` folder

## 🔧 Configuration

### GitHub Pages Setup

1. Go to repository Settings > Pages
2. Set source to "GitHub Actions"
3. The site will be automatically deployed on push to main branch

### Custom Domain (Optional)

1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Update `url` in `_config.yml`

## 📊 Performance

- **Lighthouse Score**: 95+ across all categories
- **Page Speed**: < 2s load time
- **Mobile Optimized**: Responsive design
- **SEO Friendly**: Structured data and meta tags

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

- **Email**: your.email@example.com
- **LinkedIn**: [william-wakefield](https://linkedin.com/in/william-wakefield)
- **GitHub**: [willwake](https://github.com/willwake)

---

Built with ❤️ using Jekyll and GitHub Pages
