SAS.Planet Shom Raster plugin
===============================

SAS.Planet est un logiciel développé par SASGIS. Le site est en Russe. http://www.sasgis.org/download/ ou depuis https://sasplanet.geojamal.com/

Il inclut un certain nombre de connecteurs pour charger les fonds de carte depuis différentes sources.

Ce script permet de charger les données depuis https://data.shom.fr/

# Installation

Copier le dossier `Shom.zmp` dans le dossier `SAS.Planet/Maps/`

# Utiliser les selections

Dans le dossier vous trouverez quelques (pas tous) selections des côtes françaises pour lesquelles le Shom propose des cartes.

Dans SAS.Planet :

- Aller dans `Operations` > `Selection Manager` > `Load from File`
- Chercher un des fichiers de selection `*.hlg`
- Cocher les niveaux de zoom correspondants au nom du fichier Ex : `selection-z11-z12-atlantique-manche.hlg` zoom 11 et 12
- Puis `Start` pour lancer la récupération des tuiles
- Recommencer pour toutes les zones qui vous intéresses
- Suiver la méthode d'exporter Mbtiles pour exporter les données (non décrite ici)