YALADANDI DILIP KUMAR | Frontend Developer Portfolio
##Output Video It is uploaded in the given file

 Project Description: SPA Portfolio
This is the official portfolio website for Yaladandi Dilip Kumar, an Aspiring Web Developer. The site is designed as a Single-Page Application (SPA), built with Vanilla JavaScript, HTML5, and modern CSS, ensuring a fast, smooth, and modern user experience without full page reloads.

The design is based on a dark-themed, professional aesthetic with a focus on readability, color accents, and full responsiveness across all devices.

 Key Features
Single-Page Application (SPA): Uses Vanilla JavaScript for client-side routing, enabling instant panel switching between Home, About, Skills, Projects, and Contact without refreshing the browser.
Modern Design: Implements a dark mode theme with vibrant blue/purple gradient accents, inspired by contemporary developer portfolio designs.
Fully Responsive: Built with Flexbox and Media Queries to ensure a seamless layout on desktops, tablets, and mobile phones.
Dynamic Content Integration: All personal, educational, and project data is managed via a central JavaScript object, making updates quick and centralized.
Professional Sections: Includes dedicated panels for:
Home/Hero: Introduction, CTA buttons, and social links.
About: Detailed Objective, Education, and Certifications.
Skills: Categorized list of technical proficiencies (JAVA, HTML, CSS, JAVASCRIPT, WebSockets, Git).
Projects: Detailed cards for key projects like the Real-Time Chat App and Amazon/Myntra clones, with direct GitHub links.
Contact: Direct links to email, LinkedIn, and phone.
 What I Learned (Code & Concepts)
Developing this SPA portfolio was a great opportunity to reinforce advanced vanilla JavaScript and CSS techniques. The key learning points were:

Vanilla SPA Routing: Implemented routing by intercepting click events (e.preventDefault()), using the History API (history.pushState()) to update the URL without a page reload, and dynamically rendering the correct HTML content based on the URL path.
Modular JavaScript: Structured the code using dedicated functions (getHomeView, getProjectsView, etc.) and a single resumeData object to maintain a clean separation of data and view logic, promoting maintainability and readability.
Advanced CSS Styling: Mastered techniques for:
Creating Gradient Text using background-clip: text and -webkit-text-fill-color: transparent.
Implementing smooth, dark-mode color schemes using CSS Variables (:root).
Designing the circular profile image mask and subtle glow effect (using box-shadow) as seen in the mockup.
Responsive Layouts: Ensured the two-column hero section correctly collapses into a single-column layout on mobile devices using Flexbox and well-defined @media queries.
Project Data Management: Practiced mapping complex data structures (like the projects array) to HTML elements using JavaScript's .map() and .join('') methods for efficient dynamic content generation.
 Technology Stack
HTML5
CSS3
Vanilla JavaScript
Font Awesome (for social icons)
Google Fonts (Poppins)
 Getting Started (Run Locally)
To get a copy of this project up and running on your local machine for development and testing:


Deployment: The project is static and can be hosted easily on platforms like GitHub Pages or Netlify.
