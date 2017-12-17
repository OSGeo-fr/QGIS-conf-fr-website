---
layout: page
title: Compte rendu du BarCamp
tagline: Nous remercions nos généreux sponsors !
---
# Retours sur la journée BarCamp du jeudi

Énorme succès cette année avec une affluence record!
A peu près deux fois plus de personnes qu'en 2016, une salle comble, et toujours un esprit très constructif et enthousiaste.

Cette année, évidemment nous avons eu beaucoup de questions autour de QGIS3, mais pas uniquement. Voilà une liste des sujets abordés:


##  Structurer l'association QGIS FR V1. Sujet traité deux fois !

  Comment ça marche ailleurs ?
  A quoi ça sert ?
  Comment on accélère?
  Certification, formation?
  Simplifier l'interlocuteur
  Neutralité
  Faciliter le lien local
  Financement
      Proactivité / explication logique OSS
      Marché national SGMAP

##  Structurer l'association QGIS FR V2. plus en détail !

  Préconisation QGIS.org :
  - Groupes d'intérêts
  - Ne pas shunter Georezo AFIGEO
  - Existe déjà mais informel
    - Liste mail
    - Droit de vote QGIS.org via Harrissou

  - Décryptage des groupes QGIS utilisateurs existants:

    - Suisse:
          Président Andreas Neumman. Membre du PSC QGIS. financeur de collectivité (QGIS server, et beaucoup de choses)
          Association selon les art. 60-79 du Code Civil (CC) suisse.
          Buts et activités
          Le groupe d’utilisateurs QGIS est composé de:
           ● membres individuels (privés)
           ● membres collectifs (entreprises, autorités, fac, écoles, assos)
           ● membres honoraires (individus au mérite sur vote)

          Ressources : cotisation, dons, autres
          AG annuelle + journée Utilisateurs annuelle
          Projets
              Application métier QGEP
              QGIS server et QWC2
              Export DXF
          Exemple de soutien 2016
              Amélioration du GPKG
              Import DWG
              Edition multiattribut

    - UK :soutenu osgeo UK
    
              personnes morales et physiques
              5 groupes régionaux
              blog

    - ITALIE :
    
              4 tarifs 375 € - > 3 votes
              mini > 250 euros 2 voix
              etudiants 25 euros

    - Portugal :
    
          structuration légère    
          un dépôt de plugins nationaux
          1 événement annuel

    - Pologne:

          peu d'infos

  - Synergies groupes association Postgresql FR :

      Appel récent des grandes entreprises pour le support de PostgreSQL par les grands éditeurs logiciels
      Asso indépendante depuis 2005
      5 groupes locaux
      traduction / livre blanc / forums aide
      pgday / dalibo / octopus db cap data
      400 euros / an entreprise
       20 euros particuliers
      Sponsor EDF, RATP, etc..
      Charte de com' normalisée (mail, sites, pas d'adresse perso, que des fonctions)
      Charte club entreprise
          Cooptation des entreprises
          Engagements de confidentialité

  - Feuille de route QGIS User FR :

        Changer les statuts de l'OSGEO-FR pour autoriser l'adhésion de personnes morales.
        Acheter qgis.fr
        Déplacer les pages osgeo fr qgis vers qgis fr
        Identifier des acteurs potentiels
        Chantier rédaction de statuts
        Lancer des meetup locaux (mode postgresqlfr ) indépendants
        Cotisation globale osgeofr + don ciblé thématique
        Favoriser le renouvellement des contributeurs!

-   Sous groupes ?
      - Entreprises
      - Collectivités
      - Utilisateurs




## GitHub, les workflow Git, c'est quoi?

    Dépot QGIS
    Les bonnes pratiques
    Comment contribuer ?

## QGIS et python

    Le Cookbook pyQgis
    API QGIS C++
    Difficulté d'accès doc dédiée API QGIS Python (indice à posteriori, ça arrive  [ici](http://qgis-python.kartoza.com/docs/) )
    Console python
    script / actions
    processing grass SAGA etc .
    script vs plugin
    application standalone
    C++ vs python
    macros d'ouverture de projet

## QGIS server retour d'expérience

    perfs, installation etc..

## GPKG + spatiaLITE

      [Shapefile must die](http://switchfromshapefile.org/)] !
      standard OGC / conteneur base de données
      extensions métadonnées, styles, raster , MB Tiles etc..
      stocker le projet et données . extensions existantes
      vers un format d'[échange de projets](https://eos.geocat.net/gitlab/joana.simoes/foss4g_gpkg/raw/master/foss4g_gpkg.pdf) ?

## partage de styles avancés

      Ressource sharing plugin

## les relations dans QGIS + SGDBS

      Vaste sujet de discussion autour des bases relationnelles et des relations QGIS3
      Relations = utilisation pour les formulaires
      QGIS3 : auto discover Relations
      pas encore de relation au sens ArcGIS avec propagation de sélections (est-ce vraiment utiles?)

## Traitement et GRASS / OTB etc...

      exemple de traitement OSM

## Mobilité

      Qfield
      OpenDataKit (ODK)
      QtQuick

## QGIS server

      factcgi >> nginx / superviseur day

## Dockeriser ses applications

      Julien Hansselin à la pédagogie ! Tout est en ligne pour qui sait chercher :)

## Processing

      Découverte
      Refonte QGIS 3

## OSGEO4W

      packages ministère
      personnalisation, configuration déploiement
      Gestion de profils etc..
      installation en masse

## Barcamp REX

      Ou comment faire mieux la prochaine fois?
      écran / projecteur pour chaque groupe
      Communication à améliorer
      limiter à 50 pers ?
      Indiquer le numero des tables par atelier
      Collecter les sujets d'intérêt et niveau d'intérêt dans le formulaire d'inscription
      Inverser les deux journées?
      Moibiliser plus d'animateurs potentiels?
      Faire intervenir les étudiants agro pour le public en découverte?


## sujets orphelins, on a pas eu assez d'animateurs !

      Qu'est-ce qui vous manque dans QGIS?
      QGIS et Agriculture
      TimeManager
      Les graphes réseau
      Les plugins essentiels
