# Datasets used in the Evaluating LLMs for Check Set Selection and Improving LLM Confidence Estimates for Classification papers

This repository contains the **dataset samples used in the experiments** reported in:

> dela Cruz, J. A., Hendrickx, I., & Larson, M. (2025). “Evaluating large language models for confidence-based check set selection.” *Findings of the Association for Computational Linguistics: ACL 2025*, 16249–16265. Association for Computational Linguistics.
> https://aclanthology.org/2025.findings-acl.836/

and 
> dela Cruz, J. A., Hendrickx, I., & Larson, M. (2025). “Improving Large Language Model Confidence Estimates using Extractive
Rationales for Classification” *Proceedings of the Fourth Workshop on Generation, Evaluation and Metrics (GEM²)*, 549-560. Association for Computational Linguistics.
> https://aclanthology.org/2025.gem-1.49.pdf


The datasets are derived samples of previously published datasets and are provided to support reproducibility of the accompanying paper.

## Task 1: CrisisBench

The Task 1 dataset is sampled from the **CrisisBench** dataset. The sample contains tweets from **six disaster events from 2013–2014**, with **500 tweets per event**, for a total of **3,000 tweets**.

For our research, the original labels were renamed:

* `informative` → `humanitarian`
* `not informative` → `not humanitarian`

CrisisBench itself is consolidated from the **CrisisMMD** dataset. Please cite both when using this sample.

## Task 2: HumAID

The Task 2 dataset is sampled from the **HumAID** dataset, which contains Twitter data collected between **2016 and 2019** for humanitarian information classification.

The original dataset contains 11 labels. For our research, we selected **five labels that were present across all selected crisis events**.

The sample contains **300 tweets from ten disaster events**, for a total of **3,000 tweets**.

Please cite the original HumAID publication when using this sample.

## Citation

If you use these dataset samples, please cite the accompanying paper and the original dataset publications.

### The papers

```bibtex
@inproceedings{dela-cruz-etal-2025-evaluating,
    author = {dela Cruz, Jane Arleth and Hendrickx, Iris and Larson, Martha},
    title = {Evaluating Large Language Models for Confidence-Based Check Set Selection},
    booktitle = {Findings of the Association for Computational Linguistics: ACL 2025},
    pages = {16249--16265},
    year = {2025},
    publisher = {Association for Computational Linguistics},
    url = {https://aclanthology.org/2025.findings-acl.836/}
}
```
```bibtex
@inproceedings{dela-cruz-etal-2025-evaluating,
  title = "Improving Large Language Model Confidence Estimates using Extractive Rationales for Classification",
    author = "dela Cruz, Jane Arleth  and
      Hendrickx, Iris  and
      Larson, Martha",
    booktitle = "Proceedings of the Fourth Workshop on Generation, Evaluation and Metrics (GEM{\texttwosuperior})",
    pages = {549--560},
    year = {2025},
    publisher = {Association for Computational Linguistics},
    url = {https://aclanthology.org/2025.gem-1.49/}
}
```

### CrisisBench

```bibtex
@inproceedings{alam-etal-2021-crisisbench,
    author = {Alam, Firoj and Sajjad, Hassan and Imran, Muhammad and Ofli, Ferda},
    title = {CrisisBench: Benchmarking Crisis-Related Social Media Datasets for Humanitarian Information Processing},
    booktitle = {Proceedings of the International AAAI Conference on Web and Social Media},
    volume = {15},
    number = {1},
    pages = {923--932},
    year = {2021},
    doi = {10.1609/icwsm.v15i1.18115}
}
```

### CrisisMMD

```bibtex
@inproceedings{alam-etal-2018-crisismmd,
    author = {Alam, Firoj and Ofli, Ferda and Imran, Muhammad},
    title = {CrisisMMD: Multimodal Twitter Datasets from Natural Disasters},
    booktitle = {Proceedings of the International AAAI Conference on Web and Social Media},
    volume = {12},
    number = {1},
    pages = {465--473},
    year = {2018}
}
```

### HumAID

```bibtex
@inproceedings{alam-etal-2021-humaid,
    author = {Alam, Firoj and Qazi, Umair and Imran, Muhammad and Ofli, Ferda},
    title = {HumAID: Human-Annotated Disaster Incidents Data from Twitter},
    booktitle = {Proceedings of the International AAAI Conference on Web and Social Media},
    volume = {15},
    pages = {873--883},
    year = {2021},
    doi = {10.1609/icwsm.v15i1.18167}
}
```

## License and Data Provenance

These datasets are derived from CrisisBench, CrisisMMD, and HumAID. Please consult the original dataset publications and repositories for information about licensing, data provenance, and restrictions concerning the underlying Twitter data.
