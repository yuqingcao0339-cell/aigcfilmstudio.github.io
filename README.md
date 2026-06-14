# AIGC Film Studio

A minimalist online film journal documenting AI-generated cinema. Editorial layout inspired by Nowness, A24, and Magnum Photos.

## Stack

- Next.js 15
- Tailwind CSS 4
- Framer Motion

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Pages

- **Home** — Fullscreen hero video, featured film projects (~1 viewport each), hover reveals project info
- **Project** (`/projects/[slug]`) — Video player, metadata, synopsis, BTS gallery, AI workflow
- **Artists** (`/artists`) — Creator grid
- **Artist Profile** (`/artists/[slug]`) — Bio and related projects

## Sample Content

Edit `src/data/projects.ts` and `src/data/artists.ts` to add your own films and creators.
