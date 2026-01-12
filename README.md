# The Gateway Group Website

A modern, responsive website for The Gateway Group - a collaborative network for education leaders along the South Coast.

## Design Inspiration

The website is inspired by the clean, modern design aesthetic of [Statamic.com](https://statamic.com/), featuring:
- Modern sans-serif typography (Inter font)
- Clean, spacious layouts
- Subtle animations and transitions
- Professional yet approachable design
- Responsive grid systems

## Features

### Homepage
- **Hero Animation**: Animated "Connect. Collaborate. Create." tagline with gradient text effects
- **Floating Cards**: Three animated cards showcasing the core values
- **Feature Grid**: Six key benefits of joining The Gateway Group
- **Call-to-Action Section**: Prominent CTA to encourage visitor engagement

### Pages
1. **Home** (`index.html`) - Landing page with hero animation and overview
2. **About** (`about.html`) - Information about The Gateway Group and The Gateway Trust
3. **Who Can Join** (`who-can-join.html`) - Eligible educational settings and geographic coverage
4. **Membership** (`membership.html`) - Benefits, costs, and membership options
5. **Contact** (`contact.html`) - Comprehensive form for expressing interest

### Design Elements
- Sticky navigation bar with blur effect
- Colorful logo integration with brand colors
- Gradient backgrounds and text effects
- Card-based layouts with hover effects
- Smooth animations and transitions
- Fully responsive design for mobile, tablet, and desktop

## File Structure

```
gatewaygroup/
├── index.html              # Homepage
├── about.html              # About page
├── who-can-join.html       # Who Can Join page
├── membership.html         # Membership page
├── contact.html            # Contact/Express Interest page
├── css/
│   └── styles.css          # Main stylesheet
├── js/
│   └── main.js             # JavaScript for interactions
├── images/
│   └── logo.png            # The Gateway Group logo
└── README.md               # This file
```

## Color Palette

The design incorporates colors from the logo:
- **Purple**: #8B3A9C
- **Pink**: #E91E63
- **Yellow**: #FDD835
- **Green**: #8BC34A
- **Blue**: #00BCD4
- **Primary**: #2563eb (used for buttons and accents)

## Typography

- **Font Family**: Inter (Google Fonts)
- **Weights Used**: 300, 400, 500, 600, 700, 800

## Animations

### Hero Section
1. **Connect** - Slides up with purple-to-pink gradient (0.2s delay)
2. **Collaborate** - Slides up with blue-to-green gradient (0.5s delay)
3. **Create** - Slides up with yellow-to-green gradient (0.8s delay)

### Floating Cards
- Three cards float in with staggered timing
- Continuous floating animation creates dynamic visual interest

### Hover Effects
- Features cards lift and show shadow on hover
- Buttons transform and elevate on hover
- Navigation links smoothly change color

## Browser Compatibility

The website uses modern CSS features and is compatible with:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Setup

1. Open `index.html` in a web browser to view the website
2. All assets are included (CSS, JS, logo)
3. No build process required - pure HTML/CSS/JS

## Customization

### Updating Content
- Edit HTML files directly to modify text content
- Update form fields in `contact.html` as needed

### Styling Changes
- Modify CSS variables in `css/styles.css` (lines 15-35) to adjust colors
- Update spacing variables to change layout density

### Adding Pages
1. Copy an existing HTML file as a template
2. Update the navigation in all files to include the new page
3. Ensure footer links are updated across all pages

## Form Handling

The contact form currently uses client-side JavaScript for basic validation. To make it functional:
1. Connect to a backend service (e.g., FormSpree, Basin, or custom API)
2. Update the form action attribute in `contact.html`
3. Or integrate with an email service provider

## Future Enhancements

Potential improvements:
- Add a map showing geographic coverage
- Photo gallery of member schools
- Testimonials from current members
- News/blog section for updates
- Member login area

## Credits

- Design inspired by Statamic.com
- Built for The Gateway Group (Part of The Gateway Trust)
- Logo design featuring colorful gateway arch

---

**Note**: This is a static website. For production use, consider:
- Adding a backend for form submissions
- Implementing analytics tracking
- Setting up hosting (GitHub Pages, Netlify, Vercel, etc.)
- Adding SEO meta tags and structured data
- Implementing a Content Security Policy
