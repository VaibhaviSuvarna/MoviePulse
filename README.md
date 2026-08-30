# 🎬 MoviePulse

A modern, interactive movie discovery application built with React and Vite. Browse popular movies, build your personalized watchlist, and discover new films with an intuitive and responsive interface.

**Live Demo:** [https://vaibhavisuvarna.github.io/MoviePulse/](https://vaibhavisuvarna.github.io/MoviePulse/)

---

## 🌟 Features

- **Movie Discovery**: Browse a curated collection of popular movies with stunning visuals
- **Search & Filter**: Easily search for movies and filter results to find exactly what you're looking for
- **Watchlist Management**: 
  - Add movies to your personal watchlist
  - Remove movies from your watchlist
  - Persistent storage using browser's localStorage
- **Responsive Design**: Seamless experience across desktop, tablet, and mobile devices
- **Movie Details**: View comprehensive information about each movie
- **Pagination**: Navigate through large movie lists efficiently
- **Banner Display**: Eye-catching banner featuring highlighted content

---

## 🛠️ Tech Stack

- **Frontend Framework**: React 18
- **Build Tool**: Vite
- **Routing**: React Router v7
- **Styling**: Tailwind CSS
- **HTTP Client**: Axios
- **State Management**: React Hooks
- **Code Quality**: ESLint
- **Deployment**: GitHub Pages

---

## 📁 Project Structure

```
MoviePulse/
├── src/
│   ├── Components/
│   │   ├── Banner.jsx          # Hero banner component
│   │   ├── Navbar.jsx          # Navigation bar
│   │   ├── Movies.jsx          # Movies listing page
│   │   ├── MovieCard.jsx       # Individual movie card
│   │   ├── WatchList.jsx       # Watchlist page
│   │   └── Pagination.jsx      # Pagination controls
│   ├── Utility/                # Utility functions
│   ├── assets/                 # Static assets
│   ├── App.jsx                 # Main App component
│   ├── main.jsx                # Entry point
│   ├── App.css                 # App styles
│   └── index.css               # Global styles
├── public/                     # Public assets
├── package.json                # Project dependencies
├── vite.config.js              # Vite configuration
├── tailwind.config.js          # Tailwind CSS config
├── eslint.config.js            # ESLint rules
└── index.html                  # HTML template
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/VaibhaviSuvarna/MoviePulse.git
   cd MoviePulse
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```
   The application will open in your browser at `http://localhost:5173`

---

## 📦 Available Scripts

- **`npm run dev`** - Start the development server with hot module replacement
- **`npm run build`** - Build the application for production
- **`npm run lint`** - Run ESLint to check code quality
- **`npm run preview`** - Preview the production build locally
- **`npm run deploy`** - Deploy the application to GitHub Pages

---

## 🎯 Key Components

### **App.jsx**
Main component that manages:
- Watchlist state
- Add/remove from watchlist functions
- Routing between home and watchlist pages
- Local storage persistence

### **Movies.jsx**
Displays the main movie browsing page with:
- Movie grid layout
- Search and filter functionality
- Add to watchlist buttons
- Pagination support

### **MovieCard.jsx**
Individual movie card showing:
- Movie poster image
- Title and rating
- Add/remove watchlist button
- Movie details

### **WatchList.jsx**
Dedicated watchlist page featuring:
- Sorted and filtered watchlist items
- Remove from watchlist functionality
- Persistent storage management
- Genre-based filtering

### **Navbar.jsx**
Navigation component with:
- App branding
- Navigation links
- Watchlist counter
- Responsive mobile menu

### **Banner.jsx**
Hero banner component displaying:
- Featured content
- Eye-catching visuals
- Call-to-action elements

### **Pagination.jsx**
Navigation for large lists:
- Page controls
- Previous/Next buttons
- Current page indicator

---

## 💾 Data Persistence

MoviePulse uses the browser's `localStorage` to persist your watchlist. This means:
- Your watchlist is saved locally on your device
- Data persists even after closing the browser
- No backend server required for basic functionality

---

## 🎨 Styling

The application uses **Tailwind CSS** for styling, providing:
- Responsive grid layouts
- Dark mode compatible design
- Smooth animations and transitions
- Consistent color scheme throughout

---

## 📱 Responsive Design

The application is fully responsive and works seamlessly on:
- Desktop browsers (1920px and up)
- Tablets (768px to 1024px)
- Mobile phones (320px to 767px)

---

## 🔄 State Management

The app uses React Hooks for state management:
- **useState**: For managing watchlist and UI state
- **useEffect**: For loading watchlist from localStorage on mount
- **useContext** (if needed): For global state sharing

---

## 🚢 Deployment

The project is configured for deployment to GitHub Pages:

```bash
npm run build
npm run deploy
```

View the live site at: https://vaibhavisuvarna.github.io/MoviePulse/

---

## 📄 License

This project is open source and available under the MIT License.

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📧 Contact

**Author**: [Vaibhavi Suvarna](https://github.com/VaibhaviSuvarna)

For questions or feedback, feel free to open an issue or contact me through GitHub.

---

## 🙏 Acknowledgments

- Movie data sourced from TMDB/IMDB APIs
- Built with modern web technologies
- Inspired by popular movie streaming platforms
- Thanks to the React and Vite communities

---

**Happy Movie Watching! 🎥✨**
