# CSS Grid Complete Guide 🎨

A comprehensive, hands-on guide to CSS Grid Layout with live examples for every property. From fundamental concepts to advanced responsive layouts.

## 📚 Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [01. Basics](#01-basics)
- [02. Container Properties](#02-container-properties)
- [03. Item Properties](#03-item-properties)
- [04. Advanced Layouts](#04-advanced-layouts)
- [05. Responsive Examples](#05-responsive-examples)
- [Resources](#resources)
- [Contributing](#contributing)

## 🌟 Introduction

CSS Grid is a powerful two-dimensional layout system in CSS. This repository provides a complete learning path with:

- ✅ Live, interactive examples for each property
- ✅ Clear explanations and use cases
- ✅ Real-world layout patterns
- ✅ Responsive design techniques
- ✅ Best practices and tips

## 📁 Project Structure

```
CSS-Grid-Complete-Guide/
├── index.html                          # Main navigation page
├── styles.css                          # Base styles
├── README.md                           # This file
│
├── 01-basics/
│   ├── 01-display-grid.html           # Introduction to display: grid
│   ├── 02-grid-terminology.html        # Grid terminology explained
│   ├── 03-grid-lines.html             # Understanding grid lines
│   └── 04-grid-tracks.html            # Grid tracks and sizing
│
├── 02-container-properties/
│   ├── 01-grid-template-columns.html   # Defining columns
│   ├── 02-grid-template-rows.html      # Defining rows
│   ├── 03-grid-template-areas.html     # Named grid areas
│   ├── 04-grid-template.html           # Shorthand property
│   ├── 05-gap.html                     # Grid gaps (row-gap, column-gap)
│   ├── 06-justify-items.html           # Align items horizontally
│   ├── 07-align-items.html             # Align items vertically
│   ├── 08-place-items.html             # Shorthand for align/justify items
│   ├── 09-justify-content.html         # Align grid horizontally
│   ├── 10-align-content.html           # Align grid vertically
│   ├── 11-place-content.html           # Shorthand for align/justify content
│   ├── 12-grid-auto-columns.html       # Implicit column sizing
│   ├── 13-grid-auto-rows.html          # Implicit row sizing
│   └── 14-grid-auto-flow.html          # Auto-placement algorithm
│
├── 03-item-properties/
│   ├── 01-grid-column-start.html       # Column start position
│   ├── 02-grid-column-end.html         # Column end position
│   ├── 03-grid-column.html             # Shorthand for column placement
│   ├── 04-grid-row-start.html          # Row start position
│   ├── 05-grid-row-end.html            # Row end position
│   ├── 06-grid-row.html                # Shorthand for row placement
│   ├── 07-grid-area.html               # Shorthand for all placement
│   ├── 08-justify-self.html            # Align item horizontally
│   ├── 09-align-self.html              # Align item vertically
│   ├── 10-place-self.html              # Shorthand for align/justify self
│   └── 11-order.html                   # Visual order of items
│
├── 04-advanced-layouts/
│   ├── 01-nested-grids.html            # Grids within grids
│   ├── 02-overlapping-items.html       # Layering grid items
│   ├── 03-minmax-function.html         # Flexible sizing with minmax()
│   ├── 04-repeat-function.html         # Repeat pattern with repeat()
│   ├── 05-auto-fill.html               # Auto-fill tracks
│   ├── 06-auto-fit.html                # Auto-fit tracks
│   ├── 07-fr-unit.html                 # Fractional unit (fr)
│   ├── 08-fit-content.html             # fit-content() function
│   ├── 09-min-content-max-content.html # Content-based sizing
│   └── 10-subgrid.html                 # Subgrid feature
│
└── 05-responsive-examples/
    ├── 01-basic-responsive.html        # Basic responsive grid
    ├── 02-holy-grail-layout.html       # Classic Holy Grail layout
    ├── 03-card-layout.html             # Responsive card grid
    ├── 04-magazine-layout.html         # Magazine-style layout
    ├── 05-dashboard-layout.html        # Dashboard with widgets
    ├── 06-masonry-layout.html          # Pinterest-style masonry
    ├── 07-12-column-system.html        # 12-column grid system
    └── 08-asymmetric-layout.html       # Creative asymmetric design
```

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Jayasakthi-07/CSS-Grid-Complete-Guide.git
   cd CSS-Grid-Complete-Guide
   ```

2. **Open in browser:**
   - Open `index.html` in your browser to access the main navigation
   - Click on any example to see it in action

3. **Explore and Learn:**
   - Start with the basics folder
   - Progress through container and item properties
   - Experiment with advanced layouts
   - Build responsive designs

## 01. Basics

### Topics Covered:
- **Display Grid**: Converting an element into a grid container
- **Grid Terminology**: Container, items, lines, tracks, cells, areas
- **Grid Lines**: Numbered lines that define the grid structure
- **Grid Tracks**: Rows and columns between grid lines

## 02. Container Properties

Properties applied to the grid container (parent element):

### Layout Definition:
- `grid-template-columns` - Define column tracks
- `grid-template-rows` - Define row tracks
- `grid-template-areas` - Create named grid areas
- `grid-template` - Shorthand for rows, columns, and areas

### Spacing:
- `gap` (row-gap, column-gap) - Space between grid items

### Alignment:
- `justify-items` - Align items along the row axis
- `align-items` - Align items along the column axis
- `place-items` - Shorthand for align-items and justify-items
- `justify-content` - Align the grid along the row axis
- `align-content` - Align the grid along the column axis
- `place-content` - Shorthand for align-content and justify-content

### Implicit Grid:
- `grid-auto-columns` - Size implicitly-created columns
- `grid-auto-rows` - Size implicitly-created rows
- `grid-auto-flow` - Control auto-placement algorithm

## 03. Item Properties

Properties applied to grid items (child elements):

### Placement:
- `grid-column-start` - Start position on column axis
- `grid-column-end` - End position on column axis
- `grid-column` - Shorthand for column placement
- `grid-row-start` - Start position on row axis
- `grid-row-end` - End position on row axis
- `grid-row` - Shorthand for row placement
- `grid-area` - Shorthand for all placement or named area

### Alignment:
- `justify-self` - Align item along the row axis
- `align-self` - Align item along the column axis
- `place-self` - Shorthand for align-self and justify-self

### Order:
- `order` - Control visual order of items

## 04. Advanced Layouts

Advanced techniques and functions:

- **Nested Grids**: Creating grids within grid items
- **Overlapping Items**: Layering elements using z-index
- **minmax()**: Flexible sizing with minimum and maximum values
- **repeat()**: Repeating track patterns efficiently
- **auto-fill**: Fill container with as many tracks as possible
- **auto-fit**: Similar to auto-fill but collapses empty tracks
- **fr unit**: Fractional unit for flexible space distribution
- **fit-content()**: Size based on content with max limit
- **min-content/max-content**: Content-based sizing keywords
- **Subgrid**: Inherit grid definition from parent grid

## 05. Responsive Examples

Real-world responsive layouts:

1. **Basic Responsive**: Foundation responsive grid patterns
2. **Holy Grail Layout**: Header, footer, sidebar, main content
3. **Card Layout**: Auto-responsive card grid
4. **Magazine Layout**: Complex editorial design
5. **Dashboard**: Widget-based dashboard layout
6. **Masonry**: Pinterest-style masonry grid
7. **12-Column System**: Bootstrap-like grid system
8. **Asymmetric Layout**: Creative, non-uniform designs

## 📖 Resources

### Official Documentation:
- [MDN CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- [W3C CSS Grid Specification](https://www.w3.org/TR/css-grid/)

### Learning Resources:
- [CSS-Tricks Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Grid by Example](https://gridbyexample.com/)
- [CSS Grid Garden](https://cssgridgarden.com/) - Interactive game

### Tools:
- [Firefox Grid Inspector](https://developer.mozilla.org/en-US/docs/Tools/Page_Inspector/How_to/Examine_grid_layouts)
- [Chrome DevTools Grid](https://developer.chrome.com/docs/devtools/css/grid/)

## 🤝 Contributing

Contributions are welcome! If you'd like to add examples, fix bugs, or improve documentation:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-example`)
3. Commit your changes (`git commit -m 'Add new grid example'`)
4. Push to the branch (`git push origin feature/new-example`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- CSS Grid specification authors
- MDN Web Docs contributors
- CSS-Tricks and all CSS Grid educators
- The web development community

---

**Happy Grid Learning! 🎉**

If you find this guide helpful, please ⭐ star this repository!
