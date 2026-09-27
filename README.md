# KODEZ FIZZ — React + Vite (v2)

Complete editable source for the KODEZ FIZZ website. React manages the page, navigation, flavor selection and motion preferences. Three.js renders the cans. Vite runs the development server and creates the production build.

## Run on Windows / VS Code
1. Install Node.js 22.12 or newer (Node 22 LTS recommended).
2. Extract this ZIP and open its folder in VS Code.
3. Open Terminal → New Terminal.
4. Run `npm ci`.
5. Run `npm run dev`.
6. Open the localhost URL printed in the terminal.

## Production
- `npm run build` creates `dist/`.
- `npm run preview` serves the production build locally.
- Upload the contents of `dist/` to any static hosting provider.
- No backend, API keys, or database are required.
- Do not open index.html using file://; use the Vite server.

## Where to edit
- `src/main.jsx`: React UI, tabs, collection sections, FAQ and interactions.
- `src/flavors.js`: all six flavor names, descriptions, colors and labels.
- `src/scene.js`: Three.js geometry, materials, lighting and scroll choreography.
- `src/style.css`: desktop/mobile styling and animation transitions.
- `index.html`: page metadata and favicon.

## Included behavior
Original six-can carousel, swipe and keyboard controls, home scroll close-up, Explore Collection tab, six sequential scroll chapters, configuration panels, chapter navigation, synchronized colors, motion toggle and device reduced-motion support. Renderer and event listeners are cleaned up on component unmount.

Product profiles are fictional design content, not ingredient or nutrition claims. Original KODEZ concept branding is used.

Three.js is MIT licensed; npm installs its accompanying license. Google Fonts is optional and has system-font fallbacks.

## Validation
Production build and JavaScript module parsing checked. Browser visual testing is not available in this environment.
