# TryChicagoEats! - Restaurant Recommendation Website

A modern, responsive web application showcasing Chicago's best local restaurants. Built with React, this project demonstrates best practices in frontend development including component-based architecture, accessibility, and user-friendly design.

## Project Overview

TryChicagoEats helps visitors discover authentic Chicago dining experiences beyond the typical tourist spots. The site features a curated list of top 10 local favorites and allows users to submit their own restaurant recommendations.

## Live Demo

*Deployment URL will be added here*

## Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Interactive Carousel**: Auto-playing carousel with manual controls and keyboard navigation
- **Top 10 Restaurants**: Curated list of Chicago's best local dining spots
- **Recommendation Form**: User-friendly form with client-side validation
- **Accessibility**: WCAG 2.1 compliant with semantic HTML, ARIA labels, and keyboard navigation
- **Modern UI**: Clean design with pink and cream color scheme matching the brand

## Technologies Used

### Core
- **React 18** - UI library
- **Vite** - Build tool and development server
- **JavaScript (ES6+)** - Programming language
- **React Router v6** - Client-side routing
- **PropTypes** - Runtime type checking

### Styling
- **CSS Modules** - Scoped styling
- **Custom CSS Variables** - Consistent theming

### Development Tools
- **ESLint** - Code linting
- **Vitest** - Unit testing framework
- **React Testing Library** - Component testing

## Project Structure

```
steph-proj/
├── src/
│   ├── components/
│   │   ├── carousel/          # Carousel with auto-play
│   │   ├── form/              # Form components
│   │   ├── layout/            # Header, Footer, Layout
│   │   └── restaurant/        # Restaurant card components
│   ├── context/               # React Context for state
│   ├── data/                  # Mock JSON data
│   ├── hooks/                 # Custom React hooks
│   ├── pages/                 # Page components
│   ├── styles/                # Global styles
│   └── utils/                 # Utility functions
├── public/                    # Static assets
└── tests/                     # Test files
```

## Getting Started

### Prerequisites
- Node.js 18+ and npm

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd steph-proj
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

4. Open your browser to `http://localhost:5173`

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm test` - Run tests
- `npm run test:coverage` - Run tests with coverage

## Key Features Explained

### 1. Carousel Component
- Auto-play functionality with 5-second intervals
- Pause on hover for better UX
- Keyboard navigation (Arrow keys, Spacebar)
- Accessible with ARIA labels
- Smooth transitions between slides

### 2. Restaurant Cards
- Dynamic data loading from JSON
- Ranked display (#1-#10)
- Responsive image handling
- Specialty tags and ratings
- Hover effects for interactivity

### 3. Recommendation Form
- Client-side validation
- Real-time error feedback
- Accessible form labels and error messages
- Console logging of submissions (no backend required)
- Success state with auto-reset

### 4. Context API Implementation
- Global restaurant data management
- Helper functions for data filtering
- Loading and error states
- Efficient data sharing across components

## Accessibility Features

- Semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<footer>`, `<article>`)
- ARIA labels and live regions
- Keyboard navigation support
- Focus visible indicators
- Color contrast compliance (WCAG AA)
- Alt text for all images
- Form error announcements for screen readers

## Design Decisions

### Why React Context API?
For this small-to-medium sized application, React Context API provides sufficient state management without the complexity of Redux. It's perfect for sharing restaurant data across components.

### Why CSS Modules?
CSS Modules offer scoped styling by default, preventing class name collisions while keeping the familiar CSS syntax. This makes the codebase easier to maintain and understand.

### Why Vite?
Vite offers lightning-fast hot module replacement (HMR) and optimized builds out of the box, significantly improving the development experience.

## Future Enhancements

- Backend integration for persistent data storage
- User authentication and personalized recommendations
- Restaurant search and filtering
- Interactive maps integration
- User reviews and ratings system
- Social media sharing
- Multi-language support
- Dark mode toggle
- Progressive Web App (PWA) capabilities

## Lessons Learned

1. **Component Reusability**: Building small, focused components like RestaurantCard makes the codebase maintainable and scalable.

2. **Accessibility First**: Implementing accessibility from the start is easier than retrofitting it later.

3. **Prop Validation**: Using PropTypes catches bugs early and serves as documentation.

4. **CSS Variables**: Custom properties make theming and design updates significantly easier.

5. **User Experience**: Small touches like pause-on-hover for the carousel and real-time form validation greatly improve UX.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

This is an educational project for a final assignment. Contributions are welcome but please note this is primarily for learning purposes.

## License

This project is created for educational purposes.

## Acknowledgments

- Design inspiration from the provided Figma mockup
- Restaurant images from Unsplash
- Chicago food scene for endless inspiration

---

**Built with** ❤️ **by students, for food lovers**

© 2025 TryChicagoEats - HTML, CSS & JavaScript
