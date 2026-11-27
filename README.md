# Gyra : site vitrine

Page statique (HTML et CSS, aucune dépendance ni build) qui présente Gyra, l'éditeur d'emotes GTA V / FiveM.

- `index.html` : le contenu, en français ;
- `en/index.html` : la version anglaise (mêmes styles et images ; lien FR / EN dans la barre de navigation) ;
- `styles.css` : la mise en page (palette du studio, police Manrope et JetBrains Mono via Google Fonts) ;
- `assets/` : icône et captures réelles du studio.

Aperçu local :

```powershell
python -m http.server 8765
```

puis ouvrir http://localhost:8765. Hébergeable tel quel (GitHub Pages, Netlify, Cloudflare Pages…).

À mettre à jour à chaque version : le numéro (`0.2.0`, trois endroits dans `index.html` et autant dans `en/index.html`). Le bouton « Télécharger sur Patreon » / « Download on Patreon » mène à la page Patreon, où sont publiées les versions.
