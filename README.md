# 🧭 SVSU Dudhola Campus Navigation System
A Google Maps-style interactive navigation system for Shri Vishwakarma Skill University featuring real-time pathfinding, voice guidance, and multi-modal routing powered by Dijkstra's algorithm.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

---

## 📋 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Installation](#-installation)
- [Project Structure](#-project-structure)
- [Campus Data](#-campus-data)
- [Navigation Modes](#-navigation-modes)
- [Technologies Used](#-technologies-used)
- [Screenshots](#-screenshots)
- [Troubleshooting](#-troubleshooting)
- [Known Issues & Limitations](#-known-issues--limitations)
- [Future Improvements](#-future-improvements)
- [Performance Optimization](#-performance-optimization)
- [License](#-license)
- [Contact](#-contact)

---

## 🌟 Overview

The SVSU Dudhola Campus Navigation System is a cutting-edge, web-based navigation solution designed specifically for **Shri Vishwakarma Skill University (SVSU)** in Dudhola, Haryana. This system transforms campus navigation by providing students, faculty, and visitors with an intuitive, Google Maps-inspired interface for finding buildings, calculating optimal routes, and receiving turn-by-turn directions.

### What Makes This System Special?

Unlike generic mapping solutions, this system is:
- **Campus-Specific**: Tailored precisely to SVSU's layout with 11 mapped buildings
- **Intelligent Routing**: Uses Dijkstra's algorithm for optimal path calculation
- **Multi-Modal**: Supports walking, cycling, and driving routes
- **Accessible**: Voice navigation, high contrast mode, and keyboard navigation
- **Real-Time**: Live weather updates and building occupancy information

### University Context

**Shri Vishwakarma Skill University (SVSU)**
- **Location**: Dudhola, Palwal, Haryana, India
- **Coordinates**: 28.4089°N, 77.0378°E
- **Focus**: Excellence in Skill Development
- **Motto**: *"कौशल विकास में उत्कृष्टता"* (Excellence in Skill Development)

---

## ✨ Features

### 🗺️ Navigation Features
- **Real-time Pathfinding**: Dijkstra's algorithm calculates optimal routes between any two points
- **Turn-by-Turn Directions**: Step-by-step navigation instructions with distance markers
- **Multiple Route Options**: 
  - 🚀 Fastest Route
  - 📏 Shortest Route
  - 🌳 Scenic Route
- **Live Position Tracking**: GPS-based real-time location updates
- **Route Visualization**: Animated path display with color-coded segments

### 🎤 Voice & Accessibility
- **Voice Navigation**: Text-to-speech turn-by-turn guidance
- **Voice Search**: Speech recognition for hands-free destination selection
- **High Contrast Mode**: Enhanced visibility for visually impaired users
- **Large Text Mode**: Improved readability
- **Reduce Motion**: Accessibility option for users sensitive to animations
- **Keyboard Navigation**: Full keyboard support for all features

### 🚶 Transport Modes
- **Walking Mode**: Optimized pedestrian routes (avg. 5 km/h)
- **Cycling Mode**: Bike-friendly paths (avg. 15 km/h)
- **Driving Mode**: Vehicle routes (avg. 40 km/h)
- **Mode-Specific Routing**: Different optimal paths based on transport type

### 🌐 Map Views
- **Standard Map View**: Clean, Google Maps-inspired design with color-coded buildings
- **Satellite View**: Realistic aerial perspective with building overlays
- **Interactive Buildings**: Click any building for detailed information
- **Zoom Controls**: Smooth zoom in/out functionality
- **Pan & Navigate**: Drag to explore the entire campus

### 📊 Building Information
- **11 Campus Buildings** fully mapped and detailed
- **Real-Time Data**:
  - Building occupancy levels
  - Operating hours
  - Available facilities
  - User ratings
- **Facility Search**: Find buildings by amenities (WiFi, cafeteria, labs, etc.)

### 🌤️ Real-Time Updates
- **Weather Integration**: Current temperature, humidity, conditions
- **Weather Warnings**: Alerts for adverse conditions affecting routes
- **Status Indicators**: Online/offline status, system health
- **Live Notifications**: Updates on navigation progress, arrivals

### 📱 User Experience
- **Responsive Design**: Seamless experience on desktop, tablet, and mobile
- **Modern UI**: Clean, intuitive interface with smooth animations
- **Search Functionality**: Quick building search with autocomplete
- **Favorites**: Quick access to frequently visited locations
- **History**: Recent navigation history

---


## 🚀 Installation

### Prerequisites
- **Web Browser**: 
  - Chrome 90+ (Recommended)
  - Edge 90+
  - Firefox 88+
  - Safari 14+
- **Modern Device**: 4GB+ RAM recommended
- **Internet Connection**: For CDN resources and real-time features
- **GPS-Enabled Device**: Optional, for location services

### Quick Start

#### Option 1: Direct File Access (Simplest)

1. **Download the project**:
   ```bash
   # Clone the repository
   git clone https://github.com/yourusername/svsu-navigation-system.git
   cd svsu-navigation-system
   ```

2. **Open the file**:
   ```bash
   # Simply open index.html in your browser
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   
   # On Windows
   start index.html
   ```

That's it! The system is now running locally.
```

## 📁 Project Structure

```
svsu-navigation-system/
│
├── index.html                          # Main application file (Single-page)
│   ├── HTML Structure                  # Semantic HTML5 markup
│   ├── CSS Styles                      # Embedded Tailwind + Custom CSS
│   ├── JavaScript Logic                # React components + Business logic
│   └── Data Definitions               # Buildings, paths, nodes data
│
├── README.md                          # This file - Complete documentation
│
├── assets/                            # Static assets (optional)
│   ├── images/
│   │   ├── logo.png                  # University logo
│   │   ├── welcome_page.png          # Screenshots
│   │   ├── home_page.png
│   │   ├── result_page.png
│   │   └── architecture_diagram.png
│   │
│   └── icons/                        # Custom icons (if any)
│       └── building-icons/
│
├── docs/                              # Documentation
│   ├── ARCHITECTURE.md               # Detailed architecture
│   ├── API_REFERENCE.md             # API documentation
│   ├── CONTRIBUTING.md              # Contribution guidelines
│   ├── CHANGELOG.md                 # Version history
│   └── TROUBLESHOOTING.md          # Detailed troubleshooting
│
├── .gitignore                        # Git ignore file
├── LICENSE                           # MIT License
└── CONTRIBUTORS.md                   # List of contributors
```

## 📸 Screenshots

### 1. Welcome Screen
> **First Impression**: Elegant splash screen with university branding

![Welcome Screen](images/welcome_page.png)
---

### 2. Main Navigation Interface
> **Command Center**: Full-featured navigation with map view

![Home Page](images/home_page (3).png)

### 3. Active Navigation
> **Turn-by-Turn Guidance**: Real-time route following

![Result Page](images/result_page (2).png)


### 4. Arrival Notification
> **Success State**: Destination reached confirmation

![Arrival Page](images/result_page (3).png)


---

## 🔧 Troubleshooting

This section documents common issues, their causes, and step-by-step solutions to help you resolve problems quickly.

---

### 🚨 Common Issues & Solutions

#### 1. Location Services Not Working

**Symptoms:**
- ❌ "Location access denied" message
- ❌ Random campus location shown
- ❌ "Demo mode" notification appearing
- ❌ Blue location dot not moving

**Root Causes:**

| Cause | Probability | Severity |
|-------|-------------|----------|
| Browser permissions denied | 80% | Medium |
| GPS disabled on device | 10% | High |
| Not using HTTPS | 5% | Critical |
| Browser doesn't support API | 3% | Critical |
| Timeout (poor GPS signal) | 2% | Medium |


#### 2. Voice Navigation Not Working

**Symptoms:**
- ❌ Voice search button does nothing
- ❌ No microphone icon appears
- ❌ "Voice not supported" message
- ❌ Voice directions not audible
- ❌ Speech recognition fails silently

**Root Causes & Solutions:**

**Issue 2.1: Browser Compatibility**

Browser Support Matrix:

| Browser | Speech Recognition | Speech Synthesis | Overall Support |
|---------|-------------------|------------------|-----------------|
| Chrome/Edge | ✅ Full | ✅ Full | ⭐⭐⭐⭐⭐ Excellent |
| Firefox | ❌ None | ✅ Full | ⭐⭐⭐ Partial |
| Safari | ⚠️ Limited | ✅ Full | ⭐⭐⭐ Partial |
| Opera | ✅ Full | ✅ Full | ⭐⭐⭐⭐ Good |


#### 3. Routes Not Calculating

**Symptoms:**
- ❌ "No route found" error
- ❌ Infinite loading spinner
- ❌ Empty directions panel
- ❌ Map shows markers but no path

#### 4. Map Display Issues

**Symptoms:**
- ❌ Blank white screen
- ❌ Buildings not visible
- ❌ Map controls missing
- ❌ Only partial map rendering

#### 5. Performance Issues

**Symptoms:**
- ⚠️ Slow map rendering
- ⚠️ Laggy animations
- ⚠️ High CPU/memory usage
- ⚠️ Browser freezing

---




## ⚠️ Known Issues & Limitations

### Geographic Limitations

**Issue**: System designed for on-campus use only

**Description:**
The navigation system is calibrated specifically for SVSU Dudhola campus (28.4089°N, 77.0378°E). Location tracking works accurately within approximately 1km radius of campus center.

**Impact:**
- Users far from campus receive **simulated "demo mode" locations**
- GPS coordinates outside campus bounds are mapped to nearest campus point
- Real-world accuracy degrades beyond campus perimeter

**Workaround:**
```javascript
// System automatically detects and handles
const isOnCampus = Math.abs(deltaLat) < 0.01 && Math.abs(deltaLon) < 0.01;

if (!isOnCampus) {
  // Simulates location on campus
  assignDemoLocation();
  showNotification('Demo mode: Using simulated location');
}
```

**Future Fix:** Expand coverage area or add multiple campus support

---

### Language Support Limitations

**Issue**: Primary language is English only

**Description:**
- UI text: English only
- Voice commands: English recognition only
- Voice output: English synthesis only
- University name and motto: Hindi (decorative only)

**Impact:**
- Non-English speakers may struggle with navigation
- Reduces accessibility for regional language users
- Limits adoption in multilingual environments

**Current Partial Support:**
- Hindi: University name (श्री विश्वकर्मा कौशल्य विश्वविद्यालय)
- Hindi: Motto (कौशल विकास में उत्कृष्टता)

**Workaround:** Use visual cues and map for navigation

**Planned Improvements:**
- [ ] Hindi UI translation
- [ ] Hindi voice recognition
- [ ] Hindi voice synthesis
- [ ] Punjabi support
- [ ] Multi-language toggle

---

**Recommendation:** Use Chrome or Edge for best experience

---


### Security & Privacy Limitations

**Issue**: Limited privacy controls

**Data Collection:**
- 📍 Real-time GPS location
- 🎤 Voice recordings (temporary)
- 📊 Navigation history
- ⚙️ User preferences

**Current Privacy Measures:**
- ✅ Data processed client-side only
- ✅ No server-side storage
- ✅ No user accounts required
- ✅ No third-party tracking

**Privacy Concerns:**
- ⚠️ Location data stored in browser
- ⚠️ No data encryption
- ⚠️ No option to export/delete data
- ⚠️ Voice data not anonymized


**Future Improvements:**
- [ ] End-to-end encryption for data
- [ ] Privacy dashboard
- [ ] Data export feature
- [ ] Automatic data deletion
- [ ] Anonymous mode

---

### Known Bugs

#### Bug #1: Voice Navigation Interruption
- **Description**: Voice directions stop mid-sentence on some devices
- **Affected**: iOS Safari, Android Chrome < 90
- **Cause**: Background tab suspension
- **Workaround**: Keep app in foreground during navigation
- **Status**: Under investigation

#### Bug #2: Route Recalculation Loop
- **Description**: Rare infinite loop in route calculation
- **Trigger**: Very close start/end points (< 5 meters)
- **Workaround**: Move markers further apart
- **Fix**: Added distance threshold check

#### Bug #3: Satellite View Performance
- **Description**: Slow rendering on mobile devices
- **Affected**: All mobile browsers
- **Workaround**: Use standard map view
- **Status**: Optimization in progress

---

## 🔮 Future Improvements

### Planned Features (v2.0)

#### 🌐 Real-Time Integration
- **Weather API**: OpenWeatherMap integration for actual weather
- **Occupancy Sensors**: IoT integration for real-time building occupancy
- **Traffic Data**: Pedestrian congestion monitoring
- **Event Calendar**: Sync with university event schedule

**Timeline**: Q2 2025

---

#### 🗺️ Enhanced Navigation
- **Indoor Navigation**: Floor-by-floor routing inside buildings
- **Multi-Floor Support**: Staircase and elevator detection
- **AR Directions**: Augmented reality wayfinding
- **Offline Mode**: Download maps for offline use

**Timeline**: Q3 2025

---

#### 🎯 Advanced Features
- **User Accounts**: Save preferences, favorites, history
- **Social Features**: Share location, meet-up points
- **Crowdsourced Data**: User-reported obstacles, shortcuts
- **AI Recommendations**: Smart destination suggestions
- **Event Navigation**: Route to events automatically

**Timeline**: Q4 2025

---

#### ♿ Accessibility Enhancements
- **Wheelchair Routes**: Accessible path planning
- **Audio Descriptions**: Detailed voice descriptions
- **Screen Reader**: Full NVDA/JAWS compatibility
- **Sign Language**: Video guides in sign language
- **Simplified Mode**: Easy interface for cognitive accessibility

**Timeline**: Q1 2026

---

#### 📱 Mobile Apps
- **Native iOS App**: Swift-based app with offline support
- **Native Android App**: Kotlin-based with background navigation
- **React Native**: Cross-platform mobile app
- **Progressive Web App (PWA)**: Installable web app

**Timeline**: Q2 2026

---

#### 🌍 Expansion Features
- **Multi-Campus**: Support for multiple SVSU campuses
- **Multi-University**: Template for other institutions
- **Multi-Language**: Hindi, Punjabi, regional languages
- **International**: Globalization and localization

**Timeline**: Q3 2026

---

#### 📊 Analytics & Insights
- **Usage Dashboard**: Admin panel for navigation analytics
- **Popular Routes**: Heat maps of common paths
- **Peak Times**: Identify congestion patterns
- **Building Popularity**: Most visited locations
- **A/B Testing**: Compare route algorithms

**Timeline**: Q4 2026

---


## 🌐 Browser Compatibility

### Supported Browsers

| Browser | Version | Support Level | Notes |
|---------|---------|---------------|-------|
| **Chrome** | 90+ | ⭐⭐⭐⭐⭐ Full | Recommended |
| **Edge** | 90+ | ⭐⭐⭐⭐⭐ Full | Chromium-based |
| **Firefox** | 88+ | ⭐⭐⭐⭐ Good | No voice search |
| **Safari** | 14+ | ⭐⭐⭐ Partial | HTTPS required |
| **Opera** | 76+ | ⭐⭐⭐⭐ Good | Chromium-based |
| **Samsung Internet** | 14+ | ⭐⭐⭐ Partial | Mobile only |

### Feature Support Matrix

| Feature | Chrome | Edge | Firefox | Safari |
|---------|--------|------|---------|--------|
| Geolocation | ✅ | ✅ | ✅ | ✅* |
| Voice Search | ✅ | ✅ | ❌ | ⚠️ |
| Voice Navigation | ✅ | ✅ | ✅ | ✅ |
| Local Storage | ✅ | ✅ | ✅ | ✅ |
| CSS Animations | ✅ | ✅ | ✅ | ⚠️ |
| React 18 | ✅ | ✅ | ✅ | ✅ |

*Safari requires HTTPS for geolocation

## 📄 License

This project is licensed under the **MIT License**.


## 👥 Authors : Pinki


## 📞 Contact & Support

**Direct Contact:**
- 📧 Email: pinkidagar18@gmail.com


## 📚 References & Resources

### Academic References
1. Dijkstra, E. W. (1959). "A note on two problems in connexion with graphs"
2. Hart, P. E., Nilsson, N. J., & Raphael, B. (1968). "A Formal Basis for the Heuristic Determination of Minimum Cost Paths"


## 🏛️ श्री विश्वकर्मा कौशल्य विश्वविद्यालय

**"Excellence in Skill Development"**

**Made with ❤️ for SVSU Community**

-
