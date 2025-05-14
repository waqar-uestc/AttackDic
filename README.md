# Navigating Threats in Federated Recommender Systems: A Survey of Poisoning Attacks and Defense Strategies
This repository complements our survey by providing curated codebases, datasets, and tools related to poisoning attacks and defense strategies in Federated Recommender Systems (FedRS). It aims to support reproducibility, benchmarking, and practical experimentation for researchers and developers working in this emerging domain. In addition to summarizing academic efforts, we provide hands-on resources to help the community reproduce existing works, test new hypotheses, and accelerate deployment in both research prototypes and real-world production environments. This bridge between theory and implementation is critical for driving innovation in secure federated recommendation systems.

## Reproducibility Aspects (Evaluation Frameworks and Data Sets):
We have carefully selected widely-used, publicly available datasets and evaluation frameworks that are commonly adopted in federated recommender systems research. These resources include real-world user-item interaction datasets, federated data partitioning schemes, and benchmark metrics to ensure fair and consistent comparison across different attack and defense models. The goal is to enable reproducibility of experimental results and support standardized evaluation for future studies in this domain.

#### Evaluation Frameworks 
| Tile                                   | Affiliations                                                                            | Venue Year | Material                                                                                                                 |
|----------------------------------------|-----------------------------------------------------------------------------------------|-------|--------------------------------------------------------------------------------------------------------------------------|
|	Recommenders	|	National University of Defense Technology, China	|	2025	|	[Paper](https://www.amazon.com/Recommender-Systems-Frontiers-Practices-Dongsheng/dp/9819989639/), [Code](https://github.com/recommenders-team/recommenders)	|
|	NVIDIA AI HugeCTR	|	NVIDIA	|	2025	|	[Paper](https://developer.nvidia.com/merlin), [Code](https://github.com/NVIDIA-Merlin/HugeCTR)	|
|	Surprise	|	Columbia University, USA	|	2023	|	[Paper](https://doi.org/10.21105/joss.02174), [Code](https://surpriselib.com/)	|
|	Case Recommender	|	University of São Paulo, Brazil	|	2023	|	[Paper](http://doi.acm.org/10.1145/3240323.3241611), [Code](https://github.com/caserec/CaseRecommender)	|
|	Microsoft Recommender	|	Micrrosoft UK	|	2023	|	[Paper](https://dl.acm.org/doi/abs/10.1145/3366424.3382692), [Code](https://github.com/microsoft/recommenders)	|
|	ELLIOT	|	SisInfLab Group	|	2023	|	[Paper](https://doi.org/10.1145/3404835.3463245), [Code](https://github.com/sisinflab/elliot)	|
|	RecZilla	|	University of Maryland, USA	|	2023	|	[Paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/1c446a652e50b1ea5618b66c07bfc0c5-Abstract-Conference.html), [Code](https://github.com/naszilla/reczilla)	|
|	RecBole	|	Renmin University of China	|	2023	|	[Paper](https://dl.acm.org/doi/abs/10.1145/3511808.3557680), [Code](https://github.com/RUCAIBox/RecBole)	|
|	RGRecSys	|	University of Illinois at Chicago, USA	|	2023	|	[Paper](https://dl.acm.org/doi/abs/10.1145/3488560.3502192), [Code](https://github.com/salesforce/RGRecSys)	|
|	DaisyRec 	|	Macquarie University, Australia	|	2023	|	[Paper](https://dl.acm.org/doi/10.1145/3383313.3412489), [Code](https://github.com/AmazingDD/daisyRec)	|
|	LightFM	|	Maciej Kula	|	2023	|	[Paper](http://ceur-ws.org/Vol-1448/paper4.pdf), [Code](https://github.com/lyst/lightfm)	|
|	TensorFlow Recommenders	|	Google TensorFlow 	|	2023	|	[Paper](https://www.tensorflow.org/recommenders), [Code](https://github.com/tensorflow/recommenders)	|
|	Cornac	|	Singapore Management University, RIT France	|	2023	|	[Paper](https://dl.acm.org/doi/abs/10.1145/3460231.3473324), [Code](https://github.com/PreferredAI/cornac)	|
|	ClayRS	|	University of Bari Aldo Moro, Italy	|	2023	|	[Paper](https://www.sciencedirect.com/science/article/pii/S0306437923001096), [Code](https://github.com/swapUniba/ClayRS)	|
|	FuxiCTR	|	Huawei Noah Ark Lab, China	|	2023	|	[Paper](https://dl.acm.org/doi/10.1145/3477495.3531723), [Code](https://github.com/reczoo/FuxiCTR)	|
|	ReChorus	|	Tsinghua University, China	|	2023	|	[Paper](https://dl.acm.org/doi/abs/10.1145/3397271.3401131), [Code](https://github.com/THUwangcy/ReChorus)	|
|	RecList	|	Coveo Labs, USA	|	2023	|	[Paper](https://doi.org/10.1145/3487553.3524215), [Code](https://github.com/RecList/reclist)	|


## Federated Learning Toolkit: 
We explored a range of open-source libraries and codebases designed to implement federated learning techniques. Whether you're interested in preserving user privacy, enhancing recommendation performance, or both, these resources provide a foundation to build upon.

#### FL Codebases Recent Implementations

| Tile                                   | Affiliations                                                                            | Venue Year | Material                                                                                                                 |
|----------------------------------------|-----------------------------------------------------------------------------------------|-------|--------------------------------------------------------------------------------------------------------------------------|
| FATE - Federated AI Technology Enabler | AI Group from WeBank, [FedAI](https://www.fedai.org)                                       | 2023  | [Paper](https://www.jmlr.org/papers/volume22/20-815/20-815.pdf) , [Code](https://github.com/FederatedAI/FATE)            |
| OpenFL                                 | Intel and The University of Pennsylvania, [FeTS](https://www.med.upenn.edu/cbica/fets/) | 2022  | [Paper](http://iopscience.iop.org/article/10.1088/1361-6560/ac97d9), [Code](https://github.com/securefederatedai/openfl) |
| TFF - TensorFlow Federated |	Google [TensorFlow](https://www.tensorflow.org/federated)	| 2023 |	[Link](https://www.tensorflow.org/federated) |
| FedML - Federated Machine Learning |	[FEDML](https://fedml.ai/)	| 2023 |	[Paper](https://arxiv.org/pdf/2007.13518.pdf), [Code](https://github.com/FedML-AI/FedML) |
| Flower - A Friendly Federated Learning Framework |	Adap Hamburg - Germany, University of Cambridge - UK, Nokia Bell Labs - UK 	| 2023 |	[Paper](https://arxiv.org/pdf/2007.14390.pdf), [Code](https://github.com/adap/flower) |
| Google research on Federated Learning |	Open source |	2023 |	[Link](https://github.com/google-research/federated) |
| A general collection of FL resources-1 |	Poga Po - Open source | 	2023 |	[Link](https://github.com/poga/awesome-federated-learning) |
| A general collection of FL resources-2 |	Anbu Huang - Innovation Cat |	2023 |	[Link](https://github.com/innovation-cat/Awesome-Federated-Machine-Learning)| 
| An organized collection FL codebases and papers for **Federated RS** |	- |	2023 |	[Link](https://github.com/XuanangD/FederatedRS) |
| An organized collection FL codebases and papers for __Federated RS__ |	Austin Liu, [YANG](https://github.com/AustinNeverPee) | 2023 |	[Link](https://github.com/AustinNeverPee/FedRecPapers)|
| Vertical Federated Graph Neural Network for Recommender System|	National University of Singapore |	ICML 2023 |	[Paper](https://arxiv.org/pdf/2303.05786.pdf), [Code](https://github.com/maiph123/VerticalGNN) |
| Privacy Matters: Vertical Federated Linear Contextual Bandits for Privacy Protected Recommendation |	University of Cambridge |	KDD 2023 |	[Paper](https://dl.acm.org/doi/abs/10.1145/3580305.3599475), [Code](https://github.com/umbc-sanjaylab/FedPseudo_KDD23) |
| UA-FedRec: Untargeted Attack on Federated News Recommendation| 	University of Science and Technology of China |	KDD 2023 |	[Paper](https://dl.acm.org/doi/10.1145/3580305.3599923), [Code](https://github.com/yjw1029/UA-FedRec) |
| PrivateRec: Differentially Private Model Training and Online Serving for Federated News Recommendation |	Renmin University of China |	KDD 2023 |	[Paper](https://dl.acm.org/doi/abs/10.1145/3580305.3599889), [Code]() |
| FedAttack: Effective and Covert Poisoning Attack on Federated Recommendation via Hard Sampling | Tsinghua University                                         | KDD 2022   | [Paper](https://dl.acm.org/doi/abs/10.1145/3534678.3539119), [Code](https://github.com/wuch15/FedAttack)                |
| Dual Personalization on Federated Recommendation                                               | Jilin University - China, University of Technology Sydney   | IJCAI 2023 | [Paper](https://www.ijcai.org/proceedings/2023/0507.pdf), [Code](https://github.com/Zhangcx19/IJCAI-23-PFedRec)         |
| Efficient federated item similarity model for privacy-preserving recommendation                | Huazhong University of Science and Technology Wuhan - China | IPM 2023   | [Paper](https://www.sciencedirect.com/science/article/pii/S0306457323002078), [Code](https://github.com/XuanangD/FedIS) |
| Federated News Recommendation with Fine-grained Interpolation and Dynamic Clustering                     | University of Science and Technology of China, State Key Laboratory of Cognitive Intelligence Hefei China | CIKM 2023  | [Paper](https://dl.acm.org/doi/10.1145/3583780.3614881), [Code](https://github.com/yusanshi/FINDING)        |
| Untargeted Attack against Federated Recommendation Systems via Poisonous Item Embeddings and the Defense | University of Science and Technology of China, State Key Laboratory of Cognitive Intelligence Hefei China | AAAI 2023  | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25611), [Code](https://github.com/yflyl613/FedRec) |
| Fine-Grained Preference-Aware Personalized Federated POI Recommendation with Data Sparsity               | Shandong University, Qingdao, China                                                                       | SIGIR 2023 | [Paper](https://dl.acm.org/doi/10.1145/3539618.3591688), [Code](https://github.com/Leavesy/PrefFedPOI)      |
| Wyze Rule: Federated Rule Dataset for Rule Recommendation Benchmarking               | Wyze Labs, Washington, USA  | NeurIPS 2023 | [Paper](https://openreview.net/pdf?id=qynH28Y4xE), [Code](https://github.com/yh-yao/FedRule)      |
| FedSlate: A Federated Deep Reinforcement Learning Recommender System                 | Westlake University, Hangzhou, China  | NeurIPS 2024 | [Paper](https://arxiv.org/pdf/2409.14872v1), [Code](https://github.com/TianYaDY/FedSlate)      |
| FedHCDR: Federated Cross-Domain Recommendation with Hypergraph Signal Decoupling     |  HIT, Shenzhen, China     | ECML/PKDD 2024 | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-70341-6_21), [Code](https://github.com/orion-orion/fedhcdr)      |
| Federated Recommendation via Hybrid Retrieval Augmented Generation         | UoI at Urbana-Champaign, USA    | arXive 2024 | [Paper](https://arxiv.org/pdf/2403.04256v1), [Code](https://github.com/huiminzeng/gpt-fedrec)      |



## Attack models 

This section collects and curates recent implementations of poisoning attack models specifically adapted or designed for federated recommender systems. Federated learning introduces unique vulnerabilities due to decentralized training, which attackers exploit through gradient manipulation, malicious client behaviors, or data poisoning. We selected state-of-the-art and representative attack models—including both classical and AI-driven methods—to facilitate understanding, benchmarking, and extension by researchers and practitioners.


| Tile                                   | Affiliations                                                                            | Venue Year | Material                                                                                                                 |
|----------------------------------------|-----------------------------------------------------------------------------------------|-------|--------------------------------------------------------------------------------------------------------------------------|
|	Untargeted Embedding Attacks on FedRec	|	University of Science and Technology of China	|	2023	|	[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/25611), [Code](https://github.com/yflyl613/FedRec)	|
|	RAIFLE: attacks on Federated Learning with Adversarial Data Manipulation	|	University of Massachusetts Amherst	|	2025	|	[Paper](https://arxiv.org/pdf/2310.19163), [Code](https://github.com/dzungvpham/raifle)	|
|	Cocktail Party Attack	|	Meta AI	|	2023	|	[Paper](https://proceedings.mlr.press/v202/kariyappa23a/kariyappa23a.pdf), [Code](https://github.com/facebookresearch/cocktail_party_attack)	|
|	Focused Flip: Vulnerability of Backdoor Defenses for Federated Learning	|	Pennsylvania State University	|	2023	|	[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/26393), [Code](https://github.com/jinghuichen/Focused-Flip-Federated-Backdoor-Attack)	|
|	Untargeted Attack on Federated News Recommendation	|	University of Science and Technology of China	|	2023	|	[Paper](https://dl.acm.org/doi/pdf/10.1145/3580305.3599923), [Code](https://github.com/yjw1029/UA-FedRec)	|
|	Robust FedRS Against Model Poisoning	|	Binghamton University, USA	|	KDD 2024	|	[Paper](https://dl.acm.org/doi/10.1145/3637528.3671906), [Code](https://github.com/GYan58/KDD-2024-FedRoLA)	|
|	An Optimization-Based Attack Framework	|	Jilin University, China	|	arXiv 2024	|	[Paper](https://arxiv.org/abs/2407.15267), [Code](https://github.com/Yuxin104/BreakSTOAPoisoningDefenses)	|
|	Backdoor FL by Poisoning Backdoor-critical Layers	|	Stony Brook University, USA	|	ICLR 2024	|	[Paper](https://openreview.net/pdf?id=AJBGSVSTT2), [Code](https://github.com/zhmzm/Poisoning_Backdoor-critical_Layers_Attack)	|
|	Poisoning Attack on Federated Knowledge Graph Embedding	|	Hong Kong Polytechnic University, China	|	WWW 2024	|	[Paper](https://dl.acm.org/doi/10.1145/3589334.3645422), [Code](https://github.com/jisooma/FKGEPoison)	|
|	Poisoning Attacks and Defenses in Recommender Systems	|	The University of Queensland, Australia	|	arXiv 2024	|	[Paper](https://arxiv.org/abs/2406.01022), [Code](https://github.com/CoderWZW/ARLib)	|
|	Federated Recommendation with Additive Personalization	|	VinUniversity Hanoi, Vietnam	|	ICLR 2024	|	[Paper](https://arxiv.org/pdf/2401.03748v1), [Code](https://github.com/mtics/FedRAP)	|
|	An Efficient Federated Graph Neural Network for PoI Recommendation	|	Federation University, Australia	|	ACM-TSN 2024	|	[Paper](https://dl.acm.org/doi/abs/10.1145/3694682), [Code](https://github.com/yushuowiki/FedGST)	|
|	Privacy-preserving federated knowledge graph aware recommender system	|	Zhongnan University of Economics and Law, China	|	 Applied Intelligence  2024	|	[Paper](https://dl.acm.org/doi/abs/10.1145/3694682), [Code](https://github.com/yushuowiki/FedGST)	|
|	Semi-global sequential recommendation via EM-like federated training	|	Polytechnic University, China	|	Expert Systems with Applications 2024	|	[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0957417424003257), [Code](https://github.com/MuziLee-x/FedEM)	|

## Defense models 
This section compiles key defense mechanisms tailored to mitigate poisoning attacks in federated recommender systems. Given the collaborative yet vulnerable nature of FL-based RS, defense strategies must address adversarial behaviors while preserving model utility and personalization. We include recent implementations of robust aggregation techniques, anomaly detection methods, and adaptive learning strategies that have shown effectiveness in FL settings. These resources support the community in replicating, comparing, and extending defense techniques in realistic scenarios.

| Tile                                   | Affiliations                                                                            | Venue Year | Material                                                                                                                 |
|----------------------------------------|-----------------------------------------------------------------------------------------|-------|--------------------------------------------------------------------------------------------------------------------------|
|	PFedRec: Dual Personalization	|	University of Technology Sydney	|	2023	|	[Paper](https://arxiv.org/abs/2301.08143), [Code](https://github.com/Zhangcx19/IJCAI-23-PFedRec)	|
|	PFGNNPlus for Item-to-Item FedRec	|	University of Illinois Chicago	|	2023	|	[Paper](https://arxiv.org/abs/2306.03191), [Code](https://github.com/zfan20/PFGNNPlus)	|
|	Parameter Transmission-Free Federated Recommender System	|	The University of Queensland	|	2024	|	[Paper](https://arxiv.org/pdf/2311.14968), [Code](https://github.com/hi-weiyuan/PTF-FedRec)	|
|	FedDefender: Client-Side Defense	|	Microsoft Research Asia	|	2023	|	[Paper](https://arxiv.org/pdf/2307.09048), [Code](https://github.com/deu30303/FedDefender)	|
|	CoLR: Low-Rank FedRec	|	College of Engineering & Computer
Science, VinUniversity	|	2024	|	[Paper](https://arxiv.org/pdf/2401.03748), [Code](https://github.com/NNHieu/CoLR-FedRec)	|
| FATE - Federated AI Technology Enabler | AI Group from WeBank, [FedAI](https://www.fedai.org)                                       | 2023  | [Paper](https://www.jmlr.org/papers/volume22/20-815/20-815.pdf) , [Code](https://github.com/FederatedAI/FATE)            |
| OpenFL                                 | Intel and The University of Pennsylvania, [FeTS](https://www.med.upenn.edu/cbica/fets/) | 2022  | [Paper](http://iopscience.iop.org/article/10.1088/1361-6560/ac97d9), [Code](https://github.com/securefederatedai/openfl) |
