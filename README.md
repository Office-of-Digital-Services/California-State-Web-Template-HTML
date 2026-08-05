# California-State-Web-Template-HTML

The California State Web Template is an HTML template and website standard offered by the California Department of Technology to state agencies and departments within the State of California and beyond.

This repository is the plain HTML/CSS/JS version focused on:

- static pages
- reusable UI component examples
- sample implementations with no framework requirement

If you need build tooling or framework-specific integration, use one of the framework repositories listed below.

## About This Repository

This project is designed for teams who want to:

- ship static sites or CMS-driven pages
- prototype quickly with copy/paste-ready examples
- work directly in HTML, CSS, and JavaScript

You can open and edit files directly in any code editor and run pages locally in a browser.

## Quick Start

1. Clone or download this repository.
2. Open the repository folder in your editor.
3. Start a local static server from the project root.

## Project Structure

Key folders and files:

- `index.html` and other root `.html` files: main page templates and content pages.
- `samples/`: focused examples for individual components and patterns.
- `independent-components/`: standalone component implementations.
- `ca_state_template/css/`: template stylesheets.
- `ca_state_template/js/`: template JavaScript.
- `ca_state_template/fonts/`: template font assets.
- `images/`: shared image assets used by templates and samples.

## Working With HTML/CSS/JS

### 1. Start from a template page

Use one of the root template files (for example, `template-card.html` or `template-site-footer.html`) as your base page.

### 2. Reuse sample markup

Copy structure and classes from pages in `samples/` when adding components such as:

- buttons
- cards
- banners
- forms
- navigation

### 3. Include template assets

Reference CSS and JS from `ca_state_template/` so components render and behave correctly.

### 4. Keep customization layered

Prefer adding your own site-specific stylesheet after template styles, and add custom JavaScript separately from template JS files.

CDN option for template assets:

- https://template.webstandards.ca.gov/cdn.html

State Web Template NPM package:

- https://template.webstandards.ca.gov/get-started/npm.html

## Available State Web Template Frameworks

- [California-State-Web-Template-react](https://github.com/Office-of-Digital-Services/California-State-Web-Template-react)
- [California-State-Template-NET-Core-MVC](https://github.com/Office-of-Digital-Services/California-State-Web-Template-NET-Core-MVC)
- [California-State-Web-Template-eleventy](https://github.com/Office-of-Digital-Services/California-State-Web-Template-eleventy)

## Publishing Notes

Before publishing:

- verify page titles and metadata
- confirm keyboard and screen-reader accessibility behavior
- check all links, navigation, and form interactions
- validate that your custom CSS does not break template component states

## License

Use and distribution should follow the California State Web Template licensing and policy guidance from the California Department of Technology and the Office of Digital Services.
