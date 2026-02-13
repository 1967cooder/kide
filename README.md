## Kide – WordPress Practice Project

Local development URL: http://kide.local/
Kide is a WordPress practice project developed to demonstrate practical knowledge of modern WordPress (Full Site Editing) and custom Gutenberg block development using React. The project combines an existing block-based theme (Fleks) with a custom-built React Hero Block to create a structured, responsive front page.

## 🚀 Live (Local Development)

This project runs locally using WordPress:

http://kide.local/

## Screenshots

![Homepage](images/kide.desktop.png)
![Mobile](images/kide.mobile.png)

– Hero section (showing the React Hero Block)

- Site Editor – Front Page layout
- Gutenberg Editor – Custom Hero Block settings panel

## Example structure:

/screenshots
├── home-hero.png
├── site-editor-front-page.png
└── hero-block-editor.png
Example usage:

## Project Goals

This project was created to:

- Practice working with WordPress Full Site Editing (FSE)
- Understand block-based theme architecture
- Customize and extend an existing block theme
- Learn how to create custom Gutenberg blocks using React
- Practice CSS layout techniques for complex hero sections
- Work in a local WordPress development environment

## Theme & Architecture

Base theme: Fleks (Block Theme)
The project uses WordPress Full Site Editing, which means:

- Layouts are defined using HTML templates instead of PHP templates
- Page structure is composed of blocks
- Global styles (colors, typography, spacing) are managed via theme.json
  Used WordPress features:
- Templates (templates/\*.html)
- Template Parts (parts/\*.html)
- Block Patterns (patterns/\*.php)
- Global Styles (theme.json)

## Custom React Hero Block

In addition to core WordPress blocks, the project includes a custom Gutenberg Hero Block built with React.

### Purpose of the Custom Block

The custom Hero Block was built to:

- Go beyond the limitations of core blocks
- Practice React-based block development
- Handle foreground and background images dynamically
- Create layered visuals (image on top of dark green background)
  Technical Highlights
- Built using @wordpress/scripts
- React-based edit and save functions
- Uses MediaUpload and InspectorControls
- Outputs clean, semantic HTML
- Layout and layering handled entirely with CSS

## Styling & Layout

The Hero section design focuses on:

- Dark green background defined via theme colors
- Foreground image positioned using position: absolute
- SVG logos arranged with CSS Grid
- Responsive behavior implemented using CSS only
  This separation keeps JavaScript logic minimal and styling flexible.

## Project Structure (Key Files)

wp-content/
└── themes/
└── fleks/
├── assets/
│ ├── css/
│ └── img/
├── parts/
│ ├── header.html
│ └── footer.html
├── patterns/
│ └── front-page-1.php
├── templates/
│ └── front-page.html
├── react-build/
│ ├── index.js
│ └── index.css
├── functions.php
├── theme.json
├── style.css
└── screenshot.jpg

## Development Environment

- WordPress 6.x
- PHP 8.x
- MySQL
- LocalWP (or similar local environment)
- Node.js & npm
- Gutenberg Block Editor

# How to Use

1. Copy the theme to:
   wp-content/themes/fleks/
1. Activate the theme:
   Dashboard → Appearance → Themes → Fleks
1. Open the Site Editor:
   Appearance → Editor
1. Edit the Front Page and configure the custom Hero Block

## 📚 What I Learned

- How block themes differ from classic WordPress themes

- How Full Site Editing works internally

- How Gutenberg blocks are built with React

- How to connect React builds to WordPress

- How to debug editor vs frontend rendering

- How to structure complex hero sections cleanly

## Future Improvements

- Add more custom Gutenberg blocks
- Improve mobile layout for hero section
- Create block variations
- Optimize React build loading

## Author

Silvana Lindholm

- GitHub: [@1967cooder](https://github.com/1967cooder)
- GitHub:[Kide] (https://github.com/1967cooder/kide)

- LinkedIn: https://www.linkedin.com/in/silvanalindholm
- Email: silvanalindholm@hotmail.com
- Portfolio: [Live Demo](https://portfoliosilvana.netlify.app/)

This project is intended for learning and portfolio demonstration purposes.
