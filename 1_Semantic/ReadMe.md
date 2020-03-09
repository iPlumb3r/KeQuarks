Semantic
==

To Be Completed ...

In order to avoid any debate about terminology : 
* Concepts are here primary identifier by non significative IDs
* Terms of each paradigm are mapped to Concepts

Key Concepts
-
<table>
    <thead>
        <tr>
            <th>Concept ID</th>
            <th>1st or ... ?</th>
            <th>Path</th>
            <th>Path</th>
            <th>Prefered Label</th>
            <th>Description</th>
            <th>Comment</th>         
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>#0</td>
            <td>1st</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>topic</td>
            <td>A particular thing</td>
            <td>Start with a "lowercase"</td>
        </tr>
        <tr>
            <td>#1</td>
            <td>1st</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>tuple</td>
            <td>A link between 2 (or potentially more ?) particular things.</td>
            <td> A #1 is - aslo - a #0</td>
        </tr>
        <tr>
            <td>#2</td>
            <td>1st</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>Type</td>
            <td>A set of particular things.</td>
            <td>A #2 is - aslo - a #0</td>
        </tr>
        <tr>
            <td>#3</td>
            <td>...</td>
            <td>#0 #2(s)</td>
            <td>#2 of #0</td>
            <td>Topic Type</td>
            <td>As - given - set of "similar" topic(s)</td>
            <td></td>
        </tr>
        <tr>
            <td>#4</td>
            <td>...</td>
            <td>#1 #2(s)</td>
            <td>#2 of #1</td>
            <td>Tuple Type</td>
            <td>As - given - set of "similar" tuple(s)</td>
            <td></td>
        </tr>
        <tr>
            <td>#5</td>
            <td>...</td>
            <td>#2 #2(s)</td>
            <td>#2 of all #2(s)</td>
            <td>Thing</td>
            <td>The set of all topics</td>
            <td></td>
        </tr>
    </tbody>
</table>

__Imporant Note__ :
* As a #1 is also a #0, the (Meta-)Model automatically provide a reification mechanism !

Mapping with other paradigms
-

<table>
    <thead>
        <tr>
            <th>Concepts / Paradigms</th>
            <th>#0</th>
            <th>#1</th>
            <th>#2</th>
            <th>#3 = #2 of #0 = #0 #2(s)</th>
            <th>#4 = #2 of #1 = #1 #2(s)</th>
            <th>#5 = #2 of all #2(s)</th>
            <th>Comment</th>    
        </tr>
    </thead>
    <tbody>
         <tr>
            <td>KeQuarks (Knowledge Engineering)</td>
            <td>topic</td>
            <td>tuple (is - also - a topic)</td>
            <td>type (is -also - a topic)</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>Has also : changes happenning to things</td>
        </tr>
        <tr>
            <td>BORO (Data Modeling)</td>
            <td>Element (a particular thing)</td>
            <td>Tuple (a relashionship between thing)</td>
            <td>Type (a general type of things)</td>
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
            <td>N/A</td>
            <td>N/A</td>
            <td>N/A</td>
            <td>Has also : changes happenning to things</td>
        </tr>
        <tr>
            <td>RDF/RDFS (Semantic Web)</td>
            <td>Resource (or Individual)</td>
            <td>Predicat (Between a Resource "As a Subject" & Resource "As an Object")</td>
            <td>Class</td>
            <td>Object Property</td>
            <td>Thing</td>
            <td>Datatype Property</td>    
            <td>-</td>   
        </tr>
        <tr>
            <td>Topic Maps (Semantic Web)</td>
            <td>Topic</td>
            <td>Association</td>
            <td>Topic Type</td>
            <td>Association Type</td>
            <td>N/A</td>
            <td>Occurence</td>
            <td>TM has also Role</td>   
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
            <td>Set of all Sets</td>
            <td>N/A</td>
            <td>-</td>
        </tr>
    </tbody>
</table>
