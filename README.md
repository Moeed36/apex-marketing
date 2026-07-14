# Apex Marketing Agency Website

A modern, responsive marketing agency website for an HCI course project, inspired by Disruptive Advertising.

## Live Demo

🔗 [View Live Site](https://apex-marketing-drab.vercel.app/)

## About This Project

This project was developed as part of the Human-Computer Interaction (HCI) course. The goal was to study an existing professional website, analyze its design patterns and user experience, and recreate a similar site from scratch. An AI coding assistant (Opencode) was used as a development tool to speed up repetitive tasks, while all design decisions, content strategy, and final edits were done by me.

## My Role & AI Assistance

| Task | Done By |
|------|---------|
| Research and analyze reference website | Me |
| Plan site structure and sections | Me |
| Choose color scheme and typography | Me |
| Write initial HTML skeleton | AI assisted |
| Style components with CSS | Me + AI assisted |
| Add JavaScript interactivity | Me + AI assisted |
| Create responsive layouts | Me |
| Write documentation | AI assisted |
| Deploy to GitHub & Vercel | Me |

## Tools Used

### AI Coding Tool
- **Opencode CLI** - Used as a coding assistant for generating boilerplate code and debugging

### Technologies
- **HTML5** - Semantic markup structure
- **CSS3** - Custom styling with CSS variables, animations, and responsive design
- **JavaScript (ES6+)** - Interactive features and animations
- **Google Fonts** - Inter font family for modern typography

### Deployment
- **GitHub** - Version control and code hosting
- **Vercel** - Static site hosting and deployment

## How It Was Built

### Step 1: Research & Planning
- Analyzed the reference website (disruptiveadvertising.com)
- Studied its layout, sections, color palette, and user flow
- Identified key sections to include: hero, client logos, stats, services, testimonials, and contact form
- Planned the information architecture and decided on a clean, professional design

### Step 2: Design Decisions
- **Color Scheme**: Chose a red gradient (#e63946 to #ff6b6b) as the primary accent with dark navy (#1d3557) for contrast
- **Typography**: Selected Inter font for a clean, modern look
- **Layout**: Used CSS Grid and Flexbox for responsive page layouts
- **Animations**: Added subtle hover effects and scroll-triggered animations for better engagement

### Step 3: Development Process

1. **HTML Structure** (`index.html`)
   - Built the full page layout with semantic HTML5 elements
   - Organized sections: navigation, hero banner, client logos, statistics, services, timeline, about, testimonials, contact form, and footer
   - Ensured accessibility with proper heading hierarchy and alt attributes

2. **CSS Styling** (`styles.css`)
   - Defined CSS custom properties for consistent colors and spacing
   - Created responsive breakpoints for mobile, tablet, and desktop
   - Added gradient effects, card hover animations, and smooth transitions
   - Styled form elements and interactive components

3. **JavaScript Interactions** (`script.js`)
   - Implemented mobile hamburger menu toggle
   - Added smooth scrolling for anchor links
   - Created animated counters for the statistics section
   - Used Intersection Observer for fade-in animations on scroll
   - Built form submission handling with success feedback
   - Added parallax effects on the hero background shapes

### Step 4: Testing & Optimization
- Tested on Chrome, Firefox, and Edge browsers
- Verified responsive behavior on different screen sizes
- Checked performance and kept animations lightweight
- Validated HTML structure

### Step 5: Deployment
- Initialized a local Git repository
- Created a GitHub repository and pushed all code
- Connected the repository to Vercel for automatic deployment

## Features

- Fully responsive design (mobile, tablet, desktop)
- Smooth scroll animations and hover effects
- Interactive navigation with mobile menu
- Animated statistics counters
- Client logo carousel
- Contact form with validation and success feedback
- Modern gradient accents and card-based layouts
- Fast loading times with no external dependencies

## Project Structure

```
apex-marketing/
├── index.html      # Main HTML file with page structure
├── styles.css      # All custom CSS styles and responsive design
├── script.js       # JavaScript for interactivity and animations
└── README.md       # Project documentation
```

## Key Sections Explained

### Hero Section
- Bold headline with gradient text highlight
- Call-to-action button with hover animation
- Animated floating background shapes for visual depth
- Trust indicators with star rating

### Services Grid
- Six service cards in a responsive grid layout
- Custom SVG icons for each service
- Hover effects with top-border reveal animation

### Statistics Section
- Counter animations triggered on scroll
- Dark background for visual contrast
- Gradient text for numerical values

### Contact Form
- Clean two-column layout
- Input validation on required fields
- Success message animation on submission

## Challenges & Solutions

1. **Responsive Design**: Used CSS media queries and Flexbox/Grid to ensure the site looks good on all devices
2. **Animations Performance**: Kept CSS transitions lightweight and used `requestAnimationFrame` for JS counters
3. **Form Handling**: Built client-side validation without any external libraries
4. **Cross-browser Compatibility**: Tested and adjusted vendor prefixes where needed

## What I Learned

- How to analyze and deconstruct professional website designs
- The importance of semantic HTML for accessibility
- CSS custom properties make theming much easier
- Intersection Observer API is powerful for scroll-based animations
- AI tools speed up development but require human oversight for quality

## Future Improvements

- Add multiple pages (About, Services, Blog)
- Implement a backend for form submissions
- Add more interactive elements like a portfolio gallery
- Integrate analytics to track user behavior

## Credits

- Design inspiration: Disruptive Advertising (disruptiveadvertising.com)
- AI Assistant: Opencode CLI for code generation assistance
- Fonts: Google Fonts - Inter

---

**HCI Course Project** | Built with AI assistance + manual development

---

**Student:** Muhammad Moeed
**Roll No:** 23018020085
