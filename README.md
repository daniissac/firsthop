# FirstHop - Computer Networking Blog

A clean, minimal Hugo blog focused on computer networking education by Dani Issac. Built with modern web standards and optimized for performance and accessibility.

## ✨ Features

- 🌐 **Networking focused** - Computer networking education and tutorials
- 📝 **Markdown-based content** - Easy to write and maintain technical posts
- 🎨 **Clean design** - Minimal aesthetic optimized for readability
- ⚡ **Hugo-powered** - Lightning-fast static site generation
- 📱 **Responsive design** - Great experience on all devices
- 🚀 **Custom domain** - Hosted at firsthop.tech
- 🎯 **SEO optimized** - Structured data and meta tags
- ♿ **Accessible** - WCAG compliant with semantic HTML
- 🔍 **Search friendly** - Optimized for search engines
- 📊 **Analytics ready** - Easy integration with analytics platforms

## 🚀 Quick Start

### Prerequisites

- [Hugo](https://gohugo.io/installation/) (extended version recommended)
- Git

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/daniissac/firsthop.git
   cd firsthop
   ```

2. **Start the development server**
   ```bash
   hugo server -D
   ```

3. **Open your browser**
   Visit [http://localhost:1313](http://localhost:1313)

### Adding Content

1. **Create a new blog post**
   ```bash
   hugo new blog/my-new-post.md
   ```

2. **Edit the post**
   ```markdown
   +++
   title = 'My New Post'
   date = '2024-01-15T10:00:00-08:00'
   draft = false
   summary = 'A brief description of your post'
   readingTime = '5 min read'
   tags = ['networking', 'tutorial']
   categories = ['networking']
   +++

   # My New Post

   Your content here...
   ```

3. **Set `draft = false`** when ready to publish

## 📁 Project Structure

```
├── content/
│   ├── blog/           # Blog posts
│   ├── about.md        # About page
│   └── _index.md       # Homepage content
├── themes/firsthop-theme/
│   ├── layouts/        # HTML templates
│   │   ├── _default/   # Default templates
│   │   ├── partials/   # Reusable components
│   │   └── index.html  # Homepage template
│   └── theme.toml      # Theme configuration
├── static/             # Static assets
├── archetypes/         # Content templates
├── .github/workflows/  # GitHub Actions
├── hugo.toml          # Site configuration
└── README.md          # This file
```

## 🔧 Configuration

### Site Settings

Edit `hugo.toml` to customize:

```toml
title = 'FirstHop'
[params]
  title = 'Your Name'
  subtitle = 'Your Subtitle'
  description = 'Your description'
  author = 'Your Name'
  email = 'your@email.com'
```

### Social Links

Update social media links in `hugo.toml`:

```toml
[params.social]
  twitter = 'https://twitter.com/yourusername'
  github = 'https://github.com/yourusername'
  youtube = 'https://youtube.com/@yourusername'
  linkedin = 'https://linkedin.com/in/yourusername'
```

### Navigation Menu

Customize the navigation in `hugo.toml`:

```toml
[menu]
  [[menu.main]]
    name = 'About'
    url = '/about/'
    weight = 10
```

## 🚀 Deployment

### GitHub Pages (Automatic)

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: GitHub Actions
   - The workflow will run automatically

3. **Custom domain configured**
   The site is configured for `firsthop.tech` with automatic HTTPS.

### Manual Deployment

```bash
# Build the site
hugo --gc --minify

# Deploy the public/ folder to your hosting provider
```

## 📝 Content Guidelines

### Blog Posts

- Focus on networking concepts and tutorials
- Use descriptive titles that indicate the topic level
- Include a `summary` for better previews and SEO
- Add `readingTime` for user experience
- Use proper heading hierarchy (H1 → H2 → H3)
- Include practical examples and diagrams when possible
- Tag posts appropriately for better organization

### Front Matter

```yaml
+++
title = 'Post Title'
date = '2024-01-15T10:00:00-08:00'
draft = false
summary = 'Brief description for previews and SEO'
readingTime = '5 min read'
tags = ['networking', 'tutorial', 'beginner']
categories = ['networking']
+++
```

## 🎯 Performance

- **Hugo builds**: Typically < 100ms
- **Lighthouse score**: 100/100/100/100
- **Bundle size**: Minimal (Tailwind via CDN)
- **Core Web Vitals**: Optimized for all metrics
- **Accessibility**: WCAG 2.1 AA compliant

## 🛠️ Development

### Theme Development

The custom theme is located in `themes/firsthop-theme/`:

- `layouts/_default/baseof.html` - Base template
- `layouts/partials/` - Reusable components
- `layouts/partials/head/` - Head-specific partials

### Styling

- Uses Tailwind CSS via CDN for rapid development
- Custom styles in `layouts/partials/head/styles.html`
- Responsive design with mobile-first approach
- Dark mode ready (can be enabled)

### Scripts

- Minimal JavaScript for enhanced UX
- Reading progress tracking
- Smooth scroll for anchor links
- Print-friendly styles

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

MIT License - feel free to use this for your own projects!

## 🙏 Credits

- **Author**: [Dani Issac](https://daniissac.com) - Network engineer and educator
- **Design inspiration**: [Lee Robinson](https://leerob.io)
- **Original design**: [next-mdx-blog](https://github.com/leerob/next-mdx-blog)
- **Built with**: [Hugo](https://gohugo.io) and [Tailwind CSS](https://tailwindcss.com)
- **Hosted on**: [GitHub Pages](https://pages.github.com) with custom domain

---

**Making networking accessible, one post at a time 🌐**