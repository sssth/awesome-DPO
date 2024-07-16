# awesome-DPO
Papers related to Direct Preference Optimization（DPO）

## explicit reward model(dataset)  
ADPO - Reinforcement Learning from Human Feedback with Active Queries [[pdf]](https://arxiv.org/pdf/2402.09401)  
APO - Active Preference Learning for Large Language Models [[pdf]](https://arxiv.org/pdf/2402.08114)  
f-DPO - Filtered Direct Preference Optimization [[pdf]](https://arxiv.org/pdf/2404.13846)  
RSO - Statistical Rejection Sampling Improves Preference Optimization [[pdf]](https://arxiv.org/pdf/2309.06657)  
RS-DPO - RS-DPO: A Hybrid Rejection Sampling and Direct Preference Optimization Method for Alignment of Large Language Models [[pdf]](https://arxiv.org/pdf/2402.10038)
## explicit reward model(loss)
ODPO - Direct Preference Optimization with an Offset [[pdf]](https://arxiv.org/pdf/2402.10571)  
Sr-DPO - Direct Alignment of Language Models via Quality-Aware Self-Refinement [[pdf]](https://arxiv.org/pdf/2405.21040)  
BRAIN - BRAIN: Bayesian Reward-conditioned Amortized INference for natural language generation from feedback [[pdf]](https://arxiv.org/pdf/2402.02479)  
## pairwise data structure expansion
KTO - KTO: Model Alignment as Prospect Theoretic Optimization [[pdf]](https://arxiv.org/pdf/2402.01306)  
ULMA - ULMA: Unified Language Model Alignment with Human Demonstration and Point-wise Preference [[pdf]](https://openreview.net/pdf?id=E5CMyG6jl0)  
LiPO - LiPO: Listwise Preference Optimization through Learning-to-Rank [[pdf]](https://arxiv.org/pdf/2402.01878)  
Curry-DPO - Curry-DPO: Enhancing Alignment using Curriculum Learning & Ranked Preferences [[pdf]](https://arxiv.org/pdf/2403.07230)  
BCO - Binary Classifier Optimization for Large Language Model Alignment [[pdf]](https://arxiv.org/pdf/2404.04656)  
## other methods for data
RPO - Relative Preference Optimization: Enhancing LLM Alignment through Contrasting Responses across Identical and Diverse Prompts [[pdf]]()  
D2O - Negating Negatives: Alignment without Human Positive Samples via Distributional Dispreference Optimization [[pdf]]()  
r-DPO - Refined Direct Preference Optimization with Synthetic Data for Behavioral Alignment of LLMs [[pdf]]()  
XPO - Exploratory Preference Optimization: Harnessing Implicit Q*-Approximation for Sample-Efficient RLHF [[pdf]]()  
## online/interactive DPO
D2PO - D2PO: Discriminator-Guided DPO with Response Evaluation Models [[pdf]]()  
OAIF - Direct Language Model Alignment from Online AI Feedback [[pdf]]()  
sDPO - sDPO: Don’t Use Your Data All at Once [[pdf]]()  
TR-DPO - Learn Your Reference Model for Real Good Alignment [[pdf]]()  
Self-Rewarding - Self-Rewarding Language Models [[pdf]]()  
Interactive-DPO - Iterative Reasoning Preference Optimization [[pdf]]()  
## conparison methods
PRO - Preference Ranking Optimization for Human Alignment [[pdf]]()  
SLiC-HF - SLiC-HF: Sequence Likelihood Calibration with Human Feedback [[pdf]]()  
## divergence
f-DPO - Beyond Reverse KL: Generalizing Direct Preference Optimization with Diverse Divergence Constraints [[pdf]]()  
EXO - Towards Efficient and Exact Optimization of Language Model Alignment [[pdf]]()  
## sequence/token level optimization
R-DPO - Disentangling Length from Quality in Direct Preference Optimization [[pdf]]()  
Sim-DPO - SimPO: Simple Preference Optimization with a Reference-Free Reward [[pdf]]()  
PCO - Some things are more CRINGE than others:Iterative Preference Optimization with the Pairwise Cringe Loss [[pdf]]()  
DPO - From r to Q∗: Your Language Model is Secretly a Q-Function [[pdf]]()  
TDPO - Token-level Direct Preference Optimization [[pdf]]()  
## other method for training
ORPO - ORPO: Monolithic Preference Optimization without Reference Model [[pdf]]()  
MPO - Mixed Preference Optimization: Reinforcement Learning with Data Selection and Better Reference Model [[pdf]]()  
ICDPO - ICDPO: Effectively Borrowing Alignment Capability of Others via In-context Direct Preference Optimization [[pdf]]()  
ATO - Distributional Preference Alignment of LLMs via Optimal Transport [[pdf]]()  
VPO - Value-Incentivized Preference Optimization:A Unified Approach to Online and Offline RLHF [[pdf]]()  
## likelihood decrease/overfitting
NCA - Noise Contrastive Alignment of Language Models with Explicit Rewards [[pdf]]()  
DPOP - Smaug: Fixing Failure Modes of Preference Optimisation with DPO-Positive [[pdf]]()  
IPO - A General Theoretical Paradigm to Understand Learning from Human Preferences [[pdf]]()  
d-DPO - Robust Preference Optimization through Reward Model Distillation [[pdf]]()  
## denoise
r-DPO - Provably Robust DPO: Aligning Language Models with Noisy Feedback [[pdf]]()  
Impact of Preference Noise on the Alignment Performance of Generative Language Models [[pdf]]()  
## self-play DPO
Nash Learning from Human Feedback [[pdf]]()  
Direct Nash Optimization: Teaching Language Models to Self-Improve with General Preferences [[pdf]]()  
Human Alignment of Large Language Models through Online Preference Optimisation [[pdf]]()  
Self-Play Fine-Tuning Converts Weak Language Models to Strong Language Models [[pdf]]()  
Self-Play Preference Optimization for Language Model Alignment [[pdf]]()  
A Minimaximalist Approach to Reinforcement Learning from Human Feedback [[pdf]]()  
## multi objective
Controllable Preference Optimization: Toward Controllable Multi-Objective Alignment [[pdf]]()  
Direct Preference Optimization With Unobserved Preference Heterogeneity [[pdf]]()  
Group Robust Preference Optimization in Reward-free RLHF [[pdf]]()  
Hybrid Preference Optimization: Augmenting Direct Preference Optimization with Auxiliary Objectives [[pdf]]()  
Mallows-DPO: Fine-Tune Your LLM with Preference Dispersions [[pdf]]()  
SPO: Multi-Dimensional Preference Sequential Alignment With Implicit Reward Modeling [[pdf]]()  
## analysis paper
A Mechanistic Understanding of Alignment Algorithms: A Case Study on DPO and Toxicity [[pdf]]()  
Generalized Preference Optimization: A Unified Approach to Offline Alignment [[pdf]]()  
Insights into Alignment: Evaluating DPO and its Variants Across Multiple Tasks [[pdf]]()  
Is DPO Superior to PPO for LLM Alignment? A Comprehensive Study [[pdf]]()  
Iterative Preference Learning from Human Feedback: Bridging Theory and Practice for RLHF under KL-constraint [[pdf]]()  
Policy Optimization in RLHF: The Impact of Out-of-preference Data [[pdf]]()  
Preference Learning Algorithms Do Not Learn Preference Rankings [[pdf]]()  
Reward Model Learning vs. Direct Policy Optimization: A Comparative Analysis of Learning from Human Preferences [[pdf]]()  
Towards Analyzing and Understanding the Limitations of DPO: A Theoretical Perspective [[pdf]]()  
Understanding the performance gap between online and offline alignment algorithms [[pdf]]()  
When is RL better than DPO in RLHF? A Representation and Optimization Perspective [[pdf]]()  



### loss change
| Title | Method | Time  | Discription | Structure | Loss Function|
|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|
| KTO: Model Alignment as Prospect Theoretic Optimization|KTO|arXiv24|maximizes the utility of generations instead of maximizing the log-likelihood of preferences that are hard-to-get|![image](https://github.com/sssth/awesome-DPO/assets/105367602/f66fdb6c-6829-481e-af5d-d8a1c7dcef05)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/cd22ad60-e8cf-4df4-a473-3ad20de4154e)|
| LiPO: Listwise Preference Optimization through Learning-to-Rank|LiPO|arXiv24| formulate the LM alignment as a listwise ranking problem, where the policy can potentially learn more effectively from a ranked list of plausible responses| ![image](https://github.com/istarryn/LLM4REC/assets/105367602/49c4daa2-5fa3-4bb7-8bbe-523a4e50c2a7)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/baebdbb4-807d-4ac0-8802-0696dbdd8675)|
| ULMA: Unified Language Model Alignment with Human Demonstration and Point-wise Preference|ULMA|arXiv23|directly learns from point-wise preference dataset with binary or continuous labels||![image](https://github.com/sssth/awesome-DPO/assets/105367602/22cd7164-508c-4655-81c3-e2eee6f46b34)|
| Statistical Rejection Sampling Improves Preference Optimization | RSO | ICLR24 | DPO only sample preference pairs from SFT policy, use statistical rejection sampling to generate a distribution equal to optimal policy| ![image](https://github.com/istarryn/LLM4REC/assets/105367602/bed64e50-1975-4775-9965-6e0f5643d13c) |![image](https://github.com/sssth/awesome-DPO/assets/105367602/9e77e302-2296-4141-8a3e-d9e992547af7)|
| Direct Preference Optimization with an Offset| ODPO| arXiv24 | use offset to represent the likelihood of the preferred and dispreferred data | ![image](https://github.com/istarryn/LLM4REC/assets/105367602/55327f61-ebb6-47ab-9e18-f18e45a4651f)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/973bd5eb-d8c0-42cb-a763-0a4017949748)|
| Direct Alignment of Language Models via Quality-Aware Self-Refinement|Sr-DPO|arXiv24|use offset to represent the likelihood of the preferred and dispreferred data, difference is that it uses trained model to generate reward||![image](https://github.com/sssth/awesome-DPO/assets/105367602/391711ec-3ff5-4605-bd32-15e89d4d5570)|
| Relative Preference Optimization: Enhancing LLM Alignment through Contrasting Responses across Identical and Diverse Prompts|RPO|arXiv24|compare prefered response to all disprefered response in the dataset and use similarity of prompts to represent adaptive weight|![image](https://github.com/sssth/awesome-DPO/assets/105367602/764c9e2a-89d1-4d71-b93a-0d00da42622b)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/4f3b790c-07d5-4f39-b9b9-76655b8de13f)|
| Noise Contrastive Alignment of Language Models with Explicit Rewards|NCA|arXiv24|regard DPO as a noise contrastive classification problem, design InfoNCA to make loss scalable to any response numbers, while design NCA to prevent likelihood of the best response continually decreases during training||![image](https://github.com/sssth/awesome-DPO/assets/105367602/7054e3b2-be44-46e2-a90b-4d10b0a90b21)|
| Smaug: Fixing Failure Modes of Preference Optimisation with DPO-Positive|DPOP|arXiv24|find that datasets with small edit distance are more likely to suffer from likelihood decrease, add a regularisation to prevent|![image](https://github.com/sssth/awesome-DPO/assets/105367602/e37e6cde-8324-4887-92b1-289c20b7b375)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/43147341-2f71-47b4-ab6e-d5a4b0adf335)|
| Refined Direct Preference Optimization with Synthetic Data for Behavioral Alignment of LLMs|r-DPO|arXiv24|use self-critique prompt of teacher LLM to generate response as data, use another teacher LLM to score the data and use the score to modify the loss of DPO|![image](https://github.com/sssth/awesome-DPO/assets/105367602/62be8536-cdf8-4685-b598-81954c061288)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/09aa9255-1b08-4484-9acf-9083d251b627)|
| Iterative Reasoning Preference Optimization|Interactive RPO|arXiv24|use CoT to let model generate response and reason, then use reward model to construct preference pairs; add NLL regularization to alleviate likelihood decrease and train model interactively|![image](https://github.com/sssth/awesome-DPO/assets/105367602/3a1a6156-403e-4952-be79-02303a8696e8)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/d9ea0ff5-856b-48a5-a083-28e2a73c7496)|
| ORPO: Monolithic Preference Optimization without Reference Model|ORPO|arXiv24|find that SFT training increase the likelihood of undesired response, create a straightforward optimization without reference model|![image](https://github.com/sssth/awesome-DPO/assets/105367602/35d82015-1042-4b35-80d7-57de4964e713)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/5f3b3332-454c-4ce5-adf1-043f124b2ba2)|
| Mixed Preference Optimization: Reinforcement Learning with Data Selection and Better Reference Model|MPO|arXiv24| first train DPO on an easy dataset, and then perform RLHF on a difficult set with DPO model being the reference model|![image](https://github.com/sssth/awesome-DPO/assets/105367602/e7ebfe0b-8624-4fe1-8d0b-5925c36808f3)||
| Negating Negatives: Alignment without Human Positive Samples via Distributional Dispreference Optimization|D2O|arXiv24|because high quality preference pairs are hard to get, use solely human-annotated negative samples and use trained model to generate positive data|![image](https://github.com/sssth/awesome-DPO/assets/105367602/9c20dafb-3d85-464f-a8fc-e4ad9e91555e)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/d6d23b2f-cb43-4f43-93e6-fc2559ebe2b1)|
| Some things are more CRINGE than others:Iterative Preference Optimization with the Pairwise Cringe Loss|PCO|arXiv23|modify DPO loss to pairwise cringe loss|![image](https://github.com/sssth/awesome-DPO/assets/105367602/6eb90182-ecc8-414c-8833-d9c2c738c106)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/0c2827f1-cf1a-4da6-8b80-c13d3c831854)|




### data construction
| Title | Method | Time  | Discription | Structure |
|:-------:|:-------:|:-------:|:-------:|:-------:|
| Reinforcement Learning from Human Feedback with Active Queries | ADPO | arXiv24 | use active-learning and elimilate preference pairs with low reward differential | ![image](https://github.com/istarryn/LLM4REC/assets/105367602/af0fbd5b-3f02-425e-8018-67cf4d529f39)|
| RS-DPO: A Hybrid Rejection Sampling and Direct Preference Optimization Method for Alignment of Large Language Models| RS-DPO | arXiv24 | elimilate preference pairs with low reward differential using a explicit reward model and rejection sampling| ![image](https://github.com/istarryn/LLM4REC/assets/105367602/89f0420e-5a0e-4d3f-92d7-3de9ee5655f3)|
| Filtered Direct Preference Optimization|f-DPO|arXiv24|disgard preference pairs with low reward in prefered response using a explicit reward model|![image](https://github.com/sssth/awesome-DPO/assets/105367602/2fe21743-f7dc-4552-a1bd-b345addb7226)|
| Aligning Large Language Models with Counterfactual DPO|Counterfactual DPO| arXiv24|add desired style imformation to the prompt to let LLM generate preference pairs automatically without human annotation| ![image](https://github.com/sssth/awesome-DPO/assets/105367602/f0143336-cbba-4389-b336-3245be15c1f7)|


### online DPO(update SFT policy during training)
| Title | Method | Time  | Discription | Structure |
|:-------:|:-------:|:-------:|:-------:|:-------:|
| Curry-DPO: Enhancing Alignment using Curriculum Learning & Ranked Preferences | Curry-DPO | arXiv24 |ultilize multiple responses creating multiple preference pairs and use curriculum learning to train preference pairs from easy to hard  | ![image](https://github.com/istarryn/LLM4REC/assets/105367602/f30f96f5-972f-4e03-9234-e195976368d3)|![image](https://github.com/sssth/awesome-DPO/assets/105367602/c4bfa2e7-04bc-4a58-9594-a786eaabc4e1)|
| D2PO: Discriminator-Guided DPO with Response Evaluation Models | D2PO | arXiv24 | update explicit reward model and use it to generate preference pairs during training | ![image](https://github.com/istarryn/LLM4REC/assets/105367602/0903b4e4-5f3c-42af-985f-3bf42c3303d5)|
| Learn Your Reference Model for Real Good Alignment|TR-DPO|arXiv24|update SFT model using soft-update and hard-update|![image](https://github.com/istarryn/LLM4REC/assets/105367602/f96f57fe-94bd-490e-9f77-c6589c353fdc)|
| sDPO: Don’t Use Your Data All at Once|sDPO|arXiv24|dividing the available preference datasets and utilizing them in a step-wise manner|![image](https://github.com/istarryn/LLM4REC/assets/105367602/0ceac2e8-c996-4cc1-9956-e1959d646b47)|
| Direct Language Model Alignment from Online AI Feedback|OAIF|arXiv24|sample responses from current model during training and use LLM to annotate|![image](https://github.com/istarryn/LLM4REC/assets/105367602/44c94172-934b-4b51-a298-e9c669b36ba8)|
| Self-Rewarding Language Models|Self-Rewarding|arXiv24|model itself acts as a reward model to construct preference pairs and update SFT model in interations|![image](https://github.com/sssth/awesome-DPO/assets/105367602/4ab7a888-fcaa-44ea-b80f-63b658c88484)|

### response
| Title | Method | Time  | Discription | Loss Function |
|:-------:|:-------:|:-------:|:-------:|:-------:|
| Disentangling Length from Quality in Direct Preference Optimization|R-DPO|arXiv24|indicate the verbosity bias in DPO, add a regularization term to prevent exploitation of length|![image](https://github.com/sssth/awesome-DPO/assets/105367602/edffc48b-3aca-448d-8549-8c2484b5d846)|
| SimPO: Simple Preference Optimization with a Reference-Free Reward|Sim-DPO|arXiv24|modify the implicit reward to average log probability of response sequences and thus eliminate the need of reference model|![image](https://github.com/sssth/awesome-DPO/assets/105367602/be7ff27c-9c64-4a55-8d95-c8f40c14da6d)|

### optimization direction
| Title | Method | Time  | Discription | Loss Function |
|:-------:|:-------:|:-------:|:-------:|:-------:|
| A General Theoretical Paradigm to Understand Learning from Human Preferences|IPO|PMLR24|DPO is vulnerable to overfitting and neglect the KL divegence term when preference pairs are deterministic, add a regularization to regress the gap between log-likelihood ratios of policy to a constant|![image](https://github.com/sssth/awesome-DPO/assets/105367602/8060d3cb-2c37-4b3b-b519-8278108354a2)|
| Exploratory Preference Optimization: Harnessing Implicit Q*-Approximation for Sample-Efficient RLHF|XPO|arXiv24|add a regularization to DPO loss to enpower model explore outside the support of the initial model and human feedback data, use output of SFT model as negtive sample and use output of trained model as positive sample|![image](https://github.com/sssth/awesome-DPO/assets/105367602/cfafbe91-d952-4ff8-b42c-b857ffe0b26b)|
| Soft Preference Optimization: Aligning Language Models to Expert Distributions|SPO|arXiv24|make model converges to a softmax of scaled rewards with the distribution’s “softness" adjustable via the softmax exponent, and use online KL divegence regularization term|![image](https://github.com/sssth/awesome-DPO/assets/105367602/e534e419-9623-4691-91a4-369baaee2fb6)|
| Distributional Preference Alignment of LLMs via Optimal Transport|ATO|arXiv24|modify DPO's optimization from sample level to distributional level, making making the reward distribution of the positive samples stochastically dominant in the first order on the distribution of negative samples|![image](https://github.com/sssth/awesome-DPO/assets/105367602/2edf2e3b-89b0-4a48-a9cc-0384747cb5b5)|
| Value-Incentivized Preference Optimization:A Unified Approach to Online and Offline RLHF|VPO|arXiv24|directly optimizes the LLM policy with the optimistic/pessimistic principles under uncertainty of the reward model|![!image](https://github.com/sssth/awesome-DPO/assets/105367602/761df919-b4f7-4ac4-b567-3c27e6210042)|

### divergence
| Title | Method | Time  | Discription | Loss Function |
|:-------:|:-------:|:-------:|:-------:|:-------:|
| Towards Efficient and Exact Optimization of Language Model Alignment|EXO|arXiv24|confirm that DPO corresponds to minimizing the forward KL divergence while RLHF minimize the reverse KL divergence, leading to distinct solutions when considering the realistic constraints of model capacity, so they modify the DPO loss to be equal to reverse KL divergence|![image](https://github.com/sssth/awesome-DPO/assets/105367602/7edfefc9-a617-4ad7-aa3a-374563955447)|
| Beyond Reverse KL: Generalizing Direct Preference Optimization with Diverse Divergence Constraints|f-DPO|arXiv24|incorperate diverse divergence constraints toensure a balance between alignment performance and generation diversity|![image](https://github.com/sssth/awesome-DPO/assets/105367602/eda6fe7f-c385-46dc-aaed-6a35e44fc2bf)|
