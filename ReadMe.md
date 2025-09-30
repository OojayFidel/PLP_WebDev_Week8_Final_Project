**Project Documentation:** Jonathan Odey's Personal Portfolio Website
**Author:** Jonathan Odey
**Date:** September 22, 2025
**Live Site URL:** https://oojayfidel.github.io/My-website/

## 1. Project Overview
This project is a multi-page personal portfolio website designed to showcase my unique professional identity, blending skills in Social Media Management with a growing expertise in Backend and AI Engineering. The primary goal is to provide a clean, professional, and user-friendly platform for potential employers and collaborators to understand my capabilities, review my work, and get in touch.

The website is built as a static site using foundational web technologies, emphasizing clean code, accessibility, and a clear user journey.

## 2. Tech Stack
The project was developed using a stack focused on simplicity, performance, and maintainability:

**HTML5:** For the core structure and content of the website, using semantic markup for better accessibility and SEO.

**CSS3:** For all styling, layout, and responsiveness. The stylesheet utilizes CSS Custom Variables (:root) for a maintainable and consistent design system (colors, fonts, spacing).

**Vanilla JavaScript (ES6+):** For all client-side interactivity. No external frameworks or libraries were used, demonstrating proficiency with core JavaScript principles.

**GitHub Pages:** For hosting and deployment, enabling a straightforward continuous deployment workflow directly from the project repository.

## 3. Key Features
The website incorporates several key features to create a comprehensive and interactive user experience:

**Multi-Page Architecture:** The site is logically organized into four main sections to guide the user through my professional story:

**Home:** A landing page with a clear value proposition and links to other key sections.

**Bio:** An "About Me" page detailing my professional journey, skills, and experience via a timeline.

**Portfolio:** A gallery of my projects, demonstrating practical application of my skills.

**Elevator Pitch:** A dedicated page to present a concise summary of my professional value (with a placeholder for a future video).

**Interactive Portfolio with Filtering:** The portfolio page features a dynamic filtering system that allows users to categorize projects (e.g., "Tech," "Social Media"). This is powered by Vanilla JavaScript to manipulate the DOM based on user selection.

**Project Detail Modals:** Each featured project can be explored in more detail through an accessible modal window. The modals provide key information such as the project's purpose, the challenges faced, the solutions implemented, and the technologies used.

**Accessibility (a11y) Focused:** Significant attention was paid to making the website accessible:

**Skip to Main Content Link:** For users navigating via keyboard.

**Semantic HTML:** Proper use of 
```
<header>, <footer>, <main>, <nav>, and <section> tags

```

**ARIA Attributes:** Correct implementation of role, aria-modal, and aria-label for dynamic components like modals, ensuring they are usable with screen readers.

**Responsive Design:** The layout is fully responsive and was designed with a mobile-first approach, ensuring a seamless experience on all devices from small phones to desktop monitors.

**UI/UX Enhancements:**

**Back-to-Top Button:** Appears on scroll to improve navigation on longer pages.

**Toast Notifications:** Non-intrusive feedback for form submissions.

**Consistent Navigation:** A sticky header ensures that the main navigation is always accessible.

## 4. Project Structure
The project files are organized in a logical and intuitive manner:

```text
.
├── index.html        # Home page
├── bio.html          # Bio/About Me page
├── portfolio.html    # Portfolio page
├── elevator-pitch.html # Elevator Pitch page
├── assets/
│   ├── css/
│   │   └── styles.css  # Main stylesheet
│   ├── js/
│   │   └── main.js   # Main JavaScript file
│   └── img/          # Project images, logos, etc.
└── docs/
    └── resume.pdf    # CV/Résumé file

```

## 5. Deployment
The website is automatically deployed and hosted via GitHub Pages. Any push to the main branch of the GitHub repository triggers a new deployment, making updates efficient and simple.

The live version can be accessed at: https://oojayfidel.github.io/My-website/

## 6. Future Improvements
While the current version is a robust static site, several improvements could be made in the future, particularly to align with my focus on backend development:

Refactor with a Backend Framework: To eliminate code repetition (e.g., the header and footer are duplicated on each page), the site could be rebuilt using a Python framework like Flask or Django. This would allow for a templating system (like Jinja2) to manage shared components, adhering to the Don't Repeat Yourself (DRY) principle.

Headless CMS Integration: The project data currently resides in the HTML. It could be migrated to a headless CMS (like Strapi or Sanity.io) and fetched via an API. This would make it easier to add or update projects without touching the source code.