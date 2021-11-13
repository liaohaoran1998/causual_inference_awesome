按阅读顺序  

1. **Counterfactual Story Reasoning and Generation**, EMNLP, 2019. [[paper](https://arxiv.org/pdf/1909.04076.pdf),[code](https://github.com/qkaren/Counterfactual-StoryRW)]  
    - new task: *Counterfactual Story Rewriting*
    - new dataset: *TIMETRAVEL*
    - compete several baselines
2. **Counterfactual Vision and Language Learning**, CVPR, 2020. [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Abbasnejad_Counterfactual_Vision_and_Language_Learning_CVPR_2020_paper.pdf)]  
    - task: *Visual Question Answering* (VQA)
    - core idea: counterfactual training method
    - exploit from *multiple modalities* and improves *generalization*
3. **Counterfactual Generator: A Weakly-Supervised Method for Named Entity Recognition**, EMNLP, 2020. [[paper](https://aclanthology.org/2020.emnlp-main.590.pdf), [code](https://github.com/xijiz/cfgen)]  
    - task: *Named Entity Recognition* (NER)
    - core idea: intervene on the location entity
    - propose counterfactual generator to augment dataset; eliminate spurious correlations (mostly *identity*); improves generalization under limited data.
1. **Counterfactual Data Augmentation for Neural Machine Translation**, NAACL-HLT, 2021. [paper](https://aclanthology.org/2021.naacl-main.18.pdf) 
    - task: *Neural machine translation* (NMT)
    - core idea: generate counterfactual aligned phrases
    - interpret translation language model as a Gumbel-Max Structural Causal Model.
1. **KACE: Generating Knowledge Aware Contrastive Explanations for Natural Language Inference**, ACL, 2021. [[paper](https://aclanthology.org/2021.acl-long.196.pdf)]  
    - task: *explanation generation* and *natural language inference* (NLI)
    - core idea: perturbe/intervene and then
