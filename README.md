# The RDF knowledge graph of the Archives nationales of France Sparnatural prototype | le graphe de connaissances RDF du prototype Sparnatural des Archives nationales de France 

## Version 1.0 (août 2022) | v1.0 (August 2022)

Download the release | Télécharger la release : [https://github.com/ArchivesNationalesFR/Sparnatural_prototype_data/releases/tag/1.0](https://github.com/ArchivesNationalesFR/Sparnatural_prototype_data/releases/tag/1.0). 

## Description

### [en]

The RDF data of this repository are those published in the Sparnatural prototype of the Archives nationales of France ([https://sparna-git.github.io/sparnatural-demonstrateur-an/index.html](https://sparna-git.github.io/sparnatural-demonstrateur-an/index.html)). In this website, the documentation, which is available in French and in English  ([https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-en.html](https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-en.html)), explains the objectives of this ongoing project, presents the source data selected, the data graph production process, the current content of the knowledge graph obtained, and the first outcomes of the project.

Scope and content: the graph describes the archives of 40 notarial offices (out of 122 offices) in Paris, produced and preserved continuously since the end of the 15th to the beginning of the 20th century, and kept by the Archives nationales of France. More information about this record set which is about 9 linear km: [https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-en.html#metadata](https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-en.html#metadata). 

Format of the data: RDF/XML

Number of triples: 57,9 million, including about 37 million inferred (in a GraphDB Standard repository that has been configured using RDFS-Plus Optimized inference rules)

Main vocabularies and ontologies used:  [RiC-O](https://www.ica.org/standards/RiC/ontology) (the last official version, v 0.2 dated February 2021) and  [SKOS](https://www.w3.org/2004/02/skos/).

More information: [https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-en.html#stats](https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-en.html#stats)


The 'RDF' folder contains, in the 'imported_data' subfolder, the whole of the data imported into the graph base used. In the 'other_entities' subfolder, for now, you can find exactly the same data as in the [https://github.com/ArchivesNationalesFR/Referentiels/tree/main/concepts/rdf](https://github.com/ArchivesNationalesFR/Referentiels/tree/main/concepts/rdf), [https://github.com/ArchivesNationalesFR/Referentiels/tree/main/agents/personnesPhysiques](https://github.com/ArchivesNationalesFR/Referentiels/tree/main/agents/personnesPhysiques), and [https://github.com/ArchivesNationalesFR/Referentiels/tree/main/agents/collectivites](https://github.com/ArchivesNationalesFR/Referentiels/tree/main/agents/collectivites) folders.

In the 
'sparql_updates' subfolder you can find a text file, that contains the SPARQL INSERT DATA and INSERT queries used to enrich the graph obtained once imported.

Once these operations have been done, it has been possible to design and produce the two exploration interfaces that are currently available in the prototype, using the [Sparnatural](https://sparnatural.eu/) SPARQL query visual editor.

In the 'source_metadata' folder, you can find the most of the source metadata from which the RDF data are generated. This includes 1577 EAD 2022 archival finding aids and 1120 EAC-CPF authority records. About these source metadata, see [https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-en.html#metadata](https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-en.html#metadata).

### [fr]
Les données RDF de ce dépôt (contenues dans le dossier RDF) sont celles publiées dans le prototype Sparnatural des Archives nationales de France ([https://sparna-git.github.io/sparnatural-demonstrateur-an/index.html](https://sparna-git.github.io/sparnatural-demonstrateur-an/index.html)). Dans ce site web, la documentation, disponible en français ([https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-fr.html](https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-fr.html)) et en anglais, présente les objectifs de ce projet en cours de réalisation, les données sélectionnées, le processus de sémantisation de ces données et d'enrichissement du graphe obtenu, le contenu actuel du graphe de connaissances, et les premiers résultats du projet. 

Objet et portée du graphe: le graphe décrit les archives de 40 études notariales parisiennes (sur les 122 existantes), produites et préservées sans rupture depuis la fin du XVe jusqu’au début du XXe siècle, conservées aux Archives nationales de France. Plus d'informations sur cet ensemble d'archives d'environ 9 km linéaires: [https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-fr.html#metadata](https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-fr.html#metadata).

Format des données RDF : RDF/XML

Nombre de triplets obtenus : 57,9 millions, dont environ 37 millions de triplets inférés (dans un entrepôt d'une instance de GraphDB Standard, configuré pour utiliser simplement les règles d'inférence 'RDFS-Plus Optimized')

Principaux modèles et ontologies utilisés : [Records in Contexts - Ontology](https://www.ica.org/standards/RiC/ontology) (dans sa dernière version officielle en date, la v0.2 de février 2021) et  [SKOS](https://www.w3.org/2004/02/skos/). 

Plus d'informations : [https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-fr.html#stats](https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-fr.html#stats).


Le dossier 'RDF' contient, dans le sous-dossier 'imported_data', l'ensemble des données RDF importées dans la base de graphes utilisée. Dans le sous-dossier 'other_entities', on trouve pour l'instant exactement les mêmes données que celles contenues dans les dossiers  [https://github.com/ArchivesNationalesFR/Referentiels/tree/main/concepts/rdf](https://github.com/ArchivesNationalesFR/Referentiels/tree/main/concepts/rdf), [https://github.com/ArchivesNationalesFR/Referentiels/tree/main/agents/personnesPhysiques](https://github.com/ArchivesNationalesFR/Referentiels/tree/main/agents/personnesPhysiques) et [https://github.com/ArchivesNationalesFR/Referentiels/tree/main/agents/collectivites](https://github.com/ArchivesNationalesFR/Referentiels/tree/main/agents/collectivites).
Dans le dossier 'sparql_updates' on trouve un fichier texte contenant les requêtes SPARQL de type INSERT DATA ou INSERT utilisées pour enrichir le graphe obtenu.

Une fois ces opérations effectuées, il a été possible de concevoir et réaliser les deux interfaces de recherche disponibles dans le démonstrateur, à l'aide de l'éditeur visuel de requêtes SPARQL [Sparnatural](https://sparnatural.eu/).

Dans le dossier 'source_metadata', on trouve la plupart des fichiers source à partir desquels les données RDF ont été générées. Cela inclut 1577 EAD 2022 instruments de recherche archivistiques en EAD 2022 et 1120 notices d'autorité en EAC-CPF. Au sujet de ces métadonnées source, voyez [https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-fr.html#metadata](https://sparna-git.github.io/sparnatural-demonstrateur-an/presentation-fr.html#metadata).


## Licence | License


[en] For now, **you are not allowed to reuse these data without first getting an official, written, agreement from the Archives nationales of France (ANF).** 

[fr] Pour l'instant, **vous n'êtes pas autorisé à réutiliser ces données sans avoir au préalable obtenu un accord écrit officiel des Archives nationales de France (ANF).**

## Avertissement | Warning

### [en]

The Sparnatural demonstrator where you can query and display these data is a prototype that was developed to address the needs of a specific project.

As the ANF do not have yet a web application enabling to publish all the RDF data they have produced, and to make them accessible to humans and machines, **the IRIS of the entities described cannot be dereferenced.** However, the last segment of the IRIS (after the base URI, which has been set to 'http://data.archives-nationales.culture.gouv.fr/' and is specified as the value of the xml:base attribute of the root element in each file), is based upon unique and persistent local identifiers given to some of the entities described in the information system of the ANF.

**The data and the prototype itself will be improved in the coming months.** New releases of the data can therefore be made in this repository.

### [fr]

The démonstrateur Sparnatural qui permet d'explorer et d'afficher les données RDF présentes dans ce dépôt est un prototype développé dans le cadre d'un projet spécifique. Comme les ANF ne disposent pas encore d'une application web permettant de publier toutes les données RDF qu'elles ont produites, et de les rendre accessibles aux humains et aux machines, **les IRIS des entités décrites par ces données ne sont pas déréférençables**. Cependant, le segment final de ces IRIS (après le segment de base, qui est 'http://data.archives-nationales.culture.gouv.fr/' et qui est stocké comme valeur de l'attribut xml:base de l'élément racine de chacin des fichiers), est fondé sur des identifiants uniques et pérennes locaux assignés par le système d'information des ANF à certaines des entités décrites. 

Les données et le prototype seront améliorés dans les prochains mois. **De nouvelles releases pourraient donc être publiées dans le présent entrepôt**.


## For more information | Pour plus d'informations

[en] You can contact the Lab of the Archives Nationales de France by email at the following address: <le-lab.archives-nationales@culture.gouv.fr>.

[fr] Vous pouvez contacter par courriel le Lab des Archives nationales de France, à l'adresse suivante :  <le-lab.archives-nationales@culture.gouv.fr>.
