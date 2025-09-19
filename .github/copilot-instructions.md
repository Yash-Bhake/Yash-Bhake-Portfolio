# Copilot Instructions for Yash-Bhake-Portfolio

This repository is for a professional personal website. AI agents should follow these guidelines for productive contributions:

## Architecture Overview
- The site is a multi-page portfolio, with sections for Home, Projects, Publications, Resume, Side Quests, and Contact.
- All content is static and should be elegant, professional, and visually appealing.
- Use modern HTML/CSS/JS. No frameworks are currently present, but you may suggest lightweight ones if justified.

## Key Pages & Content
- **Home/About Me**: Catchy, elegant intro. Use information from `slot4_analytics_2pg.pdf` for profile details.
- **Projects**: Display project cards with descriptions and GitHub links. Use real projects from the user's GitHub.
- **Publications**: List research papers with arXiv links, brief summaries, and other relevant research info.
- **Resume**: Embed/display the resume PDF. Show last updated date.
- **Side Quests**: Highlight rocket team experience (details from `Core_2pg_4thyr.pdf`) and iKshana project.
- **Contact**: Show email, GitHub, LinkedIn, and phone number.

## Conventions & Patterns
- Keep navigation simple and consistent across all pages.
- Use cards for projects and publications for visual clarity.
- Prefer semantic HTML and accessible design.
- Reference PDFs for content, but do not attempt to parse them directly—request summaries from the user if needed.

## Developer Workflow
- No build tools or package managers are present; edit HTML/CSS/JS directly.
- Preview changes locally in a browser.
- No automated tests or CI/CD configured.

## Integration Points
- External links: GitHub repos, arXiv, LinkedIn, email, phone.
- Resume PDF should be embedded or linked for download.

## Examples
- For project cards: `<div class="project-card"><h3>Project Name</h3><p>Description</p><a href="...">GitHub</a></div>`
- For publications: `<div class="pub-card"><h3>Title</h3><p>Summary</p><a href="...">arXiv</a></div>`

## Key Files
- `index.html`: Entry point, will be updated for navigation and homepage.
- `slot4_analytics_2pg.pdf`: Use for profile/about content.
- `Core_2pg_4thyr.pdf`: Use for rocket team/side quest content.
- `README.md`: Basic project info.

---

If you need more details from PDFs, ask the user for summaries. Always keep the site professional, elegant, and easy to navigate.
