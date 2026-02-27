# Alexandra Landing Animation

A responsive landing page animation built with Next.js, Tailwind CSS, and GSAP.

## What this project does

- Shows a cinematic hero entrance with image stagger, scaling, and text reveal.
- Uses `GSAP.matchMedia()` to run different sizing logic for desktop and mobile.
- Animates overlay masks and background cover for a smooth intro effect.

## Tech stack

- Next.js 16
- React 19
- TypeScript
- Tailwind CSS 4
- GSAP + `@gsap/react`

## Run locally

1. Install dependencies:

```bash
npm install
```

2. Start dev server:

```bash
npm run dev
```

3. Open:

`http://localhost:3000`

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Create production build
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Project structure

- `app/page.tsx` - Main landing page UI + GSAP timeline
- `app/layout.tsx` - Global layout and metadata
- `app/globals.css` - Global styles
- `public/` - Static image assets

## Animation flow (quick)

1. Images enter from below with opacity fade-in.
2. Gallery gap and image scale animate.
3. Overlay masks slide to reveal images.
4. Hero image resizes based on screen width.
5. Dark overlay retracts and title text reveals.

## Notes

- The page uses `<img>` elements intentionally for this animation setup.
- If you want easier image optimization later, you can migrate to Next.js `Image` with layout adjustments.
