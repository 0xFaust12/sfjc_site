# CLAUDE.md - Guidelines for AI Assistance

## Project Overview
San Francisco Journal Club website - Minimalist HTML/CSS site with animated network background and text placed directly on white background.

## Commands
- No build system identified
- For linting HTML: `npx htmlhint *.html`
- For validating HTML: `npx html-validate *.html`
- For serving locally: `python -m http.server 8000`

## Code Style Guidelines
- **HTML**: Follow semantic HTML5 structure
- **CSS**: Use CSS variables for colors (--site-*)
- **Spacing**: 4-space indentation
- **Naming**: Use kebab-case for CSS classes
- **Color Theme**: Monochrome with white background and black text/elements (--site-black, --site-white, --site-gray, --site-light-gray)
- **Animation**: Network graph animation with light grey nodes and connections in background
- **Responsiveness**: Include media queries for mobile (max-width: 768px)
- **Font**: Use monospace as default font family
- **Accessibility**: Include proper meta descriptions, semantic structure

## JavaScript Guidelines
- Use ES6+ syntax
- Organize animation code with clear function separation
- Use requestAnimationFrame for smooth animations
- Include mouse interaction with network nodes
- Add try/catch blocks with appropriate error logging for any additions

## Future Development
- Maintain minimalist design aesthetic and monochrome color scheme
- Consider performance optimizations for the network animation on mobile devices
- Ensure canvas animation remains subtle and doesn't distract from content