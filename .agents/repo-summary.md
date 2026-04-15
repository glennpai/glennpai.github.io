# glennpai.github.io

Personal portfolio site for Christopher Glenn, deployed at https://glennpai.github.io.

## Stack
- Astro 5, TypeScript, astro-icon

## Structure
- `src/pages/` — Routes (index, about, projects, contact)
- `src/components/` — Header, Footer, Navigation (all .astro)
- `src/layouts/Layout.astro` — Base layout, CSS variables, global styles
- `src/assets/` — Images (chi.png logo)
- `.github/workflows/deploy.yaml` — CI/CD to GitHub Pages

## Design Constraints
- **Font**: Monospace (Menlo/Meslo LG), 14px
- **Colors**: primary=#EDCC6F, secondary=#829AB1, bg=#2B2C41
- **Layout**: Centered max-width 48rem

## Development
- `npm run dev` — localhost:4321
- `npm run build` — output to ./dist/

## Agent Notes
- About (/about) and Projects (/projects) pages are placeholders — expand these
- Favicon and logo use chi.png (chihuahua)
- Contact page has hardcoded social links (GitHub, LinkedIn, Bluesky)
- No backend/API — static site only
