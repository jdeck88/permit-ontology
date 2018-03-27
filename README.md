# permit-ontology

DISCLAIMER! This is a rough draft of what a permit ontology *could* look like.   In its current form, it is not meant to be correct or authorative in any way.  This may change in the future, if we continue to pursue this project.

The permit ontology was conceived of at the BCoN workshop at Harvard University, March 27, 2018 and meant to convey the different types of permits, certificates, memorandums, copyrights, and usage agreements that are possible for attachment to biological samples.  The initial build of this ontology was started based on a set of basic definitions provided to workshop participants.

To view the initial ontology load the following URL into protege:

```
https://raw.githubusercontent.com/jdeck88/permit-ontology/master/ontology/permit-ontology-merged-reasoned.owl
```

To build the ontology, install [Ontopilot](https://github.com/stuckyb/ontopilot/), download this source code from this repository,  and run the following commands:

```
ontopilot make ontology
ontopilot make ontology --merge_imports --reason
```
