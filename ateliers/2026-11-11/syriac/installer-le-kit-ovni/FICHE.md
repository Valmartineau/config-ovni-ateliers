# Installer le kit Config OVNI quand on ne code pas

- **Auteur** : Syriac
- **Atelier** : Config OVNI, 12 et 13 novembre 2026
- **Licence** : CC BY 4.0
- **État** : ça marche à moitié. Les étapes 0 à 5 du kit sont installées, avec une vérification finale sans erreur. Les étapes 6 à 10 restent à faire.

## Le besoin

Je dirige une TPE, je travaille seule et je n'écris pas de code.
Je voulais un Claude Code qui me connaisse, qui m'explique simplement et qui demande mon accord avant toute action risquée.

## Ce que ça fait

Le kit est installé et réglé pour moi :
- **une fiche de consignes personnelle**, que Claude relit à chaque session. Elle contient :
  - le français et le vouvoiement ;
  - des explications simples, en listes ;
  - l'obligation de demander mon accord avant d'envoyer, de publier, de supprimer ou de payer ;
  - la liste des dossiers privés interdits.
- **11 savoir-faire (skills)** : des recettes lancées par une commande. Exemple : `/session-note` archive la session.
  - Celui du travail autonome sur du code reste **verrouillé** tant qu'aucun dossier autorisé n'est déclaré. C'est voulu.
- **3 réflexes automatiques (hooks)**. Exemple : au démarrage, Claude vérifie si la note du jour existe.
- **La ligne d'information** en bas de l'écran (status line).
- **Un carnet Obsidian** : Claude y range une note par session, avec ce qui a été fait, les décisions et ce qui reste à faire.

## L'interface

- Le terminal et Claude Code. Je parle en français ; Claude fait les manipulations.
- Les commandes du kit, qui commencent par `/`.
- Obsidian, pour relire les notes de session.

## Pour le relancer

1. Télécharger le kit Config OVNI.
2. Ouvrir Claude Code dans son dossier.
3. Demander à Claude de suivre le guide d'installation fourni avec le kit.
4. Répondre à ses questions, et dire « je ne comprends pas » dès que c'est le cas.

Prévoir une matinée sans interruption. Une pause en cours de route ne pose pas de problème : la reprise se fait à l'étape suivante.

## Ce qui a coincé

- **Les explications trop techniques.** Au début, Claude m'a montré un tableau de fichiers, de réglages et de symboles d'erreur, et je n'ai rien compris.
- **Ce qui a débloqué** : dire simplement « explique-moi différemment ». La deuxième explication passait par un exemple concret (« lundi vous faites ceci, mardi Claude se souvient de cela »), et j'ai compris.
- **Ce que je ferais autrement** : écrire dès le départ, dans la fiche de consignes, **comment je veux qu'on m'explique les choses**.
- **Un intérêt découvert après coup** : un matin, la session de la veille n'apparaissait pas dans la liste de reprise de Claude Code. La note du carnet m'a permis de repartir sans rien perdre.

## Ce qui a servi

- Le kit **Config OVNI** de Valentin Martineau (OVNI Conseil), sous licence CC BY-NC 4.0. Rien n'en est recopié ici : cette fiche est un retour d'expérience.
- **Obsidian**, pour le carnet de notes.
