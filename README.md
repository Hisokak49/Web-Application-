# BMX Cycle Configurator

A lightweight, CSS-driven BMX bicycle configurator built with plain HTML and CSS. The page lets visitors open the configurator, switch between wheel options, preview the bicycle, and simulate adding the configured bike to a cart.

## Features

- Responsive viewport setup for desktop and mobile screens
- Interactive wheel selection using native radio controls
- CSS-based BMX bicycle illustration
- Cart interaction with a displayed price of Rs6999
- Font Awesome icons and a small set of CDN-hosted styling dependencies
- Semantic and accessible labels for the interactive controls and bicycle preview

## Project structure

```text
.
├── index.html   # Configurator markup and controls
├── style.css    # Layout, bicycle illustration, and interactions
└── README.md    # Project documentation
```

## Run locally

No build step or package manager is required.

1. Clone the repository.
2. Open `index.html` directly in a browser, or serve the folder with a simple static server.

For example, with Python:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## External dependencies

The page loads Roboto from Google Fonts and Normalize CSS and Font Awesome from cdnjs. An internet connection is therefore required for those external assets to load when running the page locally.

## Contributing

Keep changes focused and preserve the existing CSS-driven interaction model. When changing controls or interactive states, verify the page with keyboard navigation and a responsive viewport before opening a pull request.

## License

No license is currently declared for this repository. If you intend to reuse or redistribute the project, contact the repository owner before doing so.
