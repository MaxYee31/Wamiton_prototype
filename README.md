# Wamiton — Prototype PWA

Prototype interactif du parcours acheteur Wamiton · 14 écrans navigables.

## Déploiement sur Vercel (gratuit)

### Option 1 — via GitHub (recommandé)

1. Crée un repo GitHub (public ou privé)
2. Upload les fichiers : `index.html`, `vercel.json`, `package.json`
3. Va sur [vercel.com](https://vercel.com) → **New Project** → importe le repo
4. Clique **Deploy** — c'est tout ✓

### Option 2 — via Vercel CLI

```bash
npm install -g vercel
cd wamiton/
vercel --prod
```

### Option 3 — drag & drop

1. Va sur [vercel.com/new](https://vercel.com/new)
2. Glisse le dossier `wamiton/` dans la zone de dépôt
3. Deploy

---

## Structure

```
wamiton/
├── index.html      # Tout le prototype (HTML + CSS + JS inline)
├── vercel.json     # Config Vercel static
├── package.json    # Métadonnées
└── README.md
```

## Écrans

| # | Écran | Description |
|---|-------|-------------|
| S1 | Splash | Zan flottant + wordmark |
| S2 | Onboarding | 3 slides swipables |
| S3 | Rôle | Acheteur / Organisateur |
| S4 | Auth | Saisie numéro +229 |
| S5 | OTP | Code 4 chiffres |
| S6 | Accueil | Feed événements + filtres |
| S7 | Événement | Fiche détaillée |
| S8 | Achat | Sélection billet + quantité |
| S9 | Paiement | KkiaPay (MTN, Moov, Orange, Carte) |
| S10 | Traitement | Spinner + auto-advance 2.5s |
| S11 | Confirmation | Zan bras levés |
| S12 | Mes billets | Tabs À venir / Passés |
| S13 | Billet QR | Design billet physique complet |
| S14 | Billet passé | Grisé + tampon UTILISÉ |

## Stack

- HTML/CSS/JS vanilla — 0 dépendances
- Fonts Google : Archivo Black, Manrope, JetBrains Mono, Instrument Serif
- SVG inline : Wordmark + Zan 4 variantes + motifs
- Responsive : mobile-first + frame téléphone desktop + side-nav desktop
