# Young Muslim Leadership Program Website

## Overview

This is a static website for the Young Muslim Leadership Program (YML) in Northwest Arkansas, designed to empower Muslim youth aged 8-14 through Islamic values, leadership development, and community engagement. The website serves as an informational platform and registration portal for the program, featuring multiple pages including home, about, updates, media gallery, registration, and donations.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
The website follows a traditional multi-page static HTML architecture with shared styling and interactive elements:

- **Static HTML Pages**: Six main pages (index, about, updates, media, registration, donation) with consistent navigation structure
- **Responsive Design**: Mobile-first approach with hamburger menu for mobile devices and full navigation for desktop
- **CSS Architecture**: Single stylesheet (styles.css) using CSS custom properties for theming and consistent design tokens
- **JavaScript Enhancement**: Minimal JavaScript (script.js) focused on mobile menu toggle functionality and user interaction

### Design System
- **Typography**: Inter font family with multiple weights (300-700) for modern, readable text
- **Color Palette**: Primary green (#22a575), secondary blue-gray (#4b5c6b), and neutral grays for a professional, accessible design
- **Component Library**: Reusable button styles, navigation components, and layout containers
- **Shadow System**: Consistent box-shadow variables for depth and visual hierarchy

### Navigation Architecture
- **Consistent Header**: Fixed navigation bar across all pages with brand identity (YML acronym)
- **Active State Management**: Visual indication of current page through active CSS classes
- **Mobile Responsiveness**: Collapsible hamburger menu with smooth animations for mobile devices
- **Call-to-Action**: Prominent donation button in navigation to encourage financial support

### Content Strategy
The website is structured to guide visitors through a logical flow:
1. **Home**: Introduction and program overview
2. **About**: Detailed mission and program information  
3. **Updates**: Latest news and announcements
4. **Media**: Visual content and program highlights
5. **Registration**: Program enrollment process
6. **Donation**: Financial support portal

## External Dependencies

### Web Fonts
- **Google Fonts**: Inter font family loaded via CDN for consistent typography across devices

### Performance Optimizations
- **Font Preconnection**: DNS prefetching for Google Fonts domains to improve loading performance
- **Responsive Images**: Proper image sizing and optimization for different screen sizes

### SEO and Accessibility
- **Meta Descriptions**: Unique, descriptive meta tags for each page to improve search engine visibility
- **Semantic HTML**: Proper heading hierarchy and navigation structure for screen readers
- **Viewport Configuration**: Mobile-responsive meta viewport settings

Note: The current implementation is purely frontend-focused with no backend services, databases, or external API integrations. Future enhancements may require adding form processing capabilities for registration and donation functionality.