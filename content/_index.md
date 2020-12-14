+++
title = "PgMetadata"
outputs = ["Reveal"]
[logo]
src = "3liz.png"
alt = "Product logo"
width = "7%"
+++

## PgMetadata

### Stocker des métadonnées dans PostgreSQL

QGIS-Fr 


🦎

16-12-2020

---

## 3Liz

* QGIS et PostgreSQL lovers
* QGIS contributeurs (serveur principalement)
* 8 employées
* Société de Services Open-Source
* QGIS, QGIS-Serveur, PostgreSQL, Lizmap
* Développement formation, hébergement Lizmap, support
* https://www.3liz.com

---

## Petit état des lieux de la métadonnées dans QGIS

---

### QEP

* QGIS Enhancement Proposal

* https://github.com/qgis/QGIS-Enhancement-Proposals/issues

---

## QEP numéro 91, 2017

### Découpe en multiples "Work Package"

* Schéma interne des métadonnées dans QGIS
* API Métadonnées
* Stockage
* Visualisateur
* Métadonnées au niveau d'une couche
* Métadonnées au niveau du projet
* Export : Dublin Core...  
* ...

https://github.com/qgis/QGIS-Enhancement-Proposals/issues/91

---

## QGIS 3.0

Février 2018

---

### Panneau édition

#### Vecteurs et rasters

![Vector editor](vector_editor_qgis.jpg)

Vecteur et rasteur

---

### Panneau visualisation

![Vector viewer](visualisation.jpg)

---

## Ajouts progressifs

* QGIS 3.2 : Juin 2018
  * Ajout de l'édition pour un projet
* QGIS 3.16 : Juin 2020
  * Ajout de l'édition pour les mesh

---

## État actuel

* Enregistrement possible : 
  * QMD : QGIS MetaData, XML propre à QGIS
  * Au sein du projet QGS/QGZ

---

# Prototype récurrent

* Petit projet maison d'une table de métadonnées dans PostgreSQL

* Réalisation d'une table : `schema`, `table`, `abstract`, `title` etc

---

Début sur CKAN

---

Début du projet PgMetadata

---

## Quelques tables

![Tables](https://docs.3liz.org/qgis-pgmetadata-plugin/database/diagrams/summary/relationships.real.compact.png)

https://docs.3liz.org/qgis-pgmetadata-plugin/database/relationships.html

---

## Quelques fonctions/triggers

Calcul des entités, CRS, emprise, fiche valide etc

https://docs.3liz.org/qgis-pgmetadata-plugin/database/routines.html

---

### Côté administrateur de données

* Projet QGIS

---

### Côté utilisateurs finaux

---

### Recherche dans les commentaires de la table

![Search comment](search_comment.jpg)

---

### Locator

IMAGE LOCATOR

---

## Intégration dans Lizmap

Lizmap, outil open-source de publication sur le web d'un projet QGIS
https://www.lizmap.com

Développment d'un module

https://github.com/3liz/lizmap-pgmetadata-module

---

### Plateforme Lizmap du Gard

https://sig.gard.fr/index.php/view/map/?repository=commun&project=A_Dns_ouvertes_2019

![CD30](cd_30.png)

---

### Liens

#### Extension QGIS
* Documentation utilisateur
* Schéma de la base de données
* Traitement Processing
https://docs.3liz.org/qgis-pgmetadata-plugin/

### Module Lizmap
* https://github.com/3liz/lizmap-pgmetadata-module

---

### Merci de votre attention
