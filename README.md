# Sujet - Workflow git

- [Sujet - Workflow git](#sujet---workflow-git)
  - [Objectifs](#objectifs)
  - [Prérequis](#prérequis)
  - [Livrables](#livrables)
  - [Date limite](#date-limite)
  - [Énoncé](#énoncé)
  - [Spécifications](#spécifications)
  - [Bonus](#bonus)
  - [Notation](#notation)
  - [Ressources](#ressources)


## Objectifs

Utiliser le workflow [Gitflow](https://www.atlassian.com/fr/git/tutorials/comparing-workflows/gitflow-workflow) pour couvrir le développement d'une simple application web de calculatrice.

## Prérequis

- Git installé sur votre machine
- Accès internet et à un dépôt central sur GitHub, GitLab, etc. (au choix)

## Livrables

**Déposer** votre travail **sur un dépôt git public** (GitHub, Gitlab, BitKeeper, etc.) et fournir **le lien du dépôt**. Le dépôt contiendra votre code source et un fichier `README` donnant les instructions pour installer et lancer le projet.

> Penser à utiliser un `.gitignore` pour éviter de pousser sur votre dépôt le contenu de `node_modules` !

**Envoyer** l'url du dépôt à l'adresse mail suivante: <a href="mailto:contact@pschuhmacher.com?subject=rendu - rvaluation Git workflow">contact@pschuhmacher.com</a>, avec le sujet suivant `rendu - rvaluation Git workflow`, ou cliquer simplement sur le lien précédent.

## Date limite

Vous avez jusqu'au ... pour me rendre votre travail. Un clone de votre dépôt sera fait à cette date. Le travail publié au-delà de cette date ne sera pas pris en compte.

> La date est fixée en classe

## Énoncé

On souhaiterait développer une application web de calculatrice. Le code doit fonctionner, mais l'historique de votre développement doit être *propre* et respecter les principes du workflow *Gitflow*. Une *attention particulière* sera apportée aux commentaires des commits.

1. [**Cloner** le dépôt suivant](https://github.com/paul-schuhm/tp1-mds-git-workflow-calculatrice) sur votre machine qui contient le projet dans un état initial non fonctionnel.
2. **Créer** le patch (un ensemble de commits) pour corriger l'application en utilisant le pattern *Gitflow*. 
3. **Développer** les fonctionnalités [définies dans le cahier des charges mis à votre disposition](#cahier-des-charges) en respectant le workflow **Gitflow** et en gardant *un historique propre*.

> Vous êtes libre d'utiliser des librairies ou des frameworks JS/CSS de votre choix.

## Spécifications

Voici la liste des exigences fonctionnelles de l'application :

- L'utilisateur·ice doit pouvoir choisir réaliser les opérations standards et bien définies suivantes: l'addition, la soustraction, la multiplication et la division;
- La calculatrice doit être simple à utiliser (un effort sur la mise en page sera apprécié);
- La calculatrice doit implémenter les fonctionnalités `CE` et `C`;
- La calculatrice conserve un historique des opérations réalisées durant la session;
- La calculatrice doit pouvoir manipuler des nombres entiers et décimaux;
- La calculatrice doit être documentée (manuel) pour que n'importe qui puisse l'utiliser.

## Bonus

> Vous ne sera pas pénalisé·es si vous n'implémentez pas ces spécifications

- Export CSV de l'historique du calcul (**2pts**)
- Manipuler la calculatrice avec les touches du clavier (**1pt**)

## Notation

- Respect du modèle Gitflow (penser à pousser toutes vos branches locales sur le dépôt central) (**8pts**)
- Historique des commits propre (messages des commits, corps de message éventuels justifiant nu choix éventuel etc.) (**4pts**)
- Un fichier `README.md`, bien formé, qui précise comment installer et exécuter votre application (**2pts**)
- La qualité du code (lisibilité, maintenabilité) (**2pts**)
- Implémentation de l'ensemble des spécifications (**4pts**)

> Utiliser le rebase interactif et le squash pour refactor votre historique de commits !

## Ressources

- [Le dépôt à cloner pour démarrer le projet](https://github.com/paul-schuhm/tp1-mds-git-workflow-calculatrice)
- [Une bonne application de calculatrice en ligne documentée](https://www.ma-calculatrice.fr/index.php), un exemple duquel s'inspirer
