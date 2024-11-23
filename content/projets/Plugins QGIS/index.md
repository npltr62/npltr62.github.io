---
title: Plugins QGIS
summary: Outils facilitant les manipulations des utilisateurs
type: docs
math: false
date: '2024-05-07'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
Afin de récupérer ou de saisir des données, il était necessaire de créer quelques outils {{< icon name="python" >}}Python. J'ai donc développé une barre d'outils {{< icon name="qgis" icon_pack= "custom" >}} Qgis avec plusieurs plugins.

## Création d'un entrepot de plugins

Il était nécessaire de pouvoir versionner et mettre en ligne les plugins, pour cela j'ai créé [un dépôt GitLab](https://gitlab.com/npltr62/pluginsfd49)

### Mise en ligne

- GitLab Pages s’appuie sur un pipeline de CI/CD (Intégration Continue / Déploiement Continu) pour générer et déployer le site.
- Ce pipeline est défini dans le fichier `.gitlab-ci.yml` à la racine du dépôt, où l’on peut spécifier les étapes de génération du site.
- Une fois le pipeline exécuté, les fichiers générés sont déployés pour être accessibles sur GitLab Pages.
- Par convention, les fichiers de sortie qui doivent être publiés sur GitLab Pages doivent être placés dans un dossier nommé **`public`**. Ce dossier est ensuite copié par le pipeline vers le serveur de pages pour être servi au public.
Qgis demande un `.zip` pour être installé
![screen reader text](gitlab_page.PNG "Page déployé en statique par GitLab")

### Dossier public

On y trouve le dossier du plugin compressé `FD49.zip` 
Le fichier cible du dépôt est le fichier `plugins.xml`, il permet à Qgis de lire les informations (nom des plugins, date de mise à jour, détails, tags...).
ensuite le dossier du plugin est au format .zip 