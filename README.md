# E-Portfolio Website

A professional e-portfolio website built with HTML, CSS, and JavaScript, designed to showcase projects and provide contact information. This website is optimized for GitHub Pages deployment.

## Features

- **Home Page**: Professional landing page with hero section, about section, and featured projects
- **Work Page**: Portfolio showcase with filtering capabilities and project categories
- **Contact Page**: Interactive contact form with email functionality
- **Project Pages**: Detailed project descriptions with case studies
- **Responsive Design**: Mobile-first approach with modern UI/UX
- **Modern Styling**: Clean, professional design with smooth animations
- **Accessibility**: Semantic HTML and ARIA labels for screen readers

## Technologies Used

- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **JavaScript ES6+**: Interactive features and form handling
- **Font Awesome**: Professional icons
- **Google Fonts**: Modern typography (Inter font family)

## Project Structure

```
engl394_eportfolio/
├── index.html          # Home page
├── work.html           # Work/portfolio page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
├── work/               # Project subpages
│   ├── project1.html   # E-Commerce Platform
│   ├── project2.html   # Brand Identity Design
│   ├── project3.html   # User Experience Research
│   ├── project4.html   # Mobile App Development
│   ├── project5.html   # Data Visualization Dashboard
│   └── project6.html   # UI Component Library
└── README.md           # This file
```

## Getting Started

### Prerequisites

- A GitHub account
- Git installed on your local machine (optional)

### GitHub Pages Setup

1. **Create a GitHub Repository**
   - Go to [GitHub](https://github.com) and sign in
   - Click the "+" button in the top right corner
   - Select "New repository"
   - Name your repository `your-username.github.io` (replace with your GitHub username)
   - Make it public
   - Don't initialize with README (we'll add our files)
   - Click "Create repository"

2. **Upload Your Files**
   - Click "uploading an existing file" link
   - Drag and drop all your website files (HTML, CSS, JS, and work folder)
   - Or use Git commands if you prefer command line

3. **Enable GitHub Pages**
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Under "Build and deployment", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access Your Website**
   - Your site will be available at `https://your-username.github.io`
   - It may take a few minutes to initially deploy

### Using Git Commands (Alternative Method)

If you prefer using Git commands:

```bash
# Initialize Git repository
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: E-Portfolio website"

# Add remote repository (replace with your repository URL)
git remote add origin https://github.com/your-username/your-repo-name.git

# Push to GitHub
git push -u origin main
```

## Customization

### Personal Information

Update the following placeholders with your information:

- **Name**: Replace "Your Name" throughout the files
- **Email**: Update `your.email@example.com` in contact.html and script.js
- **Social Links**: Update href attributes in the footer sections
- **Project Details**: Modify project descriptions, technologies, and links

### Styling

The website uses CSS custom properties for easy theming. Modify the `:root` section in `styles.css` to change:

- Colors (primary, secondary, text, background)
- Shadows and transitions
- Font sizes and spacing

### Adding New Projects

1. Create a new HTML file in the `work/` folder
2. Follow the existing project template structure
3. Add the project to `work.html` in the work grid
4. Update the project navigation and related projects sections

## Deployment

### GitHub Pages

This website is designed specifically for GitHub Pages deployment. The setup process above will automatically deploy your site.

### Alternative Hosting

The website can also be hosted on:
- Netlify
- Vercel
- Any static hosting service

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized images and assets
- Minimal JavaScript for fast loading
- CSS optimization with custom properties
- Semantic HTML for better SEO

## Security

- No server-side processing required
- Contact form uses mailto: protocol (client-side)
- No sensitive information stored in the code
- HTTPS ready (GitHub Pages provides SSL)

## Maintenance

- Regularly update project information
- Test contact form functionality
- Check for broken links
- Update copyright year annually

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you encounter any issues or have questions:

1. Check the GitHub repository for common solutions
2. Review the setup instructions carefully
3. Ensure all file paths are correct
4. Verify GitHub Pages is properly configured

---

**Note**: This website template is designed for educational and professional portfolio purposes. Feel free to customize it according to your needs and brand identity.
