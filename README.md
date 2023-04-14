# Persuasive Essays - Argument Quality Dataset


The Persuasive Essays - Argument Quality Dataset consists of persuasive essays extracted from the dataset proposed by Stab and Gurevych 2017 [1]. The essays are annotated with argument components, argumentative relations and, what constitutes our contribution, annotated with 3 quality dimensions for each argument.

For details regarding the creation of the dataset and experiments based on this data, please see the paper below.

# License

The Persuasive Essays - Argument Quality Dataset is released under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License:

https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode

# Citation

If you are using our dataset for research purposes, please cite the following
paper:

Santiago Marro, Elena Cabrio, and Serena Villata. 2022. Graph Embeddings for Argumentation Quality Assessment.
In Findings of the Association for Computational Linguistics: EMNLP 2022, pages 4154–4164, Abu Dhabi, United Arab Emirates. Association for Computational Linguistics.

```
@inproceedings{marro-etal-2022-graph,
    title = "Graph Embeddings for Argumentation Quality Assessment",
    author = "Marro, Santiago  and
      Cabrio, Elena  and
      Villata, Serena",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2022",
    month = dec,
    year = "2022",
    address = "Abu Dhabi, United Arab Emirates",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.findings-emnlp.306",
    pages = "4154--4164",
    abstract = "Argumentation is used by people both internally, by evaluating arguments and counterarguments to make sense of a situation and take a decision, and externally, e.g., in a debate, by exchanging arguments to reach an agreement or to promote an individual position. In this context, the assessment of the quality of the arguments is of extreme importance, as it strongly influences the evaluation of the overall argumentation, impacting on the decision making process. The automatic assessment of the quality of natural language arguments is recently attracting interest in the Argument Mining field. However, the issue of automatically assessing the quality of an argumentation largely remains a challenging unsolved task. Our contribution is twofold: first, we present a novel resource of 402 student persuasive essays, where three main quality dimensions (i.e., cogency, rhetoric, and reasonableness) have been annotated, leading to 1908 arguments tagged with quality facets; second, we address this novel task of argumentation quality assessment proposing a novel neural architecture based on graph embeddings, that combines both the textual features of the natural language arguments and the overall argument graph, i.e., considering also the support and attack relations holding among the arguments. Results on the persuasive essays dataset outperform state-of-the-art and standard baselines{'} performance.",
}
```

# References
[1] Christian Stab and Iryna Gurevych. 2017. Parsing argumentation structures in persuasive essays. Computational Linguistics, 43(3):619–659.