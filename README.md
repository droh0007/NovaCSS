NovaCSS is our MTM6407 mini framework: Sass modules, clean tokens, and purposeful utilities.

Install & Build
npm install
npm run build (or npm run sass:watch during edits)

Usage
Link the compiled stylesheet: <link rel="stylesheet" href="./css/nova.css"> and start using the utilities/components shown in index.html.

Customization
Quick tweaks: override the CSS vars (e.g. --color-primary, --radius) in your own stylesheet or in a <style> block.
Deeper changes: adjust the maps in src/variables/, then rebuild with npm run build.

We leaned on partials, shared maps, and the @use/@forward pattern to keep everything tidy and reusable.

Team Roles
Kate – Project lead & review
Mohammed – Tokens & typography
William – Utilities & layout
Ramneek – Components & docs