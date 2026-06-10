# My science repository pattern 

> guidance for organizing computational science repositories around reproducible provenance, clear workflow structure, and separation of raw inputs, generated intermediates, reusable code, and final outputs. use when chatgpt needs to advise on repository structure, snakemake-based workflow layout, where files should live, how to add a new analysis step, or how to distinguish intermediate data from final scientific results.


* Explanation: https://blog.jordan.matelsky.com/Scientific-repositories/
* Demonstration: https://github.com/j6k4m8/scientific-repo-demo


TLDR:
* use workflow DAGs to make flows reproducible
* keep data, code, and documentation separate from results, and each in only one (organized) place
