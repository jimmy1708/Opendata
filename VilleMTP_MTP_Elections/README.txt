   

 
--------------------------------------------------
Données publiques ouvertes - Montpellier Territoire Numérique
--------------------------------------------------
Fiche métadonnées
--------------------------------------------------

* ID : 100

* URL : http://opendata.montpelliernumerique.fr/Resultats-des-elections

* IDENTIFIANT : VilleMTP_MTP_Elections

* TITRE : Résultats des élections

* DESCRIPTION : Résultats des élections sur la commune de Montpellier, par bureau de vote et par élection depuis le premier tour des élections cantonales du 20 mars 1994, jusqu’au dernier scrutin en date. 

Une API (interface de programmation) est désormais disponible pour les résultats des élections depuis 1994. 

Le code est disponible sur le dépôt libre sur GitHub (serveur en nodejs) : https://github.com/Bype/apimtnlab 

Les élections ayant eu lieu depuis 1994, sont disponibles dans un fichier json à cette url, chaque élection à un numéro propre : http://api.mtnlab.org/elections/scrutins/election.json 

Ensuite un fichier json peut être généré par numéro d'élection (disponible dans le fichier json des 57 élections), par exemple http://api.mtnlab.org/elections/resultat/232 pour le l'élection numéro 232. 

Les résultats sont aussi disponibles par numéro d'élection avec la géométrie (cartographie) des bureaux de votes. Par exemple http://api.mtnlab.org/elections/resultat/232?geometry=1 pour l'élection numéro 232. 

La géométrie des bureaux de vote est issue de la donnée open data des bureaux de vote disponible à cette url : http://opendata.montpelliernumerique.fr/Bureaux-de-vote 

En résumé : argument &#171; scrutin &#187; : l’api renvoie la description de chacune des 57 élections dans un fichier json à cette url, chaque élection ayant un numéro propre. argument &#171; resultat/x &#187; : l’api renvoie les résultats de l’élection n&#176;x dans un fichier json. argument &#171; geometry=1 &#187; : l’api complète le fichier renvoyé par une description géographique de chaque secteur électoral. Comme le volume est important, cette fonctionnalité est à utiliser de préférence une fois à l’initialisation de l’application.

* CATÉGORIE : Politique Publique &amp; Démocratie

* THÈME INSPIRE : Société

* LICENCE : LICENCE OUVERTE / OPEN LICENCE http://www.etalab.gouv.fr/pages/licence-ouverte-open-licence-5899923.html

* MOTS CLÉS : élection ; politique ; résultat ; cantonale ; présidentielle ; législative ; municipale ; européenne : régionale ; référendum ; démocratie ; montpellier

* DATE PUBLICATION : 2012-09-10

* MISE À JOUR : 2014-04-03

* COUVERTUTE GÉOGRAPHIQUE : Montpellier



* PÉRIODE VALIDITÉE : Annuelle

* PRORIÉTAIRE : Ville de Montpellier

* DIFFUSEUR : Ville de Montpellier



* LANGUE : français

* TARIFICATION : Gratuite





--------------------------------------------------
Site : http://opendata.montpelliernumerique.fr
--------------------------------------------------
