# 🧭 SportsVoyager

**SportsVoyager** is a modular, editorial-style travel guide tailored for sports enthusiasts seeking immersive match weekend experiences. Built with semantic HTML5 and scalable CSS3, the site delivers a visually striking and responsive user experience that’s ready for commercial deployment and affiliate integration.

This project was developed as part of **Project 1 for Code Institute’s Full Stack Software Development Diploma**. It demonstrates core front-end development skills while laying the foundation for a commercially viable product. The codebase is structured to meet professional standards and is open to future expansion.

---

## 📌 Overview

SportsVoyager blends clean structure, bold design, and practical scalability to showcase iconic sports trips across Europe. Each page is crafted to highlight city-specific match weekends, with a layout optimized for storytelling, conversion, and future growth.

---

## 🧠 User experience (UX)


SportsVoyager was designed to deliver an emotionally engaging and intuitive experience for football fans planning match weekend escapes. The layout, content, and navigation were shaped for user goals, ensuring the site feels both editorial and practical for the UX to be as easy as possible to navigate.

🔍 User Stories

🧭 First-Time Visitor Goals

a. As a first-time visitor, I want to instantly understand the purpose of the site so I can decide whether to explore further.

b. As a first-time visitor, I want to easily navigate the homepage and trip listings to find destinations that interest me.

c. As a first-time visitor, I want to read testimonials and check social media links to gauge trust and community presence.

🔁 Returning Visitor Goals

a. As a returning visitor, I want to quickly find new trip additions or updated match previews.

b. As a returning visitor, I want to locate the contact form to ask questions or suggest destinations.

c. As a returning visitor, I want to explore community features like fan reviews or curated travel tips.

🔄 Frequent User Goals

a. As a frequent user, I want to check for newly added cities or matchday packages.

b. As a frequent user, I want to explore deeper editorial content like fan testimonials and travel tips to enrich my experience.

c. As a frequent user, I want to use the site as a planning tool for future trips, comparing cities and match schedules.

---

## 🎨 Design


The design of SportsVoyager was crafted to evoke editorial warmth, trust, and fan-first energy. Every visual choice—from typography to imagery—was made to support clarity, emotional impact, and responsive usability.

🎨 Colour Scheme

The site uses a warm, editorial palette designed to balance energy with readability:

Primary: Deep navy and warm gold tones for contrast and trust

Accent: Soft greys and whites to support content hierarchy

Call-to-Action: Bold reds and vibrant yellows to guide user interaction

These colors were chosen to reflect the excitement of matchday travel while maintaining professional polish.

✍️ Typography

Primary Font: Montserrat — a clean, modern sans-serif used throughout for headings and body text

Fallback: Sans-serif — ensures consistency across browsers

Montserrat was selected for its editorial clarity and emotional neutrality, supporting both storytelling and structure.

🖼️ Imagery

Imagery plays a central role in creating an immersive experience:

Hero Image: A full-width background photo sets the tone for matchday excitement

Trip Cards: Destination-specific images highlight iconic stadiums and fan culture

Testimonials: Real-person video paired with quotes build trust and emotional resonance

All images were curated to support editorial storytelling and visual rhythm.

🧮 Wireframes

Wireframes were created to guide layout decisions and ensure responsive clarity they all follow the same pattern of design:

Home Page Wireframe – Featured trips, hero section, and navigation

Mobile Wireframe – Optimized layout for small screens

Destinations Wireframe - Featured all trips and Destinations

Info Wireframe - How it works, What's included, FAQS, Fan experience Video, Testimonials from Fan

Contact Page Wireframe – Form structure, social icons, and footer layout

These wireframes informed the modular structure and helped maintain grading-safe hierarchy across devices.

## 🧱 Project Structure

sports-voyager/
├── index.html               # Homepage with hero section and highlight featured trips
├── trips.html               # Modular layout for destination listings
├── info.html                # All info and Q&A 
├── contact.html             # Dedicated contact form page
├── README.md                # Project documentation

├── assets/
│   ├── css/
│   │   ├── base.css         # Base and global styles
│   │   ├── buttons.css      # CTA and link button styling
│   │   ├── components.css   # Modular blocks and reusable UI elements
│   │   ├── featured.css     # Styling for featured trip cards
│   │   ├── info-card.css    # Layout for About/Contact info blocks
│   │   ├── layout.css       # Grid and responsive structure
│   │   ├── navigation.css   # Header and nav bar styling
│   │   ├── responsive.css   # Responsive layout tuning for mobile and desktop
│   │   ├── typography.css   # Font styles and text hierarchy
│   │   └── variables.css    # CSS custom properties for color and spacing

│   ├── icons/
│   │   ├── facebook.svg     # Footer social icon
│   │   ├── instagram.svg    # Footer social icon
│   │   └── twitter.svg      # Footer social icon

│   └── images/
│       ├── Barcelona-1.jpg  # Destination imagery
│       ├── barcelona-2.jpg  # Destination imagery
│       ├── dortmund-1.jpg   # Destination imagery
│       ├── dortmund-fan.jpg # Editorial testimonial image
│       ├── hero-bg.jpg      # Homepage hero background
│       └── logo-card.jpg    # Branding asset






Each HTML file uses semantic tags (`<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`) to ensure accessibility, SEO optimization, and clean content hierarchy.

---

## ✨ Features

- ✅ Semantic HTML5 for accessibility and SEO
- ✅ Modular CSS with responsive layout
- ✅ Editorial hero section and trip cards
- ✅ Unified navigation bar across all pages
- ✅ Real-person testimonials with emotional tone
- ✅ Social media icons with hover transitions

---

## 🧪 Testing

### ✅ Validation
- All pages passed W3C HTML and CSS validation
- No critical errors flagged

### ✅ User Stories
- First-time visitors can understand site purpose instantly
- Navigation is readable and intuitive
- CTA buttons are functional and accessible
- Contact form tested for validation and confirmation

### ✅ Browser Testing

| Device        | Chrome | Safari | Firefox | Edge |
|---------------|--------|--------|---------|------|
| Windows Laptop| ✅     | N/A    | ✅      | ✅   |
| MacBook       | ✅     | ✅     | ✅      | ✅   |
| iPhone        | ✅     | ✅     | ✅      | ✅   |
| Android Phone | ✅     | N/A    | ✅      | ✅   |
| iPad          | ✅     | ✅     | ✅      | ✅   |

### ✅ Audit Scores (Chrome DevTools)
- Performance: 93  
- Accessibility: 100  
- Best Practices: 92

---

## 🐞 Known Bugs

- Hero image may overflow on some mobile screens  
- Footer text alignment varies across devices

---

## 🚀 Deployment

This site is designed to be deployed as a static project using GitHub Pages.

### To deploy:
1. Push the repository to GitHub  
2. Navigate to **Settings** → **Pages**  
3. Under **Source**, select `main` branch and `/root`  
4. Save and wait for the site to publish  

Your site will be live at:  
`https://Pierre-Louis789.github.io/sports-voyager/`

---

## 🧭 Roadmap

Planned future enhancements include:

- ➕ Additional trip detail pages for other European cities  
- 🔗 Integration of affiliate links for ticketing and accommodation  
- 📝 Fan review sections with moderated submissions  
- 📸 Image galleries and dynamic content zones  
- 🌍 Multi-language support for international audiences

---

## 📜 Credits

### Code
- Bootstrap Grid System  
- StackOverflow (hero image logic)  
- MDN Web Docs (form validation patterns)

### Content
- All written by developer  
- Color psychology reference: [source](#)

### Media
- All images created by developer

### Acknowledgements
- Thanks to Code Institute and Level 5 Web Application Development cohort

---

## 📬 Contact

For collaboration, feedback, or commercial inquiries:  
📧 sicot.pierrelouis@gmail.com  
Or open an issue via [GitHub](https://github.com/Pierre-Louis789/sports-voyager)

---

## 🧠 Author

Created by [Pierre-Louis789](https://github.com/Pierre-Louis789)  
Focused on modular architecture, editorial UX, and scalable front-end development.
