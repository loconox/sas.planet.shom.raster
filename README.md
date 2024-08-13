SAS.Planet Shom Raster connector
===============================

SAS.Planet est un logiciel développé par SASGIS. Le site est en Russe. http://www.sasgis.org/download/

Il inclut un certain nombre de connecteurs pour charger les fonds de carte depuis différentes sources.

Ce script permet de charger les données depuis https://data.shom.fr/

# Installation

Copier le dossier `Shom.zmp` dans le dossier `SAS.Planet/Maps/sas.plus.maps/_water`

# Utiliser les selections

Dans le dossier vous trouverez quelques (pas tous) selections des côtes françaises pour lesquelles le Shom propose des cartes.

Dans SAS.Planet :

- Aller dans `Operations` > `Selection Manager` > `Load from File`
- Chercher un des fichiers de selection `*.hlg`
- Cocher les niveaux de zoom correspondants au nom du fichier Ex : `selection-z12-z13-mediterranee-corse.hlg` zoom 12 et 13
- Puis `Start` pour lancer la récupération des tuiles
- Recommencer pour toutes les zones qui vous intéresses
- Suiver la méthode d'exporter Mbtiles pour exporter les données (non décrite ici)