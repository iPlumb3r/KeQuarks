Multiple typing
==

Definition
-
The __multiple typing__ consists in the fact that an ITEM/Individual can _ belong to 2 (or more) TYPES/Classes at the same time.     
> This is a feature that becomes necessary very quickly as soon as the knowledge domain becomes a bit "chunky".

What about OWL?
-
OWL supports it "in theory", but "in practice" the OWL-Compliant tools usually only offer : 
   - nor a suitable GUI to handle this functionality.
   - no reconciliation function in case of class change (= processing of "statements" which have been added in ontology-driven mode in the context of a class, but which might no longer make sense in case of class change)

Avantage
-
Deals with _combinatorial class explosions_.

__Explanation__ : 
It is sometimes possible to circumvent the need for __multiple typing__ (because not supported by all modeling paradigms and/or associated tools) by __multiple class inheritance__ ...    
... but this "workaround" can only be used in a limited number of cases, as it does not allow to cope with the __combinatorial explosion of classes_.

__Example__ :
If one has to deal with a situation which requires the manipulation of ITEMS/Individuals which are potentially characterized in a "space" made up of 5 TYPES/Intentional Classes & 30 TYPES/Extentional Classes, then :
* The "multiple inheritance" solution will require 150 TYPES/Classes.
* Where "multiple typing" will only require 35 TYPES/CLASSES

Cases of use
-
Here are 3 cases of use that show the importance of multiple typing for a good representation of the reality of the field ...  

__Enterprise product lifecycle management application__ :      
Here each "product" must be bi-typed:
* By Intention : i.e. According to the purpose of the product (here "to be designed")
* By Extension: i.e. Depending on the nature of the product (here a "tire")
> NB : Each membership to a type allows to bring to the product its own properties ...

![Classification](https://github.com/iPlumb3r/KeQuarks/blob/master/images/Multi-Typing_Classification.png)


__"Human resource" application for linking positions VS profiles__ :    
Here each "actor" is potentially multi-type:
> NB : Each membership to a type allows to bring to the product its own properties ...

![Roles](https://github.com/iPlumb3r/KeQuarks/blob/master/images/Multi-Typing_Roles.png)

__Application of semantic mapping of ecosystem(s)__ :   
Here all the elements of the "map" potentially belong to 1 intentional type and 1 extensional type.

![E2M](https://github.com/iPlumb3r/KeQuarks/blob/master/images/Multi-Typing_EcosystemMapping.png)

