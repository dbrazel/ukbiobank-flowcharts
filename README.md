# ukbiobank-flowcharts
[GraphViz](http://www.graphviz.org/) flowcharts of the questionnaire logic for selected [UK Biobank](http://biobank.ctsu.ox.ac.uk/showcase/index.cgi) assessments.

- TouchscreenQuestionsMainFinal.pdf - The UK Biobank documentation of the touchscreen questionnaires.
- alcohol_phenotypes.dot - The GraphViz specification for the alcohol questions.
- alcohol_phenotypes.pdf - The flowchart for the alcohol questions.
- smoking_phenotypes.dot - The GraphViz specification for the smoking questions.
- smoking_phenotypes.pdf - The flowchart for the smoking questions.

If you have installed GraphViz, each PDF can be generated with a single command: `dot -Tpdf alcohol_phenotypes.dot -o alcohol_phenotypes.pdf`
