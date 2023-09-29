# etudesnordiques
Dépôt contenant des scripts interrogant les catalogues de bibliothèques et les entrepôts d'archives ouvertes dans le domaine des langues et études nordiques.

* Test_API_SRU_Sudoc_langue.ipynb, permet d'observer et de quantifier la présence de notices de documents pour une langue donnée dans les bibliothèques appartenant au réseau français universitaire du Sudoc. Ce script interroge l'ensemble des RCR du Sudoc grâce à l'API d'IdRef, et utilise l'encodage des langues ISO 639-2 à partir de laliste fournie par la Bibliothèque du Congrès.
* 
* Test_suecana.ipynb permet de requêter la base Suecana dans le catalogue collectif suédois Libris, et d'étudier le nombre de traductions françaises d'ouvrages suédois et d'ouvrages sur la Suède publiés en français recensés dans cette base.

* Test_traductions_fre_swe_API_SRU_BnF.ipynb permet de requêter le Catalogue général de la BnF, et d'étudier le nombre de traductions françaises d'ouvrages suédois recensées dans ce catalogue.

* Test_API_SRU_Sudoc_suedois.ipynb permet d'observer et de quantifier la présence de notices de documents en langue suédoise dans les bibliothèques appartenant au réseau français universitaire du Sudoc. Ce test pour le suédois peut être généralisé aux autres langues nordiques, comme à d'autres langues étrangères. 

* Test_plein-texte_notices_HAL.ipynb permet d'observer le nombre de dépôts de documents en plein texte par rapport aux dépôts de notices seules dans la collection "ETUDES-NORDIQUES" dans HAL.
