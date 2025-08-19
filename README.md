# David Cornish - Personal Portfolio Website

![Portfolio Website](public/social_img.webp)

A modern, responsive portfolio website showcasing my web development expertise and professional experience. Built with cutting-edge technologies for optimal performance and user experience.

## 🚀 Live Demo

Visit the live website: [davidcornish.dev](https://davidcornish.dev)

## 📋 About

This is my personal portfolio website featuring:
- **Professional CV/Resume** - Complete work history and education
- **Project Showcase** - Highlighting my best development work
- **Blog Section** - Sharing insights and tutorials
- **Services** - What I offer to clients
- **Contact Information** - Easy ways to get in touch

## 🛠️ Tech Stack

- **[Astro](https://astro.build)** - Modern static site generator with islands architecture
- **[TailwindCSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[DaisyUI](https://daisyui.com/)** - Beautiful component library for Tailwind
- **[TypeScript](https://www.typescriptlang.org/)** - Type-safe JavaScript
- **[MDX](https://mdxjs.com/)** - Markdown with JSX for blog content

## 🎨 Features

- ⚡ **Lightning Fast** - Static site generation with Astro
- 📱 **Fully Responsive** - Looks great on all devices
- 🌙 **Dark/Light Themes** - Multiple theme options with DaisyUI
- 🔍 **SEO Optimized** - Meta tags, sitemap, and RSS feed
- ♿ **Accessible** - WCAG compliant design
- 🎯 **Performance Focused** - Optimized images and minimal JavaScript

## 💼 Professional Background

**Freelance Web Developer** (2003 - Present)
- WordPress websites and custom solutions
- Logo design and branding
- Computer consultation and training

**Senior Web Developer** at Designs of the 5 Domains (2010-2012)
- PHP and CMS development (WordPress, Drupal, Joomla)
- Graphic design with Photoshop and Illustrator
- MySQL database integration

## 🎓 Education

- **Master of Science in Management Information Systems** - Bellevue University (2008-2009)
- **Bachelor of Science in Computer Science** - Mount Mercy College (2003-2006)
- **Associate of Applied Science in PC & Internet Programming** - Kirkwood Community College (2000-2003)

## 🔧 Skills

**Frontend:** HTML, CSS, JavaScript, TypeScript, React, Astro, Tailwind, Bootstrap

**Backend:** PHP, WordPress, Drupal, Joomla, MySQL

**Tools:** Elementor, Photoshop, Illustrator, Git

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- pnpm (recommended) or npm

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/davidcornishdev.git
cd davidcornishdev
```

2. Install dependencies
```bash
pnpm install
```

3. Start the development server
```bash
pnpm run dev
```

4. Open your browser and visit `http://localhost:4321`

### Build for Production

```bash
pnpm run build
```

### Preview Production Build

```bash
pnpm run preview
```

## 📁 Project Structure

```
├── public/                 # Static assets
│   ├── favicon.svg
│   ├── profile.webp
│   └── ...
├── src/
│   ├── components/         # Reusable UI components
│   ├── content/           # Blog posts and store items
│   ├── layouts/           # Page layouts
│   ├── pages/             # Route pages
│   └── styles/            # Global styles
├── astro.config.mjs       # Astro configuration
├── tailwind.config.cjs    # Tailwind configuration
└── package.json
```

## 🎨 Customization

### Changing Themes

The website uses DaisyUI themes. To change the theme, modify the `data-theme` attribute in `src/layouts/BaseLayout.astro`:

```html
<html lang="en" data-theme="sunset">
```

Available themes: `light`, `dark`, `cupcake`, `bumblebee`, `emerald`, `corporate`, `synthwave`, `retro`, `cyberpunk`, `valentine`, `halloween`, `garden`, `forest`, `aqua`, `lofi`, `pastel`, `fantasy`, `wireframe`, `black`, `luxury`, `dracula`, `cmyk`, `autumn`, `business`, `acid`, `lemonade`, `night`, `coffee`, `winter`, `dim`, `nord`, `sunset`

### Adding Content

- **Blog Posts:** Add `.md` or `.mdx` files to `src/content/blog/`
- **Projects:** Update `src/pages/projects.astro`
- **Services:** Update `src/pages/services.astro`

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- **Website:** [davidcornish.dev](https://davidcornish.dev)
- **Email:** [david@davidcornish.dev](mailto:david@davidcornish.dev)
- **LinkedIn:** [Your LinkedIn Profile](https://linkedin.com/in/davidcornish)
- **GitHub:** [Your GitHub Profile](https://github.com/iowahawkeyedave)

---

⭐ **Star this repository if you found it helpful!**

Built with ❤️ using Astro and modern web technologies.
