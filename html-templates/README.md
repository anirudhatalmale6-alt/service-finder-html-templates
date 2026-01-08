# Service Finder - HTML Templates

Converted from the Service Finder WordPress Theme (ThemeForest) to clean, standalone HTML/CSS/JS templates.

## Folder Structure

```
html-templates/
├── layout-1/          # Style 1: Classic Blue Theme
├── layout-2/          # Style 2: Green Theme with Center Logo
├── layout-3/          # Style 3: Purple Theme with Light Footer
├── layout-4/          # Style 4: Red Theme with Dark Header
├── layout-5/          # Style 5: Teal/Cyan Modern Gradient Theme
├── layout-6/          # Style 6: Orange/Dark Premium Theme
└── README.md
```

Each layout folder contains:
```
layout-X/
├── index.html         # Homepage
├── about.html         # About Us page
├── contact.html       # Contact page
├── listing-grid.html  # Service providers listing
├── css/               # Stylesheets
│   ├── bootstrap.min.css
│   ├── fontawesome/
│   ├── animate.css
│   ├── owl.carousel.css
│   ├── slick.css
│   ├── magnific-popup.css
│   ├── style.css
│   ├── layout-X.css
│   ├── theme-style.css
│   └── custom.css
├── js/                # JavaScript files
│   ├── jquery-1.11.3.min.js
│   ├── bootstrap.min.js
│   ├── owl.carousel.js
│   ├── slick.js
│   ├── jquery.magnific-popup.js
│   └── custom.js
├── images/            # Image assets
└── fonts/             # Font files
```

## Third-Party Libraries Used

### CSS Libraries
| Library | Version | Purpose | License |
|---------|---------|---------|---------|
| Bootstrap | 3.4.x | Grid system, components, responsive utilities | MIT |
| Font Awesome | 5.x | Icon fonts | SIL OFL 1.1 / MIT |
| Bootstrap Icons | 1.x | Additional icon set | MIT |
| Animate.css | 4.x | CSS animations | MIT |
| Owl Carousel | 2.x | Carousel/slider styles | MIT |
| Slick | 1.8.x | Carousel/slider styles | MIT |
| Magnific Popup | 1.x | Lightbox/popup styles | MIT |

### JavaScript Libraries
| Library | Version | Purpose | License |
|---------|---------|---------|---------|
| jQuery | 1.11.3 | DOM manipulation, AJAX, events | MIT |
| jQuery Migrate | 1.2.1 | jQuery backwards compatibility | MIT |
| Bootstrap JS | 3.4.x | Bootstrap interactive components | MIT |
| Owl Carousel | 2.x | Touch-enabled carousel slider | MIT |
| Slick | 1.8.x | Responsive carousel slider | MIT |
| Magnific Popup | 1.x | Lightbox and popup dialogs | MIT |
| Masonry | 4.x | Grid layout library | MIT |
| Theia Sticky Sidebar | 1.x | Sticky sidebar functionality | MIT |

### Fonts
- **Poppins** (Google Fonts) - Primary font family
- **Font Awesome** - Icon font
- **Bootstrap Icons** - Icon font
- **Simple Line Icons** - Icon font
- **Feather Icons** - Icon font

## Layout Descriptions

### Layout 1 (Blue Theme)
- Classic header with top bar
- Blue primary color (#1767ef)
- Yellow/gold accent color (#ffb600)
- Standard navigation layout

### Layout 2 (Green Theme)
- Center-aligned logo
- Green primary color (#28a745)
- Yellow accent color (#ffc107)
- Search-focused design

### Layout 3 (Purple Theme)
- Light footer design
- Purple primary color (#6f42c1)
- Orange accent color (#fd7e14)
- Clean modern look

### Layout 4 (Red Theme)
- Dark header background
- Red/coral primary color (#dc3545)
- Cyan accent color (#17a2b8)
- Bold, striking design

### Layout 5 (Teal/Cyan Theme)
- Gradient headers and buttons
- Teal/cyan primary (#20c997 to #17a2b8)
- Pink accent color (#e83e8c)
- Modern rounded elements

### Layout 6 (Orange/Dark Theme)
- Premium dark design
- No top bar for cleaner look
- Orange primary color (#ff6600)
- Sharp, square elements
- Best for premium/corporate sites

## Browser Compatibility

Tested and compatible with:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Safari (latest)
- Microsoft Edge (latest)
- Internet Explorer 11 (basic support)

## Responsive Breakpoints

- Extra large devices (≥1200px)
- Large devices (992px - 1199px)
- Medium devices (768px - 991px)
- Small devices (576px - 767px)
- Extra small devices (<576px)

## How to Use

1. Choose a layout folder that matches your preferred style
2. Copy the entire layout folder to your web server
3. Customize colors in `css/custom.css`
4. Replace placeholder images in `images/` folder
5. Update content in HTML files
6. Modify navigation links as needed

## Customization

### Changing Primary Colors
Edit the `css/custom.css` file and modify the color values:
- Primary color: `.btn-primary`, links, icons
- Secondary color: `.btn-secondary`, accents
- Update hover states accordingly

### Adding New Pages
1. Copy an existing HTML file as template
2. Update the page title and content
3. Modify the navigation active states
4. Link the page in the navigation menu

## Credits

- Original WordPress Theme: Service Finder by Aonetheme
- Converted to HTML templates for standalone use

---
Generated: January 2026
