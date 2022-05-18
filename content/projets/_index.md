---
title: "Les projets 10%"
description: Les derniers projets 10%
---

Le programme 10% vise à développer des projets d'intérêt communs en interministériel.

## Proposez vos idées de projets d'intérêt commun 

Vous êtes agent public et vous souhaitez nous faire part d'une idée de projet à dimension interministérielle, vous pouvez nous en faire part en répondant à notre [questionnaire projet](https://framaforms.org/appel-a-idees-de-projets-programme-10-pourcent-1648137237). 


## Les projets retenus suite à l'atelier d'idéation du 16 mai 

### Template de description de projet 

Courte description du projet. 

* Porteur : 
* La problématique identifiée
* Les ambitions du projet / Les livrables attendus 
* Les profils recherchés :  
* Pourquoi rejoindre le projet ? 
* Code source : 
Bouton "je participe " -> lien vers le questionnaire 


<figure class="fr-content-media fr-content-media--sm">
    <div class="fr-content-media__img">
        <img src="" alt="Illustration du projet">
    </div>
</figure>



### OCR et extraction d'informations à partir de documents adminsitratifs

#### La problématique identifiée:
Les administrations ont régulièrement besoin d’exploiter en masse des documents administratifs sous des formats non directement exploitable (PDF scannés, images, etc.). 
L’information contenue dans ces documents, pour être exploitée, doit passer par une étape d'extraction et de structuration de l’information, qui est vite très chronophage si elle doit être réalisée à la main.

#### Les défis data sciences associés :
- OCR : de 3 types tapuscrit, manuscrit, tableau 
- Extraction d'informations : à partir de tableaux, de texte, de documents avec textes/ éléments visuels (de type cartes d'identités, bulletins de salaires)


#### Les différents cas d'usage: 
* Ministère des Armées: fiches de poste, rapports du contrôle général des armées (on peut avoir des mélanges entre écritures manuscrites et tapuscrites)
* Haute Autorité de la Santé: rapports des recommandations professionnelles (PDF numérisés): extraire info pour construire un arbre de décision
* INSEE : 
  * la numérisation de tickets de caisse collectés par l’enquête budget des familles. 
  * extraire les tableaux des comptes sociaux (données, API INPI). PDF scannés. Objectif: extraire les données des tableaux
* Services statistiques ministériels: ont beaucoup publié par le passé en format papier (numérisation puis structuration automatique des informations présentes dans ces publications pourraient permettre de publier ces données en open data afin de rendre possible des réutilisations par des chercheurs, data scientists) 
* La start-up d'Etat [Dossier Facile](https://www.dossierfacile.fr/) : OCR et extraction d'informations sur les cartes d'identités, bulletins de salaires, quittances de loyer 

#### Les objectifs : 
- Dans un premier temps, il s'agira de faire l'état des lieux des travaux déjà réalisés dans le domaine, de partager des retours sur les librairies testées et de centraliser ces éléments dans une documentation de tpe wiki. 
- Dans un 2eme temps, prioriser les cas d'usages identifiés et dévelepper des briques open source pour y répondre. 

