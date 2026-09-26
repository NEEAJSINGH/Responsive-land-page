# Nova — Responsive Landing Page

A portfolio-ready responsive landing page created from a creative interpretation of a standard landing-page wireframe.

## Assignment Coverage

- Semantic HTML5 structure
- Responsive header and navigation
- Desktop, tablet, and mobile layouts
- Hero section with dashboard preview
- Feature highlights
- About section
- Call-to-action section
- Footer
- Responsive hamburger menu
- Active navigation section detection
- Dynamic footer year
- CSS Flexbox and CSS Grid
- CSS media queries
- Vanilla JavaScript
- Accessibility-friendly focus states
- Reduced-motion support
- No external frameworks required

## Files

```text
responsive-landing-page/
├── index.html
├── style.css
├── script.js
└── README.md
```

## How to Run

1. Extract the ZIP file.
2. Open the `index.html` file in Chrome, Edge, Firefox, or another modern browser.
3. Resize the browser to test desktop, tablet, and mobile layouts.
4. For a development workflow, you can also open the folder with VS Code and use Live Server.

## Wireframe / Layout Plan

```text
DESKTOP
┌─────────────────────────────────────────────────────────────┐
│ LOGO          HOME FEATURES ABOUT CONTACT       GET STARTED │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  EYEBROW                     ┌──────────────────────────┐    │
│  MAIN HERO HEADING           │                          │    │
│  Supporting paragraph        │    DASHBOARD PREVIEW    │    │
│  [CTA] [Explore]             │                          │    │
│  Social proof                └──────────────────────────┘    │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│                  FEATURE SECTION                             │
│        ┌──────────┐ ┌──────────┐ ┌──────────┐              │
│        │ Feature  │ │ Feature  │ │ Feature  │              │
│        └──────────┘ └──────────┘ └──────────┘              │
├─────────────────────────────────────────────────────────────┤
│             ABOUT / DESIGN APPROACH                         │
├─────────────────────────────────────────────────────────────┤
│                 CALL TO ACTION                              │
├─────────────────────────────────────────────────────────────┤
│                         FOOTER                              │
└─────────────────────────────────────────────────────────────┘

MOBILE
┌───────────────────────┐
│ LOGO            ☰     │
├───────────────────────┤
│ HERO HEADING          │
│ paragraph             │
│ [CTA]                 │
│ [Explore]             │
│ dashboard preview     │
├───────────────────────┤
│ Feature 1             │
│ Feature 2             │
│ Feature 3             │
├───────────────────────┤
│ About                 │
├───────────────────────┤
│ CTA                   │
├───────────────────────┤
│ Footer                │
└───────────────────────┘
```

## Responsive Breakpoints

- Desktop: above 980px
- Tablet: 721px–980px
- Mobile: 420px–720px
- Small phones: below 420px

## Design Decisions

The page uses a clean purple/indigo visual identity, large typography, generous whitespace, rounded cards, and a dashboard-style hero illustration. The dashboard is created entirely with HTML/CSS so the project remains self-contained and does not depend on external image assets.

## Testing Checklist

- [x] Navigation links scroll to the correct sections.
- [x] Mobile navigation opens and closes.
- [x] Navigation closes after selecting a link.
- [x] Active section is reflected in the navigation.
- [x] Footer year updates automatically.
- [x] Layout switches from two-column desktop to single-column mobile.
- [x] Buttons remain usable on narrow screens.
- [x] Keyboard focus states are visible.
- [x] Reduced-motion preference is respected.

## Browser Testing

Recommended browsers:
- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

## Customization

You can change the main design colors in `:root` at the top of `style.css`. The page content, brand name, buttons, and email address can be changed directly in `index.html`.
