# Three Hundred Replay Studio

https://sociisgroup-flow-concept.jeremie836072.chatgpt.site 
I want you to recreate the reference website as accurately as technically possible.

REFERENCE WEBSITE
https://sociisgroup-flow-concept.jeremie836072.chatgpt.site


OBJECTIVE:
Rebuild the website so that the new implementation visually and functionally matches the reference website as closely as possible. Treat the reference website as the source of truth for the design, layout, typography, interactions, responsiveness, animations, and user experience.

IMPORTANT:
Do NOT create a generic interpretation or redesign.
Do NOT simplify the design.
Do NOT replace elements with approximate alternatives.
Do NOT invent a new visual style.
Reproduce the observed design and behavior as precisely as possible.

## 1. ANALYZE THE REFERENCE FIRST

Before writing the implementation, thoroughly inspect the reference website.

Analyze every accessible page, section, component, interaction, and responsive state.

Identify:

- Page structure
- Header/navigation
- Announcement bars
- Hero sections
- Buttons
- Cards
- Forms
- Images
- Videos
- Icons
- Logos
- Navigation menus
- Dropdowns
- Modals
- Sliders/carousels
- Accordions
- Tabs
- Footers
- Floating elements
- Sticky elements
- Hover states
- Scroll behavior
- Loading states
- Transitions
- Animations
- Micro-interactions
- External links
- Internal links
- Forms and validation
- Any other interactive functionality

Do not begin implementation until you understand the structure of the reference.

## 2. PIXEL-PERFECT VISUAL RECREATION

Match the reference as closely as possible at the visual level.

Pay particular attention to:

### Typography

Identify and reproduce:

- Exact font family
- Font source/import method
- Font weights
- Font sizes
- Line heights
- Letter spacing
- Text transformations
- Heading hierarchy
- Paragraph styling
- Button typography
- Navigation typography

If the exact font is available, use it.

Do not substitute a different font unless the original is genuinely unavailable.

### Layout

Match:

- Container widths
- Maximum widths
- Grid structure
- Column widths
- Section heights
- Padding
- Margins
- Gaps
- Alignment
- Positioning
- Borders
- Border radius
- Shadows
- Backgrounds
- Overlapping elements
- Z-index relationships

Avoid arbitrary CSS values when the reference clearly indicates a consistent spacing system.

### Colors

Reproduce the actual visual palette:

- Background colors
- Text colors
- Accent colors
- Button colors
- Border colors
- Hover colors
- Gradient colors
- Overlay opacity

Use consistent CSS variables for the color system.

### Images and Media

Use the closest available original assets.

Match:

- Aspect ratio
- Crop
- Object positioning
- Resolution
- Border radius
- Overlay
- Image placement
- Video behavior

Do not replace prominent imagery with unrelated stock imagery.

If an asset cannot be accessed, create a clearly marked placeholder rather than silently changing the layout.

## 3. RESPONSIVE DESIGN

The recreation must work correctly across:

- Desktop
- Laptop
- Tablet
- Mobile

Analyze how the reference changes at different viewport sizes.

Match:

- Breakpoints
- Navigation behavior
- Mobile menu
- Typography scaling
- Column stacking
- Image resizing
- Section spacing
- Button sizing
- Content visibility
- Horizontal scrolling
- Card behavior
- Sticky elements

Do not simply shrink the desktop version.

Reproduce the reference's actual responsive behavior.

## 4. INTERACTIONS

Every observable interaction should be recreated.

Examples include:

- Navigation dropdowns
- Mobile navigation
- Hamburger menu
- Buttons
- Links
- Hover effects
- Focus states
- Active states
- Accordions
- Tabs
- Sliders
- Carousels
- Modals
- Forms
- Form validation
- Search
- Filters
- Scroll-triggered elements
- Sticky headers
- Back-to-top buttons
- Video controls
- Image galleries

If an interaction exists on the reference website, implement it rather than creating a static visual imitation.

## 5. ANIMATIONS

Inspect the reference for animations and reproduce them.

Pay attention to:

- Entrance animations
- Fade effects
- Slide effects
- Scale effects
- Hover transitions
- Button animations
- Menu animations
- Scroll animations
- Parallax effects
- Image transitions
- Loading animations

Match:

- Duration
- Delay
- Easing
- Direction
- Trigger
- Distance
- Scale

Animations should feel like the original rather than generic animations added afterward.

## 6. NAVIGATION AND ROUTING

Recreate the site's information architecture.

Every visible navigation item should lead to the correct corresponding page or section.

Implement:

- Header navigation
- Footer navigation
- Internal routes
- Anchor links
- Breadcrumbs if present
- Mobile navigation
- External links where appropriate

Do not leave visible navigation items as dead buttons.

## 7. COMPONENT ARCHITECTURE

Build the website using reusable components.

Create appropriate components for things such as:

- Header
- Navigation
- Footer
- Hero
- Buttons
- Cards
- Sections
- Forms
- Modals
- Accordions
- Tabs
- Carousels
- Testimonials
- Content blocks

Avoid duplicating large amounts of markup unnecessarily.

Keep the implementation clean, maintainable, and scalable.

## 8. CODE QUALITY

Use a modern production-quality architecture.

Prefer:

- React
- TypeScript where appropriate
- Semantic HTML
- CSS/Tailwind where appropriate
- Reusable components
- CSS variables/design tokens
- Responsive layouts
- Accessible interactive elements

Avoid:

- Hardcoded hacks
- Excessive absolute positioning
- Unnecessary inline styles
- Duplicate components
- Broken responsive behavior
- Console errors
- Unused dependencies
- Placeholder content where real content can be reproduced

## 9. CONTENT

Reproduce the visible content from the reference as accurately as possible:

- Headings
- Paragraphs
- Button labels
- Navigation labels
- Form labels
- Footer content
- Section titles
- Captions
- Lists

Preserve:

- Capitalization
- Punctuation
- Line breaks where visually important
- Text hierarchy

Do not rewrite the copy unless required because of unavailable source content.

## 10. ACCESSIBILITY

While preserving the visual design, also implement:

- Semantic HTML
- Proper heading hierarchy
- Accessible buttons
- Keyboard navigation
- Focus states
- Alt text
- Form labels
- ARIA attributes where necessary
- Sufficient interaction targets

Accessibility improvements must not unnecessarily alter the visual appearance.

## 11. PERFORMANCE

Keep the recreated site performant.

Optimize:

- Images
- Fonts
- Lazy loading
- Component rendering
- Animations
- Network requests
- Bundle size

Do not sacrifice visual fidelity unnecessarily for performance.

## 12. SEO

Recreate the appropriate SEO structure:

- Page titles
- Meta descriptions
- Heading hierarchy
- Semantic HTML
- Canonical URLs where appropriate
- Open Graph metadata where applicable
- Image alt text
- Structured data where clearly applicable

## 13. VALIDATION / COMPARISON

After implementation, perform a visual comparison against the reference.

Check each page section systematically.

Compare:

1. Overall layout
2. Header
3. Navigation
4. Hero
5. Typography
6. Spacing
7. Colors
8. Images
9. Buttons
10. Cards
11. Forms
12. Footer
13. Responsive behavior
14. Animations
15. Interactive states

Fix discrepancies instead of accepting approximate results.

Pay special attention to:

- Font rendering
- Section heights
- Container width
- Vertical spacing
- Element alignment
- Image cropping
- Button dimensions
- Border radius
- Shadows
- Mobile layout

## 14. DO NOT STOP AT THE FIRST VERSION

The first implementation should be treated as Version 1.

After building it:

→ Inspect the result
→ Compare it against the reference
→ Identify visual differences
→ Fix them
→ Re-check responsive layouts
→ Test interactions
→ Fix remaining inconsistencies

Continue refining until the result is as close to the reference as technically possible.

## 15. IMPORTANT RULE

When there is a choice between:

A) creating something that is easier to code

and

B) reproducing the reference accurately

choose B.

The reference website is the design specification.

Do not make creative design decisions unless the reference does not provide enough information.

## FINAL ACCEPTANCE CRITERIA

Consider the recreation complete only when:

- The overall appearance closely matches the reference
- Typography is matched
- Layout and spacing are matched
- Colors are matched
- Images/media are correctly positioned
- Navigation works
- Interactions work
- Animations are reproduced
- Responsive behavior matches
- Mobile layout works correctly
- No major console errors exist
- No visible placeholder UI remains where the reference provides real content
- All major pages and sections have been implemented
- The implementation is clean and maintainable

Most importantly:

DO NOT BUILD A WEBSITE "INSPIRED BY" THE REFERENCE.

BUILD A FUNCTIONAL, HIGH-FIDELITY RECREATION OF THE REFERENCE WEBSITE.

If something cannot be reproduced exactly because the required asset, API, font, or functionality is inaccessible, clearly identify that limitation and reproduce everything else as accurately as possible.
also change the url to this  https://the300.sociisgroup.com

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/7a8f61ce-5a54-463d-ac77-8e079f57171f).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
