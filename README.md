# Netflix Clone Landing Page

A modern, responsive Netflix-inspired landing page built with HTML5 and CSS3. This project replicates the visual design and layout of Netflix's streaming platform homepage with a focus on clean aesthetics and user engagement.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Future Enhancements](#future-enhancements)
- [License](#license)

## 🎯 Overview

This Netflix clone is a front-end landing page that captures the essence of Netflix's user interface. It features a promotional banner, navigation bar with language selection, sign-in functionality, and an engaging hero section designed to drive user conversions and subscription sign-ups.

The project demonstrates modern web design principles including responsive design, gradient effects, and semantic HTML structure.

## ✨ Features

### Current Features
- **Sticky Promotional Banner**: Eye-catching gradient banner offering a 7-day free trial at the top of the page
- **Hero Section**: Full-height background image with gradient overlay for visual depth
- **Navigation Bar**: Professional navbar with:
  - Netflix logo branding
  - Multi-language support (English, Telugu, Hindi)
  - Sign-in button with distinctive styling
- **Subscription Call-to-Action**: Prominent heading section promoting unlimited content with pricing information
- **Responsive Design**: Clean, professional layout that adapts to different screen sizes
- **Modern Styling**: Gradient effects and smooth visual hierarchy using CSS3

## 📁 Project Structure

```
net/
├── net.html          # Main HTML file with page structure
├── net.css           # Styling and layout definitions
├── netflix_bg.jpg    # Hero background image (referenced in CSS)
└── README.md         # Project documentation
```

### File Descriptions

| File | Purpose |
|------|---------|
| `net.html` | Contains the semantic HTML structure of the landing page |
| `net.css` | Defines all visual styling, layouts, and responsive behavior |
| `netflix_bg.jpg` | Background image for the hero section |

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for page structure
- **CSS3**: Advanced styling with:
  - CSS Gradients (linear gradients for visual effects)
  - Flexbox for layout management
  - Fixed positioning for sticky elements
  - CSS variables and modern selectors
- **Responsive Web Design**: Viewport meta tag and flexible units (vw, vh)

## 🚀 Setup & Installation

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or build tools required

### Steps

1. **Clone or Download the Repository**
   ```bash
   git clone <https://github.com/HARISHKAMIREDDI/netflix-clone>
   cd net
   ```

2. **Add the Background Image**
   - Place a Netflix-style background image in the project folder
   - Name it `netflix_bg.jpg` or update the path in `net.css`
   - Recommended: Use a high-quality movie/entertainment background image (1920x1080 or higher)

3. **Open in Browser**
   - Double-click `net.html` or
   - Right-click → Open with → Browser
   - Or use a local server for better performance:
     ```bash
     python -m http.server 8000
     # Then visit http://localhost:8000
     ```

## 💻 Usage

The landing page is immediately ready to use. Users can:

1. **View the Promotional Banner**: See the free trial offer at the top
2. **Select Language**: Choose from English, Telugu, or Hindi
3. **Sign In**: Click the Sign In button to proceed (currently a placeholder)
4. **Browse Subscription Info**: View pricing and subscription details
5. **Call-to-Action**: See the invitation to enter email for membership

## 🎨 Customization

### Changing Colors
Edit `net.css` to modify:
- **Primary Red**: Change `background-color: red;` in `.signin button`
- **Logo Color**: Modify `.logo { color: red; }`
- **Gradient**: Update the `linear-gradient()` values in `.sticky` and `.hero`

### Modifying Content
Edit `net.html` to:
- Update the Netflix logo text or brand name
- Change subscription pricing (currently ₹149)
- Modify promotional offers and copy
- Add more language options

### Responsive Breakpoints
Add media queries to `net.css` for mobile optimization:
```css
@media (max-width: 768px) {
    /* Mobile-specific styles */
    .navbar { padding: 10px 20px; }
    .head { top: 150px; }
}
```

## 🌐 Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full Support |
| Firefox | ✅ Full Support |
| Safari | ✅ Full Support |
| Edge | ✅ Full Support |
| IE 11 | ⚠️ Limited Support |

## 🔮 Future Enhancements

### Planned Features
- [ ] **Mobile Responsive Design**: Add comprehensive media queries for tablets and mobile devices
- [ ] **Interactive Elements**: Add hover effects and transitions
- [ ] **Email Subscription Form**: Functional email input for membership signup
- [ ] **Movie Grid**: Display featured movies/shows with thumbnails
- [ ] **User Authentication**: Implement sign-in functionality
- [ ] **Multiple Language Support**: Full UI localization
- [ ] **Accessibility**: ARIA labels, keyboard navigation, screen reader support
- [ ] **Performance Optimization**: Image lazy loading, minification
- [ ] **Dark/Light Theme Toggle**: User preference switching
- [ ] **Backend Integration**: API connections for dynamic content

### Code Improvements
- Extract CSS to SCSS for better maintainability
- Add CSS custom properties for theming
- Implement BEM methodology for class naming
- Add JavaScript for interactivity
- Create component-based structure

## 📝 License

This project is created for educational and portfolio purposes. Netflix is a registered trademark of Netflix, Inc. This is a fan project and is not affiliated with Netflix.

---

## 📞 Contact & Support

For questions or suggestions, please feel free to reach out or open an issue.

**Author**: HARISHKAMIREDDI  
**Repository**: [netflix_clone](https://github.com/HARISHKAMIREDDI/netflix_clone)

---

**Last Updated**: 2026-07-22  
**Version**: 1.0.0