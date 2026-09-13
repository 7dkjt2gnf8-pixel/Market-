# 🧺 Market+ (Mon Petit Marché)

Un jeu de gestion de marché de fruits exotiques en vue isométrique 3/4, jouable directement dans le navigateur (HTML/CSS/JavaScript vanilla, sans dépendance ni build).

![status](https://img.shields.io/badge/status-jouable-brightgreen) ![tech](https://img.shields.io/badge/tech-HTML%20%2F%20CSS%20%2F%20JS-informational)

## 🎮 Aperçu

Construis des stands de fruits exotiques (mangue, ananas, coco, kiwi, banane, avocat, melon, pastèque, raisin, pêche, mandarine, fraise, litchi...), sers les clients qui arrivent automatiquement, améliore et fusionne tes stands, agrandis ton marché, embauche du personnel, puis fais 💰 pour débloquer de nouveaux décors : Marché, Parc, Centre Commercial, Parking...

## ✨ Fonctionnalités

- **Écran de démarrage** : logo animé « Market+ », bouton **Reprendre la partie** (si une sauvegarde existe) ou **Nouvelle partie**. La progression est sauvegardée automatiquement dans le navigateur (`localStorage`).
- **Installable sur iOS / Android** : jeu complet d'icônes (favicon, `apple-touch-icon` toutes tailles, icônes Android/`maskable`) + `manifest.webmanifest`. Ajouté à l'écran d'accueil, le jeu s'affiche sous le nom **Market+**.
- **Vue isométrique 3/4** : sol en tuiles, stands en volumes 3D (toit, façades, jauge de stock), bâtiment de coin avec enseigne.
- **Gestion de stands** : construction, réapprovisionnement, amélioration (niveaux 1 à 10), fusion de deux stands en un stand magique.
- **Clients animés** : arrivent automatiquement, plus nombreux si le marché compte plus de stands.
- **Personnel** : à partir de 2 stands niveau 5+, embauche un employé (200€) qui réapprovisionne automatiquement +1 fruit/10s sur chaque stand éligible. Un employé supplémentaire se débloque tous les 2 stands niveau 5+ en plus.
- **Agrandissement du marché** : augmente la taille de la grille en échange d'argent.
- **Revenu passif** : +1€ toutes les 5 secondes pour ne jamais rester bloqué.
- **Niveaux à décor variable** : atteins l'objectif d'argent (1000€, puis 2000€, 4000€... il double à chaque niveau) pour déménager vers un nouveau décor (Marché → Parc → Centre Commercial → Parking → ...).
- **Caméra tactile** : zoom pince-à-deux-doigts (et molette sur ordinateur), cadrage automatique adapté à la taille du marché.
- **Mode paysage optimisé mobile**, avec invite de rotation en portrait.

## 🚀 Lancer le jeu

Aucune installation nécessaire : c'est une page HTML autonome.

- **En local** : ouvre `index.html` directement dans un navigateur.
- **En ligne (GitHub Pages)** :
  1. Pousse ce dépôt sur GitHub.
  2. Dans *Settings → Pages*, choisis la branche `main` et le dossier `/ (root)`.
  3. Le jeu sera accessible à `https://<ton-utilisateur>.github.io/<nom-du-repo>/`.

## 🗂️ Structure du dépôt

```
.
├── index.html               # Le jeu complet (HTML + CSS + JS, fichier unique)
├── manifest.webmanifest     # Manifest PWA (nom "Market+", icônes, mode standalone)
├── favicon.ico
├── icons/                   # Jeu complet d'icônes (favicon, apple-touch-icon, Android/maskable)
├── README.md
└── LICENSE
```

## 🛠️ Stack technique

- HTML5 Canvas 2D pour le rendu du jeu (moteur isométrique fait main).
- JavaScript vanilla (aucune dépendance, aucun bundler).
- CSS pour l'interface (rail latéral, panneaux, badges).

## 📄 Licence

Distribué sous licence MIT — voir [LICENSE](./LICENSE).
