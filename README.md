# Cursor Clone - AI-Powered Code Editor Landing Page

A desktop-first, HTML and CSS recreation of the **Cursor** AI code editor landing page. This project focuses on visual accuracy, semantic structure, and design fidelity without any JavaScript, animations, or responsive design.

## Project Preview
![alt text](assets/Cursor-vlone-screenShot.png)


## 📋 Project Overview

This is a static website clone inspired by [Cursor.com](https://cursor.com), built purely with **HTML and CSS** to match the original design as closely as possible. The site demonstrates modern web design principles including dark mode UI, clean typography, and a professional layout optimized for desktop viewing.

---

## ✅ Sections Recreated

All 11 major sections from the assignment have been successfully implemented:

### 1. **Top Navigation Bar**
- Cursor logo (SVG wordmark)
- Navigation links: Features, Enterprise, Pricing, Resources
- CTA buttons: "Sign in" and "Download"
- Fixed position with dark background for persistent navigation

### 2. **Hero Section**
- Main headline: "Built to make you extraordinarily productive, Cursor is the best way to code with AI"
- Descriptive subtext highlighting AI capabilities
- "Download for Linux" CTA button with download icon
- Large hero product screenshot showcasing the IDE interface

### 3. **Trusted By / Company Logos**
- Grid layout displaying company logos (6 companies)
- Includes: Stripe, OpenAI, Linear, DataDog, NVIDIA, Figma, Ramp, Adobe
- Clean, centered spacing for professional appearance
- Subtitle: "Trusted every day by millions of professional developers"

### 4. **Feature Sections (3 blocks)**
- **Agent Section** – "Agent turns ideas into code" with feature description and CTA
- **Tab Autocomplete Section** – "Magically accurate autocomplete" with product screenshot
- **Ecosystem Section** – "Everywhere software gets built" with integration showcase
- Two-column layout (alternating text and image positions)
- Hover effects for interactivity

### 5. **Testimonials / Reviews Section**
- "The new way to build software" section header
- Grid of 6 testimonial cards from industry leaders:
  - **Diana Hu** (General Partner, Y Combinator)
  - **shadcn** (Creator of shadcn/ui)
  - **Andrej Karpathy** (CEO, Eureka Labs)
  - **Patrick Collison** (Co-Founder & CEO, Stripe)
  - **ThePrimeagen** (@ThePrimeagen)
  - **Greg Brockman** (President, OpenAI)
- Quote cards with author avatars, names, and roles
- Dark background cards with hover effects

### 6. **Feature Cards Section / Frontier**
- "Stay on the frontier" section header
- Grid of 3 feature cards with images:
  - **Access the best models** – Model selection and integration
  - **Complete codebase understanding** – Code analysis capabilities
  - **Develop enduring software** – Enterprise reliability and scale
- Each card includes description text, feature highlights, and product imagery
- Hover effects for visual feedback

### 7. **Changelog / Updates**
- "Changelog" section title
- Grid of 4 update cards with dates and version numbers:
  - Version 2.4 (Jan 22, 2026) – Subagents, Skills, and Image Generation
  - Jan 16, 2026 – CLI Agent Modes and Cloud Handoff
  - Jan 8, 2026 – New CLI Features and Improved Performance
  - Version 2.3 (Dec 22, 2025) – Layout Customization and Stability
- CTA link: "See what's new in Cursor"

### 8. **Team / About Section**
- "Cursor is an applied team focused on building the future of coding" headline
- "Join us" CTA button
- Large team photo with rounded corners
- Professional typography and spacing

### 9. **Recent Highlights Section**
- "Recent Highlights" section header with sticky positioning
- Grid of 3 highlight cards:
  - "Introducing Cursor 2.0 and Composer"
  - "Improving Cursor Tab with online RL"
  - "1.5x faster MoE training with custom MXFP8 kernels"
- Each card includes title, description, category, and date
- Full-width background section with distinct styling
- "View more posts" CTA link

### 10. **Final Call-to-Action**
- Large headline: "Try Cursor now"
- "Download for Linux" button
- Prominent positioning for maximum engagement

### 11. **Footer**
- Multi-column link structure with 5 sections:
  - **Product** (Features, Enterprise, Web Agents, Bugbot, CLI, Pricing)
  - **Resources** (Download, Changelog, Docs, Learn, Forum, Status)
  - **Company** (Careers, Blog, Community, Workshops, Students, Brand)
  - **Legal** (Terms of Service, Privacy Policy, Data Use, Security)
  - **Connect** (X, LinkedIn, YouTube)
- Copyright notice: "© 2026 Cursor"
- SOC 2 Certified badge
- Theme and language selectors
- Dark background with organized link grid

---

## 🎨 Design System

### Fonts

- **Primary Font:** `Cursor Gothic`
  - Custom font loaded via `@font-face`
  - Source: Local font file (CursorGothic-Regular.woff2)
  - Fallback: `sans-serif`
  - Used for all headings, body text, buttons, and navigation

### Colors

All colors are defined throughout the CSS and use both RGB and OKLab color spaces:

| Element | Color | Usage |
|---------|-------|-------|
| **Background Color** | `rgb(20, 18, 11)` | Main page and navbar background |
| **Text Color (Primary)** | `#edecec` | Headings and primary text |
| **Text Color (Secondary)** | `oklab(0.943853 0.00107113 0.000336707 / 0.6)` | Muted/secondary text, captions |
| **Card Background** | `rgb(27, 25, 19)` | Testimonial cards, feature cards |
| **Accent Background** | `rgb(35, 33, 28)` | Hover states and highlights |
| **Border Color** | `#302e29` | Button borders and dividers |
| **Logo/Featured Logo Background** | `#1B1913` | Trusted by section background |
| **Accent Color (Orange)** | `#f54e00` | Links and CTAs ("Learn about", "Explore") |

### Typography Scale

- **Hero/Section Headlines:** 36–72px, font-weight: normal
- **Subheadings:** 22–26px, font-weight: normal
- **Body Text:** 14–16px, font-weight: normal
- **Small Labels/Captions:** 12–14px, font-weight: normal
- **Line Heights:** 1.4–1.6 for readability

### Layout Features

- **Desktop-first:** Optimized for 1920×1080+ displays
- **Max-width sections:** 1300px container width
- **Spacing:** Consistent 10–95px margins and padding
- **Border Radius:** 4–5px for cards, `2.68435e+07px` (pill-shaped) for buttons
- **Grid Layouts:** CSS Grid used for testimonials (3×2), features, changelog, footer, and highlights
- **Flexbox:** Used for navigation, hero sections, cards, and spacing

---

## 🛠️ Tech Stack

- **HTML5** – Semantic markup with proper document structure
- **CSS3** – Modern styling with custom properties, Grid, and Flexbox
- **SVG** – Cursor logo as scalable vector graphic
- **No dependencies** – Pure static site
- **Constraints met:**
  - ✅ HTML & CSS only (no JavaScript)
  - ✅ No TailwindCSS
  - ✅ No AI-generated content
  - ✅ No animations or fancy effects
  - ✅ Desktop-only design (1300px fixed width)
  - ✅ Brand assets from original Cursor website

---

## 📁 Project Structure

```
ChaiaurCode-Cursor-Clone/
├── index.html                  
├── style.css                   
├── README.md                   
├── assets             
└── fonts  
```

---

## Author
### Krish Varma