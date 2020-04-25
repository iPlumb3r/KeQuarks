Reification of links
==

Definition
-
The __reification mechanism__ of a LINK/Statement between 2 (or more) ITEMS/Individuals consists in considering this LINK/Statement - also - as an ITEM/Individual.   
De facto, it can thus - in turn - be engaged in 1 (or more) other LINK(s)/Statement(s)!

Emblematic situation
-
__Example in OWL__ :   
If one establishes a relationship "employed by" between an individual of the Class #Person and an individual of the Class #Company, then one cannot say anything about this relationship (because it was modeled by a pair of ObjectProperties inverse to each other)!   

Unless, of course, we have anticipated this when designing the model and have modeled this relationship by a Class that connects to the Class #Person on the one hand and the Class #Company on the other hand.   

In a relatively large model with a large number of Classes (and especially Relationships), it quickly becomes a headache to "say things" about the relationships, because they must then be modeled as Classes and not as pairs of ObjectProperties that are inverse to each other.

However, in many cases, we would like to avoid this type of question and make sure that relationships can "evolve" (i.e. to be able to model them simply at the beginning, and then to be able to say things about them later on if the need arises).

=> However, this is IMPOSSIBLE in OWL, because in order to do so, you have to break the initial modeling!!

Use case
-
There are 3 main use cases that can profitably exploit the __mechanism of reification__ of the links:
* The "soft" evolution of the model
* The refinement of the semantics of relations
* Meta-data management
(The 2nd and 3rd cases are particular situations of the 1st case).

------------
__"Smooth evolution of the model :__    
To be able to start a knowledge base linking the TYPES/Classes #Person & #Organization according to a relatively simple model allowing to know which #Organization affiliates which #Person ...   
... then be able to evolve it into a more complex model where we could then know (for example) :
   - when the #Person became a member...
   - the role of the #Person in the #Organisation
   - how #Persons contribute to #Organization 
   - ...
   
   And all this, without NEVER having to "break" the initial model...    
   ...BUT just by making it "evolve smoothly", according to new needs.  

------------
__Refining the semantics of relations :__  
Let's consider a model that allows to link ITEMS/individuals of the TYPE/Class #Product with ITEMS/individuals of the TYPE/Class #Function via a semantic relation "#Product provides #Function". 
Without a reification mechanism, it will be necessary to "break" this model if one wishes to refine its semantics according to the modality according to which the function is rendered: centralized, decentralized or distributed mode (because one cannot "catch" any new information on the relations already created).
With a reification mechanism, it will be possible to refine this semantics by adding a PROPERTY "Mode" on the definition of the relation and thus to inform this mode on each instance of the relation. 

------------
__Meta-data management :__   
The idea of use cases is to be able to - for example - systematically record :
* The date on which a relationship was created/modified
* The user who created this relationship
* The justification for the existence of this relationship 
* ...

Resources
-
Article : <a href="https://github.com/blazegraph/database/wiki/Reification_Done_Right">Reification Done Right</a>   
Article : <a href="https://github.com/blazegraph/database/wiki/Reification_Done_Right">RDF* and SPARQL* (The modeling challenge)</a>

