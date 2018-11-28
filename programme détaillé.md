---
layout: page
title: Programme détaillé
tagline: Programme détaillé
published: false
---

## Programme détaillé

### Créons un projet commun de gestion des réseaux d'eau avec QGIS et PostGIS - Régis Haubourg - OSLANDIA

La gestion des réseaux d'eau potable, assainissement et écoulements pluviaux est en pleine restructuration avec les transferts de compétences en cours dans les collectivités territoriales.
Les enjeux de connaissance précise des réseaux sont renforcés, et s'imposent également aux plus petites collectivités - souvent démunies d'infrastructure géomatique. Un géostandard RAEPA COVADIS est disponible pour l'échange de données. 
De nombreuses collectivités ou acteurs privés développent leurs propres solutions sur briques Open Source. 

Dans ce contexte, l'absence de projet open source partagé et de mutualisation de besoins et de ressources est criant, alors que de l'autre coté de la frontière Franco-Suisse, des communes lancent une série de projet Open Source pour la gestion des réseaux d'utilités publiques sur base QGIS et PostGIS 
Nous proposons un tour d'horizon des projets existants, des acteurs activement intéressés par la mise en oeuvre de projets communautaire Open Source français. 
Quelle stratégie pour démarrer? Quel modèle de données ? Quelle stratégie Open Source, communautaire et quelle gournvernance souhaitons nous face à des besoins parfois différents ? Quel structuration d'un groupe d'intérêt utilisateurs pour piloter cela au travers de l'OSGEO-FR ?"	Je propose ça - désolé pour le délai, suite à des discussions aux pgsessions avec au moins 5 personnes motivées pour démarrer une communauté. Idéalement, si Charente Eau propose une présentation alternative, je peux laisser ma place

### Présentation d'un outil de création / numérisation des éléments graphiques d'un Plan Local d'Urbanisme Intercommunal (PLUI) dans un eco-système QGIS & PostGis - Grenoble Alpes Métropole - Vo	Anh Tam	PLUI Versionning	

L'outil permet la gestion de version en utilisant des notions de cycle, versions, projets ... 
L'application repose sur un développement lourd en base accompagné de fonction python et d'actions QGIS.

### Structurer et fédérer les développements : les QEPs	- Camptocamp - Yves Jacolin 

"Structurer et fédérer un projet passe par une organisation de la communauté : comment communiquer, comment sont prises les décisions, quelles modifications seront apportées au code, comment dynamiser un projet.

Cette présentation montrera un des aspects de cette structuration : la rédaction des propositions d'améliorations (QEP) au travers de différents exemples de QEP réalisées (ou en attente). Comment et pourquoi rédiger ces propositions, à quel moment. Pourquoi la communauté des utilisateurs doivent ils s'y intéresser ?"	

### Développement de plugins procéduraux orientés métier - IRSTEA - Mathieu Chailloux

L'extension 'processing' permet de regrouper et d'uniformiser les algorithmes disponibles. La création de nouveaux scripts ou de nouvelles chaînes de traitement s'intègre très bien dans cet environnement, notamment par la création automatique d'interfaces graphiques unifiées respectant une même charte graphique.

Dans le cas de chaînes de traitement complexes à destination d'utilisateurs métier n'ayant pas de compétences avancées en SIG, le regroupement des paramètres de chaque étape au sein d'une même fenêtre complexifie le paramétrage et la prise en main de l'outil.
Cette présentation revient sur un exemple de développement, le plugin BioDispersal, et propose des suggestions d'améliorations comme la possibilité de créer un onglet par étape ou de sauvegarder un paramétrage.


### AZIMUT - Jean-Marie ARSAC	Migration vers QGIS dans un syndicat d'électricité	

Présentation de la migration d'un syndicat d'électricité d'outils propriétaires orientés DAO vers QGIS et PostgreSQL/PostGIS dans le cadre de la réforme anti-endommagement des réseaux dite réforme DT-DICT.


### Hy2roresO: un plugin QGIS dédié à la hiérarchisation automatique de réseaux hydrographiques - Ecole Nationale des Sciences Géographiques - Cécile Duchêne

Nous proposons de présenter un plugin QGIS, développé par trois étudiants ingénieurs dans le cadre d'un projet développement. Ce plugin, nommé Hy2roresO, permet de hiérarchiser un réseau hydrographique en calculant automatiquement sur les tronçons hydrographiques de la couche en entrée les ordres de Strahler, Shreve et Horton. Le calcul de l'ordre de Horton suppose de grouper les tronçons en ""cours d'eau"": l'algorithme implémenté fait cela sur un critère de toponyme si des toponymes sont renseignés, et à défaut sur des critères de continuité géométrique, selon des principes proposés par Thomson et Brooks (2000) et Touya (2007). En sortie, le plugin étiquette aussi les tronçons appartenant à un même cours d'eau avec un même identifiant. L'algorithme implémenté par ce plugin a la particularité de gérer des cas complexes non gérés par les plugins de notre connaissance (v.stream.order de GRASS, par exemple): il s'agit des cas où le réseau présente des cycles dus à la présence d'îles, de groupes d'îles ou de chenaux anastomosés.

Hiérarchiser un réseau hydrographique peut servir à en extraire des tronçons ayant des caractéritiques similaires en terme d'importance au sein du réseau, à simplifier le réseau et l'élaguant (généralisation) comme proposé par Thomson et Brooks (2000), cela peut également contribuer à la caractérisation du relief par l'extraction de ""fonds de vallées"" définis comme des zones plates traversées par un cours d'eau ayant un ordre suffisamment élevé dans la hiérarchie (Straumann et Purves 2008).

Le plugin Hy2roresO part du postulat que les tronçons hydrographiques sont orientés dans le sens de l'écoulement de l'eau. Il possède un module de vérification du sens des tronçons, qui signale à l'utilisateur les tronçons dont le sens est suspect compte tenu des angles d'incidences, et lui permet de corriger (ou non) ce sens tronçon par tronçon.

Le plugin Hy2roresO est en cours de dépôt en open source, il est accompagné d'une documentation contenant un manuel utilisateur, et qui décrit également en détail le fonctionnement de l'algorithme sous-jacent, disponible ici: https://hy2roreso.readthedocs.io/. Nous souhaitons le faire connaître auprès des utilisateurs qui pourraient être intéressés (nous en avons déjà identifiés quelques-uns), d'une part pour favoriser sa réutilisation, d'autre part pour qu'il puisse être testé pour des usages variés et amélioré en conséquence.

### Intégration et déploiement de QGIS via Openshift dans un portail GeoMapFish	QGIS server couplé à QGIS permet de déployer facilement des services OGC - Camptocamp - Yves Jacolin

Cette facilité peut être accrue en utilisant des outils de déploiement et de virtualisation. Cette présentation montrera comment QGIS est intégré dans une infrastructure de déploiement automatisé dans un portail GeoMapFish à l'aide de docker et OpenShift.	Cette présentation ne sera pas une présentation technique et s'adresse à des utilisateurs qui souhaitent automatiser leur processus de déploiement QGIS Server.

### QGIS, les enjeux d'une alternative - Antea Group - Robin PREST

Cette présentation se penche sur les freins et les atouts qui ont permis en quelques années à Antea Group de basculer les pratiques et usages hérités d'un organisme public vers une démarche plus ouverte et innovante en se basant sur une démocratisation et une pratique encouragée du logiciel QGIS.

Le titre de cette présentation s'inspire de la démarche de migration d'une pratique de logiciels propriétaires vers de l'open source évoquée dans le mémoire du CNAM de (feu) Frédéric LABBE, ""Suite bureautique, les enjeux d'une alternative"", 24/06/2003, CNAM"

### Le plugin cadastre - Intégration et exploitation des données cadastre - 3Liz - Michaël Douchin

Le plugin cadastre a été initié par l'Agence d'Urbanisme du Grand Amiénois (ADUGA) avec le soutient de la Région Picardie, le Fonds Européen de Développement Régional de Picardie et l'Union Européenne.
Ce plugin permet aux utilisateurs des données cadastrales françaises de constituer une base de données à partir des fichiers EDIGeo et MajicIII. Il permet aussi de faire des recherches dans ces données et des générer des fiches de propriétaire et parcellaire.
Depuis sa publication en Novembre 2013, celui-ci a été principalement soutenu par l'ADUGA. La ville de Megève a financé le portage sur QGIS 3 cette année.


### Plugin Go2Mapillary - Une nouvelle approche de la cartographie - SOGEFI - Vincent ROBBE

Les images géolocalisées offrent une nouvelle dimension aux systèmes d'informations géographiques. Elles permettent de créer, d'améliorer et d'illustrer les données localisées.

Le plugin QGIS go2mapillary, développé en 2018, facilite l'exploitation des images acquises sur le terrain en offrant aux utilisateurs des fonctionnalités de visualisation, d'édition ou encore de mesure.

SOGEFI, contributeur actif de Mapillary, a développé un Kit d'acquisition d'images géolocalisées à 360° qui simplifie le versement des images sur Mapillary et leur exploitation dans QGIS.

Mapillary offre d'autre part de nouvelles perspectives grâce à la photogrammétrie (mesure d'objets) et au machine learning (détection d'objets).
