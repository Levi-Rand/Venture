# Venture - Chord Progression Tool

## Project Overview
Venture is a beginner-friendly chord progression tool for music producers. It's a Progressive Web App (PWA) built with React that helps users explore, build, and understand chord progressions.

## Tech Stack
- **Frontend Framework**: React (with functional components)
- **Build Tool**: Vite (indicated by bundled output structure)
- **PWA Features**: Service Worker, Web App Manifest
- **Styling**: CSS (bundled stylesheets)
- **Animation**: Framer Motion (detected in bundled code)

## Project Structure
This repository contains the production build/deployment files:
- `index.html` - Main entry point
- `index-*.js` - Bundled JavaScript application
- `index-*.css` - Bundled stylesheets
- `sw.js` - Service Worker for PWA functionality
- `manifest.json` - PWA manifest
- Icons and assets for PWA installation

## Coding Guidelines
- Follow React best practices with functional components and hooks
- Maintain PWA functionality (service worker, manifest)
- Keep the build optimized for production
- Ensure offline functionality works correctly
- Maintain responsive design for mobile and desktop

## PWA Requirements
- Service worker must precache all necessary assets
- Manifest must include proper icons and metadata
- App should work offline after initial load
- Handle navigation fallback to index.html for SPA routing

## Testing Guidelines
- Test PWA functionality (installation, offline mode)
- Verify service worker caching behavior
- Check responsive design across devices
- Test chord progression functionality

## Deployment Notes
- This repository contains the built/compiled version
- Any changes should preserve PWA functionality
- Update service worker cache name when assets change
- Ensure all referenced assets exist in precache list
