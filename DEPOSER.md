# Déposer votre travail d'atelier

Deux chemins. Le premier est le plus simple.

## Avant de commencer

- Un compte GitHub : https://github.com/signup (gratuit).
- Claude Code installé (vous l'avez depuis l'atelier).
- Le dossier de ce que vous avez fabriqué pendant l'atelier.

## Chemin 1 : avec Claude Code

1. Ouvrez un terminal et tapez :

   ```bash
   git clone https://github.com/Valmartineau/config-ovni-ateliers.git
   cd config-ovni-ateliers
   claude
   ```

2. Dites à Claude :

   > Dépose mon travail de l'atelier du 11 novembre. Il est dans le dossier … (donnez le chemin).

3. Claude vous pose quelques questions (votre nom à afficher, le nom du projet, le besoin),
   copie vos fichiers, écarte ce qui ne doit pas sortir, et remplit la fiche.

4. Claude vous montre la liste de ce qui va être publié. **Rien ne part sans votre « oui ».**

5. Claude envoie une proposition de dépôt (une « pull request »). Valentin la relit et l'accepte.
   Votre travail apparaît alors dans le dépôt.

La première fois, Claude vous demandera de vous connecter à GitHub (`gh auth login`) :
suivez ce qui s'affiche, tout se passe dans le navigateur.

## Chemin 2 : à la main

1. Sur la page du dépôt, cliquez sur **Fork** (en haut à droite) : vous obtenez votre copie.
2. Clonez votre copie, puis créez votre dossier :
   `ateliers/<date de l'atelier>/<prénom ou pseudo>/<nom du projet>/`
3. Copiez-y vos fichiers et une `FICHE.md` (modèle : `gabarits/FICHE.md`).
4. Vérifiez la liste « Ce qui ne doit jamais être déposé » du `README.md`.
5. Enregistrez et envoyez (`git add`, `git commit`, `git push`), puis ouvrez une pull request vers ce dépôt.

## Ça coince ?

Écrivez à cabinet@ovniconseil.fr en joignant le message d'erreur tel qu'il s'affiche.

## Retirer ou corriger un dépôt

Vous pouvez corriger votre dossier par une nouvelle proposition, ou demander son retrait à
cabinet@ovniconseil.fr. À savoir : ce qui a été publié sous CC BY 4.0 reste réutilisable
par ceux qui l'ont déjà copié.
