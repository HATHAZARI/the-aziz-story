# The Aziz Story — website prototype

A responsive React + Vite prototype for a Bangladesh travel, culture and city-storytelling brand. The visual direction uses a warm editorial layout and a CSS-built clay-inspired miniature illustration, inspired by the broad idea of city dioramas rather than copying the reference website.

## Run locally

Requirements: Node.js 18+.

```bash
npm install
npm run dev
```

Open the local URL shown by Vite. To build a production static bundle:

```bash
npm run build
npm run preview
```

## Prototype features

- Responsive public home page and story cards
- Search and category filters
- Story preview modal
- Destination sections
- Newsletter form interaction (demo only; no emails are sent)
- Studio/admin interface with create, edit and delete story interactions
- Story changes persist in the current browser via `localStorage`

## Important production limitations

This is a front-end prototype, not a production CMS. The admin Studio is accessible without authentication and browser-local data can be changed by the user; do not publish it as a secure admin panel. Before public launch, add a backend/API, real authentication and authorization, a database, image uploads/storage, server-side validation, rate limiting, backups, and an email marketing provider. Connect a proper Bengali/English language system and SEO metadata. Replace sample story text and externally hosted sample imagery with original, verified content and images that you have rights to use.
