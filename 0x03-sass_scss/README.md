# 0x03-sass_scss

## Project Overview

This directory contains a practical introduction to SASS/SCSS, a powerful CSS preprocessor. The project covers foundational concepts of SASS, from installation and setup to using variables, nesting, and mixins.

## Learning Objectives

- Install and configure the SASS compiler in a development environment
- Understand the core philosophy of a CSS preprocessor and its advantages over vanilla CSS
- Write and compile SASS (.scss) files into standard CSS
- Apply core SASS features to solve common styling problems:
  - Use variables to store and reuse values (colors, fonts, sizes)
  - Structure CSS rules using nesting to mirror HTML hierarchy
  - Create reusable code blocks with mixins for consistent styles

## Files Description

### 0-installation-script

Contains step-by-step instructions for installing SASS on different operating systems, including Node.js setup and npm installation commands.

### 0-debug_log.scss

A simple SASS file that demonstrates the `@debug` directive by printing "Hello world" to the debug output when compiled.

### 1-color_variable.scss

Demonstrates SASS variables by defining a color variable and applying it to both `body` and `p` HTML tags. Shows how variables promote consistency and make global changes easy.

### 2-nested_tag.scss

Showcases SASS nesting functionality by setting margin and padding for the body tag, and nested margin for paragraph tags inside the body. This mirrors HTML hierarchy and reduces repetitive selector writing.

### 3-mixin_margins.scss

Illustrates the power of SASS mixins by creating a reusable mixin for setting left and right margins. The mixin is then applied to both `body` and `div` tags with different values.

## Key SASS/SCSS Concepts Covered

### Variables

```scss
$variable-name: value;
```

Store and reuse values throughout your stylesheet for consistency and easy maintenance.

### Nesting

```scss
.parent {
  property: value;
  
  .child {
    property: value;
  }
}
```

Write CSS rules inside other rules to match HTML structure visually.

### Mixins

```scss
@mixin mixin-name($parameter) {
  property: $parameter;
}

.selector {
  @include mixin-name(value);
}
```

Create reusable blocks of styles that can accept parameters for flexibility.

## Compilation

To compile SASS files to CSS, use:

```bash
sass input.scss output.css
```

For the debug output:

```bash
sass 0-debug_log.scss | head -n 0
```

## Requirements

- Node.js (v20.16.0 recommended)
- SASS compiler (v3.7.4)
- Basic understanding of CSS

## Real-World Applications

SASS/SCSS is widely used in professional web development for:

- Creating and enforcing design systems
- Managing large codebases with better organization
- Increasing development speed through reusable components
- Improving maintainability with centralized variable management

## Author

This project is part of the ALX Intermediate Frontend curriculum, focusing on CSS preprocessors and efficient styling techniques.
