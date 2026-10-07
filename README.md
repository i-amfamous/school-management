# Premium Academy

![Premium Academy](image.png)

A responsive static school landing page for Premium Academy, built with plain HTML, CSS, and JavaScript. The site showcases the school's academic levels, facilities, testimonials, news, and an admissions enquiry form.

## Overview

This project is designed as a marketing and admissions website for a multi-level academic institution. It includes:

- A homepage highlighting the school and academic offerings
- Dedicated pages for Creche, Nursery, Primary, SHS, and University
- A modern, responsive layout for desktop and mobile devices
- A modal-based admissions enquiry form
- Styling and JavaScript interactions for navigation and UI behavior

## Project structure

- `index.html` — homepage
- `creche.html` — creche section
- `nursery.html` — nursery section
- `primary.html` — primary and JHS section
- `shs.html` — senior high school section
- `university.html` — university section
- `css/` — site stylesheets
- `js/` — front-end script logic
- `img/` — images and branding assets

## Local development

Because this is a static website, you can run it locally without a build step.

1. Open a terminal in the project folder.
2. Start a local web server:

```bash
python3 -m http.server 8000
```

3. Visit:

```text
http://localhost:8000
```

## Deployment

The site can be deployed as a static website on GitHub Pages, Netlify, Vercel, or any web hosting provider that serves HTML files.

## Notes

- The project uses a custom stylesheet system with shared styling in `css/global.css` and page-specific styling in the corresponding CSS files.
- The `js/script.js` file handles page interactions such as the menu and modal behavior.
- Images and school branding are stored in the `img/` folder.

## License

This project is provided for educational and demonstration purposes.
