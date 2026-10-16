# Branche `demo` — Réseau social ENSPD

Cette branche contient la **version de démonstration** publiée sur https://mko-reseau-social.vercel.app.
Toutes les données affichées sont **simulées** ; aucun appel n'est envoyé à un backend réel.

## Ce qui diffère de la branche principale

- `demo/banner.js` affiche le bandeau « Démo · données simulées ».
- Site HTML statique : `index.html` à la racine redirige vers `Réseau social/index.html`, `demo/banner.js` affiche le bandeau.
- Lien Google Fonts corrigé (`googmeappis` → `googleapis`).

## Construire

Aucun build : les fichiers sont servis tels quels.

Branche de référence du code : `main`. Cette branche n'est pas destinée à y être fusionnée.
