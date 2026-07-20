# Webpack Template

A simple Webpack starter template for building frontend projects quickly. It includes a basic development and production setup with HTML, CSS, and JavaScript support.

## Features
- Webpack configuration for development and production builds
- HTML template support via HtmlWebpackPlugin
- CSS loading with style-loader and css-loader
- Asset handling for images and other static files
- Ready for a small JavaScript project structure

## Prerequisites
Make sure you have the following installed:
- Node.js
- npm

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/LeejanAlipio/webpack-template.git
```

2. Navigate into the project folder:
```bash
cd webpack-template
```

3. Install dependencies:
```bash
npm install
```

4. Start the development server:
```bash
npm run dev
```

5. Build for production:
```bash
npm run build
```

## Project Structure
```text
webpack-template/
├── src/
│   ├── index.html
│   └── index.js
├── webpack.common.js
├── webpack.dev.js
├── webpack.prod.js
├── package.json
└── README.md
```

## Notes
This template is a good starting point for small projects and can be expanded as needed for more advanced front-end builds.
