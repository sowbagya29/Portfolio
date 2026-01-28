# Personal Portfolio Website

A  portfolio website showcasing my work, skills, and journey as Undergraduate student and interest in software and Tech feilds and Machine Learning enthusiast.

## Features

✨ **Sticky Header with Navigation**
- Fixed header that stays visible while scrolling
- Smooth scroll navigation to all sections
- Active link highlighting based on scroll position
- Mobile-responsive hamburger menu

🎨 **Personal Information Section**
- Professional photo display
- Name, role, and introduction
- Quick facts (languages, current role, interests)
- Downloadable resume button

🖼️ **Interactive Image Gallery**
- Masonry layout with hover zoom effects
- Lightbox popup for full-size viewing
- Keyboard navigation (arrow keys, ESC)
- Smooth transitions and animations

🌟 **Animated Hero Section**
- Text reveal animations
- Floating background shapes with parallax effect
- Smooth scroll indicator
- Call-to-action buttons

🌓 **Dark/Light Mode Toggle**
- Persistent theme preference (saved in localStorage)
- Smooth theme transitions
- Natural color palette for both themes

📱 **Fully Responsive Design**
- Mobile-first approach
- Optimized for all screen sizes
- Touch-friendly interactions

## Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with CSS variables, animations, and transitions
- **JavaScript (Vanilla)** - Interactive features and animations
- **Google Fonts** - Inter & Playfair Display for natural typography

## Getting Started

1. **Clone or download** this repository
2. **Add your resume PDF** to the `assets` folder and name it `resume.pdf`
3. **Update contact links** in `index.html`:
   - Replace GitHub and LinkedIn placeholder URLs with your actual profiles
4. **Open `index.html`** in your web browser

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── script.js           # Interactive features and functionality
├── assets/
│   ├── profile-photo.png  # Your profile photo
│   └── resume.pdf         # Your resume (add this)
└── README.md           # This file
```

## Customization

### Colors
Edit the CSS variables in `styles.css` under `:root` and `[data-theme="dark"]` to match your preferences.

### Content
- Update personal information in the About section
- Modify skills, projects, and gallery items in `index.html`
- Replace gallery images with your own (update URLs or add local images)

### Gallery Images
The gallery currently uses Unsplash images. To use your own:
1. Add images to the `assets/gallery/` folder
2. Update image `src` attributes in the gallery section of `index.html`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings → Pages
3. Select your branch and folder
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify
1. Drag and drop your portfolio folder to Netlify
2. Or connect your GitHub repository for automatic deployments

### Vercel
1. Import your GitHub repository
2. Vercel will automatically detect and deploy your site

## Notes

- The portfolio uses natural, organic design elements to feel handmade
- All animations are smooth and non-distracting
- The design is optimized for both desktop and mobile experiences
- Dark mode preference is saved in browser localStorage

## License

This portfolio is created for personal use. Feel free to use it as inspiration for your own portfolio!

---

**Built with care and attention to detail** ✨

