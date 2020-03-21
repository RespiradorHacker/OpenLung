![Logo](images/OL_BANNER.png)

Ce document dans d'autres langues:

|[english](README.md)|[català](README-ca.md)|[français](README-fr.md)|[español](README-es.md)|[日本語](README-ja.md)|[汉语](README-zh-Hans.md)|[漢語](README-zh-Hant.md)|[português](README-pt_BR.md)|[nederlands](README-nl.md)|[Русский](README-ru.md)
|---|---|---|---|---|---|---|---|---|---|

# Respirateur - Ballon Autoremplisseur à Valve Unidirectionnelle (BAVU) à bas coût

- Ce projet a démarré lors de la pandémie globale du COVID-19 sous la forme d'une discussion de la communauté sur un groupe nommé Open Source COVID19 and OpenSourceVentilator, c'est la raison pour laquelle j'ai initié un nouveau projet Gitlab open source appelé **OpenLung**
- Plus spécifiquement lors d'une discussion autour des respirateurs d'urgence basés sur les **Ballons Autoremplisseurs à Valve Unidirectionnelle** (**BAVU** ou **Ambu-Bag**) à bas prix, nous avons évoqué les solutions qui ont été dévelopées dans le passé. [Le premier par une équipe de recherche du MIT](https://web.mit.edu/2.75/projects/DMD_2010_Al_Husseini.pdf) composée des personnes suivantes (Abdul Mohsen Al Husseini, Heon Ju Lee, Justin Negrete, Stephen Powelson, Amelia Servi, Alexander Slocum et Jussi Saukkonen). [Le second appareil d'une équipe d'étudiants en ingénierie mécanique de la Rice University](http://oedk.rice.edu/Sys/PublicProfile/47585242/1063096) composée des personnes suivantes (Madison Nasteff, Carolina De Santiago, Aravind Sundaramraj, Natalie Dickman, Tim Nonet et Karen Vasquez Ruiz).

*AVERTISSEMENT/CLAUSE DE NON RESPONSABILITÉ*: à chaque fois que c'est possible, merci de consulter l'avis d'un professionnel de santé possédant une formation sur un équipement adéquat. N'utilisez pas d'informations hasardeuses trouvées sur internet. Nous ne sommes pas des professionnels du domaine médical, juste des personnes sur internet.*

# Raisons d'utiliser un Ambu-Bag

- Produit massivement
- Composants certifiés
- Besoins mécaniques faibles et simples
- État de l'art de la recherche et des tests dans le domaine
- Adapté à la fois à l'intubation et aux masques

# Conditions requises par le projet

- Les conditions requises par le projet sont listées [ici](documentation/design-requirements.md).

# Avancement du project

![Concept Mécanique Actuel](images/CONCEPT_6_MECH.png)
*Concept Mécanique Actuel 6 avec certains problèmes connus*

# TO-DO (Nous avons besoin d'aide)

*Si vous pouvez nous assister dans les domaines suivant, merci de cloner ou de forker ce dépôt et de créer une merge request avec vos modification.*

- ~~Design d'un mécanisme de déclenchement en 3D plus complet~~
- ~~Spécifications d'un moteur efficace~~
- Spécifications dune interface (LCD et bouttons)
- Specifications de capteurs de feedback pour le PEEP, à bas voltage, pour évènements de pression haute ou basse
- Grandes lignes visuelles de l'interface

## EN COURS (Ce sur quoi nous travaillons à ce jour, le 17 Mars 2020)

- Organisation de la structure du Dépôt
- ~~Mise à jour du modèle CAD de l'Ambu-Bag~~
- Schéma d'interaction
- Construction d'une passerelle de communication avec le [projet de respirateur open source Ireland](https://opensourceventilator.ie/)
- Évaluation des méthodes actuelles de communication et de délégation

## TERMINÉ (Ce qui est fini)

- ~~Besoins en design~~

## Prochaines itérations d'amélioration


- ~~Raccordement perpendiculaire de l'arbre moteur/direction du à des problèmes de charge axiale~~
- ~~Simplification de la struction de la transmission~~
- ~~Réduction supplémentaire de la construction générale~~
