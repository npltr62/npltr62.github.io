---
title: WebPDPG
summary: Interface WEB de consultation du PDPG.
date: 2023-10-24
type: docs
math: false
tags:
  - Python
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
---

La **Fédération de Maine-et-Loire pour la Pêche et la Protection du Milieu Aquatique** a initié l'idée d'un outil cartographique permettant la mise à disposition et une mise à jour en continue de :

  -  Données scientifiques
  -  L'expertise sur l’état des milieux aquatiques et des ressources piscicoles
  -  L’état d’avancement des actions.

<video src="demo.mp4" controls></video>

## Qu’appelle-t-on le PDPG ?

La mise en place de plans de gestion relève des obligations légales des Fédérations pour la Pêche et Protection des Milieux Aquatiques. En effet, l’article L. 433-3 du Code de l’Environnement indique que « l’exercice d’un droit de pêche emporte obligation de gestion des ressources piscicoles. Celle-ci comporte l’établissement d’un plan de gestion ».

Le PDPG est:
> Un document technique et complet destiné aux gestionnaires des milieux aquatiques, mais également un instrument de référence pour argumenter les revendications du monde de la pêche dans les négociations avec les autres usagers.

Pour cela, le PDPG diagnostique l’état du milieu en utilisant les poissons comme indicateurs de la qualité du milieu. L’objectif final étant de restaurer, gérer et protéger durablement les milieux aquatiques et les ressources piscicoles de nos rivières, fleuves et grands lacs littoraux.

Le Plan Départemental pour la Protection des milieux aquatiques et la Gestion des ressources piscicoles (**PDPG**) est un outil de programmation des Structures Associatives de la Pêche de Loisir pour la gestion des milieux aquatiques et des peuplements piscicoles.Le PDPG est un document technique qui permet la coordination de la gestion piscicole à l’échelle départementale. Ses objectifs sont :

  - D’évaluer la qualité et la fonctionnalité des peuplements piscicoles à l’échelle des contextes,
  - De définir un cadre d’action pour l’amélioration de chaque contexte,
  - D’être un outil de communication auprès des autres acteurs / usagers du milieu aquatique.
  
## Déploiement de l'outil

En aout 2020, j'ai été recruté en tant que Géomaticien afin de dévellopper un outil cartographique.

### Etat des lieux
D'un point de vue interne, la FD49 ne possédant pas de base de données, il a fallu faire l'inventaire des données existantes.
  - Une base de données Access
  - Fichiers Excel

Ensuite faire l'inventaire des données externe nécessaires au PDPG
  - Les données du Sandre
  - BDTopage
