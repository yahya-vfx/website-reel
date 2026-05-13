# CHANGELOG

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Full-screen video background for hero section
- Gradient overlay for improved text readability over video
- Responsive video element with autoplay, loop, and muted attributes
- Fallback background for browsers that don't support video

### Changed
- Replaced "INITIATE REEL" button with immersive video background
- Updated hero section layout to accommodate full-screen video
- Adjusted main content container styling for proper layout flow
- Enhanced z-index layering for proper content stacking

### Technical Details
- Video element uses `object-cover` for proper aspect ratio maintenance
- Implemented three-layer z-index system (video: 0, overlay: 10, content: 20)
- Maintained original typography and styling consistency
- Added `playsinline` attribute for better mobile compatibility

---

## [0.1.0] - 2026-05-12

### Added
- Initial VFX portfolio website
- Hero section with "UNSEEN DIMENSIONS ARCHIVED" branding
- 3D asset preview grid with glass panel styling
- Social network links section
- Responsive design with mobile navigation
- Custom Tailwind CSS configuration with dark theme
- Google Fonts integration (Inter, JetBrains Mono, Sora)
- Material Symbols icons
- Ambient background image with blend effects
- Glass morphism UI components
- Neon glow hover effects

### Features
- Dark mode aesthetic with cyan/violet color scheme
- Responsive grid layout for asset previews
- Tech stack badges (Houdini, Arnold)
- Mobile-optimized bottom navigation
- Smooth transitions and hover states
- Custom CSS animations and effects

---

## Version History

- **0.1.0** - Initial release with basic portfolio structure
- **Unreleased** - Current development version with video background enhancement
