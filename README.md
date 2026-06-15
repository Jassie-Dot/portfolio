# Jaskaranveer Singh Portfolio

A modern personal portfolio for Jaskaranveer Singh, an Information Technology student, freelance developer, and AI product builder. The site presents selected web projects, AI experiments, technical skills, experience, hackathon wins, and contact links in a polished interactive interface.

## Highlights

- Responsive portfolio built with React, TypeScript, Vite, and Tailwind CSS
- Animated hero section with Motion-powered entrance, scroll, hover, and project shuffle interactions
- Interactive 3D visual powered by Spline on desktop screens
- Dark and light theme toggle with animated switch and full-site theme transition
- Shuffled project deck with clickable active cards that open deployed client and cafe projects
- Accessible icon buttons, visible focus states, reduced-motion support, and semantic links
- Production-ready build flow with ESLint and TypeScript checks

## Featured Projects

| Project | Description | Live Link |
| --- | --- | --- |
| Aurora Table Cafe | Polished cafe website with refined menu presentation and atmospheric visuals. | [Open project](https://aurora-table-cafe.vercel.app/) |
| Cafe Website | Modern cafe landing experience with clear sections and responsive browsing. | [Open project](https://cafe-website-alpha-seven.vercel.app/) |
| TR Enterprises | Business website for services, brand details, and customer contact paths. | [Open project](https://tr-enterpriises.vercel.app/) |
| South Cafe Pizza | Pizza cafe website focused on menu discovery and mobile-friendly presentation. | [Open project](https://south-cafe-pizza.vercel.app/) |
| Sentinel Pro AI | AI platform concept with modular plugin architecture and automation thinking. | Portfolio showcase |

## Tech Stack

- React 19
- TypeScript
- Vite
- Tailwind CSS
- Motion / Framer Motion API
- Spline
- Lucide React
- ESLint

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

The app will start on a local Vite development URL, usually `http://localhost:5173/`.

### Production Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Lint

```bash
npm run lint
```

## Project Structure

```text
portfolio/
  public/
    favicon.svg
    icons.svg
    jaskaranveer-profile.png
  src/
    assets/
    components/ui/
    lib/
    App.css
    App.tsx
    index.css
    main.tsx
  package.json
  vite.config.ts
```

## Key Implementation Notes

- Theme state is stored in `localStorage` using the `portfolio-theme` key.
- Theme colors are driven by CSS variables in `src/index.css`.
- The theme toggle uses Motion for the sliding thumb, icon crossfade, pulse feedback, and site-wide reveal animation.
- The project section uses a Motion-powered shuffle deck, with optional external links through the `href` field in the `projects` data array.
- The Spline scene is lazy-revealed on desktop after idle time to keep the first render lighter.

## Deployment

This project is ready for Vercel or any static hosting provider that supports Vite builds.

Recommended Vercel settings:

```text
Build Command: npm run build
Output Directory: dist
Install Command: npm install
```

## Contact

- GitHub: [Jassie-Dot](https://github.com/Jassie-Dot)
- Email: [jassie.08191@gmail.com](mailto:jassie.08191@gmail.com)

## License

This portfolio is maintained by Jaskaranveer Singh. Add a license file if you plan to make reuse terms explicit.
