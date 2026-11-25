# pixelabsgames.com

Le site du studio PixeLabs Games, publié par GitHub Pages : l'accueil, la page de chaque jeu, la politique de
confidentialité (adresse fixe : https://pixelabsgames.com/confidentialite/) et les mentions légales.

`patchwork-party/codes.json` : les codes promo de Patchwork Party, que le jeu lit quand un joueur écrit un code dans
ses réglages. Chaque ligne donne l'empreinte d'un code (SHA-256 de « patchwork-party: » suivi du code en majuscules),
ce qu'il offre et son dernier jour, jamais le code lui-même. La ligne d'un nouveau code se prépare avec
`node tools/code-promo.js` dans le dépôt du jeu.
