## Research code template (top level)

Template files for starting a new set of research codes. include PRJ numbers at the top.

### Purpose (second level)

Make a reasonable template, with notes for documentation, linting, and other git repo maintenance guidelines so that
it's easily accessible, and that I start producing codes that are consistently documented across projects.

In this section, it's good to note the general purpose of a research project. 3-4 sentences will suffice. Can also
include a few notes on goals (in separate 3rd level section)

#### Goals (third level)

1. make list of research goals
    1. and exactly what kind of output we are expecting (plots, etc.)

### Samples 

Usually start with some note about the samples that we are taking

|sample|category|meta1|meta2|
|------|--------|-----|-----|
|table |is a    |good |idea |

### Data storage

Include where the data will be moved to (ones not on git). usually just a `gs://` address

### Conclusion

Add a conclusion on what we decided to do with the analysis (stop, pursue later, or add more samples) here before we
open PR and merge in with rest of the research code.

Start a repo using this as your template. Remove the LICENSE file, and fill out READMEs.