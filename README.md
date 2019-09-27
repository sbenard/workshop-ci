# Atelier sur l'intégration continue

> This project contains all the documentation needed for a basic workshop on CI
implementation on a project versionned with Git. As this workshop is created for
[Paris Web](https://www.paris-web.fr/) 2019, all the content will be in French.
You are welcome to provide translations of this project.

Ce projet contient toute la documentation nécessaire pour un atelier basique sur
l'implémentation d'une intégration continue sur un projet versionné avec Git.
L'atelier étant préparé dans le cadre de [Paris Web](https://www.paris-web.fr/)
2019, le contenu sera entièrement écrit en français. Toute traduction est la
bienvenue.

Et maintenant, commençons !

## Pré-requis

Pour pouvoir suivre cet atelier en toute tranquilité, il vous faudra :
- avoir une connaissance basique de Git,
- avoir votre propre compte GitHub,
- à partir de votre compte, créer un fork de [ce présent
  dépôt](https://github.com/Ynote/workshop-ci).

## Déroulement de l'atelier

### 1. Brève (très brève) partie théorique

Nous allons expliquer les concepts de :
- intégration continue,
- livraison continue,
- déploiement continu.

### 2. Mise en place d'une intégration continue très basique

Nous vous proposons de mettre en place tous ensemble une intégration continue sur
ce présent projet avec [Codeship](https://codeship.com/). Le projet de ce dépôt
contient :
- un simple fichier écrit en Ruby
  `[hello_world.rb](https://github.com/Ynote/workshop-ci/blob/master/hello_world.rb)`,
- un fichier de test associé
  `[hello_world_spec.rb](https://github.com/Ynote/workshop-ci/blob/master/hello_world_spec.rb)`.

Il n'est pas nécessaire de connaître le langage Ruby pour pouvoir suivre ce
tutoriel. [Allons-y pas à pas !](/docs/codeship/basic-ci_FR.md).

### 3. Aller plus loin selon vos envies

Nous vous proposons de creuser vous-même les problématiques qui vous
intéressent. Plusieurs tutoriels sont à votre disposition en fonction de votre
envie :

#### Circle CI
- [Mise en place d'un CI basique](https://github.com/Ynote/workshop-ci/blob/master/docs/circle-ci/basic-ci_FR.md)
- Gestion des données persistentes (cache)
