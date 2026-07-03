# Urban Epidemiology Lab — Neomorphism Website

A polished static website redesign packaged as an **RStudio project**. It uses plain HTML, CSS, and JavaScript: no server, R package, or build step is required.

## Open locally in RStudio
1. Unzip the folder.
2. Open `UEL-Neomorphism.Rproj` in RStudio.
3. Run `run_site.R`, or open `index.html` in a browser.

> The project is intentionally static. This makes it fast to preview and easy to host later on NYU WordPress, GitHub Pages, Netlify, or another approved platform.

## Edit content
- Page layout: `*.html` files in the project root
- Current people, publications, presentations, press, and alumni: `assets/js/site-data.js`
- Visual system and responsive layout: `assets/css/uel.css`
- Interactions, filters, modal, navigation, and theme setting: `assets/js/site.js`

## Important before publishing
The text and records were reorganized from the public UEL site on **July 3, 2026**. Confirm names, affiliations, roles, active projects, publication status, media links, and joining requirements with the lab director before deployment. The design is a concept and is not an official NYU website or brand template.


### Theme artwork note
The hero illustration uses separate dark and light SVG assets. The light version is automatically swapped through CSS so the orbit rings and research-grid lines retain contrast against the pale background.

## Current project content

The homepage and `research.html` were updated to show the three user-confirmed current projects: cannabis package data cleaning, ArcGIS mapping of hemp stores across NYC, and cannabis/hemp store field-survey data collection.
