# Jimmie Maggard's Resume Site

A modern, responsive, and print-friendly resume website built with [Astro](https://astro.build/) and Sass.

## 🚀 Project Overview

This project serves as the digital home for Jimmie Maggard's professional resume. It features a clean, professional design that is fully responsive for mobile devices and optimized for printing.

## 🛠 Tech Stack

- **Framework:** [Astro 5](https://astro.build/)
- **Styling:** [Sass (SCSS)](https://sass-lang.com/)
- **Icons:** [Font Awesome](https://fontawesome.com/)
- **Fonts:** [Google Fonts (Montserrat & Open Sans)](https://fonts.google.com/)
- **Deployment:** GitHub Actions & AWS S3

## 📦 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (latest LTS recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/akitafuki/my-resume-site.git
   cd my-resume-site
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Development

Start the development server:
```bash
npm run dev
```
The site will be available at `http://localhost:4321`.

### Build

To create a production build:
```bash
npm run build
```
The output will be in the `dist/` directory.

## 📁 Project Structure

- `src/pages/index.astro`: The main resume content and structure.
- `src/styles/mystyles.scss`: All custom styling, including variables, layout, and print optimizations.
- `astro.config.mjs`: Astro configuration.
- `public/`: (Optional) Static assets like images or favicon.

## 🚢 Deployment

The project is automatically deployed to an AWS S3 bucket via GitHub Actions whenever changes are pushed to the `main` branch. See `.github/workflows/workflow.yml` for details.

## 📄 License

This project is licensed under the [LICENSE](LICENSE) file.
