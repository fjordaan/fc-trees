# Fulham Cemetery Tree Map

Interactive map showing tree locations at Fulham Cemetery. Single HTML page with embedded CSS, JavaScript, and SVG overlaid on an aerial photo.

## Project Structure

- `index.html` - Main page with all code embedded
- `fulhamcemetery-aerial-photo.jpg` - Aerial background image

## Important: SVG Content

The SVG in `index.html` (lines ~240-728) is **auto-generated from Figma** and must not be modified, except for adding an `id` attribute. Do not:
- Reformat or restructure the SVG
- Modify paths, circles, or coordinates
- Change text content or styling within the SVG
- Add or remove SVG elements

## How It Works

- SVG groups (`<g>`) represent trees, identified by their `id` attribute
- Table of contents (`.toc`) lists tree names with matching CSS classes
- Hovering TOC items highlights corresponding tree groups on the map
- Touch events are handled for mobile devices
