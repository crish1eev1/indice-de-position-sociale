# Etude de la répartition public/privé des établissements scolaires français

## Sources

<table>
    <tr>
        <th><p style="text-align:left">DATA CONTENT & USE</p></th>
        <th><p style="text-align:left">SOURCE</p></th>
        <th><p style="text-align:left">INFORMATION LINK</p></th>
        <th><p style="text-align:left">UPDATE</p></th>
    <tr>
    <tr>
        <td><p style="text-align:left">Indices de position sociale dans les collèges de France métropolitaine et DROM<br> 
        </p></td>
        <td><p style="text-align:left">data.education.gouv.fr</p></td>
        <td><p style="text-align:left"><a href="https://data.education.gouv.fr/explore/dataset/fr-en-ips_colleges/table/?disjunctive.rentree_scolaire&disjunctive.academie&disjunctive.code_du_departement&disjunctive.departement&disjunctive.uai&disjunctive.code_insee_de_la_commune&disjunctive.nom_de_la_commune&disjunctive.secteur", target="_blank">Indices de position sociale dans les collèges de France métropolitaine et DROM</a></p></td>
        <td><p style="text-align:left">October, 2022</p></td>
    </tr>
    <tr>
        <td><p style="text-align:left">Indices de position sociale dans les écoles de France métropolitaine et DROM<br>
        </p></td>
        <td><p style="text-align:left">data.education.gouv.fr</p></td>
        <td><p style="text-align:left"><a href="https://data.education.gouv.fr/explore/dataset/fr-en-ips_ecoles/information/?disjunctive.academie&disjunctive.code_du_departement&disjunctive.departement&disjunctive.uai&disjunctive.code_insee_de_la_commune&disjunctive.nom_de_la_commune&disjunctive.secteur", target="_blank">Indices de position sociale dans les écoles de France métropolitaine et DROM</a></p></td>
        <td><p style="text-align:left">October, 2022</p></td>
    </tr>
    <tr>
        <td><p style="text-align:left">Diplôme national du brevet par établissement<br>
        </p></td>
        <td><p style="text-align:left">data.education.gouv.fr</p></td>
        <td><p style="text-align:left"><a href="https://data.education.gouv.fr/explore/dataset/fr-en-dnb-par-etablissement/information/?disjunctive.session&disjunctive.numero_d_etablissement&disjunctive.denomination_principale&disjunctive.secteur_d_enseignement&disjunctive.commune_et_arrondissement&disjunctive.commune_et_arrondissement_lib_l&disjunctive.departement&disjunctive.departement_libelle&disjunctive.academie&disjunctive.academie_libelle&disjunctive.region&disjunctive.region_libelle", target="_blank">Diplôme national du brevet par établissement</a></p></td>
        <td><p style="text-align:left">June, 2022</p></td>
    </tr>
    <tr>
        <td><p style="text-align:left">Adresse et géolocalisation des établissements d'enseignement du premier et second degrés<br> 
        </p></td>
        <td><p style="text-align:left">data.education.gouv.fr</p></td>
        <td><p style="text-align:left"><a href="https://data.education.gouv.fr/explore/dataset/fr-en-adresse-et-geolocalisation-etablissements-premier-et-second-degre/table/?disjunctive.nature_uai&disjunctive.nature_uai_libe&disjunctive.code_departement&disjunctive.code_region&disjunctive.code_academie&disjunctive.secteur_prive_code_type_contrat&disjunctive.secteur_prive_libelle_type_contrat&disjunctive.code_ministere&disjunctive.libelle_ministere", target="_blank">Adresse et géolocalisation des établissements d'enseignement du premier et second degrés </a></p></td>
        <td><p style="text-align:left">October, 2022</p></td>
    </tr>
        <tr>
        <td><p style="text-align:left">Revenus des Français à la commune<br> 
        </p>Données extraites de la base Filosofi de l'INSEE spécifiant le niveau de vie des Français pour chaque commune française sur l'année 2013</td>
        <td><p style="text-align:left">Données extraites de la base Filosofi de l'INSEE</p></td>
        <td><p style="text-align:left"><a href="https://www.data.gouv.fr/fr/datasets/revenus-des-francais-a-la-commune/", target="_blank">Revenus des Français à la commune</a></p></td>
        <td><p style="text-align:left">2014</p></td>
    </tr>
</table>   

Le code permettant la collecte, la structuration et le traitement des données ainsi que la mise en forme des résultats est disponible via https://github.com/crish1eev1/public-private-distribution-french-schools
<br></br>

## 1. Répartition public/privé des écoles françaises selon l'indice de position sociale 
#### Définition de l'Indice de Position Sociale (IPS) selon wikipedia
>L'indice de position sociale des élèves (IPS) est un outil de mesure quantitatif de la situation sociale des élèves face aux apprentissages dans les établissements scolaires français. **Plus l'indice est élevé, plus l'élève évolue dans un contexte familial favorable aux apprentissages. Cet indice est construit à partir des professions et catégories socioprofessionnelles (PCS) des représentants légaux des élèves**. 
>Il est utilisé pour décrire les populations scolaires (milieu social plus ou moins favorable et mixité sociale) dans les écoles, collèges et lycées mais aussi pour classer les établissements scolaires et leur attribuer des moyens en conséquence. 
L'indice de position sociale (IPS) des élèves est un indice sans dimension compris entre 38 et 1791. Plus cet indice est élevé, plus le contexte familial de l'élève est favorable à sa réussite scolaire. 

Les données IDS sont disponibles par établissement (écoles et collèges). Dans cette section, lorsqu'on parlera d'un IDS moyen pour le public ou le privé, il faut le lire en tant que moyenne des IDS des établissements (non pondérée par le nombre d'élèves).
<br></br>

###  1.1 Distribution public/privé des écoles et collèges selon IDS (année scolaire 2021-2022)

<a href="https://crish1eev1.github.io/images/graphs/violin-distribution-prive-public-selon-ips.html" download="">
  <img src="./graphs/violin-distribution-prive-public-selon-ips_no-title.png" alt="violin-distribution-prive-public-selon-ips" width="700">
</a>


|                    |   Nombre      |  IPS moyen |  Ecart-type |   Min       |   Max       |   Mediane   |
|--------------------|---------------|------------|-------------|-------------|-------------|-------------|
| Ecoles publiques   |         27549 |      101.2 |     15.7    |        49.6 |       155.6 |       101.9 |
| Ecoles privées     |          4542 |      112.2 |       15.1  |        56.8 |       155.4 |       110.4 |
| Collèges publics   |         5303  |      99.9  |     15.3    |        51.3 |       157.6 |       100.5 |
| Collèges privés    |          1659 |      114.2 |       16.0  |        66.0 |       154.9 |       112.8 |


On constate une distribution inégale entre établissements publics et privés avec un IPS moyen très supérieur dans le privé mais aussi des queues de distribution à l'allure inversée. En effet, les queues de distribution du public s'affinent très rapidement lorsque l'IPS augmente et inversement. Cette inégalité de répartition est plus importante pour les collèges que pour les écoles. 

Divisons les établissements scolaires en 7 groupes d'IPS afin de mieux nous rendre compte de cette distribution inégale. 
<br></br>

###  1.2 Répartition public/privé des établissments selon 7 tranches d'IDS (année scolaire 2021-2022)
#### Ecoles en pourcentage du nombre d'établissements
- Parmi les écoles avec un IPS inférieur à 90, seules 3,2% sont privées.
- Parmi celles avec un IPS supérieur à 140, 60,3% sont privées.

<img src="./graphs/ecole_repartition-prive-public-selon-ips_no-title.png" alt="ecole_repartition-prive-public-selon-ips" width="700"/>



#### Ecoles en valeur absolue du nombre d'établissements (année scolaire 2021-2022)
|                    |   Moins de 90 |   90 à 100 |   100 à 110 |   110 à 120 |   120 à 130 |   130 à 140 |   Plus de 140 |
|--------------------|---------------|------------|-------------|-------------|-------------|-------------|---------------|
| privé sous contrat |           202 |        763 |        1256 |        1040 |         653 |         388 |           240 |
| public             |          6069 |       6276 |        7276 |        4928 |        2134 |         708 |           158 |



#### Collèges en pourcentage du nombre d'établissements (année scolaire 2021-2022)
- Parmi les collèges avec un IPS inférieur à 90, 5,7% sont privées.
- Parmi celles avec un IPS supérieur à 140, 77,9% sont privées.

<img src="./graphs/college_repartition-prive-public-selon-ips_no-title.png" alt="college_repartition-prive-public-selon-ips" width="700"/>

#### Collèges en valeur absolue du nombre d'établissements (année scolaire 2021-2022)
|                    |   Moins de 90 |   90 à 100 |   100 à 110 |   110 à 120 |   120 à 130 |   130 à 140 |   Plus de 140 |
|--------------------|---------------|------------|-------------|-------------|-------------|-------------|---------------|
| privé sous contrat |            76 |        245 |         396 |         383 |         270 |         169 |           120 |
| public             |          1268 |       1291 |        1468 |         812 |         325 |         105 |            34 |

</br>


###  1.3 Répartition public/privé des établissments selon IDS par région (année scolaire 2021-2022)
Avant d'anlyser les écarts entre régions dans le détail, voici un aperçu de la répartition géographique globale en France métropolitaine.</br>
Cliquez sur les graphs si vous souhaitez naviguer vous même sur la carte. 

#### Répartition géographique des écoles publiques/privées (année scolaire 2021-2022)
<a href="https://crish1eev1.github.io/images/graphs/geolocation-ecole-prive-public-selon-ips.html" download="">
  <img src="./graphs/geolocation-ecole-prive-public-selon-ips_no-title.png" alt="geolocation-ecole-prive-public-selon-ips" width="700">
</a>

#### Répartition géographique des collèges publics/privés (année scolaire 2021-2022)
<a href="https://crish1eev1.github.io/images/graphs/geolocation-college-prive-public-selon-ips.html" download="">
  <img src="./graphs/geolocation-college-prive-public-selon-ips_no-title.png" alt="geolocation-college-prive-public-selon-ips" width="700">
</a>

On constate une forte implentation des établissements privés dans les bassins de populations les plus denses alors qu'ils sont peu présents en zones rurales. </br>
La Bretagne et la Loire-Atlantique constituent des exceptions à ce constat. 



#### Distribution public/privé des écoles par région selon IDS (année scolaire 2021-2022)
<a href="https://crish1eev1.github.io/images/graphs/boxplot-ecole-ips-selon-region.html" download="">
  <img src="./graphs/boxplot-ecole-ips-selon-region_no-title.png" alt="boxplot-ecole-ips-selon-region" width="1300">
</a>
Ce graph est ordonné par région ou l'écart d'IPS entre public et privé est le plus important.
Les "boites" representent le profil de chaque série statistique. Plus la boite est longue, plus la série statistique comprend des valeurs dispérsées. Inversement, plus la boite est petite, plus les valeurs sont homogènes. Le trait visible à l'intérieur de chaque boite représente la médiane.  

|                                    |   moyenne IPS privé |   moyenne IPS public |   différence |
|------------------------------------|---------------------|----------------------|--------------|
| guyane                             |               66.2  |               108.4  |        42.2  |
| la réunion                         |               76.05 |               114.45 |        38.4  |
| tom et collectivités territoriales |               78.1  |               108.35 |        30.25 |
| ile-de-france                      |              107.9  |               137.1  |        29.2  |
| martinique                         |               84.5  |               112.7  |        28.2  |
| corse                              |               98.15 |               122    |        23.85 |
| guadeloupe                         |               83.8  |               104.8  |        21    |
| hauts-de-france                    |               94.2  |               112    |        17.8  |
| provence-alpes-côte d'azur         |              103.5  |               121    |        17.5  |
| centre-val de loire                |              101.9  |               115.1  |        13.2  |
| grand est                          |              100.7  |               113.85 |        13.15 |
| bourgogne-franche-comté            |              101.9  |               109.6  |         7.7  |
| normandie                          |              100    |               107.05 |         7.05 |
| nouvelle-aquitaine                 |              102.2  |               108.8  |         6.6  |
| occitanie                          |              104.2  |               109.75 |         5.55 |
| pays de la loire                   |              101.3  |               106    |         4.7  |
| auvergne-rhône-alpes               |              106.3  |               111    |         4.7  |
| bretagne                           |              103.2  |               105.5  |         2.3  |
| mayotte                            |               67.9  |                 0    |         0    |

On constate un très gros écart dans les territoires d'outre-mer, en ile de France, en Corse, en PACA ainsi que dans les hauts-de-france. Régions connues pour leur forte disparité sociale. A l'inverse, on constate un faible écart entre public et privé en Bretagne ou Pays de la Loire. 

On verifiera par la suite si l'écart public/privé reste aussi important lorsqu'on se concentre sur les zones à forte de densité urbaine.

#### Distribution public/privé des collèges par région selon IDS (année scolaire 2021-2022)
<a href="https://crish1eev1.github.io/images/graphs/boxplot-college-ips-selon-region.html" download="">
  <img src="./graphs/boxplot-college-ips-selon-region_no-title.png" alt="boxplot-college-ips-selon-region" width="1300">
</a>


|                                    |   moyenne IPS privé |   moyenne IPS public |   différence |
|------------------------------------|---------------------|----------------------|--------------|
| guyane                             |               66.7  |               108.55 |        41.85 |
| la réunion                         |               79.9  |               118.6  |        38.7  |
| ile-de-france                      |              104.7  |               133.5  |        28.8  |
| martinique                         |               86.5  |               113    |        26.5  |
| corse                              |               98.9  |               119.3  |        20.4  |
| provence-alpes-côte d'azur         |              101.1  |               120.5  |        19.4  |
| hauts-de-france                    |               91.5  |               108.85 |        17.35 |
| guadeloupe                         |               87.1  |               103.9  |        16.8  |
| grand est                          |               98.6  |               112.7  |        14.1  |
| centre-val de loire                |              100.1  |               112.85 |        12.75 |
| normandie                          |               97.4  |               110.1  |        12.7  |
| auvergne-rhône-alpes               |              104    |               113.5  |         9.5  |
| occitanie                          |              103.8  |               110.55 |         6.75 |
| pays de la loire                   |              101.25 |               107.7  |         6.45 |
| nouvelle-aquitaine                 |              102.6  |               109    |         6.4  |
| bourgogne-franche-comté            |              101.4  |               106.5  |         5.1  |
| bretagne                           |              104.3  |               107.15 |         2.85 |
| tom et collectivités territoriales |               78.6  |                 0    |         0    |
| mayotte                            |               68.15 |                 0    |         0    |


## 3. Brevet