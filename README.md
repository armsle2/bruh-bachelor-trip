# Bruh Bachelor Trip - Cartagena 2025

A sophisticated landing page for Devin's bachelor party trip to Cartagena, Colombia (August 13-17, 2025).

## 🌴 Features

- **Responsive Design** - Optimized for mobile and desktop viewing
- **Interactive Carousels** - Swipeable image galleries for villa and yacht
- **Live Activity Poll** - Real-time voting system for trip activities  
- **Travel Information** - Comprehensive packing and logistics guide
- **Countdown Timer** - Live countdown to departure date
- **Dark/Gold Theme** - Sophisticated "grown & sexy" aesthetic
- **AI-Powered Features** - Colombian slang generator using Gemini API

## 🏗️ Tech Stack

- **HTML5** - Semantic markup structure
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Vanilla JavaScript** - Interactive functionality
- **Firebase** - Real-time database for polls and user management
- **Google Gemini API** - AI-powered content generation
- **Cloudinary** - Image hosting and optimization

## 🚀 Deployment

This site is deployed using GitHub Pages with a custom domain.

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/bruh-bachelor-trip.git
cd bruh-bachelor-trip
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .
```

3. Visit `http://localhost:8000` to view the site

### GitHub Pages Setup

1. Go to repository Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main` (or your preferred branch)
4. Folder: `/ (root)`
5. Add your custom domain in the "Custom domain" field

## 📱 Mobile Features

- **Touch/Swipe Navigation** - Intuitive carousel controls
- **Responsive Dot Indicators** - Visual navigation cues
- **Optimized Typography** - Scalable text for all screen sizes
- **Touch-Friendly Buttons** - Properly sized interactive elements

## 🎯 Key Sections

1. **Hero Section** - Main title with countdown timer
2. **The Grand Plan** - Trip dates, location, and vibe overview
3. **A Taste of What's to Come** - Highlights and quick navigation
4. **Villa Accommodation** - Luxury villa showcase with image carousel
5. **Private Yacht** - Yacht excursion details with media gallery
6. **Travel Information** - Essential logistics and packing guide
7. **Activity Poll** - Interactive preference voting system
8. **Cartagena Insights** - AI-powered local recommendations

## 🔧 Configuration

### Firebase Setup
Update the Firebase configuration in the script section:
```javascript
const firebaseConfig = {
  // Your Firebase config
};
```

### Gemini API Setup
Add your Gemini API key for the slang generator feature:
```javascript
const apiKey = "your-gemini-api-key";
```

## 🎨 Customization

The site uses a consistent color scheme:
- **Primary**: Gold (#fbd38d) 
- **Background**: Dark gray (#1a202c)
- **Cards**: Medium gray (#2d3748)
- **Text**: Light gray (#e2e8f0)

## 📸 Image Management

All images are hosted on Cloudinary for optimal performance:
- Villa images: Airbnb property photos
- Yacht images: Private charter photos  
- Hero background: Custom groom photo

## 🤝 Contributing

This is a private repository for the bachelor party group. If you need access or want to suggest changes, contact the repository owner.

## 📄 License

Private project - All rights reserved.

---

**Trip Details:**
- **Dates**: August 13-17, 2025
- **Location**: Cartagena, Colombia  
- **Vibe**: Grown, Sexy, Unforgettable
- **Accommodation**: 12-bedroom luxury villa
- **Activities**: Private yacht, nightlife, dining, adventures

*Built with ❤️ for an epic bachelor party* 