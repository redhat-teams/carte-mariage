# Atelier du Faire-Part — Simulateur de carte de mariage

Petite application React (Vite) qui permet de composer un faire-part de
mariage et d'en visualiser un aperçu en temps réel : prénoms, date, lieu,
mot d'invitation, et 3 palettes de papeterie (Botanique, Nuit d'encre,
Rosé poudré).

## Prérequis

- Node.js **22 LTS** (`node --version` doit afficher `v22.x`)
- npm (fourni avec Node)

## Installation et lancement

```bash
npm install
npm run dev
```

Puis ouvrez l'URL affichée dans le terminal (par défaut
`http://localhost:5173`).

## Autres commandes

```bash
npm run build     # build de production dans dist/
npm run preview   # sert le build de production localement
```

## Structure

```
src/
  App.jsx                 # état de l'application (données du carton, palette)
  palettes.js              # définition des 3 palettes de papeterie
  components/
    Controls.jsx           # formulaire (prénoms, date, lieu, message, palette)
    InvitationCard.jsx     # rendu du carton d'invitation
  App.css                  # mise en page + style du carton
  index.css                # styles globaux
```
