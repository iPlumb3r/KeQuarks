Semantic
==

To Be Completed ...

In order to avoid any debate about terminology : 
* Concepts are here primary identified by a non significative IDs (A prefered label is just provided as an example) ...
* ... then, those Concepts are "mapped" with Terms used by each paradigm

Main Concepts
-
<table>
    <thead>
        <tr>
            <th>Concept ID</th>
            <th>Path</th>
            <th>Path</th>
            <th>Prefered Label</th>
            <th>Description</th>
            <th>Example(s)</th>
            <th>Comment</th>         
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>#0</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>topic</td>
            <td>A particular thing</td>
            <td>"Tim Berner Lee", "W3C", ...</td>
            <td>Start with a "lowercase"</td>
        </tr>
        <tr>
            <td>#1</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>tuple</td>
            <td>A link between 2 (or potentially more ?) particular things.</td>
            <td>The link between "Tim Berner Lee" & "W3C" (untyped, but oriented)</td>
            <td>A #1 is (also) a #0</td>
        </tr>
        <tr>
            <td>#2</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>Type</td>
            <td>A set of particular things.</td>
            <td>"Persons", "Organizations", ...</td>
            <td>A #2 is (also) a #0</td>
        </tr>
    </tbody>
</table>

__Important Note 1__ :
* As a #1 is also a #0, the (Meta-)Model automatically provide a reification mechanism !

__Important Note 2__ :
* If #1 (tuple) arity is = 2 the it better to have a "orientation" (e.g. starts from / ends to)
* If #1 (tuple) arity is > 2 there is a need for #RoleType (& #Role) concept(s)

Derived (Useful) Concepts
-
<table>
    <thead>
        <tr>
            <th>Concept ID</th>
            <th>Path</th>
            <th>Path</th>
            <th>Prefered Label</th>
            <th>Description</th>
            <th>Example</th>
            <th>Comment</th>         
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>#3</td>
            <td>#0 #2(s)</td>
            <td>#2 of #0</td>
            <td>A type of topics (Topic Type)</td>
            <td>As - given - set of "similar" topic(s)</td>
            <td></td>
            <td>#3 is a #2</td>
        </tr>
        <tr>
            <td>#4</td>
            <td>#1 #2(s)</td>
            <td>#2 of #1</td>
            <td>A type of tuples (Tuple Type)</td>
            <td>As - given - set of "similar" tuple(s)</td>
            <td></td>
            <td>#4 is a #2</td>
        </tr>
        <tr>
            <td>#5</td>
            <td>#2 #2(s)</td>
            <td>#2 of all #2(s)</td>
            <td>Things</td>
            <td>The set of all topics</td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>

Other (Non Mandatory) Concepts
-
<table>
    <thead>
        <tr>
            <th>Concept ID</th>
            <th>Path</th>
            <th>Path</th>
            <th>Prefered Label</th>
            <th>Description</th>
            <th>Example</th>
            <th>Comment</th>         
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>#6</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>Property</td>
            <td>As - given - set of "similar" topic(s)</td>
            <td></td>
            <td>#6 is a #1 towards specific #2</td>
        </tr>
        <tr>
            <td>#4</td>
            <td>#1 #2(s)</td>
            <td>#2 of #1</td>
            <td>A type of tuples (Tuple Type)</td>
            <td>As - given - set of "similar" tuple(s)</td>
            <td></td>
            <td>#4 is a #2</td>
        </tr>
        <tr>
            <td>#5</td>
            <td>#2 #2(s)</td>
            <td>#2 of all #2(s)</td>
            <td>Things</td>
            <td>The set of all topics</td>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>

Mapping with other paradigms
-

<table>
    <thead>
        <tr>
            <th>Concepts / Paradigms</th>
            <th>#0</th>
            <th>#1</th>
            <th>#2</th>
            <th>#3</th>
            <th>#4</th>
            <th>#5</th>
            <th>Comment</th>    
        </tr>
    </thead>
    <tbody>
         <tr>
            <td>KeQuarks (Knowledge Engineering)</td>
            <td>topic</td>
            <td>tuple</td>
            <td>Type</td>
            <td>Topic Type</td>
            <td>Tuple Type</td>
            <td>Things</td>
            <td></td>
        </tr>
        <tr>
            <td>BORO (Data Modeling)</td>
            <td>Element</td>
            <td>Tuple</td>
            <td>Type</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>Has also : changes happenning to things</td>
        </tr>
        <tr>
            <td>KL Meta-Model (Mind Mapping)</td>
            <td>item</td>
            <td>link</td>
            <td>type</td>
            <td>Item Type</td>
            <td>Link Type</td>
            <td>Items</td>
            <td>Each link is oriented ("start from" item - "end to" item</td>
        </tr>
        <tr>
            <td>RDF(S)-OWL (Semantic Web)</td>
            <td>Resource (or Individual)</td>
            <td>Predicat (Between a Resource "As a Subject" & Resource "As an Object")</td>
            <td>Class</td>
            <td>Object Property</td>
            <td>Thing</td>
            <td>Thing</td>    
            <td>M has also : Datatype Property</td>   
        </tr>
        <tr>
            <td>Topic Maps (Semantic Web)</td>
            <td>Topic</td>
            <td>Association</td>
            <td>Type</td>
            <td>Topic Type</td>
            <td>Association Type</td>
            <td>???</td>
            <td>TM has also : Role & Occurence</td>   
        </tr>
        <tr>
            <td>Grakn (Graph Database)</td>
            <td>???</td>
            <td>???</td>
            <td>Entity</td>
            <td>Relation</td>
            <td>N/A</td>
            <td>Resource</td>
            <td>Has also : Role</td>   
        </tr>
        <tr>
            <td>O-O Language (Computer Science)</td>
            <td>Object (or Instance)</td>
            <td>Pointer</td>
            <td>Class</td>
            <td>Object Attribute</td>
            <td>N/A</td>
            <td>Data Attribute</td>
            <td></td>
        </tr>
        <tr>
            <td>Set Theory (Math)</td>
            <td>Element</td>
            <td>N/A</td>
            <td>Set</td>
            <td>N/A</td>
            <td>NA/</td>
            <td>Set of all elements</td>
            <td>Not suitable for relation between elements</td>
        </tr>
    </tbody>
</table>
