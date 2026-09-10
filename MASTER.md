# Vitrine — Rework tracker

## UI/UX Redesign (dark theme)
- [x] Dark palette: bg #0a0b0f, raised #12131a, card #161722
- [x] Typography: EB Garamond headings + Lato body (Google Fonts)
- [x] Spacious layout: Swiss-style, max-width 680px, generous padding
- [x] Services banner: dark raised bg, subtle border separators, hover state
- [x] Hero: Garamond 42px h1, Lato 300 subtitle, centered
- [x] About section: dim uppercase label, muted body text, 1.8 line-height
- [x] Footer: dim text, border-top separator
- [x] Admin bar: dark raised bg, accent buttons
- [x] Service editor modal: dark card bg, backdrop blur overlay
- [x] Delivery page: matching dark theme, accent download button
- [x] All transitions 200ms ease, prefers-reduced-motion respected
- [x] Responsive: column stack at 600px
- [x] Contrast: white (#fff) headings on #0a0b0f (ratio 19:1), muted #8b8fa3 on #0a0b0f (ratio 6.2:1)

## Design system source
- Generated via `ui-ux-pro-max` skill (Minimalism & Swiss Style)
- Palette adapted for dark-first: navy/slate tones, steel-blue accent #4d8fcc
- Full spec: `design-system/vitrine-rh/MASTER.md`

## Vercel structure
- [x] Pure static (no backend)
- [x] vercel.json rewrites for / and /d/:token
- [x] Security headers
- [ ] Custom domain wired

## API integration
- [x] Content fetched from hub API (CORS)
- [x] Admin check via hub API
- [x] Content save via hub API
- [x] Delivery token validation via hub API
