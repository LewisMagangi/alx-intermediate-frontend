# ALX Intermediate Frontend

This repository contains projects and exercises for the ALX Intermediate Frontend curriculum, focusing on advanced HTML, CSS, and modern web development practices including CSS preprocessors.

## Projects Overview

This repository contains three main projects that progressively build frontend development skills:

### 0x00-semantic_html - Semantic HTML: Best Practices for Accessibility and SEO

A foundation project focusing on semantic HTML structure, accessibility, and SEO optimization.

**Key Topics:**

- Semantic HTML elements (`<header>`, `<main>`, `<article>`, `<section>`, `<footer>`)
- SEO optimization with meta tags
- ARIA roles and accessibility features
- Form design best practices

**Files:**

```text
0x00-semantic_html/
├── 0-index.html    # Basic semantic HTML structure
├── 1-index.html    # Enhanced with meta tags for SEO
├── 2-index.html    # Complete blog post layout
└── 3-index.html    # Form accessibility with ARIA roles
```

### 0x02-tailwind-css - Tailwind CSS Framework

Exploration of utility-first CSS framework for rapid UI development.

**Key Topics:**

- Utility-first CSS approach
- Responsive design patterns
- Component-based styling
- Grid and Flexbox layouts

**Files:**

```text
0x02-tailwind-css/
├── package.json           # Node.js dependencies
├── tailwind.config.js     # Tailwind configuration
├── 1-index.html          # Basic Tailwind setup
├── 2-index.html          # Typography and layout
├── 3-nav_index.html      # Navigation components
├── 4-flexbox_index.html  # Flexbox layouts
├── 5-gridflex_index.html # Grid and Flex combinations
├── 6-imageGallery.html   # Image gallery with Tailwind
└── src/
    ├── input.css         # Source CSS file
    └── output.css        # Compiled CSS output
```

### 0x03-sass_scss - CSS Preprocessors: SASS/SCSS for Efficient Styling

Introduction to SASS/SCSS preprocessor for maintainable and efficient CSS development.

**Key Topics:**

- CSS preprocessor concepts and advantages
- Variables for consistent theming
- Nesting for organized code structure
- Mixins for reusable style patterns
- SASS compilation workflow

**Files:**

```text
0x03-sass_scss/
├── 0-installation-script   # SASS installation guide
├── 0-debug_log.scss       # Debug output demonstration
├── 1-color_variable.scss   # Variables usage
├── 2-nested_tag.scss      # Nesting demonstration
├── 3-mixin_margins.scss   # Mixins for reusable styles
└── README.md              # Detailed project documentation
```

## Quick Start Guide

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor or IDE (VS Code recommended)
- Node.js (v20.16.0 for SASS projects)
- Basic understanding of HTML and CSS

### Installation Steps

1. Clone this repository:

   ```bash
   git clone <repository-url>
   cd alx-intermediate-frontend
   ```

2. For Tailwind CSS projects:

   ```bash
   cd 0x02-tailwind-css
   npm install
   npm run build
   ```

3. For SASS/SCSS projects:

   ```bash
   cd 0x03-sass_scss
   npm install -g sass@3.7.4
   ```

### Running the Projects

- **HTML Projects**: Open `.html` files directly in a web browser
- **Tailwind Projects**: Run `npm run build` to compile CSS, then open HTML files
- **SASS Projects**: Compile with `sass input.scss output.css` before viewing

## Technology Stack

- **HTML5**: Semantic markup and accessibility features
- **CSS3**: Modern styling and layout techniques
- **Tailwind CSS**: Utility-first CSS framework
- **SASS/SCSS**: CSS preprocessor with advanced features
- **Node.js**: Development environment and package management
- **npm**: Package manager for dependencies

## Project Status

- **0x00-semantic_html**: Foundation HTML and accessibility ✅
- **0x02-tailwind-css**: Modern CSS framework implementation ✅
- **0x03-sass_scss**: CSS preprocessor mastery (Current - Sep 8-15, 2025) 🚧

## Real-World Applications

These projects prepare students for professional web development by covering:

- **Semantic HTML**: Essential for SEO, accessibility, and maintainable code
- **Tailwind CSS**: Rapid prototyping and consistent design systems
- **SASS/SCSS**: Large-scale CSS management in enterprise applications

## Browser Support

All projects are designed to work with:

- Modern web browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers
- Screen readers and assistive technologies

## Contributing Guidelines

This repository is part of the ALX curriculum. Each project follows specific requirements and guidelines. Please refer to individual project READMEs for detailed instructions.

## Repository Author

ALX Student - Intermediate Frontend Development Program

## Educational License

This project is part of the ALX curriculum and follows educational use guidelines.
