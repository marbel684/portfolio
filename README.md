# Portfolio de Marouane Belhaddade Zanati

Site statique en HTML, CSS et JavaScript, prêt à publier avec GitHub Pages. Aucun framework, aucune installation et aucune étape de compilation ne sont nécessaires.

## Contenu

- `index.html` : accueil et projets mis en avant
- `a-propos.html` : profil, formation et centres d'intérêt
- `projets.html` : sélection des projets
- `experiences.html` : parcours professionnel
- `competences.html` : langues, savoir-être et compétences techniques
- `contact.html` : coordonnées et recherche de stage
- `projet-*.html` : pages détaillées des projets
- `assets/` : styles, script, images, logo et CV PDF

## Publication sur GitHub Pages

1. Créer un dépôt GitHub nommé `portfolio` ou `mon-portfolio` et le définir en **Public**.
2. Dans le dépôt, cliquer sur **Add file → Upload files**.
3. Décompresser l'archive sur l'ordinateur, puis déposer **tout le contenu du dossier `portfolio-github`** dans le dépôt. Le fichier `index.html` doit se trouver à la racine du dépôt, et non dans un sous-dossier.
4. Cliquer sur **Commit changes**.
5. Ouvrir **Settings → Pages**.
6. Dans **Build and deployment**, choisir **Deploy from a branch**.
7. Sélectionner la branche `main`, le dossier `/(root)`, puis cliquer sur **Save**.
8. Après le déploiement, l'adresse du site apparaît dans **Settings → Pages**. Pour un dépôt nommé `portfolio`, elle ressemble à `https://PSEUDO.github.io/portfolio/`.

## Personnalisation

- Pour modifier les textes, ouvrir la page HTML correspondante et changer le texte situé dans le contenu de `<main>`.
- Pour changer les couleurs et la typographie, modifier les variables CSS au début de `assets/css/style.css`.
- Pour changer les images, remplacer les fichiers dans `assets/images/` en conservant leurs noms, ou adapter le chemin `src` dans le HTML.
- Pour mettre à jour le CV, remplacer `assets/documents/CV-Marouane-Belhaddade-Zanati.pdf` par le nouveau PDF en gardant le même nom.
- Les liens de navigation sont relatifs : ils fonctionnent avec l'adresse GitHub Pages du dépôt, même si le dépôt n'est pas le dépôt principal `PSEUDO.github.io`.

## Avant publication

Le dépôt GitHub et le site GitHub Pages doivent être publics avec l'offre gratuite. Le contenu du site, dont le CV, l'adresse e-mail et le numéro de téléphone, sera donc visible par toute personne qui possède le lien. Vérifier les coordonnées et les informations publiées avant le premier déploiement.
