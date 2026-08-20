# GitHub Copilot Instructions for Demented Mojo website

## Project context

This repository is the official website for Demented Mojo.

- Site type: static website built with HTML and CSS
- Hosting: GitHub Pages
- Brand: Demented Mojo
- Tagline: "Music and everything else"
- Keep the site lightweight, readable, and easy to maintain

## Core rules

- Preserve the existing static HTML/CSS architecture. Do not introduce React, Angular, Vue, Node.js, npm, build systems, frameworks, package managers, or external dependencies unless explicitly requested.
- Keep the site simple and maintainable. Favor small, focused edits over broad rewrites.
- Use semantic HTML elements where appropriate (`header`, `nav`, `main`, `section`, `footer`, etc.).
- Use responsive/mobile-friendly CSS. Consider desktop, tablet, and mobile layouts for any layout or spacing changes.
- Favor accessibility and readability: good contrast, clear typography, understandable structure, and straightforward content hierarchy.
- Keep JavaScript minimal and only add it when absolutely necessary for a specific feature or enhancement.
- Use relative paths for local assets and internal site links. Use full HTTPS URLs for external links.
- Never add secrets, API keys, passwords, tokens, credentials, or sensitive configuration to the repository.
- Preserve working functionality unless asked to change it.
- Keep changes focused and avoid unrelated cleanup or broad refactors.

## GitHub Pages and hosting constraints

- Preserve the `CNAME` file exactly as-is.
- Do not modify DNS, domain, GitHub Pages, or hosting configuration unless explicitly requested.
- Do not add deployment tooling, CI/CD setup, or framework-specific hosting changes unless specifically requested.
- Keep the site compatible with GitHub Pages static hosting.

## Brand and visual direction

- Use a dark gothic/rock aesthetic with a near-black background.
- Favor white or light text for readability.
- Use green and muted gold accents inspired by the Demented Mojo logo.
- Keep the visual tone atmospheric but readable, not generic or corporate.
- Design for a music/creator-focused brand rather than a corporate brand.
- Maintain a strong identity without making the site feel overly busy or cluttered.

## Content and social links

- Use the brand name "Demented Mojo" consistently.
- Keep the tagline visible where appropriate: "Music and everything else".
- Current social links:
  - YouTube: https://www.youtube.com/@DementedMojo
  - Facebook: https://www.facebook.com/profile.php?id=61593126482941
- Preserve existing social links unless a user explicitly asks to update them.

## Implementation guidance

- Prefer clean, well-structured HTML and CSS over clever or overly complex patterns.
- Keep `index.html` and `style.css` understandable and easy to maintain.
- Use CSS variables for recurring colors, spacing, and typography if they improve consistency without adding complexity.
- Keep layout and visual treatment lightweight and intentional.
- Avoid unnecessary dependencies, libraries, asset pipelines, or framework conventions.
- Before making major architectural changes, explain why they are necessary and keep the scope narrow.

## Quality bar

- Maintain a polished, readable static site experience.
- Ensure content remains accessible to keyboard and screen-reader users where practical.
- Make sure any new layout decisions work well across common screen sizes.
- Prefer simple, direct solutions over unnecessary complexity.

## Do not do

- Do not rewrite unrelated files.
- Do not modify the `CNAME` file without explicit permission.
- Do not add frameworks, npm scripts, package files, or new build tooling.
- Do not add secrets, credentials, or environment-specific configuration.
- Do not make hosting or DNS changes without explicit approval.
- Do not create unnecessary JavaScript or client-side complexity.
