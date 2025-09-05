# Muhammad Rizky - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a Full Stack Developer.

## 🌟 Features

- **Responsive Design** - Works perfectly on all devices
- **Modern UI/UX** - Clean and professional design
- **Smooth Animations** - Enhanced user experience with smooth scrolling and transitions
- **Contact Form** - Functional contact form with validation
- **Project Showcase** - Featured projects with live demos and source code links
- **Skills Section** - Categorized technical skills and technologies

## 🚀 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Grid and Flexbox
- **JavaScript** - Interactive functionality
- **Font Awesome** - Icons
- **Google Fonts** - Typography

## 📱 Sections

1. **Hero** - Introduction and call-to-action
2. **About** - Personal information and statistics
3. **Skills** - Technical skills organized by category
4. **Projects** - Featured work with descriptions and links
5. **Contact** - Contact form and social links

## 🛠️ Setup & Deployment

### Local Development

1. Clone the repository
2. Open `index.html` in your browser
3. No build process required - it's a static website!

### Deployment Options

#### Option 1: Netlify (Recommended)
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy to production
netlify deploy --prod --dir .
```

#### Option 2: Vercel
```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel --prod
```

#### Option 3: GitHub Pages
1. Push code to GitHub repository
2. Go to Settings > Pages
3. Select source branch
4. Your site will be live at `https://username.github.io/repository-name`

## 🎨 Customization

### Personal Information
Edit the following in `index.html`:
- Name and title in the hero section
- About me text
- Project information
- Contact details

### Styling
Modify `styles.css` to change:
- Color scheme (CSS variables at the top)
- Typography
- Layout and spacing
- Animations

### Functionality
Update `script.js` to add:
- Form submission handling
- Additional animations
- Interactive features

## 📧 Contact Form

The contact form is currently set up for client-side validation. To make it functional, you can:

1. **Netlify Forms** (Recommended for Netlify hosting)
   - Add `netlify` attribute to the form
   - Forms will be automatically handled

2. **Formspree** - External form service
   - Sign up at formspree.io
   - Replace form action with Formspree endpoint

3. **Custom Backend** - Build your own API
   - Node.js + Express
   - PHP script
   - Serverless functions

## 🔧 Performance Optimization

- Optimized images (use WebP format)
- Minified CSS and JavaScript
- Lazy loading for images
- CDN for external resources

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio!

---

**Muhammad Rizky** - [muhammadrizky.dev](https://muhammadrizky.dev)
