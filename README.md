# 🚀 AI Researcher Portfolio

A modern, minimalist black and white portfolio website for AI researchers, built with pure HTML, CSS, and JavaScript. Features easy content management through JSON files and seamless GitHub Pages deployment.

![Portfolio Preview](https://via.placeholder.com/800x400/000000/FFFFFF?text=AI+Researcher+Portfolio)

## ✨ Features

### 🎨 Design & User Experience
- **Ultra-minimalist black & white theme** with clean typography
- **Dark/light mode toggle** with persistent theme preference
- **Fully responsive design** optimized for all devices
- **Smooth animations** and interactive elements
- **Loading screens** and progress indicators
- **Accessibility-focused** with proper ARIA labels

### 📱 Pages & Sections
- **Homepage**: Hero section with animated background and typewriter effect
- **About**: Personal bio, timeline, skills, and achievements
- **Projects**: Filterable project showcase with search functionality
- **Research**: Publications, research interests, and academic metrics
- **Blog**: Article system with categories, tags, and search
- **Blog Post**: Individual blog post pages with sharing and related posts
- **Contact**: Working contact form with FAQ section

### 🛠️ Technical Features
- **No build process required** - pure HTML/CSS/JS
- **JSON-based content management** for easy updates
- **GitHub Pages ready** with automated deployment
- **SEO optimized** with proper meta tags
- **Performance optimized** with efficient loading
- **Cross-browser compatible**

### 🔧 Content Management
- **Easy editing** through JSON files in the `data/` folder
- **No coding required** for content updates
- **Structured data** for projects, blog posts, and profile info
- **Image organization** with dedicated asset folders

## 🚀 Quick Start

### 1. Clone or Download
```bash
git clone https://github.com/yourusername/ai-researcher-portfolio.git
cd ai-researcher-portfolio
```

### 2. Customize Your Content
Edit the JSON files in the `data/` folder:

- `data/profile.json` - Personal information, education, experience
- `data/projects.json` - Project details, technologies, links
- `data/blogs.json` - Blog posts, articles, and insights

### 3. Deploy to GitHub Pages

#### Option A: Automatic Deployment
1. Push to a GitHub repository
2. Go to Settings → Pages
3. Select "GitHub Actions" as source
4. The site will deploy automatically on every push

#### Option B: Manual Deployment
1. Enable GitHub Pages in repository settings
2. Select source branch (usually `main`)
3. Your site will be available at `https://yourusername.github.io/repository-name`

## 📂 Project Structure

```
ai-researcher-portfolio/
├── index.html              # Homepage
├── about.html              # About page
├── projects.html           # Projects showcase
├── research.html           # Research & publications
├── blog.html              # Blog listing
├── blog-post.html         # Individual blog post template
├── contact.html           # Contact form & info
├── css/
│   └── style.css          # Main stylesheet
├── js/
│   ├── main.js            # Core functionality
│   ├── about.js           # About page scripts
│   ├── projects.js        # Projects page scripts
│   ├── blog.js            # Blog page scripts
│   ├── blog-post.js       # Blog post page scripts
│   └── contact.js         # Contact page scripts
├── data/
│   ├── profile.json       # Personal information
│   ├── projects.json      # Project data
│   └── blogs.json         # Blog posts
├── assets/
│   ├── images/            # Profile images
│   ├── projects/          # Project screenshots
│   ├── blog/              # Blog post images
│   └── documents/         # PDFs, resume, etc.
├── .github/
│   └── workflows/
│       └── pages.yml      # GitHub Pages deployment
└── README.md              # This file
```

## 🎯 Content Management Guide

### Adding a New Project

Edit `data/projects.json`:

```json
{
  "id": 9,
  "title": "Your Project Name",
  "description": "Brief description of your project",
  "tech": ["Python", "PyTorch", "FastAPI"],
  "github": "https://github.com/yourusername/project",
  "demo": "https://your-demo-link.com",
  "image": "assets/projects/your-project.jpg",
  "featured": false,
  "category": "AI/ML",
  "status": "Complete",
  "year": "2024"
}
```

### Adding a Blog Post

Edit `data/blogs.json`:

```json
{
  "id": 6,
  "title": "Your Blog Post Title",
  "excerpt": "Short preview of your post...",
  "content": "Full content in markdown format...",
  "author": "Your Name",
  "date": "2024-01-15",
  "tags": ["AI", "Research"],
  "category": "Research",
  "readTime": "5 min read",
  "featured": false
}
```

### Updating Profile Information

Edit `data/profile.json` to update:
- Personal details and bio
- Education and experience
- Skills and research interests
- Social media links
- Achievements and awards

## 🎨 Customization

### Colors & Branding
The design uses a pure black and white theme. To customize:

1. **Colors**: Edit CSS variables in `css/style.css`
2. **Typography**: Change Google Fonts imports in HTML files
3. **Logo**: Update the `<AI/>` logo in navigation

### Adding New Sections
1. Create new HTML file
2. Add corresponding JavaScript file
3. Update navigation in all pages
4. Add data JSON file if needed

## 🚀 Deployment Options

### GitHub Pages (Recommended)
- **Free hosting** for public repositories
- **Custom domain support**
- **Automatic SSL certificates**
- **CDN distribution**

### Other Options
- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **Firebase Hosting**: Google's hosting platform
- **Traditional web hosting**: Upload files via FTP

## 📱 Mobile Optimization

The portfolio is fully responsive with:
- **Mobile-first design** approach
- **Touch-friendly** interface elements
- **Optimized loading** for slower connections
- **Hamburger menu** for mobile navigation

## 🔍 SEO Features

- **Semantic HTML** structure
- **Meta tags** for social sharing
- **Structured data** for search engines
- **Optimized images** with alt text
- **Fast loading times**
- **Mobile-friendly** design

## 🛡️ Security & Privacy

- **No server-side code** (static site)
- **No database** required
- **HTTPS** by default on GitHub Pages
- **Privacy-focused** contact form
- **No tracking** by default

## 🤝 Contributing

Contributions are welcome! Please feel free to:
1. **Report bugs** via GitHub issues
2. **Suggest features** for improvement
3. **Submit pull requests** with enhancements
4. **Share feedback** on the design

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 💬 Support

- **Documentation**: Check this README and code comments
- **Issues**: Use GitHub Issues for bug reports
- **Discussions**: Use GitHub Discussions for questions
- **Email**: Contact for custom development needs

## 🎯 Roadmap

Future enhancements planned:
- [x] Dark/light mode toggle
- [x] Blog post single page template
- [ ] Analytics integration options
- [ ] Newsletter signup functionality
- [ ] Multi-language support
- [ ] CMS integration options

---

**Built with ❤️ for the AI research community**

*Star this repository if it helped you create an amazing portfolio!*
