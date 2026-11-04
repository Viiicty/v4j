# Vul4J AI rewrite dataset workspace

This directory contains the open-source dataset artifacts and their validation evidence.

- `sources/`: vulnerable and official repaired source files;
- `methods/`: affected vulnerable and repaired method pairs;
- `generated/`: AI-rewritten candidates;
- `validation/`: compilation and PoV validation evidence;
- `manifest.csv`: final dataset index, created after candidate validation.

Temporary checkouts and build workspaces are excluded by `.gitignore`.

Clone-model predictions, rankings, and evaluation metrics are stored separately in:

`C:\haqthon\v4j_clone_experiment_results`
