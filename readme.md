# StoryCast

An accessible audio and story sharing platform built with semantic HTML and Sass.

## Project Structure

```
storycast/
├── index.html
├── story.html
├── about.html
├── css/
│   └── style.css
├── sass/
│   ├── main.scss
│   ├── _colors.scss
│   ├── _typography.scss
│   ├── _spacing.scss
│   ├── _mixins.scss
│   └── _components.scss
├── assets/
│   ├── audio/
│   ├── video/
│   └── transcripts/
└── documentation/
    └── project-documentation.pdf
```

## Accessibility Checklist

**Semantic HTML**
- Header, main, nav, article, section, aside, footer elements implemented
- Proper heading hierarchy (H1-H3) following document structure
- Landmark roles (banner, navigation, main, complementary, contentinfo)

**Media Accessibility**
- All audio/video includes WebVTT captions via track elements
- Full transcripts provided adjacent to media players
- Figcaption for all figure elements
- Descriptive alt text for informative images

**Visual Accessibility**
- Color contrast ratios exceed WCAG 2.1 AA standards (4.5:1 minimum)
- Color not used as sole information carrier
- Visible focus indicators on all interactive elements

**Navigation**
- Full keyboard operability with logical tab order
- Skip links provided for bypassing navigation
- ARIA labels where semantic HTML insufficient

## Local Development

Requirements: Sass compiler

1. Clone repository
2. Navigate to project root directory
3. Compile Sass: `sass --watch sass/main.scss css/style.css`
4. Open HTML files in browser or use local server
5. No frameworks or build processes required