# Find2Fix

Astro website for Find2Fix: reducing software errors using transparent AI.

## Development

Run `npm ci`, then `npm run dev`. Run `npm run build` to generate the static site in `dist/` and `npx astro check` to check types.

The site URL is `https://find2fix.github.io`. The old custom-domain CNAME is archived so deployment does not point at the previous lab domain.

## Content

- `src/pages/`: homepage, project overview, and page templates
- `src/people/`: project team
- `src/projects/`: research topics
- `src/publications/`: Find2Fix-related publications
- `src/news/`: project news
- `public/`: Find2Fix logo and icons

The initial team and partner information comes from the grant announcement included in this repository. Unrelated content and original branding are preserved under `archive/risenlab/`, outside Astro's content collections and public assets. Archived Markdown retains its original paths; restoring it may require restoring its referenced images too.

The initial logo combines a magnifying glass and check mark. `logo.svg` is the blue wordmark, `logo-light.svg` is for dark backgrounds, and `logo-icon.svg` is the standalone symbol.
