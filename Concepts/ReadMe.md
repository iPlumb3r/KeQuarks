Concepts
==

This page is trying a "best of breed" approach for selecting candidate concepts & concept patterns for the HGQ-4-KEEP initiative ...  
... in order to define a powerful (and beautiful ;-) KeQuarks (Meta-)Model

In order to avoid any debate about terminology : 
* __Concepts__ are here primary identified by a _non significative IDs_ (A prefered label is just provided as an example) ...
* ... then, those __Concepts__ are "mapped" with __Terms__ used by each <a href="https://github.com/iPlumb3r/KeQuarks/tree/master/2_Paradigms">paradigm</a>

Key Concepts
-
<table>
    <thead>
        <tr>
            <th>Concept ID</th>
            <th>Prefered Label</th>
            <th>Alternative Label(s)</th>
            <th>Description</th>
            <th>Example(s)</th>
            <th>Comment</th>         
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>#0</td>
            <td>topic</td>
            <td>thing, element, entity, individual, ... </td>
            <td>A particular thing.</td>
            <td>"Tim Berner Lee", "W3C", ...</td>
            <td></td>
        </tr>
        <tr>
            <td>#0s</td>
            <td>Things</td>
            <td>Topics, Elements, Entities, Individuals, ... </td>
            <td>The set of ALL #0 (topics).</td>
            <td>N/A</td>
            <td>Usage of "Things" instead of "Topics" as prefered label, because its includes also Tuples, Types, ...</td>
        </tr>
        <tr>
            <td>#1</td>
            <td>tuple</td>
            <td>link, relation, association, ...</td>
            <td>A link between 2 (or potentially more) topics.</td>
            <td>The link between "Tim Berner Lee" & "W3C" (untyped, but oriented)</td>
            <td>A #1 is (also) a #0</td>
        </tr>
        <tr>
            <td>#1s</td>
            <td>Tuples</td>
            <td>Links, Relations, Associations, ...</td>
            <td>The set of ALL #1 (Tuples).</td>
            <td>N/A</td>
            <td></td>
        </tr>
        <tr>
            <td>#2</td>
            <td>type</td>
            <td>class, category, set, ...</td>           
            <td>A set of #0 (topics) which are sharing commons characteristics.</td>
            <td>"Persons", "Organizations", "affiates to", "has part", ...</td>
            <td>A #2 is (also) a #0</td>
        </tr>
        <tr>
            <td>#2s</td>
            <td>Types</td>
            <td>Classes, Categories, Sets, ...</td>           
            <td>The set of ALL #2 (types).</td>
            <td>N/A</td>
            <td></td>
        </tr>
    </tbody>
</table>

![Concepts](https://github.com/iPlumb3r/KeQuarks/blob/master/images/KeQuarksConcepts_2020-03-16.png)

__Important Note 1__ :
* As a #1 is also a #0, the (Meta-)Model automatically provide a reification mechanism !

__Important Note 2__ :
* If #1 (tuple) arity is = 2, in order to provide a given semantic, an "orientation" is required (e.g. starts from / ends to)
* If #1 (tuple) arity is > 2, in order to provide a given semantic, there is a need for #RoleType (& #Role) concept(s)

Derived (Useful) Concepts
-
<table>
    <thead>
        <tr>
            <th>Concept ID</th>
            <th>Prefered Label</th>
            <th>Description</th>
            <th>Semantic Path</th>
            <th>Example</th>
            <th>Comment</th>         
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>#3</td>
            <td>topic type</td>
            <td>A type of topics = A - given - set of "similar" topic(s)</td>
            <td>A #2 of #0 (= "#0#2")</td>
            <td>"Persons", "Organizations", ...</td>
            <td>#3 is a #2</td>
        </tr>
        <tr>
            <td>#3s</td>
            <td>Topic Types</td>
            <td>The set of ALL #3 (topic type)</td>
            <td>#0#2s</td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td>#4</td>
            <td>tuple type</td>
            <td>A type of tuples = A - given - set of "similar" tuple(s)</td>
            <td>A #2 of #1 (= "#1#2")</td>
            <td>"affiates to", "has part", ...</td>
            <td>#4 is a #2</td>
        </tr>
        <tr>
            <td>#4s</td>
            <td>Tuple Types</td>
            <td>The set of ALL #4 (tuple type)</td>
            <td>#1#2s</td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>

![Sets](https://github.com/iPlumb3r/KeQuarks/blob/master/images/KeQuarksSets_2020-03-16.png)

At this point it is important to distinguish :
* Topic-based modeling (Based on "Oriented 2-Ary Tuples") : e.g. BORO, RDF(S)-OWL, ...
* Role-based modeling paradim (Based on "Non Oriented N-Ary Tuples") : e.g. Topic Maps, Grakn,...

Tuple-Based Concepts
-
<table>
    <thead>
        <tr>
            <th>Concept ID</th>
            <th>Prefered Label</th>
            <th>Alternative Label(s)</th>
            <th>Description</th>
            <th>Example</th>
            <th>Comment</th>         
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>#5</td>
            <td>2-Ary tuple</td>
            <td>Binary Relation</td>
            <td>A relation between 2 topics</td>
            <td>N/A</td>
            <td></td>
        </tr>
         <tr>
            <td>#5s</td>
            <td>The set of All 2-Ary tuples</td>
            <td></td>
            <td></td>
            <td>N/A</td>
            <td>Abstract type</td>
        </tr>
    </tbody>
</table>


Property-Based Concepts
-
<table>
    <thead>
        <tr>
            <th>Concept ID</th>
            <th>Prefered Label</th>
            <th>Alternative Label(s)</th>
            <th>Description</th>
            <th>Example</th>
            <th>Comment</th>         
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>#15</td>
            <td>Property</td>
            <td>Attribute, Occurence, Characteristic, Resource, ...</td>
            <td>A characteristic of a thing</td>
            <td>N/A</td>
            <td>#6 is a #1 towards specific #2</td>
        </tr>
        <tr>
            <td></td>
            <td>Topic Property</td>
            <td>-</td>
            <td>A characteristic of a topic</td>
            <td>"Tim Berner Lee" . "birth date" = "1955 June 8"</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>Tuple Property</td>
            <td>-</td>
            <td>A characteristic of a tuple</td>
            <td>"Tim Berner Lee" & "W3C" . "hiring date" = "2009"</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>Topic Type Property</td>
            <td>-</td>
            <td>Property which characterize all topics of a Topic Type</td>
            <td>"Persons" . "birth date"</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>Tuple Type Property</td>
            <td>-</td>
            <td>Property which characterize all tuples of a Tuple Type</td>
            <td>"Persons" => "Organizations" . "hiring date"</td>
            <td></td>
        </tr>
    </tbody>
</table>

Concepts x Paradigms Mapping 
-
Working space = <a href="https://docs.google.com/spreadsheets/d/1LW_tBNss0VV0i_mfG56zXhdwFJKpwTKhpGyieA7ZxJo/">This SpreadSheet on Google Drive</a>

__Remark__ : GitHub not useful for "big" table. See this clickable table :

![CxP](https://github.com/iPlumb3r/KnowledgeEngineeringParticles/blob/master/images/Concepts_x_Paradigms_2020-03-09.png)
