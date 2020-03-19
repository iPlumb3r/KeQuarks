Réification des liens
==

Définition
-
Le mécanisme de réification d'un lien entre 2 (ou plusieurs) items consiste à considérer ce lien - aussi - comme un item.   
De facto, il peut donc - à son tour - être engagé dans 1 (ou plusieurs) autre(s) lien(s) !

Situation emplématique
-
Exemple en OWL :   
Si on établit une relation « employed by » entre un individu de la Classe « Person » et un individu de la Classe « Company », on ne peux ensuite rien dire sur cette relation (car elle été modélisée par un couple d’objectProperties inverse l’une de l’autre) !   

Sauf évidement, à avoir anticipé cela lors que la conception du modèle et que l'on a modélisé cette relation par une Classe qui se connecte à la Classe « Person » d’une part et la Classe « Company » d’autre part.   

Dans un modèle relativement important avec un grands nombre de Classes (et surtout de Relations), cela devient vite un casse-tête de si on souhaite « dire des chose » sur les relations, car il faut alors les modéliser comme des Classes et non comme des couples d’ObjetProperties inverses l’une de l’autre.

Or, dans de nombreux cas de figure on voudrait ne pas avoir à se poser se type de question et faire en sorte les relations puissent « évoluer » (c'est-à-dire pourvoir les modéliser simplement au départ, puis que l’on puisse dire des choses sur elles ultérieurement si le besoin s’en fait sentir)

=> Or, cela est IMPOSSIBLE en OWL, car pour pouvoir le faire, il faut casser la modélisation initiale !!!

Cas d'usage
-
Pourvoir commencer une base de connaissances mettant en relation les TYPES/Classes #Person & #Organization selon un modèle relativement simple permettant de savoir quelle #Organization affilie quelle #Person ...   
... puis pouvoir le faire évoluer vers un modèle plus complexe où l'on pourrait ensuite savoir (par exemple) :
   - la date d'affiliation
   - le role de la personne dans l'organisation
   - son mode de contrtribution 
   - ...
   
   Et tout cela, sans avoir jamais à "casser" le modèle ...
   ...mais juste à le faire "évoluer en douceur", en fonctione des besoins nouveaux 
   
   Inutile de préciser que pour cette fonctionalité, les cas d'usage font légions !!!
