Link reification
==

Definition
-
The __reification mechanism__ of a LINK/Statement between 2 (or more) ITEMS/Individuals consists in considering this LINK/Statement - also - as an ITEM/Individual.   
De facto, it can thus - in turn - be engaged in 1 (or more) other LINK(s)/Statement(s)!

Emblematic situation
-
__Example in OWL__ :   
If one establishes a relationship "employed by" between an individual of the Class #Person and an individual of the Class #Company, then one cannot say anything about this relationship (because it was modeled by a pair of ObjectProperties that are inverse to each other)!   

Unless, of course, we have anticipated this when designing the model and have modeled this relationship by a Class that connects to the Class #Person on the one hand and the Class #Company on the other hand.   

In a relatively large model with a large number of Classes (and especially Relationships), it quickly becomes a headache to "say things" about the relationships, because they must then be modeled as Classes and not as pairs of ObjectProperties that are inverse to each other.

However, in many cases, we would like to avoid this type of question and make sure that relationships can "evolve" (i.e. to be able to model them simply at the beginning, and then to be able to say things about them later on if the need arises).

=> However, this is IMPOSSIBLE in OWL, because in order to do so, you have to break the initial modeling!!

Use case
-
To be able to start a knowledge base linking the TYPES/Classes #Person & #Organization in a relatively simple model to know which #Organization affiliates which #Person ...   
... then be able to evolve it to a more complex model where we could then know (for example) :
   - when the #Person became a member...
   - the role of the #Person in the #Organisation
   - how it contributes 
   - ...
   
   And all this, without NEVER having to "break" the initial model...    
   ...BUT just by making it "evolve smoothly", according to new needs. 
   
   Needless to say that for this functionality, the use cases are numerous ;-)__ 
