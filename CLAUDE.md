# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a React presentation application for a restaurant AI automation solution. The codebase consists of a single HTML file containing a complete React component that creates an interactive slide presentation.

## Architecture

**Single-file React App**: The entire application is contained in `index.html` with:
- React component (`Presentation`) implementing a slide-based presentation system
- 20 slides covering restaurant AI automation topics in Czech
- CSS-in-JS styling with glassmorphism design
- State management using React hooks
- Keyboard navigation (arrow keys, spacebar)
- Navigation controls and progress indicators

**Key Components**:
- **Slide System**: Dynamic slide rendering with fade transitions
- **Navigation**: Previous/next buttons, keyboard controls, slide indicators
- **Progress Tracking**: Visual progress bar and slide counter
- **Responsive Design**: Mobile-optimized layouts
- **Interactive Elements**: Call-to-action buttons with alert handlers

## Development Notes

**No Build System**: This is a static HTML file that can be opened directly in a browser - no build process, package.json, or development server required.

**Content Structure**: 
- Restaurant industry challenges and AI solutions
- Marketing automation and customer experience features
- Technology showcases (AR/VR, smart tables, dynamic pricing)
- ROI analysis and case studies
- Business presentation format in Czech language

**Styling Approach**: 
- CSS custom properties for theming
- Glassmorphism effects with backdrop-filter
- Gradient backgrounds and glass card components
- Grid layouts for content organization
- Mobile-first responsive design

## Maintenance

To modify this application:
1. Edit the `index.html` file directly
2. Slides are defined as JSX within the component
3. Styling is contained in the `<style>` tag
4. No compilation or build step needed
5. Test by opening in browser