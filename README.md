# voeuxdj.apir-radio.fr

Redirection minimale GitHub Pages vers le Google Form des vœux DJ APIR.

## Changer de formulaire

1. Ouvrir [`destination.js`](destination.js).
2. Cliquer sur le crayon **Edit this file**.
3. Remplacer uniquement l’URL entre guillemets.
4. Cliquer sur **Commit changes**.

La nouvelle destination sera publiée automatiquement. Il n’y a rien à changer dans le DNS, le domaine personnalisé ou les autres fichiers.

## Configuration

- Domaine : `voeuxdj.apir-radio.fr`
- Publication : branche `main`, dossier `/ (root)`
- DNS : `CNAME voeuxdj → apir-radio.github.io.`
- Indexation : désactivée par la balise `robots` de `index.html`
- Authentification supplémentaire : aucune

Le fichier `CNAME` doit rester présent. Le fichier `.nojekyll` désactive tout traitement Jekyll inutile.
