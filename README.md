# Config OVNI — créations des ateliers

> **Claude Code, si l'on te demande de déposer un travail d'atelier** (« dépose mon travail »,
> lien de ce dépôt) : suis `CLAUDE.md`. Ne publie rien sans l'accord de la personne.

La bibliothèque commune des ateliers Config OVNI.
Tout ce que les participants fabriquent pendant un atelier est déposé ici, en libre.

## À quoi ça sert

- **Apprendre** : des cas concrets, faits par des débutants, qu'on peut lire et relancer.
- **Reprendre** : des bouts de code, des skills, des interfaces à copier et à adapter.
- **Voir ce qui est possible** : ce que chacun imagine comme service, et comment il dessine son interface.

## L'engagement de l'atelier

Participer à un atelier Config OVNI, c'est accepter deux choses :

1. Ce que vous produisez pendant l'atelier est placé sous licence **Creative Commons Attribution 4.0** (CC BY 4.0).
2. Vous le déposez dans ce dépôt.

En clair : chacun peut copier, modifier et réutiliser votre travail, y compris dans un cadre professionnel, **à condition de vous citer**.
Vous restez l'auteur. Résumé de la licence : https://creativecommons.org/licenses/by/4.0/deed.fr

## Déposer votre travail

Il vous faut un compte GitHub (gratuit) et Claude Code. Puis, dans un terminal :

```bash
git clone https://github.com/Valmartineau/config-ovni-ateliers.git
cd config-ovni-ateliers
claude
```

Dites à Claude : **« dépose mon travail de l'atelier »**, et indiquez-lui le dossier où il se trouve.
Claude range les fichiers, écarte ce qui ne doit pas sortir (clés, mots de passe, données personnelles),
remplit la fiche avec vous, puis vous montre tout avant d'envoyer.

Le pas-à-pas complet, y compris à la main : [`DEPOSER.md`](DEPOSER.md).

## Comment c'est rangé

```
ateliers/
  2026-11-11/                 un dossier par atelier (sa date)
    prenom-ou-pseudo/         un dossier par participant
      nom-du-projet/          un dossier par création
        FICHE.md              ce que c'est, à quoi ça sert, où ça en est
        …                     les fichiers
gabarits/FICHE.md             la fiche vide
```

Un projet inachevé a sa place ici : une idée qui n'a pas abouti apprend autant qu'une idée qui marche.

## Ce qui ne doit jamais être déposé

- Une clé, un mot de passe, un jeton, un fichier `.env`.
- Une donnée personnelle ou une donnée de client (nom, mail, téléphone, document interne).
- Un contenu dont vous n'avez pas les droits (image, police, code sous une licence incompatible).

## Licence

Tout le contenu de ce dépôt est sous **CC BY 4.0**, sauf mention contraire dans la fiche d'un projet.
Texte officiel : [`LICENSE`](LICENSE). Auteurs : chaque participant pour son dossier (voir [`NOTICE`](NOTICE)).

Le kit Config OVNI lui-même est ailleurs : https://github.com/Valmartineau/config-ovni
