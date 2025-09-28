# Base - Tailwind CSS Startup Template

## Overview

This is a static website template built with Tailwind CSS designed for startups and business websites. The template provides a complete set of pages including home, features, about, contact, blog, services, and authentication pages. It features a modern design with dark mode support, responsive navigation, and interactive components powered by Alpine.js.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Static HTML Structure**: Multi-page website with semantic HTML5 structure
- **CSS Framework**: Tailwind CSS for utility-first styling with custom compiled styles
- **JavaScript Framework**: Alpine.js for reactive components and state management
- **Responsive Design**: Mobile-first approach with responsive navigation and layouts

### Component Structure
- **Navigation System**: Sticky header with hamburger menu for mobile devices
- **Dark Mode**: Toggle functionality with localStorage persistence
- **Interactive Elements**: Alpine.js directives for dynamic behavior (sticky menu, mobile navigation, scroll effects)
- **Page Routing**: Traditional multi-page application with static HTML files

### State Management
- **Local Storage**: Dark mode preferences persisted across sessions
- **Alpine.js Data**: Component-level state for navigation, menu toggles, and UI interactions
- **Page Identification**: Each page has a unique identifier for navigation highlighting

### Build System
- **Webpack**: Module bundling for JavaScript dependencies
- **PostCSS**: CSS processing with Tailwind CSS compilation
- **Swiper Integration**: Carousel/slider functionality for content sections

### Asset Management
- **Images**: Organized in images directory with separate light/dark logo variants
- **Fonts**: Google Fonts (Inter and Outfit) loaded via CDN
- **Icons**: Integrated icon system through CSS classes and SVG assets

## External Dependencies

### CDN Services
- **Google Fonts**: Inter and Outfit font families for typography
- **Google AdSense**: Advertisement integration with configured publisher ID

### JavaScript Libraries
- **Alpine.js**: Lightweight JavaScript framework for reactive components
- **Alpine Intersect**: Plugin for intersection observer functionality
- **Swiper**: Modern slider/carousel component

### Development Tools
- **Webpack**: Module bundler and development server
- **PostCSS**: CSS processing and optimization
- **CSS Loader**: CSS module loading and processing

### Third-Party Integrations
- **Google AdSense**: Monetization through display advertisements
- **Favicon**: Custom favicon integration for branding