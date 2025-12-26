# Haris Ansari - Portfolio Website

🌐 **Live at:** [harishaseebat92.github.io](https://harishaseebat92.github.io)

A modern, responsive portfolio website built with Jekyll, featuring a dark theme with smooth animations and a clean developer aesthetic.

## ✨ Features

- **Modern Dark Theme** - Professional dark navy aesthetic with indigo accent colors
- **Single-page Design** - All content on one scrollable page with smooth navigation
- **Responsive Layout** - Looks great on desktop, tablet, and mobile
- **Animated Sections** - Fade-in animations as you scroll
- **Config-driven Content** - All portfolio data managed in `_config.yml`
- **Quantum-themed Hero** - Decorative physics symbols in the background

## 🗂️ Structure

```
harishaseebat92.github.io/
├── _config.yml          # All portfolio data (edit this!)
├── _layouts/
│   └── default.html     # Main HTML template
├── _includes/
│   ├── header.html      # Fixed navigation
│   ├── hero.html        # Landing section
│   ├── about.html       # About + skills
│   ├── projects.html    # Project cards
│   ├── experience.html  # Work timeline
│   ├── education.html   # Education cards
│   └── footer.html      # Footer with social links
├── assets/
│   ├── css/style.css    # All styles
│   └── js/main.js       # Scroll interactions
└── index.md             # Main page (includes components)
```

## 🛠️ Customization

Edit `_config.yml` to update:
- Name, role, and tagline
- Social links (email, LinkedIn, GitHub)
- About me text
- Skills list
- Projects (with descriptions and tech tags)
- Work experience (with bullet points)
- Education history

## 🚀 Local Development

```bash
# Install Jekyll (if not already installed)
gem install bundler jekyll

# Clone and run
git clone https://github.com/harishaseebat92/harishaseebat92.github.io.git
cd harishaseebat92.github.io
bundle exec jekyll serve

# Open http://localhost:4000
```

## 🎨 Theme Customization

Edit CSS variables in `assets/css/style.css`:

```css
:root {
  --accent-color: #6366f1;      /* Main accent color */
  --bg-primary: #0f172a;        /* Background color */
  --text-primary: #f1f5f9;      /* Text color */
}
```

## �️ Project diagrams (SVG recommended)

The “Quantum-Enhanced Simulation Suite” case study page loads diagrams from:

`assets/images/projects/qsim/`

You can use **SVG** (recommended) for crisp, zoomable flowcharts:

- `app-flowchart.svg`
- `em-flowchart.svg`
- `qlbm-flowchart.svg`

If you prefer different filenames, update the `<img src="...">` paths in `projects/quantum-simulation-suite.html`.

## �📝 License

Feel free to use this template for your own portfolio!

This is the source for the personal GitHub Pages site.

## Local preview (optional)

If you have Ruby/Jekyll installed, you can preview locally:

```powershell
bundle exec jekyll serve
```

## Publish

GitHub → Repo Settings → Pages:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

The site will be available at:

- `https://harishaseebat92.github.io/`
