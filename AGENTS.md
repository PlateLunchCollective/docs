> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Configuration notes

- **`seo.organization` in `docs.json` is mirrored from the main site.** Its `id`, `url`, and the 13-URL `sameAs` array are copied verbatim from the main site's `app/layout.tsx` (`organizationSchema`, repo `platelunchcollective/plc-website`). This is what ties the wiki's Organization entity to the main site's canonical `@id` for AI/knowledge-graph reconciliation. If the main site's `sameAs` changes, update it here too, and vice versa — if the two arrays drift, the entity link silently breaks. Keep them byte-for-byte identical.

## Terminology

{/* Add product-specific terms and preferred usage */}
{/* Example: Use "workspace" not "project", "member" not "user" */}

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
