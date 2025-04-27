# Hugo Hextra Landing Starter

A modern, blazing-fast landing page and documentation starter built with [Hugo](https://gohugo.io/), [TailwindCSS](https://tailwindcss.com/), and [Alpine.js](https://alpinejs.dev/).

## Features
- ⚡️ Super fast static site generation with Hugo
- 🎨 Utility-first styling using TailwindCSS
- 🧩 Interactive UI enhancements with Alpine.js
- 📝 Ready-to-use documentation and landing page layouts
- 🔒 SEO-friendly and easily customizable

## Technology Stack
- **Hugo**: Static site generator for building fast, flexible websites
- **TailwindCSS**: Utility-first CSS framework, integrated via Hugo’s [official TailwindCSS function](https://gohugo.io/functions/css/tailwindcss/)
- **Alpine.js**: Lightweight JavaScript framework for interactivity

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (for TailwindCSS and Alpine.js)
- [Hugo Extended](https://gohugo.io/getting-started/installing/) (minimum version 0.124.0)

### Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/hugo-hextra-landing-starter.git
   cd hugo-hextra-landing-starter
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```
3. **Run the development server:**
   ```sh
   hugo server
   ```

### Building for Production
```sh
hugo --minify
```

## TailwindCSS Integration
This project uses Hugo’s built-in [css.TailwindCSS](https://gohugo.io/functions/css/tailwindcss/) function to process TailwindCSS. The configuration is managed in `hugo.yaml` and the main CSS entry is at `assets/css/main.css`:

```css
@import "tailwindcss";
@source "hugo_stats.json";
```

The partial template at `layouts/partials/css.html` ensures TailwindCSS is processed and included efficiently for both development and production.

## Alpine.js Usage
Alpine.js is included as a dependency (see `package.json`) and can be used to add interactivity to your components. Refer to [Alpine.js documentation](https://alpinejs.dev/start-here) for usage examples.

## Customization
- Edit `layouts/index.html` and other layout files to customize your landing page and docs.
- Modify TailwindCSS styles in `assets/css/main.css`.
- Adjust Hugo configuration in `hugo.yaml` as needed.

## References
- [Hugo Documentation](https://gohugo.io/documentation/)
- [TailwindCSS Hugo Integration](https://gohugo.io/functions/css/tailwindcss/)
- [Alpine.js Documentation](https://alpinejs.dev/)

## License
MIT