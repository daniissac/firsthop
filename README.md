# FirstHop - Computer Networking Blog

A clean, minimal Jekyll blog focused on computer networking education by Dani Issac. Built with modern web standards and optimized for performance and accessibility.

## ✨ Features

- 🌐 **Networking focused** - Computer networking education and tutorials
- 📝 **Markdown-based content** - Easy to write and maintain technical posts
- 🎨 **Clean design** - Minimal aesthetic optimized for readability
- ⚡ **Jekyll-powered** - Fast and reliable static site generation
- 📱 **Responsive design** - Great experience on all devices
- 🚀 **Custom domain** - Hosted at firsthop.tech
- 🎯 **SEO optimized** - Structured data and meta tags
- ♿ **Accessible** - WCAG compliant with semantic HTML
- 🔍 **Search friendly** - Optimized for search engines
- 📊 **Analytics ready** - Easy integration with analytics platforms

## 🚀 Quick Start

### Prerequisites

- [Ruby](https://www.ruby-lang.org/en/downloads/) (version 3.0 or higher)
- [Bundler](https://bundler.io/) gem
- Git

### Local Development

1. **Clone the repository**

   ```bash
   git clone https://github.com/daniissac/firsthop.git
   cd firsthop
   ```

2. **Install dependencies**

   ```bash
   bundle install
   ```

3. **Start the development server**

   ```bash
   bundle exec jekyll serve
   ```

4. **Open your browser**
   Visit [http://localhost:4000](http://localhost:4000)

### Adding Content

1. **Create a new blog post**

   ```bash
   # Create file: _posts/YYYY-MM-DD-title.md
   touch _posts/2024-01-15-my-new-post.md
   ```

2. **Edit the post**

   ```markdown
   ---
   layout: post
   title: "My New Post"
   date: 2024-01-15 10:00:00 -0800
   categories: [networking]
   tags: [networking, tutorial]
   reading_time: "5 min read"
   excerpt: "A brief description of your post"
   ---

   Your content here...
   ```

3. **The post will be automatically published** when you push to main

## 📁 Project Structure

```
├── _posts/             # Blog posts
├── _layouts/           # HTML templates
├── _includes/          # Reusable components
├── _site/              # Generated site (ignored)
├── .github/workflows/  # GitHub Actions
├── _config.yml         # Site configuration
├── Gemfile             # Ruby dependencies
├── index.html          # Homepage
├── about.md            # About page
├── blog.md             # Blog listing page
└── README.md           # This file
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

Update social media links in `_config.yml`:

```yaml
social:
  twitter: https://twitter.com/yourusername
  github: https://github.com/yourusername
  youtube: https://youtube.com/@yourusername
  linkedin: https://linkedin.com/in/yourusername
```

### Navigation Menu

Navigation is configured in the `_includes/header.html` file and can be customized there.

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
bundle exec jekyll build

# Deploy the _site/ folder to your hosting provider
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
---
layout: post
title: "Post Title"
date: 2024-01-15 10:00:00 -0800
categories: [networking]
tags: [networking, tutorial, beginner]
reading_time: "5 min read"
excerpt: "Brief description for previews and SEO"
---
```

## 🎯 Performance

- **Jekyll builds**: Fast and reliable
- **Lighthouse score**: 100/100/100/100
- **Bundle size**: Minimal (Tailwind via CDN)
- **Core Web Vitals**: Optimized for all metrics
- **Accessibility**: WCAG 2.1 AA compliant

## 🛠️ Development

### Theme Development

The custom theme uses Jekyll's built-in structure:

- `_layouts/default.html` - Base template
- `_includes/` - Reusable components
- `_layouts/` - Page templates

### Styling

- Uses Tailwind CSS via CDN for rapid development
- Custom styles in `_layouts/default.html`
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
- **Built with**: [Jekyll](https://jekyllrb.com) and [Tailwind CSS](https://tailwindcss.com)
- **Hosted on**: [GitHub Pages](https://pages.github.com) with custom domain

---

**Making networking accessible, one post at a time 🌐**
