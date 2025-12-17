# The Macs Abroad - Static Website

A static recreation of The Macs Abroad travel blog website (www.themacsabroad.com).

## About

This is a travel blog by a couple slightly over 40 exploring the world, sometimes with their kids. The site features blog posts about their adventures, travel tips, and resources for fellow travelers.

## Structure

```
themacsabroad/
├── index.html          # Homepage with featured blog posts
├── about.html          # About Us page
├── blog.html           # Complete blog posts listing
├── travel-tips.html    # Travel Tips and Resources page
├── css/
│   └── style.css       # Main stylesheet with dark theme
├── js/
│   └── scripts.js      # JavaScript for mobile menu and interactions
├── images/
│   └── header.jpg      # Header image
└── README.md           # This file
```

## Features

- **Dark Theme Design**: Elegant dark background with light text for comfortable reading
- **Responsive Layout**: Fully responsive design that works on desktop, tablet, and mobile devices
- **Blog Grid**: Clean grid layout for blog posts with images and excerpts
- **Navigation Menu**: Dropdown menu support for travel tips submenu
- **Mobile Menu**: Collapsible mobile navigation with hamburger menu
- **Hero Header**: Large header image on each page

## Pages

1. **Home (index.html)**: Features all blog posts in a grid layout under "Our Adventures"
2. **About Us (about.html)**: Information about the travelers and their travel style
3. **Blog Posts (blog.html)**: Complete listing of all blog posts
4. **Travel Tips (travel-tips.html)**: Detailed travel advice including:
   - Itinerary Building strategies
   - Packing tips and checklists
   - Travel wisdom and lessons learned

## Design Features

- Dark color scheme (#151515 background, #b7b7b7 text)
- Card-based blog post layout with hover effects
- Clean typography using system fonts
- Smooth transitions and animations
- Accessible navigation with ARIA labels

## Blog Posts Featured

- Beginner's Guide to Spanky's Ladder (2022)
- Tofino 2020
- Whistler 2020
- London 2020
- Greece 2019
- Peru 2018
- Hungary, Slovakia and Czech Republic 2017
- Thailand, Cambodia and Vietnam 2016/2017
- Morocco 2015
- Turkey 2014

## Technologies Used

- HTML5
- CSS3 (with Flexbox and Grid)
- Vanilla JavaScript
- No external frameworks or libraries

## Deployment

This is a static website that can be hosted on any web server or static hosting service:

- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Traditional web hosting

Simply upload all files maintaining the directory structure.

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Responsive design supports all screen sizes

## Local Development

To view locally, simply open `index.html` in your web browser, or use a local web server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx serve

# Then open http://localhost:8000 in your browser
```

## Notes

- Blog post images are currently linked from the original website
- Individual blog post pages (detail pages) are not included in this static version
- The site maintains the look and feel of the original WordPress site
- Navigation links in blog post cards currently point to "#" placeholders

## Future Enhancements

Potential improvements could include:
- Individual blog post detail pages
- Search functionality
- Blog post filtering by category
- Contact form
- Newsletter signup
- Social media integration

## License

Content recreated from www.themacsabroad.com for demonstration purposes.
