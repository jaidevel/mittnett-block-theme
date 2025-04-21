# Mittnett Block Theme

**A WordPress Block Theme Starter Template for Modern Development.**

This repository is designed as a **GitHub Template**, allowing you to quickly create new, independent WordPress Block Themes with a clean, professional development workflow.

### Features

- WordPress 6.x+ **Block Theme** ready (no page builders needed)
- **Modern SCSS + JavaScript** build workflow
- **Autoprefixer** included for cross-browser CSS
- **Separate development and production builds**
- **Source maps** for development, clean minified files for production
- **Organized assets structure**: CSS, JS, fonts, images
- **BrowserSync live reloading** support
- **Colorful terminal output** for better developer experience
- Designed to be **extensible** and **future-proof**

### How to Use This Template

1. Click **Use this template** at the top of the repository.
2. Create a **new repository** based on this template.
3. Clone your new repository locally:
   ```bash
   git clone https://github.com/yourusername/your-new-repo-name.git
   cd your-new-repo-name
   ```

### Installation

Install the required dependencies:

```bash
npm install
```

### Development Workflow

#### Start watching SCSS and JS:

```bash
npm run start
```

#### Start with BrowserSync live reload:

```bash
npm run start:sync
```

#### Fresh dev build + start watchers:

```bash
npm run start:dev
```

### 🏗 Production Build

Create a minified, production-ready build:

```bash
npm run build
```

This outputs minified, optimized CSS and JS files inside the `assets/` directory.

### Folder Structure

```text
/assets
  /css
  /js
  /fonts
  /img
  /svg
/build-scripts
  build-css.js
  build-js.js
/src
  /scss
  /js
package.json
postcss.config.js
```

### License

This project is open-sourced under the GNU GENERAL PUBLIC LICENSE.

### Author

Built with ❤️ by Mittnett  
Based on professional WordPress development standards.

> **Note:** This project is licensed under the GNU GENERAL PUBLIC LICENSE.
