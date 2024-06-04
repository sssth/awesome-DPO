# awesome-DPO
Papers related to Direct Preference Optimization（DPO）



### loss change
| Title | Method | Time  | Discription | Structure | Loss Function|
|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|
| KTO: Model Alignment as Prospect Theoretic Optimization|KTO|arXiv24||maximizes the utility of generations instead of maximizing the log-likelihood of preferences that are hard-to-get|![image](https://github.com/sssth/awesome-DPO/assets/105367602/f66fdb6c-6829-481e-af5d-d8a1c7dcef05)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/cd22ad60-e8cf-4df4-a473-3ad20de4154e)|
| LiPO: Listwise Preference Optimization through Learning-to-Rank|LiPO|arXiv24| formulate the LM alignment as a listwise ranking problem, where the policy can potentially learn more effectively from a ranked list of plausible responses| ![image](https://github.com/istarryn/LLM4REC/assets/105367602/49c4daa2-5fa3-4bb7-8bbe-523a4e50c2a7)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/baebdbb4-807d-4ac0-8802-0696dbdd8675)|


### online DPO
| Title | Method | Time  | Discription | Structure |
|:-------:|:-------:|:-------:|:-------:|:-------:|
| Curry-DPO: Enhancing Alignment using Curriculum Learning & Ranked Preferences | Curry-DPO | arXiv24 |ultilize multiple responses creating multiple preference pairs and use curriculum learning to train preference pairs from easy to hard  | ![image](https://github.com/istarryn/LLM4REC/assets/105367602/f30f96f5-972f-4e03-9234-e195976368d3)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/c4bfa2e7-04bc-4a58-9594-a786eaabc4e1)|
