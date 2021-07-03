# Topology Distillation for Recommender System
This repository provides the source code of "Topology Distillation for Recommender System" accepted in KDD2021 as a research paper.

### Overview
We develop a general topology distillation approach for RS, which guides the learning of the student by the topological structure built upon the relational knowledge in the teacher representation space.
Concretely, we propose two topology distillation methods: 

1) FTD that transfers the full topology. FTD is used in the scenario where the student has enough capacity to learn all the teacher’s knowledge.

2) HTD that transfers the decomposed topology hierarchically. HTD is adopted in the conventional KD scenario where the student has a very limited capacity compared to the teacher.


### Requirements
- Python version: 3.6.10
- Pytorch version: 1.5.0


### How to Run
```
Please refer to 'Guide to using topology distillation.ipynb' file.
```
