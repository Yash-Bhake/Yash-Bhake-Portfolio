# Copilot Instructions for Yash Bhake Portfolio Website

## Project Overview
This is a personal portfolio website for Yash Bhake, featuring:
- Homepage with About Me section
- Dedicated pages for Projects, Publications, Resume, Side Quests, and Contact
- Modern, responsive design using custom CSS (see `style.css`)

## Architecture & Structure
- Main entry: `index.html` (homepage)
- All subpages are in `pages/` directory: `projects.html`, `publications.html`, `resume.html`, `sidequests.html`, `contact.html`
- Shared navigation and footer across all pages for consistency
- Resume PDF should be placed at the root as `Yash_Bhake_Resume.pdf` and embedded in `resume.html`
- All styling is in `style.css` at the root

## Developer Workflows
- No build system or framework; edit HTML/CSS directly
- To add new projects/publications, update the respective HTML files in `pages/`
- For resume updates, replace the PDF and update the "Last updated" date in `resume.html`
- For new side quests, add sections/cards in `sidequests.html`

## Conventions & Patterns
- Use semantic HTML5 elements (`<section>`, `<nav>`, `<main>`, etc.)
- Navigation links should always point to the correct relative path (e.g., `../index.html` from subpages)
- Project and publication cards use consistent class names (`project-card`, `publication-card`)
- Contact info is hardcoded in `contact.html` and should be updated if details change
- All external links (GitHub, LinkedIn, arXiv) open in a new tab (`target="_blank"`)

## Integration Points
- GitHub repo links for projects
- arXiv links for publications
- Resume PDF embedded via `<iframe>`

## Examples
- To add a new project:
  ```html
  <div class="project-card">
    <div class="project-header">
      <div class="project-title">Project Name</div>
      <div class="project-meta">Details</div>
    </div>
    <div class="project-content">
      <p class="project-description">Description here.</p>
      <ul class="project-highlights">
        <li>Highlight 1</li>
        <li>Highlight 2</li>
      </ul>
      <a href="https://github.com/Yash-Bhake/project-repo" target="_blank">GitHub Repo</a>
    </div>
  </div>
  ```
- To update contact info, edit the list in `contact.html`

## Key Files
- `index.html`: Homepage and About Me
- `pages/projects.html`: Project portfolio
- `pages/publications.html`: Research publications
- `pages/resume.html`: Resume PDF
- `pages/sidequests.html`: Rocket team and iKshana project
- `pages/contact.html`: Contact information
- `style.css`: Site-wide styles

---
For questions or unclear conventions, review the homepage and subpages for examples, or ask for clarification.
