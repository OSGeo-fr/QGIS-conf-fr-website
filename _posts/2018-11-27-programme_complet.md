---
layout: post
title: "Le programme définitif est disponible"
published: false
---

Deux jours de rencontres autour de QGIS

**Jeudi 13 décembre** Un [BarCamp](https://fr.wikipedia.org/wiki/BarCamp) et des ateliers communautaires et moment de convivialité en soirée

**Vendredi 14 décembre** Des conférences : 1 grand témoin QGIS.ch, 8 présentations, les nouveautés par les étudiants AgroTIC


# Jeudi
## Le Barcamp


La matinée sera consacrée à deux tournées d'ateliers barcamp sur le même modèle que les années précédentes, à savoir des ateliers d'une heure organisés en séance, suivis d'une restitution collective.  

* Le nouveau outil de mise en page et de génération de rapports

* Les fonctionnalités 3D

* Les nouveaux géotraitements

* Tout sujet qui vous intéresse !

## Ateliers communautaires (après midi)

L'après midi, nous changeons un peu, venez avec vos PC si vous en avez. **Pas de malentendu, on ne code pas :)**

* Atelier Traduction QGIS, documentation et site web.

L'interface de QGIS, la documentation et le site web sont multi-lingues. Profitons de l'après midi pour comprendre l'infrastructure [Transifex](https://www.transifex.com/qgis/QGIS/translate/#fr/qgis-application/149393953?q=translated%3Ano) et les bonnes pratiques de traduction, puis de faire avancer le chantier ensemble.  *Prérequis: QGIS 3.4 installé et un navigateur web.*

* Atelier rédaction de documentation et guide utilisateur QGIS.org.

La documentation de QGIS, les guides utilisateurs, les pas à pas sont des efforts communautaires. Venez apprendre à enrichir et corriger la documentation. Attention, rédaction en anglais obligatoire. *Prérequis :  QGIS 3.4.1 installé, un bon éditeur de texte et un outil de capture d'écran.*

* Atelier Gestion des tickets et participation aux tests utilisateurs.

2200 anomalies remontées, 1623 demandes de fonctionnalités demandées. [Le bug tracker](https://issues.qgis.org/) a besoin d'amour. Venez nous aider à faire le ménage, confirmer, rendre les bugs reproductibles! *Prérequis : parler un peu anglais, avoir osgeo4w avec les versions QGIS ltr - release et master installées*

Et on peut aussi continuer le barcamp en parallèle pour ceux qui le souhaitent.

## Soirée

Nous vous proposons de se retrouver le soir pour boire un verre ensemble et discuter sur QGIS ou n'importe quel sujet !

# Vendredi
## Le déroulé de la journée

| 9h00      | Accueil - café                                                                                                                                                                                                          |
|-----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 9h30      | Introduction OSGEO-FR                                                                                                                                                                                                   |
| 9h40      | Grand témoin Suisse QGIS.ch - Stéphane Malta (Ville de Neuchâtel)                                                                                                                                                       |
| 10h15     | QGIS, les enjeux d'une alternative - Robin PREST (Antea Group)                                                                                                                                                         |
| 10h40     | Créons un projet commun de gestion des réseaux d'eau avec QGIS et PostGIS - Régis Haubourg (Oslandia)                                                                                                                   |
| 11h05     | Structurer et fédérer les développements : les QEPs - Yves Jacolin (Camptocamp)                                                                                                                                        |
| 11h30     | Présentation des étudiants AGROTIC                                                                                                                                                                                      |
|           |                                                                                                                                                                                                                         |
| **12h30** | **Pause déjeuner**                                                                                                                                                                                                      |
|           |                                                                                                                                                                                                                         |
| 14h00     | Développement de plugins procéduraux orientés métier - Mathieu Chailloux (IRSTEA)                                                                                                                                      |
| 14h25     | Hy2roresO: un plugin QGIS dédié à la hiérarchisation automatique de réseaux hydrographiques - Cécile Duchêne et Alice Gonnaud (Ecole Nationale des Sciences Géographiques) |
| 14h50     | Présentation d'un outil de création / numérisation des éléments graphiques d'un Plan Local d'Urbanisme Intercommunal (PLUI) dans un eco-système QGIS & PostGis - Anh Tam Vo (Grenoble Alpes Métropole) |
| **15h15** | **Pause**                                                                                                                                                                                                               |
| 15h35     | Migration vers QGIS dans un syndicat d'électricité - Jean-Marie ARSAC (Azimut)                                                                                                                                            |
| 16h00     | Le plugin cadastre - Intégration et exploitation des données cadastre - Michaël Douchin (3Liz)                                                                                                                         |
| 16h25     | Clôture / remerciements                                                                                                                                                                                                  |
| **16h40** | **Fin**                                                                                                                                                                                                                 |


## Le détail des présentations

### QGIS.ch - le rôle et les actions du groupe utilisateurs Suisse

Par Stéphane Malta e Sousa, Responsable de projet SIT au canton de Neuchâtel

### QGIS, les enjeux d'une alternative
Cette présentation se penche sur les freins et les atouts qui ont permis en quelques années à Antea Group de basculer les pratiques et usages hérités d'un organisme public vers une démarche plus ouverte et innovante en se basant sur une démocratisation et une pratique encouragée du logiciel QGIS.

Le titre de cette présentation s'inspire de la démarche de migration d'une pratique de logiciels propriétaires vers de l'open source évoquée dans le mémoire du CNAM de (feu) Frédéric LABBE, *"Suite bureautique, les enjeux d'une alternative", 24/06/2003, CNAM*

**Par Robin Prest - Antea Group**

#### Créons un projet commun de gestion des réseaux d'eau avec QGIS et PostGIS

La gestion des réseaux d'eau potable, assainissement et écoulements pluviaux est en pleine restructuration avec les transferts de compétences en cours dans les collectivités territoriales.
Les enjeux de connaissance précise des réseaux sont renforcés, et s'imposent également aux plus petites collectivités - souvent démunies d'infrastructure géomatique. Un géostandard RAEPA COVADIS est disponible pour l'échange de données.
De nombreuses collectivités ou acteurs privés développent leurs propres solutions sur briques Open Source.

Dans ce contexte, l'absence de projet open source partagé et de mutualisation de besoins et de ressources est criant, alors que de l'autre coté de la frontière Franco-Suisse, des communes lancent une série de projet Open Source pour la gestion des réseaux d'utilités publiques sur base QGIS et PostGIS
Nous proposons un tour d'horizon des projets existants, des acteurs activement intéressés par la mise en oeuvre de projets communautaire Open Source français.
Quelle stratégie pour démarrer? Quel modèle de données ? Quelle stratégie Open Source, communautaire et quelle gournvernance souhaitons nous face à des besoins parfois différents ? Quel structuration d'un groupe d'intérêt utilisateurs pour piloter cela au travers de l'OSGEO-FR ?

**Par Régis Haubourg - Oslandia**

#### Structurer et fédérer les développements : les QGIS Enhancement Proposals alias QEP

Structurer et fédérer un projet passe par une organisation de la communauté : comment communiquer, comment sont prises les décisions, quelles modifications seront apportées au code, comment dynamiser un projet.

Cette présentation montrera un des aspects de cette structuration : la rédaction des propositions d'améliorations (QEP) au travers de différents exemples de QEP réalisées (ou en attente). Comment et pourquoi rédiger ces propositions, à quel moment. Pourquoi la communauté des utilisateurs doivent ils s'y intéresser ?

**Par Yves Jacolin - Camptocamp**



#### Développement de plugins procéduraux orientés métier

L'extension 'processing' permet de regrouper et d'uniformiser les algorithmes disponibles. La création de nouveaux scripts ou de nouvelles chaînes de traitement s'intègre très bien dans cet environnement, notamment par la création automatique d'interfaces graphiques unifiées respectant une même charte graphique.

Dans le cas de chaînes de traitement complexes à destination d'utilisateurs métier n'ayant pas de compétences avancées en SIG, le regroupement des paramètres de chaque étape au sein d'une même fenêtre complexifie le paramétrage et la prise en main de l'outil.
Cette présentation revient sur un exemple de développement, le plugin BioDispersal, et propose des suggestions d'améliorations comme la possibilité de créer un onglet par étape ou de sauvegarder un paramétrage.

**Par Mathieu Chailloux - IRSTEA**


### Hy2roresO: un plugin QGIS dédié à la hiérarchisation automatique de réseaux hydrographiques

Nous proposons de présenter un plugin QGIS, développé par trois étudiants ingénieurs dans le cadre d'un projet développement. Ce plugin, nommé Hy2roresO, permet de hiérarchiser un réseau hydrographique en calculant automatiquement sur les tronçons hydrographiques de la couche en entrée les ordres de Strahler, Shreve et Horton. Le calcul de l'ordre de Horton suppose de grouper les tronçons en "cours d'eau": l'algorithme implémenté fait cela sur un critère de toponyme si des toponymes sont renseignés, et à défaut sur des critères de continuité géométrique, selon des principes proposés par Thomson et Brooks (2000) et Touya (2007). En sortie, le plugin étiquette aussi les tronçons appartenant à un même cours d'eau avec un même identifiant. L'algorithme implémenté par ce plugin a la particularité de gérer des cas complexes non gérés par les plugins de notre connaissance (v.stream.order de GRASS, par exemple): il s'agit des cas où le réseau présente des cycles dus à la présence d'îles, de groupes d'îles ou de chenaux anastomosés.

Hiérarchiser un réseau hydrographique peut servir à en extraire des tronçons ayant des caractéritiques similaires en terme d'importance au sein du réseau, à simplifier le réseau et l'élaguant (généralisation) comme proposé par Thomson et Brooks (2000), cela peut également contribuer à la caractérisation du relief par l'extraction de ""fonds de vallées"" définis comme des zones plates traversées par un cours d'eau ayant un ordre suffisamment élevé dans la hiérarchie (Straumann et Purves 2008).

Le plugin Hy2roresO part du postulat que les tronçons hydrographiques sont orientés dans le sens de l'écoulement de l'eau. Il possède un module de vérification du sens des tronçons, qui signale à l'utilisateur les tronçons dont le sens est suspect compte tenu des angles d'incidences, et lui permet de corriger (ou non) ce sens tronçon par tronçon.

Le plugin Hy2roresO est en cours de dépôt en open source, il est accompagné d'une documentation contenant un manuel utilisateur, et qui décrit également en détail le fonctionnement de l'algorithme sous-jacent, disponible ici: https://hy2roreso.readthedocs.io/. Nous souhaitons le faire connaître auprès des utilisateurs qui pourraient être intéressés, d'une part pour favoriser sa réutilisation, d'autre part pour qu'il puisse être testé pour des usages variés et amélioré en conséquence.

**Par Cécile Duchêne - Ecole Nationale des Sciences Géographiques**

#### Présentation d'un outil de gestion d'un PLUi dans un eco-système QGIS & PostGis

L'outil PLUI Versionning permet la gestion de version en utilisant des notions de cycle, versions, projets ...
L'application repose sur un développement lourd en base accompagné de fonction python et d'actions QGIS.
Il a été conçu et est disponible en OpenSource sur Github et a été conçu en partenariat en la Metropole de Grenoble et l'agence d'urbanisme.

**Par Anh-Tam Vo - Grenoble Alpes Métropole**



### Migration vers QGIS dans un syndicat d'électricité

Présentation de la migration d'un syndicat d'électricité d'outils propriétaires orientés DAO vers QGIS et PostgreSQL/PostGIS dans le cadre de la réforme anti-endommagement des réseaux dite réforme DT-DICT.

**Par Jean-Marie Arsac - Azimut**

### Le plugin cadastre - Intégration et exploitation des données cadastre

Le plugin cadastre a été initié par l'Agence d'Urbanisme du Grand Amiénois (ADUGA) avec le soutient de la Région Picardie, le Fonds Européen de Développement Régional de Picardie et l'Union Européenne.
Ce plugin permet aux utilisateurs des données cadastrales françaises de constituer une base de données à partir des fichiers EDIGeo et MajicIII. Il permet aussi de faire des recherches dans ces données et des générer des fiches de propriétaire et parcellaire.
Depuis sa publication en Novembre 2013, celui-ci a été principalement soutenu par l'ADUGA. La ville de Megève a financé le portage sur QGIS 3 cette année.

**Par Michaël Douchin - 3Liz**
