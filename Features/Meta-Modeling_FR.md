Meta-Modelisation
==

Définition
-
La __meta-modélisation__, consiste à pouvoir être capable de considérer qu’une "chose" qui est un ITEM/Individu d’un TYPE/Classe _dans un contexte donné_ puisse être un TYPE/Classe _dans un autre contexte_.  

Avantage
-
Permet une transition "en douceur" d'_une taxomonie vers une ontologie_

Situation emblématique
-
__Cas l'ontologie <a href="http://virtual-assembly.org/ontologies/pair/index-fr.html">PAIR</a>__.  
Dans cette ontologie, il a été décidé de traiter le TYPE/Classe #Organization à un niveau relativement générique ne faisant pas la disctinction par exemple entre une société, une association ou une université ...  
Il s'agit d'un choix "by design" qui nécessite en // de disposer une d'un TYPE/Classe #OrganizationType dont les éléments sont des ITEMS/Individus (Société, Association, Université, ...).  
Si l'on devrait faire évoluer le modèle PAIR pour traiter de problématique lié à l'enseigement, il faudrait sans doute pouvoir faire en sorte que Université ne soit plus "seulement" un ITEM/Individu du TYPE/Class #OrganizationType, mais devienne le TYPE/Classe #University à part entière, avec ses propres PROPERTY & LINK
=> Or cela est quasi-impossible en OWL, en tout cas pas sans "casser" le modèle !!!

__Cas de l'architecture d'entreprise__. 
C’est une exigence forte dans les modèles d’architecture d’entreprise dans lesquels une sous-parti du modèle est en fait dévolu à la génération des modèles que doit gérer l’entreprise. (Cf cas d'usage ci-après)

Cas d'usage
-
Dans le contexte d'un (meta-)modèle d'architecture d'entreprise (EA), il est - quasi-systématiquement - nécessaire de piloter les modèles métiers de l'entreprise à partir d'une sous-partie de ce (méta-)modèle consitué du TYPE/Classe - nommé dans l'illustration ci-après - "Business Subject".

Et bien, les éléments typés par ce TYPE/Classe sont bien des ITEMS/Instances dans le __contexte du (méta-)modèle d'EA__ ...   
... mais ce sont - également - des TYPES/Classes dans le __contexte du modèle métier__ dont ils font partis !

![EA](https://github.com/iPlumb3r/KeQuarks/blob/master/images/Meta-Modeling_EA.png)


Représentation des différents niveaux d'abstraction requis en contexte :
![Meta-Modeling UC](https://github.com/iPlumb3r/SEAMLESS/blob/master/Images/UC_Meta-Modeling_2020-04-03.jpg)
