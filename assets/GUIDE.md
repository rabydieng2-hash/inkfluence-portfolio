# Guide simple pour modifier et publier le portfolio Inkfluence

## 1. Ouvrir le projet dans Visual Studio Code

1. Ouvre Visual Studio Code.
2. Clique sur `File` puis `Open Folder`.
3. Choisis ce dossier :
   `C:\Users\rabyd\Documents\Codex\2026-05-21\files-mentioned-by-the-user-inkfluence`
4. Ouvre le fichier `index.html` pour modifier les textes.
5. Ouvre le fichier `styles.css` pour modifier les couleurs, tailles et espacements.

## 2. Voir le site sur ton ordinateur

La methode la plus simple :

1. Dans VS Code, installe l'extension `Live Server`.
2. Clique droit sur `index.html`.
3. Clique sur `Open with Live Server`.

Ton site s'ouvrira dans ton navigateur.

## 3. Ce que tu peux modifier facilement

Dans `index.html` :

- Le nom `Inkfluence`
- Le grand titre de la page
- Les descriptions des services
- L'adresse email
- Les liens Facebook et LinkedIn

Dans `styles.css` :

- `--purple` pour le violet principal
- `--pink` pour la couleur rose
- `--lime` pour la couleur verte
- `--bg` pour la couleur de fond

## 4. Mettre le site sur GitHub sans terminal

1. Va sur https://github.com et connecte-toi.
2. Clique sur `New repository`.
3. Donne un nom au projet, par exemple `inkfluence-portfolio`.
4. Choisis `Public`.
5. Clique sur `Create repository`.
6. Sur la page du nouveau projet, clique sur `uploading an existing file`.
7. Glisse ces fichiers et dossiers dans la page :
   - `index.html`
   - `styles.css`
   - `GUIDE.md`
   - le dossier `assets`
8. Clique sur `Commit changes`.

## 5. Publier gratuitement sur Vercel

1. Cree un compte sur https://vercel.com.
2. Connecte Vercel a ton compte GitHub.
3. Dans Vercel, clique sur `Add New`, puis `Project`.
4. Choisis le projet GitHub `inkfluence-portfolio`.
5. Garde les reglages par defaut.
6. Clique sur `Deploy`.

Apres quelques secondes, Vercel te donnera un lien public que tu pourras partager.

Documentation officielle utile :

- https://vercel.com/docs/getting-started-with-vercel/import
- https://vercel.com/docs/deployments/git

## 6. Structure du projet

- `index.html` : le contenu de la page.
- `styles.css` : le design de la page.
- `assets` : les images du site.
