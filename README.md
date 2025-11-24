# Flatty Landing Page

A modern, responsive landing page built with HTML5 and CSS3.

## 📁 Project Structure

```
SYMB Assignment/
├── index.html              # Main HTML file
├── src/
│   ├── assets/            # Images and media files
│   │   ├── Angelica.png
│   │   ├── chrome.png
│   │   ├── hero_section.png
│   │   ├── mail.png
│   │   ├── Michael.png
│   │   ├── mobile.png
│   │   ├── notes.png
│   │   └── Pete.png
│   └── styles/            # CSS stylesheets
│       └── styles.css
└── README.md
```

## ✨ Key Improvements

### 1. **Proper Folder Structure**
- ✅ Organized assets into `/src/assets/` directory
- ✅ Moved CSS to `/src/styles/` directory
- ✅ Fixed spelling: renamed `assests` → `assets`
- ✅ Clear separation of concerns

### 2. **Fully Responsive Design**
- ✅ **Mobile-first approach** with comprehensive media queries:
  - Desktop: 1024px and above
  - Tablet: 768px - 1023px
  - Mobile: 320px - 767px
  - Small mobile: up to 480px
- ✅ **Fluid typography** using `clamp()` for smooth scaling
- ✅ **Flexible layouts** with CSS Grid and Flexbox
- ✅ **Responsive images** that scale properly on all devices
- ✅ **Touch-friendly** button sizes on mobile
- ✅ **Stacked email forms** on small screens for better UX

### 3. **Optimized Images**
- ✅ Proper `object-fit` properties for consistent display
- ✅ Lazy loading for images (`loading="lazy"`)
- ✅ Responsive image sizing with `max-width` constraints
- ✅ Proper aspect ratios maintained
- ✅ Fixed hero image overflow issues

### 4. **Best Practices Implemented**

#### **Semantic HTML**
- ✅ Used `<header>`, `<footer>`, `<nav>`, `<article>` tags
- ✅ Proper heading hierarchy
- ✅ Forms with proper semantic structure

#### **Accessibility (A11y)**
- ✅ ARIA labels and landmarks
- ✅ Descriptive alt text for images
- ✅ Focus states for interactive elements
- ✅ Keyboard navigation support
- ✅ Proper form labels

#### **Modern CSS**
- ✅ **CSS Custom Properties** (CSS variables) for maintainability
- ✅ **Smooth transitions** and hover effects
- ✅ **Consistent spacing system** using CSS variables
- ✅ **Modern layout techniques** (Grid, Flexbox)
- ✅ **Clamp()** for responsive font sizing

#### **Performance**
- ✅ Optimized font loading with `preconnect`
- ✅ Image lazy loading
- ✅ Efficient CSS with no redundancy
- ✅ Print styles for better printing

#### **Code Quality**
- ✅ Clean, organized CSS with section comments
- ✅ Consistent naming conventions
- ✅ Well-structured HTML
- ✅ No inline styles

## 🎨 Design Features

- **Color System**: Organized color palette using CSS variables
- **Typography**: Google Fonts (Lato) with scalable sizing
- **Spacing**: Consistent spacing scale (xs, sm, md, lg, xl, 2xl)
- **Interactive Elements**: Hover, focus, and active states
- **Smooth Animations**: Subtle transitions for better UX

## 🚀 How to Use

1. Open `index.html` in any modern web browser
2. The page is fully responsive - resize your browser to see it adapt
3. All forms have proper validation

## 📱 Responsive Breakpoints

| Breakpoint | Width | Description |
|------------|-------|-------------|
| Desktop | ≥1024px | Full layout with side-by-side content |
| Tablet | 768px - 1023px | Adjusted spacing and stacked hero |
| Mobile | ≤767px | Single column, stacked forms |
| Small Mobile | ≤480px | Optimized for small screens |

## 🎯 Features

- ✅ Responsive navigation
- ✅ Hero section with CTA
- ✅ Feature cards grid
- ✅ Team member showcase
- ✅ Newsletter signup forms
- ✅ Contact form
- ✅ Social media links
- ✅ Cross-browser compatible

## 🔧 Technical Details

- **HTML5** with semantic markup
- **CSS3** with modern features
- **No JavaScript dependencies** (pure HTML/CSS)
- **No build process required**
- **Works on all modern browsers**

## 📝 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎓 Best Practices Followed

1. **Separation of Concerns**: HTML structure, CSS styling clearly separated
2. **DRY Principle**: CSS variables for repeated values
3. **Mobile-First**: Responsive design from smallest to largest screens
4. **Accessibility**: WCAG guidelines followed
5. **Performance**: Optimized loading and rendering
6. **Maintainability**: Well-organized, commented code
7. **Scalability**: Easy to extend and modify

## 📄 License

This is an assignment project for educational purposes.

---

**Built with ❤️ using modern web standards**
