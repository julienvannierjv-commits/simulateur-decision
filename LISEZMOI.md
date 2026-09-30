# Mise en ligne

Le dossier est un site statique : `index.html` est le simulateur, aucun serveur ni installation n'est nécessaire.

## Netlify Drop (le plus simple)
1. Ouvrez https://app.netlify.com/drop
2. Glissez-déposez le dossier `site` (ou le zip décompressé).
3. Netlify donne une adresse publique. Vous pouvez la renommer dans les réglages du site.

## GitHub Pages
1. Créez un dépôt public et envoyez-y le contenu du dossier `site`.
2. Réglages > Pages > Source : branche `main`, dossier `/ (root)`.
3. Le site est disponible sur `https://<utilisateur>.github.io/<dépôt>/`.

## Cloudflare Pages
Créez un projet, choisissez « Upload assets », déposez le dossier `site`.

## Mettre à jour
Remplacez `index.html` et redéployez. Les hypothèses saisies par les visiteurs ne sont pas enregistrées : elles se réinitialisent au rechargement.
