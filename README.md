# CTMH Kansen Analyse Tool

Interactieve kansen analyse tool op basis van coalitieakkoorden 2026-2030 van Nederlandse gemeenten.

## Functies

- **323 gemeenten** met coalitieakkoord-thema's 2026-2030
- **Interactieve kaart** van Nederland — klik op elke gemeente voor analyse
- **AI-analyse** per gemeente via Claude (Anthropic API)
- **Wekelijkse kansen-update** — automatisch gegenereerd elke week
- **6 expertisegebieden** — Sociaal Domein, Ruimtelijk, Bestuurszaken, HRM, Financiën, Veiligheid
- **11 CTMH-adviseurs** als persoonlijk filter
- **Kansen Matrix** — alle gemeenten × alle expertisegebieden
- **Provincie filter** — filter op alle 12 provincies
- **Strategie-analyse** — AI-gegenereerd wervingsadvies

## Lokaal draaien

```bash
npm install
npm run dev
```

Open dan [http://localhost:3000](http://localhost:3000)

## Publiceren via Vercel

1. Push deze code naar GitHub
2. Ga naar [vercel.com](https://vercel.com)
3. Klik "Add New Project" → selecteer deze repository
4. Klik "Deploy" — klaar!

## Technologie

- React 18 + Vite
- Anthropic Claude API (claude-sonnet-4-6)
- SVG kaart van Nederland
- Persistent storage voor wekelijkse updates

## CTMH

[ctmh.nl](https://ctmh.nl) — Interim en advies voor de publieke zaak
