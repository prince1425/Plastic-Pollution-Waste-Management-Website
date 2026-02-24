# PlasticFree Earth - Website Project

## Topic: Plastic Pollution and Waste Management Solutions

## Project Structure

```
plastic-pollution-site/
├── index.html          ← Home page (The Problem)
├── solutions.html      ← Solutions & Waste Management page
├── contact.html        ← Get Involved / Survey / Contact page
├── css/
│   └── style.css       ← External stylesheet (all styling)
├── media/
│   ├── ocean-plastic.mp4      ← (Add your video file here)  
│   ├── plastic-expert.mp3     ← (Add your audio file here)
└── README.md
```

## Requirements Checklist

### ✅ Website Structure
- [x] 3 linked pages: index.html, solutions.html, contact.html
- [x] Internal navigation on all pages
- [x] HTML5 semantic elements: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<fieldset>`, `<legend>`
- [x] Clean, well-indented code throughout

### ✅ Content Elements
- [x] Headings (h1–h4) and paragraphs throughout
- [x] Unordered lists (styled-list with custom bullets)
- [x] Ordered lists (styled-ol with counter)
- [x] Multiple data tables with thead/tbody/caption
- [x] Images with alt text and captions (from Unsplash)
- [x] Special characters: `&mdash;`, `&ndash;`, `&rsquo;`, `&lsquo;`, `&ldquo;`, `&rdquo;`, `&amp;`, `&thinsp;`, `&rarr;`, `&#8593;`, `&#9312;`–`&#9317;` (circled numbers), and many more

### ✅ Forms
- [x] Full HTML form on contact.html with:
  - `type="text"` (first/last name)
  - `type="email"` (email address)
  - `type="tel"` (phone number)
  - `type="number"` (bags/bottles per week)
  - `type="url"` (website)
  - `type="date"` (last cleanup)
  - `type="range"` (concern slider)
  - `type="radio"` (frequency, responsibility)
  - `type="checkbox"` (alternatives, consent, newsletter)
  - `<select>` dropdowns (age, country, problem)
  - `<textarea>` (message/pledge)
  - HTML5 attributes: `required`, `minlength`, `maxlength`, `min`, `max`, `step`, `pattern`, `placeholder`, `autocomplete`

### ✅ Multimedia
- [x] `<video>` element with multiple sources (mp4/webm) + fallback text
- [x] `<audio>` element with multiple sources (mp3/ogg) + fallback text
- Note: Place your media files in the `/media/` folder with filenames as listed above

### ✅ CSS Styling (external stylesheet: css/style.css)
- [x] Background styling: gradient backgrounds, image backgrounds, radial gradients
- [x] Positioning: sticky header, absolute wave shapes, relative/absolute dropdown menus
- [x] Box model: margins, padding, borders, border-radius throughout
- [x] Element sizing: width, height, min-height, max-width, clamp()
- [x] CSS Dropdown navigation menu using `position: absolute` + `:hover` visibility toggle

### ✅ Responsiveness
- [x] Media query for large screens (min-width: 1400px)
- [x] Media query for tablets (max-width: 1024px): collapses 2-col layouts
- [x] Media query for mobile (max-width: 768px): hamburger menu, stacked grid
- [x] Print media type styles
- [x] Fluid typography with `clamp()` and `vw` units
- [x] Flexible grid with `auto-fit` and `minmax()`

### ✅ Validation
- Validate index.html at https://validator.w3.org/
- Take screenshot of validation result and include in submission

## Notes for Media Files
The video and audio elements are configured but require actual media files. You can:
1. Record/find royalty-free ocean/plastic-related content
2. Place MP4 and WebM versions in `/media/` for video
3. Place MP3 and OGG versions in `/media/` for audio
4. The fallback links/text will display gracefully if files are absent

## Design Choices
- **Color palette**: Deep ocean blues with teal accents and coral highlights
- **Typography**: Playfair Display (serif, display font) + Source Sans Pro (body)
- **Theme**: Dark, ocean-themed — immersive and appropriate to subject matter
- **Layout**: Multi-column grids, semantic sections, card-based components
