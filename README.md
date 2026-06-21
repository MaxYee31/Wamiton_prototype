[README.md](https://github.com/user-attachments/files/29174323/README.md)
# Wamiton — Plateforme de billetterie & contrôle d'entrée

Billetterie en ligne + gestion des événements + scanner d'entrée hors-ligne pour le Bénin.

## 🚀 Installation & déploiement

```bash
# Cloner le dépôt
git clone <repo>
cd Wamiton

# Installer les dépendances
npm install

# Déployer sur Vercel
vercel deploy
```

## 📁 Structure

- **index.html** — Application complète (participant + organisateur + scan)
- **image-slot.js** — Composant web pour upload de documents (CIP, IFU, RCCM)
- **package.json** — Dépendances & scripts
- **vercel.json** — Configuration Vercel

## 🎯 Parcours

### Je participe
- Découverte d'événements
- Achat de billets (catégories, panier, paiement MM)
- Reçu & code QR
- Historique & profil

### J'organise
- Onboarding (Niveau 1 CIP / Niveau 2 IFU-RCCM)
- Création d'événements
- Billetterie (quotas, prix, catégories)
- Ventes en temps réel
- Gestion des agents de contrôle
- Profil & paramètres

### Je contrôle (agents)
- Authentification (code temporaire ou orga)
- Synchronisation hors-ligne
- Scanner QR instantané (valide / refusé)
- Stats temps réel (affluence, par catégorie)
- Équipe d'agents (activité live)

## 🛠️ Techs

- HTML5 + CSS3 + Vanilla JS
- Web Components (`<image-slot>`)
- Mobile-first (375px+)
- Thèmes par surface (Participant orange, Orga terracotta, Contrôle vert)

## 📱 Responsive

- Mobile : 375px+
- Tablet : 768px+
- Desktop : 1920px+

---

Made with ❤️ for Benin.
