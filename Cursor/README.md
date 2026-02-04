# Cursor - AI Code Editor Landing Page

A modern, responsive landing page for **Cursor**, an AI-powered code editor built with HTML, CSS, and JavaScript. This project recreates the visual design and layout of the official Cursor website.

---

## Project Overview

This is a frontend implementation of the Cursor landing page, showcasing the product's features, testimonials, and call-to-action elements. The design emphasizes a dark, modern aesthetic with a focus on AI-powered development capabilities.

---

## Sections Recreated

### 1. **Navigation Bar**
- Cursor logo on the left
- Feature links: Features, Enterprises, Pricing, Resources
- Sign In and Download buttons
- Sticky header layout with flexbox alignment

### 2. **Hero Section**
- Main headline: "Built to make you extraordinarily productive, Cursor is the best way to code with AI."
- Primary call-to-action button: "Download for Windows"
- Large Cursor IDE screenshot showcase

### 3. **Trusted Users Section**
- Introductory text: "Trusted every day by millions of professional developers."
- 8-column logo grid displaying company partners:
  - Strip
  - OpenAI
  - Linear
  - DataDog
  - NVIDIA
  - Figma
  - Ramp
  - Adobe

### 4. **Agent Introduction Section**
- Text: "Agent turns Ideas into code"
- Descriptive content about human-AI programmer effectiveness
- Associated screenshot/image
- "Learn about Agents" link

### 5. **Agent Accuracy Section**
- Feature spotlight on autocomplete functionality
- Text: "Magically accurate autocomplete"
- Description of custom tab model prediction
- Image showcase

### 6. **Card 3 Section**
- Additional feature highlight
- Similar layout to agent introduction
- Contains image and descriptive text

### 7. **Feedback/Testimonials Section**
- Heading: "The new way to build software."
- 6 testimonial cards from industry leaders:
  - Diana Hu (Y Combinator)
  - shadcn (Creator of shadcn/ui)
  - Andrej Karpathy (Eureka Labs)
  - Patrick Collison (Stripe)
  - ThePrimeagen
  - Greg Brockman (OpenAI)

### 8. **Features Section (Stay on the Frontier)**
- Three feature cards in a row:
  1. **Access the best models** - OpenAI, Anthropic, Gemini, xAI integration
  2. **Complete codebase understanding** - Semantic search capabilities
  3. **Developer enduring software** - Enterprise security and scale
- Each card includes an image and exploration link

### 9. **Join Us Section**
- Headline: "Cursor is an applied team focused on building the future of coding."
- "Join us" call-to-action button
- Background image

### 10. **Try Cursor Section**
- Prominent heading: "Try Cursor Now"
- Download button with Windows emphasis
- Call-to-action section

### 11. **Footer**
- Five columns of links:
  - **Product**: Features, Enterprises, Web Agents, Bugbot, CLI, Pricing
  - **Resources**: Download, Changelog, Docs, Learn, Forum, Status
  - **Company**: Careers, Blog, Community, Workshops, Students, Brand
  - **Legals**: Terms of Service, Privacy Policy, Data Use, Security
  - **Connect**: X, LinkedIn, YouTube
- Copyright information: "© 2026 Cursor"

---

## Colors Used

### Primary Colors
| Color | Hex Code | Usage |
|-------|----------|-------|
| Dark Background | `#0B0B0B` | Main body background |
| White/Text | `#FFFFFF` (#ffff) | Primary text color |
| Dark Card Background | `#242020` | Testimonial cards |
| Secondary Dark | `#161313` | Feature cards |
| Dark Neutral | `#171212` | Sign-in button background |

### Secondary/Accent Colors
| Color | Usage |
|-------|-------|
| `rgba(32, 29, 29, 0.445)` | Semi-transparent backgrounds for agent sections |
| `rgba(255, 255, 255, 0.2)` | Border color for logo containers |
| `rgba(30, 30, 30, 0.6)` | Logo container background |

### Color Scheme Philosophy
- **Dark Theme**: The entire design uses a dark color palette (#0B0B0B background)
- **High Contrast**: White text on dark backgrounds ensures readability
- **Subtle Accents**: Semi-transparent overlays create depth without harsh contrasts
- **Professional Look**: Neutral dark tones convey sophistication and modernity

---

## Fonts and Typography

### Font Family
- **Default System Stack**: The project uses the browser's default sans-serif font family
- No custom web fonts imported (relies on system fonts)
- Clean, modern appearance with standard font rendering

### Typography Hierarchy
| Element | Font Weight | Size | Notes |
|---------|-------------|------|-------|
| Navigation Links | Normal | Default | Clear, readable links |
| Main Heading (H1) | Bold | 80px | Used in "Try Cursor Now" section |
| Section Headings (H2) | Bold | Default | Feature descriptions |
| Sub-headings (H3, H4) | Bold | Default | Card titles and section labels |
| Body Text | Normal | Default | Testimonials and descriptions |
| Links | Normal | Default | Underline removed via CSS |

---

## Project Structure

```
Cursor/
├── index.html          # Main HTML structure
├── style.css           # Complete styling and layout
├── README.md           # This file
└── images/             # Image assets
    ├── LOCKUP_HORIZONTAL_2D_DARK copy 2.png
    ├── Screenshot 2026-02-02 192824.png
    ├── Screenshot 2026-02-02 205040.png
    ├── Screenshot 2026-02-02 221212.png
    ├── Screenshot 2026-02-02 221504.png
    ├── Screenshot 2026-02-03 090138.png
    ├── Screenshot 2026-02-03 090448.png
    ├── Screenshot 2026-02-03 091020.png
    └── Screenshot 2026-02-03 092341.png
```

---

## Key Design Features

### Layout & Spacing
- **Flexbox**: Used for navigation and directional layouts
- **CSS Grid**: Used for logo containers (8 columns) and testimonials (3 columns)
- **Margins**: Consistent 400px left and right margins for main content
- **Gaps**: 10-15px spacing between grid items

### Responsive Elements
- Navigation bar: `display: flex` with `justify-content: space-between`
- Logo containers: `grid-template-columns: repeat(8, 1fr)`
- Feedback cards: `grid-template-columns: repeat(3, 400px)`
- Feature cards: Three-column flex layout

### Interactive Elements
- Buttons with `border-radius` for rounded corners
- Hover-ready buttons (styling foundation present)
- Navigation links with `text-decoration: none`

---

## Additional Information

### Images & External Resources
- **Logo Images**: Company logos loaded from Vercel CDN (external URLs)
- **Local Screenshots**: Product screenshots stored in `/images/` directory
- **Image Sizing**: All images have explicit width and height for consistent rendering

### Browser Compatibility
- Modern CSS features used (CSS Grid, Flexbox)
- No vendor prefixes required
- Assumes modern browser support (Chrome, Firefox, Safari, Edge)

### Accessibility Notes
- All images include descriptive alt text
- Semantic HTML structure maintained
- Color contrast sufficient for readability (white on dark)

### Performance Considerations
- External images loaded from CDN (Vercel)
- No JavaScript dependencies (minimal JS setup)
- CSS organized for easy maintenance
- Modular class naming convention

---

## Future Enhancements

Potential improvements for this project:
- Add responsive design for mobile and tablet devices
- Implement smooth scroll behavior
- Add button hover and active states
- Integrate actual functionality for buttons
- Optimize image loading (lazy loading)
- Implement dark/light theme toggle
- Add animations and transitions
- Convert to semantic HTML5 elements
- Add form validation for potential contact forms

---

## Notes for Developers

- **Page Width**: Currently fixed at 1245px for main content with 400px side margins
- **Button Styling**: Buttons use a simple rounded style; consider adding more visual feedback
- **Link Colors**: All links inherit white color from body
- **Image Paths**: Ensure all local images exist in the `/images/` directory
- **External CDN**: Company logo SVGs loaded from Vercel storage; verify URLs remain active

---

**Created**: February 2026  
**Status**: Landing Page Recreation Complete  
**Version**: 1.0
