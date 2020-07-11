# PaperRank

A Python implementation of [The PageRank Citation Ranking: Bringing Order to the Web](http://ilpubs.stanford.edu:8090/422/). <br>
The [slide](https://docs.google.com/presentation/d/1KA98sy54Mz67SAL8lxCBbb4DPzD6TIVd-zIF4QeaGrg/edit?usp=sharing) includes a more detailed description.


## Introduction
The goal is to rank papers parsing from [google scholar](https://scholar.google.com/) based on interested keywords.

<img src="imgs/scholar" width="600">


## Algorithm
<img src="imgs/method" width="400">

## Experiments
### Steps
1) Searching source papers from specific scholars (鄭宇,解巽評)
2) Searching papers which cited the source papers.
3) Rank papers by PageRank
<img src="imgs/steps" width="500">

### Results 
<img src="imgs/result" width="500">


## Prerequisites
- Python 3.6
- Keras 2.2.4
