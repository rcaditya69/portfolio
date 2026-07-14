# Aditya Roy Choudhury - Portfolio Website

A modern, responsive portfolio website showcasing my experience as a Senior Integration Engineer at Hitachi Digital, with expertise in SnapLogic, Apigee, Java Spring Boot, and FastAPI.

## Features

- **Responsive Design** — Mobile-first approach, works on all screen sizes
- **Dark Theme** — Techy, modern aesthetic optimized for tech recruiter audiences
- **Smooth Scroll-Spy Navigation** — Active nav highlighting as you scroll
- **Mobile Menu** — Hamburger navigation for mobile devices
- **Scroll Animations** — Cards fade in as they come into view
- **No Build Tools** — Pure HTML, CSS, and vanilla JavaScript—no dependencies

## Sections

- **Hero** — Personal branding with call-to-action
- **About** — Brief bio and professional summary
- **Experience** — Timeline of career milestones
- **Skills** — Grouped skill tags (Integration, Backend, Tools)
- **Certifications** — Certified SnapLogic Developer badge
- **Projects** — Showcase of work (journalApp + placeholders for case studies)
- **Contact** — Email, LinkedIn, and GitHub links

## TODO Before Sharing with Recruiters

The portfolio includes placeholder content that you should customize:

1. **Projects Section**
   - **SnapLogic Case Study** — Replace the `[PLACEHOLDER]` project card with details of a real SnapLogic integration project you've worked on. Include impact metrics (e.g., "Reduced processing time by 80%").
   - **Apigee Case Study** — Replace the second placeholder with your Apigee/API management project. Include governance policies, partner impact, latency improvements, etc.

2. **Contact Section**
   - Update the LinkedIn URL from `https://linkedin.com/in/rcaditya69` to your actual LinkedIn profile URL.

## Local Preview

1. Open `index.html` in a web browser to view locally.
2. Or serve via a simple HTTP server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Then navigate to http://localhost:8000
   ```

## Deployment

This site is designed to deploy on **GitHub Pages**:

1. Push to a public GitHub repo named `portfolio` (or `rcaditya69.github.io` for the root domain)
2. Enable GitHub Pages in repository Settings → Pages
3. Set source to `main` branch
4. Site will be live at `https://rcaditya69.github.io/portfolio/` (or `https://rcaditya69.github.io/` if using the root repo)

## File Structure

```
.
├── index.html          # Main HTML file with all sections
├── css/
│   └── style.css       # Styling and animations
├── js/
│   └── main.js         # Navigation, scroll-spy, and animations
└── README.md           # This file
```

## Customization

- **Colors** — Edit CSS custom properties in `css/style.css` (`:root` section) to match your brand
- **Content** — Update text directly in `index.html`
- **Fonts** — Change `--font-sans` and `--font-mono` in the CSS
- **Spacing** — Adjust spacing values (`--spacing-*`) in the CSS

## Browser Support

Works on all modern browsers (Chrome, Firefox, Safari, Edge). Graceful degradation for older browsers.

## License

Personal portfolio — feel free to customize and use as a template.

---

**Built with:** HTML5, CSS3, Vanilla JavaScript | **Hosted on:** GitHub Pages
