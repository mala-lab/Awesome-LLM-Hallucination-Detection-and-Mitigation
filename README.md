 # Awesome-LLM-Hallucination-Detection-and-Mitigation


[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) 
![Stars](https://img.shields.io/github/stars/mala-lab/Awesome-LLM-Hallucination-Detection-and-Mitigation)
[![Visits Badge](https://badges.pufler.dev/visits/mala-lab/Awesome-LLM-Hallucination-Detection-and-Mitigation)](https://badges.pufler.dev/visits/mala-lab/Awesome-LLM-Hallucination-Detection-and-Mitigation)


A collection of papers on LLM hallucination evaluation benchmark, detection, and mitigation.

We will continue to update this list with the latest resources. If you find any missed resources (paper/code) or errors, please **feel free to open an issue or make a pull request**.

 

## Hallucinations Evaluation Benchmark 

- [Li2023] HaluEval: A Large-Scale Hallucination Evaluation Benchmark for Large Language Models in *EMNLP*, 2023. [\[paper\]](https://arxiv.org/abs/2305.11747)

- [Chen2024] FactCHD: Benchmarking Fact-Conficting Hallucination Detection in *IJCAI*, 2024. [\[paper\]](https://www.ijcai.org/proceedings/2024/0687.pdf)[\[code\]](https://github.com/zjunlp/FactCHD)  

- [Su2024] Unsupervised Real-Time Hallucination Detection based on the Internal States of Large Language Models in *Arxiv*, 2024.[\[paper\]](https://arxiv.org/pdf/2403.06448)[\[code\]](https://github.com/oneal2000/MIND/tree/main) 
  
- [Ji2024] ANAH: Analytical Annotation of Hallucinations in Large Language Models in *ACL*, 2024. [\[paper\]](https://arxiv.org/abs/2405.20315)

- [Simhi2024] Constructing Benchmarks and Interventions for Combating Hallucinations in LLMs in *Arxiv*, 2024. [\[paper\]](https://arxiv.org/abs/2404.09971)[\[code\]](https://github.com/technion-cs-nlp/hallucination-mitigation)  



## Hallucination Detection 

### Fact-checking 

- [Niu2024] RAGTruth: A Hallucination Corpus for Developing Trustworthy Retrieval-Augmented Language Models in *ACL*, 2024.  [\[paper\]](https://aclanthology.org/2024.acl-long.585.pdf)[\[code\]](https://github.com/ParticleMedia/RAGTruth)  

- [Chen2024] FactCHD: Benchmarking Fact-Conficting Hallucination Detection in *IJCAI*, 2024. [\[paper\]](https://www.ijcai.org/proceedings/2024/0687.pdf)[\[code\]](https://github.com/zjunlp/FactCHD)  
  
- [Zhang2024] KnowHalu: Hallucination Detection via Multi-Form Knowledge-Based Factual Checking in *Arxiv*, 2024. [\[paper\]](https://arxiv.org/pdf/2404.02935)[\[code\]](https://github.com/javyduck/KnowHalu)

-  [Rawte2024] FACTOID: FACtual enTailment fOr hallucInation Detection in *Arxiv*, 2024. [\[paper\]](https://arxiv.org/abs/2403.19113)[\[code\]]() 

-  [Es2024] RAGAs: Automated evaluation of retrieval augmented generation in *EACL*, 2024. [\[paper\]](https://aclanthology.org/2024.eacl-demo.16.pdf)[\[code\]](https://github.com/explodinggradients/ragas) 

- [Hu2024]  RefChecker: Reference-based Fine-grained Hallucination Checker and Benchmark for Large Language Models in *Arxiv*, 2024. [\[paper\]](https://arxiv.org/abs/2405.14486)[\[code\]](https://github.com/amazon-science/RefChecker) 

- [Zhang2025] CORRECT: Context- and Reference-Augmented Reasoning and Prompting for Fact-Checking, in *NAACL*, 2025. [\[paper\]](https://drive.google.com/file/d/1-2fieczt68O5SCFhhC4kOC7lp3D6oDrN/view)[\[code\]](https://github.com/cezhang01/correct) 
,

### Uncertainty Analysis 

- [Azaria] The internal state of an llm knows when it’s lying in *EMNLP findings*, 2023.  [\[paper\]](https://aclanthology.org/2023.findings-emnlp.68.pdf)[\[code\]](https://github.com/zthang/focus) 

- [Zhang2023] Enhancing Uncertainty-Based Hallucination Detection with Stronger Focus in *EMNLP*, 2023. [\[paper\]](https://aclanthology.org/2023.emnlp-main.58v2.pdf)[\[code\]](https://github.com/zthang/focus) 

- [Snyder2024] On Early Detection of Hallucinations in Factual Question Answering in *KDD*, 2024.[\[paper\]](https://arxiv.org/pdf/2312.14183)[\[code\]](https://github.com/amazon-science/llm-hallucinations-factual-qa)

- [Chuang2024] Lookback Lens: Detecting and Mitigating Contextual Hallucinations in Large Language Models Using Only Attention Maps in *EMNLP*, 2024.  [\[paper\]](https://arxiv.org/abs/2407.07071)[\[code\]](https://github.com/voidism/Lookback-Lens)

- [Ji2024]  LLM Internal States Reveal Hallucination Risk Faced With a Query in *Arxiv*, 2024. [\[paper\]](https://arxiv.org/pdf/2407.03282)[\[code\]](https://github.com/ziweiji/Internal_States_Reveal_Hallucination)

- [Bouchard2025] Uncertainty Quantification for Language Models: A Suite of Black-Box, White-Box, LLM Judge, and Ensemble Scorers in *Arxiv*, 2025. \[paper\]](https://arxiv.org/abs/2504.19254)[\[code\]](https://github.com/cvs-health/uqlm)

### Consistency Measure 

- [Cohen2023] LM vs LM: Detecting Factual Errors via Cross Examination in *Arxiv*, 2023. [\[paper\]](https://arxiv.org/abs/2305.13281)[\[code\]]() 

- [Manakul2023] SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models in *EMNLP*, 2023. [\[paper\]](https://arxiv.org/abs/2303.08896)[\[code\]](https://github.com/potsawee/selfcheckgpt) 

- [Chen2023] Hallucination Detection: Robustly Discerning Reliable Answers in Large Language Models in *CIKM*, 2023. [\[paper\]](https://arxiv.org/abs/2407.04121)[\[code\]]() 

- [Su2024] Unsupervised Real-Time Hallucination Detection based on the Internal States of Large Language Models in *Arxiv*, 2024.[\[paper\]](https://arxiv.org/pdf/2403.06448)[\[code\]](https://github.com/oneal2000/MIND/tree/main) 

- [Mündler2024] Self-Contradictory Hallucinations of LLMs: Evaluation, Detection and Mitigation in *ICLR*, 2024.[\[paper\]](https://arxiv.org/pdf/2305.15852)[\[code\]](https://chatprotect.ai/)

- [Chen2024] INSIDE: LLMs' Internal States Retain the Power of Hallucination Detection in *ICLR*, 2024. [\[paper\]](https://arxiv.org/abs/2402.03744)[\[code\]](https://github.com/D2I-ai/eigenscore)

- [Kossen2024] Semantic Entropy Probes: Robust and Cheap Hallucination Detection in LLMs in *ICML*, 2024.  [\[paper\]](https://arxiv.org/pdf/2406.15927)[\[code\]](https://github.com/OATML/semantic-entropy-probes)

- [Xu2024] Hallucination is Inevitable:An Innate Limitation of Large Language Models in *Arxiv*, 2024. [\[paper\]](https://arxiv.org/pdf/2401.11817)[\[code\]]() 

- [Niu2025] Robust Hallucination Detection in LLMs via Adaptive Token Selection in *Arxiv*, 2025.[\[paper\]](https://arxiv.org/abs/2504.07863)[\[code\]]()

- [Wang2025]  Latent Space Chain-of-Embedding Enables Output-free LLM Self-Evaluation in *ICLR*, 2025. [\[paper\]](https://arxiv.org/abs/2410.13640)[\[code\]](https://github.com/Alsace08/Chain-of-Embedding) 

- [Sun2025] Why and How LLMs Hallucinate: Connecting the Dots with Subsequence Associations in *Arxiv*, 2025. [\[paper\]](https://arxiv.org/abs/2504.12691)[\[code\]](https://github.com/sunyiyou/SAT) 

- [Islam2025] How Much Do LLMs Hallucinate across Languages? On Multilingual Estimation of LLM Hallucination in the Wild in *Arxiv*, 2025. [\[paper\]](https://arxiv.org/pdf/2502.12769)[\[code\]]() 


## Hallucination Mitigation 



### Model Calibration 

- [Li2023] Inference-Time Intervention: Eliciting Truthful Answers from a Language Model in *NeurIPS*, 2023. [\[paper\]](https://arxiv.org/abs/2306.03341)[\[code\]](https://github.com/likenneth/honest_llama)

- [Liu2023] LitCab: Lightweight Language Model Calibration over Short- and Long-form Responses in *ICLR*,2023.  [\[paper\]](https://arxiv.org/abs/2310.19208)[\[code\]](https://github.com/launchnlp/LitCab)

- [Ji2023] Towards Mitigating Hallucination in Large Language Models via Self-Reflection in *EMNLP findings*, 2023. [\[paper\]](https://arxiv.org/abs/2310.06271)

- [Campbell2023] Localizing Lying in Llama: Understanding Instructed Dishonesty on True-False Questions Through Prompting, Probing, and Patching in *Arxiv*, 2023. [\[paper\]](https://arxiv.org/pdf/2311.15131)

- [Shi2023] Trusting Your Evidence: Hallucinate Less with Context-aware Decoding in *Arxiv*, 2023. [\[paper\]](https://arxiv.org/pdf/2305.14739)

- [Chen2024] Truth Forest: Toward Multi-Scale Truthfulness in Large Language Models through Intervention without Tuning in *AAAI*,2024.  [\[paper\]](https://arxiv.org/abs/2312.17484)[\[code\]]()

- [Zhang2024] R-Tuning: Instructing Large Language Models to Say `I Don't Know' in *NAACL*,  2023.  [\[paper\]](https://arxiv.org/abs/2311.09677)[\[code\]](https://github.com/shizhediao/R-Tuning)

- [Chuang2024] DoLa: Decoding by Contrasting Layers Improves Factuality in Large Language Models in *ICLR*, 2024. [\[paper\]](https://arxiv.org/abs/2309.03883)[\[code\]](https://github.com/voidism/DoLa)

- [Kapoor2024] Calibration-Tuning: Teaching Large Language Models to Know What They Don’t Know in *UncertaiNLP*, 2024. [\[paper\]](https://aclanthology.org/2024.uncertainlp-1.1/)

- [Zhang2024] TruthX: Alleviating Hallucinations by Editing Large Language Models in Truthful Space in *ACL*, 2024. [\[paper\]](https://arxiv.org/abs/2402.17811)[\[code\]](https://ictnlp.github.io/TruthX-site/)

- [Zhou2025] HaDeMiF: Hallucination Detection and Mitigation in Large Language Models in *ICLR*, 2025. [\[paper\]](https://openreview.net/pdf?id=VwOYxPScxB)[\[code\]]()

- [Zhang2025] The Law of Knowledge Overshadowing: Towards Understanding, Predicting, and Preventing LLM Hallucination in *ACL*, 2025. [\[paper\]](https://arxiv.org/abs/2502.16143)[\[code\]]()

- [Wu2025] Mitigating Hallucinations in Large Vision-Language Models via Entity-Centric Multimodal Preference Optimization in *Arxiv*, 2025. [\[paper\]](https://arxiv.org/abs/2506.04039)[\[code\]](https://github.com/RobitsG/EMPO)


### External Knowledge 

- [Ji2022] RHO (ρ): Reducing Hallucination in Open-domain Dialogues with Knowledge Grounding in *ACL findings*, 2022. [\[paper\]](https://arxiv.org/abs/2212.01588)

- [Sun2025] Redeep: Detecting hallucination in retrieval-augmented generation via mechanistic interpretability  in *ICLR*, 2025. [\[paper\]](https://arxiv.org/pdf/2410.11414)[\[code\]](https://github.com/Jeryi-Sun/ReDEeP-ICLR)

- [Dey2025] Uncertainty-Aware Fusion: An Ensemble Framework for Mitigating Hallucinations in Large Language Models in *WebConf*, 2025. [\[paper\]](https://arxiv.org/abs/2503.05757)[\[code\]]()

- [Lavrinovics2025] MultiHal: Multilingual Dataset for Knowledge-Graph Grounded Evaluation of LLM Hallucinations in *Arxiv*, 2025. [\[paper\]](https://arxiv.org/abs/2505.14101)[\[code\]](https://github.com/ernlavr/multihal)

- [Sui2025] Bridging External and Parametric Knowledge: Mitigating Hallucination of LLMs with Shared-Private Semantic Synergy in Dual-Stream Knowledge in *Arxiv*, 2025. [\[paper\]](https://arxiv.org/pdf/2506.06240)[\[code\]]()

- [Ferrando2025]  Do I Know This Entity? Knowledge Awareness and Hallucinations in Language Models in *ICLR*, 2025.  [\[paper\]](https://arxiv.org/abs/2411.14257)[\[code\]](https://github.com/javiferran/sae_entities)



# Related Survey 

- [Wang2023] Survey on Factuality in Large Language Models: Knowledge, Retrieval and Domain-Specificity in *Arxiv*,2023. [\[paper\]](https://arxiv.org/abs/2310.07521) 
  
- [Ye2023] Cognitive Mirage: A Review of Hallucinations in Large Language Models  in *Arxiv*,2023. [\[paper\]](https://arxiv.org/abs/2309.06794v1) 
  
- [Zhang2023] Siren's Song in the AI Ocean: A Survey on Hallucination in Large Language Models in *Arxiv*,2023. [\[paper\]](https://arxiv.org/abs/2309.01219)

- [Gao2023] Retrieval-augmented generation for large language models: A survey in *Arxiv*, 2023. [\[paper\]](https://arxiv.org/pdf/2312.10997)

- [Huang2024] A Survey on Hallucination in Large Language Models: Principles, Taxonomy, Challenges, and Open Questions in *TOIS*, 2024. [\[paper\]](https://arxiv.org/pdf/2410.11414)

- [Ji2024] Survey of Hallucination in Natural Language Generation in *CSUR*, 2024.  [\[paper\]](https://arxiv.org/abs/2202.03629)




