# Emote Studio : site vitrine

Page statique (HTML et CSS, aucune dépendance ni build) qui présente Emote Studio, l'éditeur d'emotes GTA V / FiveM.

- `index.html` : le contenu ;
- `styles.css` : la mise en page (palette du studio, police Manrope et JetBrains Mono via Google Fonts) ;
- `assets/` : icône et captures réelles du studio.

Aperçu local :

```powershell
python -m http.server 8765
```

puis ouvrir http://localhost:8765. Hébergeable tel quel (GitHub Pages, Netlify, Cloudflare Pages…).

À mettre à jour à chaque version : le numéro (`0.2.0`, trois endroits dans `index.html`) et le lien du bouton « Télécharger la dernière version », qui pointe vers les releases du dépôt `JusteKal/emote-studio` (privé : à remplacer par un lien public avant de publier le site).
