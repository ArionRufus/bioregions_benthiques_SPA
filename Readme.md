Readme
================

Dans ce Github je présente les analyses que j’ai réalisées dans le but
de déterminer les biorégions de poissons démersaux et d’invertébrés
benthiques autour des îles de Saint-Paul et Amsterdam. Il se présente en
différents scripts expliqués en détails en format *Rmarkdown* via les
liens qui suivent. Pour les scripts originaux, ainsi que les données,
ces derniers ne sont pas pubiques mais sont disponibles sur demande.  
<br/> <br/>

## Scripts à paritr des données Croix\_du\_Sud (poissons démersaux):

[Préparation des
données](https://github.com/ArionRufus/bioregions_benthiques_SPA/blob/master/cds/data_prep_rmark.md).
C’est une mise en forme des données, qui aboutit au tableau
*catch\_op\_peche*. Ce script est une adaptation du script initial,
réalisé par Aurélien Favreau et Jules Selles. Il part des données
originales qui sont présentes dans le dossier *original\_data*,
téléchargeable ci-dessus, et le fichier transformé est stocké dans le
dossier \*modified \_data*. <br/> [Analyses de
réseaux](https://github.com/ArionRufus/bioregions_benthiques_SPA/blob/master/cds/reseaux_rmark.md).
Ce script part de *catch\_op\_peche\* pour réaliser les analyses de
réseau, et le représenter graphiquement. Le script initial est stocké
dans le dossier *réseaux* du dossier *script*, ainsi que ses sorties
utilisées pour représenter le réseau sur Gephi. Il sort également un
tableau présentant les clusters déterminés pour chaque opération de
pêche, *catch\_res*, disponible dans le dossier *modified data*. Ce
script utilise une fonction calculant les métriques qui a été modifiée,
[la
voici](https://github.com/ArionRufus/bioregions_benthiques_SPA/blob/master/cds/metrique_rmark.md).
<br/> [Analyses de
corrélation](https://github.com/ArionRufus/bioregions_benthiques_SPA/blob/master/cds/correl_rmark.md).
Ce script corrèle les clusters trouvés a des données environnementales,
et à partir du modèle sélectionné, prédit la répartition des clusters
sur la zone de Saint-Paul / Amsterdam. <br/>
[Cartographie](https://github.com/ArionRufus/bioregions_benthiques_SPA/blob/master/cds/rpz_rmark.md).
Ce script concentre toutes les cartographies faites, des cartes basiques
aux représentation géographiques des clusters et prédictions. <br/>
[Autres](https://github.com/ArionRufus/bioregions_benthiques_SPA/blob/master/cds/graph_rmark.md).
Dans ce script sont réalisées les analyses de complétudes, ainsi que
quelques graphiques.

<br/> <br/>

## Scripts à paritr des données md50 (invertébrés benthiques):

[Préparation des
données](https://github.com/ArionRufus/bioregions_benthiques_SPA/blob/master/md50/prep_data_md50.md).
C’est une mise en forme des données, qui aboutit au tableau
*md\_site\_gps*. Il part des données originales qui sont présentes dans
le dossier *original\_data*, téléchargeable ci-dessus, et le fichier
transformé est stocké dans le dossier *modified\_data*.

[Graphiques](https://github.com/ArionRufus/bioregions_benthiques_SPA/blob/master/md50/graphiques_md50.md).
Quelques représentations graphiques du jeu de données, qui sont un peu
complexes à réaliser, et sont danc dans un script à part.

[analyses de
réseau](https://github.com/ArionRufus/bioregions_benthiques_SPA/blob/master/md50/reseaux.md).
Réalisées à partir de tableau *md\_site\_gps*. Dans ce script sont
détaillées les analyses réalisées au niveau de l’espèce. D’autres ont
été faites au niveau du genre, mais n’aboutissant à rien de plus
intéressant elles ne sont pas détaillées (le script de base est tout de
même accessible
[ici](https://github.com/ArionRufus/bioregions_benthiques_SPA/blob/master/md50/scripts/reseaux/md_reseau_genre.R)).

[analyses de
corrélation](https://github.com/ArionRufus/bioregions_benthiques_SPA/blob/master/md50/correl_md50.md).
Ce sont les analyses de l’impact de la profondeur ainsi que d’autres
variables sur la détermination des clusters, dont découle la prédiction
de présence des clusters sur la zone de SPA.

[Cartographie](https://github.com/ArionRufus/bioregions_benthiques_SPA/blob/master/md50/carto_md50.md).
Représentation cartographique des analyses.  
<br/>