# NextCar - Premium Super Car Website

A modern, responsive web application showcasing premium supercars with interactive features and smooth animations. Built with vanilla JavaScript, HTML, and CSS for optimal performance.

## 🚗 Features

- **Responsive Design** - Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Interactive Navigation** - Smooth mobile-friendly navigation menu with toggle functionality
- **Video Slider** - Dynamic video carousel for showcasing supercars with smooth transitions
- **Car Filtering** - MixItUp integration for filtering and sorting supercars by category
- **Scroll Animations** - Scroll reveal animations that bring content to life as users scroll
- **Swiper Carousel** - High-performance carousel functionality for image/content sliders
- **Firebase Integration** - Backend connectivity for dynamic data and features
- **Smooth Scrolling** - Enhanced user experience with smooth scroll header effects
- **Modern UI/UX** - Clean, professional design with Remix Icons

## 📁 Project Structure

```
carwebsite/
├── index.html                          # Main HTML file
├── README.md                           # This file
└── assests/
    ├── css/
    │   ├── style.css                   # Main stylesheet
    │   ├── swiper-bundle.min.css       # Swiper carousel styles
    │   └── myCustom.css                # Custom styles
    ├── img/                            # Image assets
    ├── js/
    │   ├── main.js                     # Core JavaScript functionality
    │   ├── firebase.js                 # Firebase configuration
    │   ├── swiper-bundle.js            # Swiper carousel library
    │   ├── mixitup.js                  # Filtering library
    │   └── scrollrevelAnimation.min.js # Scroll animations
    └── video/                          # Video assets
```

## 🎨 Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with animations and transitions
- **JavaScript (Vanilla)** - No framework dependencies for lightweight performance
- **[Swiper](https://swiperjs.com/)** - Mobile-friendly carousel/slider
- **[MixItUp](https://www.kunkalabs.com/mixitup/)** - Content filtering and sorting
- **[Remix Icons](https://remixicon.com/)** - Icon library
- **[ScrollReveal](https://scrollrevealjs.org/)** - Scroll animation library
- **Firebase** - Backend services

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML, CSS, and JavaScript
- Firebase account (if using backend features)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/carwebsite.git
   cd carwebsite
   ```

2. **Open in browser:**
   - Simply open `index.html` in your preferred web browser
   - Or use a local server for better performance:
     ```bash
     python -m http.server 8000
     # or with Node.js
     npx http-server
     ```

3. **Configure Firebase (Optional):**
   - Update `assests/js/firebase.js` with your Firebase credentials
   - Enable required Firebase services in your Firebase console

## 📄 File Descriptions

| File | Purpose |
|------|---------|
| `index.html` | Main page structure with header, navigation, and content sections |
| `assests/css/style.css` | Primary stylesheet for layout and components |
| `assests/js/main.js` | Core functionality including menu toggle, scroll effects, and video slider |
| `assests/js/firebase.js` | Firebase configuration and backend integration |
| `assests/js/swiper-bundle.js` | Carousel/slider functionality |
| `assests/js/mixitup.js` | Car filtering and sorting |
| `assests/js/scrollrevelAnimation.min.js` | Scroll-triggered animations |

## 🎯 Key Functionality

### Navigation Menu
- Toggle menu on mobile devices
- Smooth scrolling to sections
- Active link highlighting
- Scroll-dependent header styling

### Video Slider
- Manual navigation buttons for video selection
- Auto-play functionality
- Smooth transitions between slides

### Car Display
- Filtered view of supercars by category
- Smooth filter transitions with MixItUp
- Responsive grid layout

### Animations
- Scroll reveal effects for content
- Smooth header transitions
- Hover animations on interactive elements

## 🔧 Customization

### Modify Colors & Styling
Edit `assests/css/style.css` to customize:
- Color scheme
- Typography
- Spacing and layout
- Animation timing

### Update Car Data
Modify `index.html` to add/remove cars in the featured and popular sections

### Adjust Animations
- Fine-tune scroll animations in the ScrollReveal configuration
- Adjust Swiper settings for carousel behavior

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues and enhancement requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

**AbdullahMoin** - Full Stack Developer

## 📞 Contact & Support

For questions or support, please open an issue on GitHub or contact the repository maintainer.

## 🙏 Acknowledgments

- Thanks to the amazing open-source communities behind Swiper, MixItUp, and ScrollReveal
- Icons provided by Remix Icons
- Inspired by modern web design patterns

---

**Happy coding! 🚗💨**
