---
title: "LIRIA : OCR et extraction d'informations à partir de documents adminsitratifs"
summary: Les administrations ont régulièrement besoin d’exploiter en masse des documents administratifs sous des formats non directement exploitable (PDF scannés, images, etc.). L’information contenue dans ces documents, pour être exploitée, doit passer par une étape d'extraction et de structuration de l’information, qui est vite très chronophage si elle doit être réalisée à la main.
responsible: Kim Montalibet (DINUM)
images: 
- /img/atelier_ideation.png
---

#### Les défis data science associés

   * _OCR_ : de 3 types tapuscrit, manuscrit, tableau 
   * _Extraction d'informations_ : à partir de tableaux, de texte, de documents avec textes/ éléments visuels (de type cartes d'identités, bulletins de salaires)


#### Exemples de cas d'usage

* Ministère des Armées: fiches de poste, rapports du contrôle général des armées (on peut avoir des mélanges entre écritures manuscrites et tapuscrites)
* Haute Autorité de la Santé: rapports des recommandations professionnelles (PDF numérisés): extraire info pour construire un arbre de décision
* INSEE : 1) la numérisation de tickets de caisse collectés par l’enquête budget des familles 2) extraire les tableaux des comptes sociaux (données, API INPI). PDF scannés. Objectif: extraire les données des tableaux
* Services statistiques ministériels: ont beaucoup publié par le passé en format papier (numérisation puis structuration automatique des informations présentes dans ces publications pourraient permettre de publier ces données en open data afin de rendre possible des réutilisations par des chercheurs, data scientists) 
* La start-up d'Etat [Dossier Facile](https://www.dossierfacile.fr/) : OCR et extraction d'informations sur les cartes d'identités, bulletins de salaires, quittances de loyer 

#### Les objectifs

- Dans un premier temps, il s'agira de faire l'état des lieux des travaux déjà réalisés dans le domaine, de partager des retours sur les librairies testées et de centraliser ces éléments dans une documentation de tpe wiki. 
- Dans un 2eme temps, prioriser les cas d'usages identifiés et dévelepper des briques open source pour y répondre. 

