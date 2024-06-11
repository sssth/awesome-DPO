# awesome-DPO
Papers related to Direct Preference Optimization（DPO）



### loss change
| Title | Method | Time  | Discription | Structure | Loss Function|
|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|
| KTO: Model Alignment as Prospect Theoretic Optimization|KTO|arXiv24|maximizes the utility of generations instead of maximizing the log-likelihood of preferences that are hard-to-get|![image](https://github.com/sssth/awesome-DPO/assets/105367602/f66fdb6c-6829-481e-af5d-d8a1c7dcef05)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/cd22ad60-e8cf-4df4-a473-3ad20de4154e)|
| LiPO: Listwise Preference Optimization through Learning-to-Rank|LiPO|arXiv24| formulate the LM alignment as a listwise ranking problem, where the policy can potentially learn more effectively from a ranked list of plausible responses| ![image](https://github.com/istarryn/LLM4REC/assets/105367602/49c4daa2-5fa3-4bb7-8bbe-523a4e50c2a7)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/baebdbb4-807d-4ac0-8802-0696dbdd8675)|
| ULMA: Unified Language Model Alignment with Human Demonstration and Point-wise Preference|ULMA|arXiv23|directly learns from point-wise preference dataset with binary or continuous labels||![image](https://github.com/sssth/awesome-DPO/assets/105367602/22cd7164-508c-4655-81c3-e2eee6f46b34)|
| Statistical Rejection Sampling Improves Preference Optimization | RSO | ICLR24 | DPO only sample preference pairs from SFT policy, use statistical rejection sampling to generate a distribution equal to optimal policy| ![image](https://github.com/istarryn/LLM4REC/assets/105367602/bed64e50-1975-4775-9965-6e0f5643d13c) |![image](https://github.com/sssth/awesome-DPO/assets/105367602/9e77e302-2296-4141-8a3e-d9e992547af7)|
| Reinforcement Learning from Human Feedback with Active Queries | ADPO | arXiv24 | use active-learning and elimilate preference pairs with low reward differential || ![image](https://github.com/istarryn/LLM4REC/assets/105367602/af0fbd5b-3f02-425e-8018-67cf4d529f39)|
| Direct Preference Optimization with an Offset| ODPO| arXiv24 | use offset to represent the likelihood of the preferred and dispreferred data | ![image](https://github.com/istarryn/LLM4REC/assets/105367602/55327f61-ebb6-47ab-9e18-f18e45a4651f)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/973bd5eb-d8c0-42cb-a763-0a4017949748)|
| Relative Preference Optimization: Enhancing LLM Alignment through Contrasting Responses across Identical and Diverse Prompts|RPO|arXiv24|compare prefered response to all disprefered response in the dataset and use similarity of prompts to represent adaptive weight|![image](https://github.com/sssth/awesome-DPO/assets/105367602/764c9e2a-89d1-4d71-b93a-0d00da42622b)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/4f3b790c-07d5-4f39-b9b9-76655b8de13f)|
| Noise Contrastive Alignment of Language Models with Explicit Rewards|NCA|arXiv24|regard DPO as a noise contrastive classification problem, design InfoNCA to make loss scalable to any response numbers, while design NCA to prevent likelihood of the best response continually decreases during training||![image](https://github.com/sssth/awesome-DPO/assets/105367602/7054e3b2-be44-46e2-a90b-4d10b0a90b21)|
| Smaug: Fixing Failure Modes of Preference Optimisation with DPO-Positive|DPOP|arXiv24|find that datasets with small edit distance are more likely to suffer from likelihood decrease, add a regularisation to prevent|![image](https://github.com/sssth/awesome-DPO/assets/105367602/e37e6cde-8324-4887-92b1-289c20b7b375)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/43147341-2f71-47b4-ab6e-d5a4b0adf335)|
| Refined Direct Preference Optimization with Synthetic Data for Behavioral Alignment of LLMs|r-DPO|arXiv24|use self-critique prompt of teacher LLM to generate response as data, use another teacher LLM to score the data and use the score to modify the loss of DPO|![image](https://github.com/sssth/awesome-DPO/assets/105367602/62be8536-cdf8-4685-b598-81954c061288)|![image]https://github.com/sssth/awesome-DPO/assets/105367602/09aa9255-1b08-4484-9acf-9083d251b627)|



### data construction
| Title | Method | Time  | Discription | Structure |
|:-------:|:-------:|:-------:|:-------:|:-------:|
| RS-DPO: A Hybrid Rejection Sampling and Direct Preference Optimization Method for Alignment of Large Language Models| RS-DPO | arXiv24 | elimilate preference pairs with low reward differential using a explicit reward model and rejection sampling| ![image](https://github.com/istarryn/LLM4REC/assets/105367602/89f0420e-5a0e-4d3f-92d7-3de9ee5655f3)|


### online DPO(update SFT policy during training)
| Title | Method | Time  | Discription | Structure |
|:-------:|:-------:|:-------:|:-------:|:-------:|
| Curry-DPO: Enhancing Alignment using Curriculum Learning & Ranked Preferences | Curry-DPO | arXiv24 |ultilize multiple responses creating multiple preference pairs and use curriculum learning to train preference pairs from easy to hard  | ![image](https://github.com/istarryn/LLM4REC/assets/105367602/f30f96f5-972f-4e03-9234-e195976368d3)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/c4bfa2e7-04bc-4a58-9594-a786eaabc4e1)|
| D2PO: Discriminator-Guided DPO with Response Evaluation Models | D2PO | arXiv24 | update explicit reward model and use it to generate preference pairs during training | ![image](https://github.com/istarryn/LLM4REC/assets/105367602/0903b4e4-5f3c-42af-985f-3bf42c3303d5)|
| Learn Your Reference Model for Real Good Alignment|TR-DPO|arXiv24|update SFT model using soft-update and hard-update|![image](https://github.com/istarryn/LLM4REC/assets/105367602/f96f57fe-94bd-490e-9f77-c6589c353fdc)|
| sDPO: Don’t Use Your Data All at Once|sDPO|arXiv24|dividing the available preference datasets and utilizing them in a step-wise manner|![image](https://github.com/istarryn/LLM4REC/assets/105367602/0ceac2e8-c996-4cc1-9956-e1959d646b47)|
| Direct Language Model Alignment from Online AI Feedback|OAIF|arXiv24|sample responses from current model during training and use LLM to annotate|![image](https://github.com/istarryn/LLM4REC/assets/105367602/44c94172-934b-4b51-a298-e9c669b36ba8)|
| Self-Rewarding Language Models|Self-Rewarding|arXiv24|model itself acts as a reward model to construct preference pairs and update SFT model in interations|![image](https://github.com/sssth/awesome-DPO/assets/105367602/4ab7a888-fcaa-44ea-b80f-63b658c88484)|

