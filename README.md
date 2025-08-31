# THM Group Website

A complete responsive website for THM Group built with HTML, TailwindCSS, and vanilla JavaScript.

## 🚀 Features

### Global Layout
- **Sticky Navigation**: Clean navbar with THM Group logo and navigation links
- **Mobile Responsive**: Hamburger menu for mobile devices
- **Consistent Footer**: Copyright information across all pages

### Pages

#### 🏠 Home Page (`index.html`)
- Hero section with gradient background
- About THM Group section
- Three feature cards linking to Graphics, Media, and Solutions
- Responsive design with smooth animations

#### 🎨 THM Graphics (`graphics.html`)
- Creative design theme with vibrant colors
- Portfolio showcase with placeholder images
- Services: Logo Design, Branding, Posters, Social Media Graphics
- Purple/pink accent colors

#### 🎬 THM Media (`media.html`)
- Cinematic dark theme with overlay text
- Video production, livestreaming, and photography services
- Media showcase grid with sample projects
- Red/orange accent colors

#### 💻 THM Solutions (`solutions.html`)
- Futuristic tech theme with blue gradients
- Services: Web Development, Mobile Apps, IT Consulting
- Case studies and technology stack showcase
- Blue/cyan accent colors

#### 📞 Contact (`contact.html`)
- Contact form with Formspree integration
- Success message functionality
- Alternative contact methods
- FAQ section

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **TailwindCSS**: Utility-first CSS framework (via CDN)
- **Vanilla JavaScript**: No frameworks, pure JS
- **Formspree**: Form handling service
- **Responsive Design**: Mobile-first approach

## 📁 Project Structure

```
thm-group-website/
├── index.html          # Home page
├── graphics.html        # THM Graphics page
├── media.html          # THM Media page
├── solutions.html       # THM Solutions page
├── contact.html        # Contact page
├── assets/             # Assets directory
└── README.md           # Project documentation
```

## 🎨 Design Features

### Color Schemes
- **Home**: Blue gradient theme
- **Graphics**: Purple/pink vibrant colors
- **Media**: Dark cinematic theme with red/orange accents
- **Solutions**: Futuristic blue/cyan gradients
- **Contact**: Clean, professional design

### Responsive Features
- Mobile-first design approach
- Hamburger menu for mobile navigation
- Responsive grid layouts
- Touch-friendly interface

### Animations
- Smooth hover effects on cards and buttons
- CSS transitions for interactive elements
- Scale and transform animations

## 📱 Responsive Breakpoints

- **Mobile**: < 768px (hamburger menu)
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🚀 Deployment

### GitHub Pages
1. Upload all files to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Set source to main branch
4. Your site will be available at `https://username.github.io/repository-name`

### Static Hosting
- Upload all files to any static hosting service
- No build process required
- Works with Netlify, Vercel, AWS S3, etc.

## 📧 Form Integration

The contact form uses Formspree with the endpoint:
```
https://formspree.io/f/xeolkeyd
```

### Form Features
- Name, Email, Service Interest, and Message fields
- Client-side validation
- Success message display
- Form reset after successful submission

## 🔧 Customization

### Colors
Each page has its own color scheme defined in the TailwindCSS config:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#3B82F6',    // Blue
                secondary: '#1E40AF',  // Dark Blue
                accent: '#F59E0B'      // Orange
            }
        }
    }
}
```

### Content
- Update text content in HTML files
- Replace placeholder images in assets folder
- Modify contact information in contact.html

## 🌟 Key Features

### Navigation
- Sticky navigation bar
- Active page highlighting
- Mobile hamburger menu
- Smooth transitions

### Performance
- Optimized for fast loading
- Minimal JavaScript
- CDN-based TailwindCSS
- No external dependencies

### Accessibility
- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images
- Keyboard navigation support

## 📋 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test on multiple devices
5. Submit a pull request

## 📄 License

© 2025 THM Group. All rights reserved.

## 📞 Support

For questions or support, please contact:
- Email: solutionsthm@gmail.com (Solutions) / thmgraphics7@gmail.com (Graphics)
- Phone: +263 71 944 5193

---

**Built with ❤️ using HTML, TailwindCSS, and Vanilla JavaScript**
