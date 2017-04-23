# WhyIsThatRelevant

For questions about this repository or dataset, email tmcdonnell@utexas.edu

Dataset for our paper:

```
Why Is That Relevant? Collecting Annotator Rationales for Relevance Judgments
Tyler McDonnell, Matthew Lease, Mucahid Kutlu, Tamer Elsayed
AAAI HCOMP 2016
```
https://www.ischool.utexas.edu/~ml/papers/mcdonnell-hcomp16.pdf


Please cite our paper whenever you use this data in any publication or presentation. The BiBTex is provided below for convenience.

```
@inproceedings{mcdonnell16-hcomp,
  author = {Tyler McDonnell and Matthew Lease and Mucahid Kutlu and Tamer Elsayed},
  title = {{Why Is That Relevant? Collecting Annotator Rationales for Relevance Judgments}},
  booktitle = {{Proceedings of the 4th AAAI Conference on Human Computation and Crowdsourcing (HCOMP)}},
  year = {2016}
}
```

Why Is That Relevant?: Dataset collected to investigate use of annotator rationales during relevance judgment collection for evaluation of IR systems.

### Introduction

The data is contained in the following PIPE-DELIMITED .csv files.

### standard.csv

| Column            | Description                                     |
|-------------------|-------------------------------------------------|
| WorkerId          | Unique identifier for worker completing task    |
| WorkTimeInSeconds | Time spent by worker on task.                   |
| Query             | Query for which document relevance judged.      |
| URL               | URL for web page judged                         |
| Relevance         | Relevance judgment for page.                    |

### rationales.csv

| Column            | Description                                     |
|-------------------|-------------------------------------------------|
| WorkerId          | Unique identifier for worker completing task    |
| WorkTimeInSeconds | Time spent by worker on task.                   |
| Query             | Query for which document relevance judged.      |
| URL               | URL for web page judged                         |
| Rationale         | Rationale selected by worker.                   |
| Relevance         | Relevance judgment for page.                    |

### stage2.csv

| Column            | Description                                     |
|-------------------|-------------------------------------------------|
| WorkerId          | Unique identifier for worker completing task    |
| WorkTimeInSeconds | Time spent by worker on task.                   |
| Query             | Query for which document relevance judged.      |
| URL               | URL for web page judged                         |
| InputRelevance    | Input judgment provided by stage 1 worker.      |
| InputRationale    | Rationale provided by stage 1 worker.           |
| Reasoning         | Reasoning provided by stage 2 worker.           |
| Relevance         | Judgment provided by stage 2 worker.            |