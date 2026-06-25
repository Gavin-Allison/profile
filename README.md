# Portfolio - Gavin Allison

This is the source code for a personal portfolio website, designed to showcase professional experience, technical skills, and academic and industry projects. The site is built with a responsive layout featuring dynamic content loading and interactive UI elements.

## Tech Stack

* Frontend: HTML5, CSS3, Vanilla JavaScript.
* Deployment Architecture: Built for static hosting environments like Github Pages

## File Structure

* index.html: The main landing page.
* style.css: Custom styling, including animations and grid layouts.
* about.html: External content file loaded into the 'About' section.
* projects/: Folder containing sub-pages and assets for individual project details. (Note that all work shown on this site is made solely by me, with one explained exception)
* resume/: Folder containing resume content and assets.
* img/: Icons and static imagery used across the site.

## How to Run Locally

1. Clone this repository to your local machine.
2. Because the site uses the fetch API to load external files, it must be served via a local development server (opening the file directly in the browser via file:// protocol may cause CORS errors).
    * If using VS Code: Use the Live Server extension.
    * If using Python: Run `python -m http.server 8000` in the root directory.
3. Open your browser to http://localhost:8000.

---
Created by Gavin Allison
