---
title: Introduction
type: docs
---

# Documentation de Collec-Science

Vous trouverez ici l'ensemble de la documentation concernant le logiciel Collec-Science.

Elle a été élaborée à partir de fichiers Markdown, et utilise le moteur [hugo](https://gohugo.io/) avec le thème [hugo-book](https://themes.gohugo.io/themes/hugo-book/) pour le rendu. Les premières pages sont des copies de la documentation présente dans l'application, certains liens sont inopérants et certaines commandes de formatage n'ont pas été supprimées.

Si vous souhaitez contribuer à cette documentation :

- créez un _fork_ du dépôt [https://github.com/collec-science/docs](https://github.com/collec-science/docs)
- réalisez les changements dans la branche _develop_, et proposez ensuite des _request for merge_.

Les documents doivent être placés dans le dossier `content/fr/` ou `content/en/`. Les entrées du menu de gauche sont à déclarer dans le fichier `content/fr/menu/index.md` (ou `en` pour la version anglaise).

## Pour tester le site localement

Consultez la documentation de _hugo_ pour savoir comment configurer correctement votre environnement.

Pour un fonctionnement en local, vous devez vérifier que le fichier `hugo.toml` contienne la ligne suivante :

```
theme = 'hugo-book'
```

La ligne avec la présence de _github_ dans le chemin est utilisée pour la publication dans Github.

Pour démarrer le serveur _hugo_, dans le dossier contenant le code, lancez la commande suivante :

```
hugo server -minify
```
