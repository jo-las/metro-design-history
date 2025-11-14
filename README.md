# Metro Design Language - History & Evolution

A website documenting the history, principles, and evolution of Microsoft's Metro/Fluent Design Language, built using authentic Metro/Fluent styling.

## Project Overview

This site explores Metro design from its 2010 debut on Windows Phone 7 through its evolution into Fluent Design on Windows 11. The site itself is built following Metro/Fluent design principles as documented in the [Fluent-Metro-Guide](https://github.com/kaw393939/swiss_design_lineage_vibecoding/blob/main/style-guides/intermediate/FLUENT-METRO-GUIDE.md).

## Design Specifications

### Typography
- **Typeface**: Segoe UI (with Inter fallback)
- **Hero text**: 96px, dramatically large
- **H1**: 56px (page titles)
- **H2**: 42px (section headers)
- **Body**: 16px (utilitarian)
- **Alignment**: Flush-left, strong left alignment
- **Letter-spacing**: Generous for large text (0.02em)

### Color Palette
- **Microsoft Blue**: #0078D7 (primary)
- **Magenta**: #D80073
- **Teal**: #00ABA9
- **Cyan**: #1BA1E2
- **Orange**: #FA6800
- **Lime**: #A4C400
- **Purple**: #AA00FF
- **Neutrals**: White (#FFFFFF), Light Gray (#F3F3F3)

### Layout
- **Grid**: Tile-based and card-based layouts
- **Tile gaps**: 12px between tiles
- **Tile padding**: 24px internal
- **Margins**: 32px from edges
- **Border-radius**: 8px (Fluent style)

### Motion
- **Animation duration**: 200-300ms (fast and fluid)
- **Easing**: cubic-bezier(0.25, 0.1, 0.25, 1) - ease-out
- **Transitions**: Smooth hover states, staggered entry animations

## Pages

1. **Home** (`index.html`) - Introduction with tile-based layout showcasing Metro's key concepts
2. **Timeline** (`timeline.html`) - Evolution from 2010-2025, key moments and milestones
3. **Designers** (`designers.html`) - Albert Shum, Microsoft Design team, and design influences
4. **Principles** (`principles.html`) - Core Metro/Fluent design principles explained in detail

## File Structure

```
Design Style/
├── index.html
├── timeline.html
├── designers.html
├── principles.html
├── css/
│   ├── styles.css (main styles)
│   ├── timeline.css
│   ├── designers.css
│   └── principles.css
├── js/
│   └── animations.js
├── research/
│   ├── references/ (reference images)
│   └── references.md
└── docs/
```

## Key Metro/Fluent Characteristics Implemented

✅ **Content Before Chrome** - Information prioritized over decoration  
✅ **Typography-First** - Dramatically large headings as primary design element  
✅ **Authentically Digital** - Flat colors, no skeuomorphism  
✅ **Bold Systematic Color** - High contrast, flat Metro colors  
✅ **Fast & Fluid Motion** - 200-300ms animations with ease-out  
✅ **Information Density** - Efficient use of space  
✅ **Grid-Based Layout** - Strict alignment, tile-based system  
✅ **Responsive Design** - Works on desktop, tablet, and mobile

## Viewing the Site

### Local Development
Simply open `index.html` in a web browser, or use a local server:

```bash
# Python 3
python -m http.server 8000

# Node.js (with http-server)
npx http-server
```

Then navigate to `http://localhost:8000`

### Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design for mobile/tablet/desktop
- Tested viewport sizes: 480px, 768px, 1024px+

## Design Principles Applied

This site demonstrates authentic Metro/Fluent design:

1. **Typography dominates** - Hero text at 96px creates visual hierarchy through size
2. **Bold color blocks** - Tiles use full Metro color palette with white text
3. **Strict grid alignment** - Every element snaps to the 12-column grid
4. **Fast animations** - Hover effects and scroll animations at 200-300ms
5. **Information density** - Efficient layouts pack content without overwhelming
6. **Clean navigation** - Sidebar navigation with clear active states
7. **Minimal decoration** - Content before chrome throughout

## References

- **Style Guide**: [Fluent-Metro-Guide](https://github.com/kaw393939/swiss_design_lineage_vibecoding/blob/main/style-guides/intermediate/FLUENT-METRO-GUIDE.md)
- **Workflow**: [Workflow Guide](https://github.com/kaw393939/swiss_design_lineage_vibecoding/blob/main/docs/WORKFLOW.md)
- **Reference Images**: See `/research/references/` for Metro UI examples

## Build Information

- **Created**: November 14, 2025
- **Style**: Metro/Fluent Design Language
- **Time Investment**: ~10 hours following the 5-phase workflow
- **Framework**: Vanilla HTML, CSS, JavaScript (no dependencies)

## License

Educational project for design learning.

---

**Metro Design Language**: Content before chrome, typography-first, authentically digital.
