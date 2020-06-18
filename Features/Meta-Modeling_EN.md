Meta-Modeling
==

Definition
-
The __meta-modeling__, consists in being able to consider that a "thing" which is an ITEM/Individual of a TYPE/Class _in a given context_ can be a TYPE/Class _in another context_.  

Advantage
-
Allows a "smooth" transition from _a taxonomy to an ontology_.

Emblematic situation
-
__Case of the <a href="http://virtual-assembly.org/ontologies/pair/index-fr.html">PAIR</a>__ ontology. 
In this ontology, it has been decided to treat the TYPE/Class #Organization at a relatively generic level that does not distinguish for example between a company, an association or a university ...  
It is a choice "by design" which requires in // to have one of a TYPE/Class #OrganizationType whose elements are ITEMS/Individuals (Company, Association, University, ...).  
If the PAIR model should evolve in order to deal with problems related to teaching, it should probably be possible to ensure that the University is no longer "only" an ITEM/Individual of the TYPE/Class #OrganizationType, but becomes the TYPE/Class #University in its own right, with its own PROPERTY and LINK.
=> But this is almost impossible in OWL, at least not without "breaking" the model !!!

__Enterprise architecture case__. 
This is a strong requirement in enterprise architecture models in which a sub-part of the model is in fact devoted to the generation of the models that the company must manage. (See use cases below)

Cases of use
-
In the context of an Enterprise Architecture (EA) (meta-)model, it is - quasi-systematically - necessary to drive the business models of the enterprise from a sub-part of this (meta-)model consisting of the TYPE/Class - named in the illustration below - "Business Subject".

Well, the elements typed by this TYPE/Class are indeed ITEMS/Instances in the __context of the EA (meta-)model__ ...   
... but they are - also - TYPES/Classes in the __context of the business model__ of which they are part!
![EA](https://github.com/iPlumb3r/KeQuarks/blob/master/images/Meta-Modeling_EA.png)

Representation of the several abstraction levels required in such context :    
(Cf original SEAMLESS <a href="https://github.com/iPlumb3r/SEAMLESS/blob/master/0_UseCases/ReadMe.md">use case</a>) 
![Meta-Modeling UC](https://github.com/iPlumb3r/SEAMLESS/blob/master/Images/UC_Meta-Modeling_2020-04-03.jpg)

