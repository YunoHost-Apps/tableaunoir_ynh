<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Tableaunoir pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/tableaunoir)](https://ci-apps.yunohost.org/ci/apps/tableaunoir/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/tableaunoir)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/tableaunoir)

[![Installer Tableaunoir avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tableaunoir)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Tableaunoir rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Tableaunoir est un outil de tableau noir collaboratif en ligne avec des aimants pour réfrigérateur disponibles dans de nombreuses langues. « Tableau noir » signifie tableau noir en français. Contrairement à de nombreux autres tableaux collaboratifs sur Internet, avec Tableaunoir vous pouvez créer des animations interactives via l'utilisation d'aimants pour réfrigérateur.

### Fonctionnalités

- Vous pouvez dessiner et effacer, avec votre souris ou une tablette graphique. Vous pouvez dessiner des formes.
- Collaborer pour éditer le même tableau en même temps (besoin d'un serveur pour cela), ne nécessite pas de compte
- Arrière-plans : portées pour l'enseignement de la musique, grille, images et documents PDF
- Vous pouvez également utiliser des sortes d'aimants de réfrigérateur prédéfinis que vous pouvez déplacer sur le tableau, pour faire des animations par exemple pour illustrer des algorithmes de tri, des algorithmes de graphes, etc. (et même jouer à Go !).
- Créez vos propres aimants de réfrigérateur pour des cours interactifs, en important n'importe quelle image, ou en transformant une partie du tableau (Ctrl + X).
- Palette de couleurs pour la craie,
- Dessinez des graphiques interactifs : les sommets sont des aimants, les étiquettes des sommets et des arêtes sont manuscrites mais sont mises à jour lorsque les sommets sont déplacés,
- Changez la couleur de l'arrière-plan des aimants,
- Chargez/Enregistrez le tableau actuel,
- Exportez en PNG ou PDF,
- Ajoutez des textes (Entrez et tapez), et déplacez des textes. Prend en charge LaTeX (en utilisant MathJax) !
- Passez d'un tableau blanc à un tableau noir, ou à n'importe quelle couleur d'arrière-plan
- Passez du curseur droitier (par défaut) au curseur gaucher,
- Divisez votre tableau en deux. Idéal pour l'enseignement. Ajoutez autant de nouveaux demi-planches que nécessaire, en allant à droite avec → puis à gauche/droite avec les flèches du clavier ←/→,
- Créez des diapositives, enregistrez des animations. Cela peut être utilisé pour préparer des diapositives pour une conférence ou pour une vidéo.


**Version incluse :** 0.1~ynh1

**Démo :** <https://tableaunoir.github.io/>

## Captures d’écran

![Capture d’écran de Tableaunoir](./doc/screenshots/screenshot.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://tableaunoir.github.io/>
- Dépôt de code officiel de l’app : <https://github.com/tableaunoir/tableaunoir>
- YunoHost Store : <https://apps.yunohost.org/app/tableaunoir>
- Signaler un bug : <https://github.com/YunoHost-Apps/tableaunoir_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/tableaunoir_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tableaunoir_ynh/tree/testing --debug
ou
sudo yunohost app upgrade tableaunoir -u https://github.com/YunoHost-Apps/tableaunoir_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
