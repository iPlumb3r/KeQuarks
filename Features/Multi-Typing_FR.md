Typage multiple
==

Définition
-
Le __typage multiple__ consiste en le fait qu’un ITEM/Individu puisse _appartenir à 2 (ou plus) TYPES/Classes en même temps_.     
> Il s'agit d'une fonctionalité qui devient très vite nécessaire dès que le domaine de connaissances deviens un peu "trapu".

Quid de OWL ?
-
OWL le supporte "en théorie", mais "en pratique" les outils OWL-Compliant ne propose généralement : 
   - ni d’IHM adaptée pour traiter cette fonctionalité
   - ni fonction de réconciliation en cas de changement de classe (= traitement des "statements" qui ont été ajoutés en mode "ontology-driven" dans le contexte d'un classe, mais qui pourrait ne plus avoir de sens en cas de changement de classe)

Avantage
-
Permet de faire face à l'_explosion combinatoire des classes_.

__Explication__ : 
Il est parfois possible de contourner le besoin de __typage multiple__ (car non supporté par tous les paradigmes de modélisation et/ou les outils associés) par de l'__héritage multiple de classes__ ...    
... mais ce "contournement" n'est utilisable que dans un nombre limité de cas, car il ne permet pas de faire face à l'_explosion combinatoire des classes_.

__Example__ :
Si l'on doit traiter une situation qui nécessite de manipuler des ITEMS/Individus qui sont potentiellement caractérisés dans un "espace" constitué de 5 TYPES/Classes intentionels & 30 TYPES/Classes extentionels, alors :
* La solution "héritage multiple" nécessaitera 150 TYPES/Classes
* Là, où le "typage multiple" ne requiera que 35 TYPES/Classes

Typologies de cas d'usage
-
Le multi-typing est une solution "fonctionelle" qui répond globalement à 2 type de situation "métier"
* Type A : 1 ITEM/Individu qui appartient "totalement" à 2 (ou plusieurs) Types/Classes (c'est typiquement le cas du bi-typage intentionel ET extensionel)
* Type B : 1 ITEM/Individu qui est "à cheval" sur plusieurs TYPES/Classe de l'ontologie sans être ni totameent d'une TYPE/Classe, ni totalement de l'autre


Cas d'usage type A
-
Ci-après 3 cas d'usage qui montre l'importance du typage multiple pour une bonne représentation de la réalité du terrain ...  

__Application de gestion de cycle de vie des produits de l'entreprise__ :      
Ici chaque "produit" doit être bi-typé :
* Par Intention : i.e. En fonction de la finalité du produit (ici "être conçu")
* Par Extension : i.e. En fonction de la nature du produit (ici un "pneu")
> NB : Chaque appartenance à un type permet d'apporter au produit les propriétés qui lui sont propres ...

![Classification](https://github.com/iPlumb3r/KeQuarks/blob/master/images/Multi-Typing_Classification.png)


__Application "ressource humaine" de mise en relation de postes VS profils__ :    
Ici chaque "acteur" est potentiellement multi-typé :
> NB : Chaque appartenance à un type permet d'apporter au produit les propriétés qui lui sont propres ...

![Roles](https://github.com/iPlumb3r/KeQuarks/blob/master/images/Multi-Typing_Roles.png)

__Application de cartographie sémantique d'écosystème(s)__ :   
Ici tous les éléments de la "carte" appartiennent potentiellement à 1 type intentionel et 1 type extensionel

![E2M](https://github.com/iPlumb3r/KeQuarks/blob/master/images/Multi-Typing_EcosystemMapping.png)

Cas d'usage type B
-

A compléter ...
