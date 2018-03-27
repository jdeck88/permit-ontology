# permit-ontology

The permit ontology was started at the BCoN workshop at Harvard University, March 27, 2018.

The initial build of this ontology was started based on a set of basic definitions provided to workshop participants.

To view the initial ontology load the following URL into protege:

```
https://raw.githubusercontent.com/jdeck88/permit-ontology/master/ontology/permit-ontology-merged-reasoned.owl
```

To build the ontology, install [Ontopilot](https://github.com/stuckyb/ontopilot/), download this source code from this repository,  and run the following commands:

```
ontopilot make ontology
ontopilot make ontology --merge_imports --reason
```
