Paradigms
==

List
-

A list of interesting paradigms : 
<table>
    <thead>
        <tr>
            <th>Label</th>
            <th>Discipline</th>
             <th>developed by</th>           
            <th>Comment</th>
            <th>About Page</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="https://github.com/iPlumb3r/KnowledgeEngineeringParticles/blob/master/2_Paradigms/BORO.md">BORO</a></td>
            <td>Data Modeling</td>
            <td><a href="http://www.borosolutions.net/">Boro Solution</a></td>
            <td>-</td>
            <td><a href="https://en.wikipedia.org/wiki/BORO/">Wikipedia (EN)</a></td>
        </tr>
        <tr>
            <td><a href="https://github.com/iPlumb3r/KnowledgeEngineeringParticles/blob/master/2_Paradigms/KL_M-M.md">KL Meta-Model</a></td>
            <td>Mind Mapping</td>
            <td><a href="http://keeplink.com/">KeepLink</a></td>
            <td>-</td>
            <td><a href="https://github.com/iPlumb3r/KeepLink/blob/master/1_Semantic/ReadMe_FR.md">Non Offical GitHub (FR)</a></td>
        </tr>
        <tr>
            <td>RDF(S)-OWL</td>
            <td>Semantic Web</td>
            <td><a href="https://www.w3.org/standards/semanticweb/">W3C (SW Section)</a></td>
            <td>-</td>
            <td><a href="https://www.w3.org/RDF/">RDF</a>, <a href="https://www.w3.org/TR/rdf-schema/">RDFS</a> & <a href="https://www.w3.org/OWL/">OWL</a></td>
        </tr>
        <tr>
            <td>Topic Maps</td>
            <td>Semantic Web</td>
            <td>TM Community</td>
            <td>Role based modeling</td>
            <td><a href="https://en.wikipedia.org/wiki/Topic_map">Wikipedia (EN)</a></td>
        </tr>
        <tr>
            <td>Grakn</td>
            <td>Graph Database</td>
            <td><a href="https://grakn.ai/">Grakn Labs</a></td>
            <td>Role based modeling</td>
            <td><a href="https://blog.grakn.ai/get-started-with-grakn-ai-72bb210f915c">Getting Started Web Page</a></td>
        </tr>
        <tr>
            <td>O-O Language(s)</td>
            <td>Computer Science</td>
            <td>N/A</td>
            <td>-</td>
            <td><a href="https://en.wikipedia.org/wiki/Object-oriented_programming">Wikipedia (EN)</a></td>
        </tr>
        <tr>
            <td>Set Theory</td>
            <td>Mathematics</td>
            <td>N/A</td>
            <td>-</td>
            <td><a href="https://en.wikipedia.org/wiki/Set_theory">Wikipedia (EN)</a></td>
        </tr>
    </tbody>
</table>

Classification
-

<table>
    <thead>
        <tr>
            <th></th>
            <th>Oriented Tuples (2-Ary) => Without Role</th>
           <th>Non Oriented Tuples (2-Ary & N-Ary) => With Role</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Property "as pointer"</td>
            <td>KL Meta-Model, RDF(S)-OWL</td>
            <td>Topic Maps, Grakn</td>
        </tr>
        <tr>
            <td>Property "as Types"</td>
            <td>BORO</td>
            <td>?</td>
        </tr>
        <td>Property "as Link"</td>
            <td>KeQuarks ?</td>
            <td>?</td>
    </tbody>
</table>

Killer-Features
-

A list of interesting paradigms : 
<table>
    <thead>
        <tr>
            <th>Paradigm</th>
            <th>Link Reification ?</th>
            <th>Multi-Typing ?</th>           
            <th>Meta-Modeling ?</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>BORO</td>
            <td>No</td>
            <td>Yes</td>
            <td>Yes ?</td>
        </tr>
        <tr>
            <td>KL Meta-Model</td>
            <td>Yes (Systematic)</td>
            <td>Yes</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td>RDF(S)-OWL</td>
            <td>No (Need to be planned via dedicated Classes)</td>
            <td>Yes (but OWL-compliant tools are not usable</td>
            <td>Yes (in theory, but not practically implemented)</td>
        </tr>
        <tr>
            <td>Topic Maps</td>
            <td>No</td>
            <td>No</td>
            <td>No</td>
        </tr>
        <tr>
            <td>Grakn</td>
            <td>No (Need to be planned via N-Ary Relations)</td>
            <td>No</td>
            <td>No (Via Inference Rules)</td>
        </tr>
     </tbody>
</table>
