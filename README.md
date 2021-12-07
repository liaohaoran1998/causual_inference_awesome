# Recent papers and resources on Causal Inference
## Survey Papers
* Toward Causal Representation Learning, IEEE, 2021. [paper](https://ieeexplore.ieee.org/abstract/document/9363924)  
  Bernhard Schölkopf, Francesco Locatello, Stefan Bauer, Nan Rosemary Ke, Nal Kalchbrenner, Anirudh Goyal, Yoshua Bengio.
* A Survey of Learning Causality with Data: Problems and Methods, ACM, 2020. [paper](https://arxiv.org/abs/1809.09337)  
  Ruocheng Guo, Lu Cheng, Jundong Li, P. Richard Hahn, Huan Liu.
* 知乎系列 [[1](https://zhuanlan.zhihu.com/p/397796913),[2](https://zhuanlan.zhihu.com/p/397974913),[3](https://zhuanlan.zhihu.com/p/398643910),[4](https://zhuanlan.zhihu.com/p/398938743),[5](https://zhuanlan.zhihu.com/p/399322196)]
* Github tools: 
## Papers
### 2019
1. Counterfactual Story Reasoning and Generation, EMNLP, 2019. [[paper](https://arxiv.org/pdf/1909.04076.pdf), [code](https://github.com/qkaren/Counterfactual-StoryRW)]  
Lianhui Qin, Antoine Bosselut, Ari Holtzman, Chandra Bhagavatula, Elizabeth Clark, Yejin Choi.
    - new task: *Counterfactual Story Rewriting*
    - new dataset: *TIMETRAVEL*
### 2020
1. Counterfactual Generator: A Weakly-Supervised Method for Named Entity Recognition, EMNLP, 2020. [[paper](https://aclanthology.org/2020.emnlp-main.590.pdf), [code](https://github.com/xijiz/cfgen)]  
Xiangji Zeng, Yunliang Li, Yuchen Zhai, Yin Zhang.  
   - task: *Named Entity Recognition* (NER)
   - core idea: intervene on the location entity. counterfactual generator - eliminate spurious correlations, suitable for low-source.
1. Counterfactual Vision and Language Learning, CVPR, 2020. [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Abbasnejad_Counterfactual_Vision_and_Language_Learning_CVPR_2020_paper.pdf)]  
Ehsan Abbasnejad ,Damien Teney ,Amin Parvaneh ,Javen Shi ,Anton van den Hengel
   - task: *Visual Question Answering* (VQA)
   - core: counterfactual training method. Exploit from *multiple modalities* and improves *generalization*
1. Adapting Text Embeddings for Causal Inference, UAI, 2020. [[paper](http://proceedings.mlr.press/v124/veitch20a/veitch20a.pdf), [code](https://github.com/vveitch/causal-text-embeddings-tf2)]  
Victor Veitch, Dhanya Sridhar, David M. Blei.
   - core: supervised dimensionality reduction and bert fine-tune...
### 2021
1. Counterfactual Data Augmentation for Neural Machine Translation, NAACL-HLT, 2021. [[paper](https://aclanthology.org/2021.naacl-main.18.pdf)]  
Qi Liu, Matt J. Kusner, Phil Blunsom
   - task: *Neural machine translation* (NMT)
   - core: generate counterfactual aligned phrases. Interpret translation language model as a Gumbel-Max Structural Causal Model.
1. KACE: Generating Knowledge Aware Contrastive Explanations for Natural Language Inference, ACL, 2021. [[paper](https://aclanthology.org/2021.acl-long.196.pdf)]  
   Qianglong Chen, Feng Ji, Xiangji Zeng, Feng-Lin Li, Ji Zhang, Haiqing Chen, Yin Zhang
   - task: *explanation generation* and *natural language inference* (NLI)
   - core idea: perturbe/intervene and then
1. Sketch and Customize: A Counterfactual Story Generator, AAAI, 2021. [paper](https://arxiv.org/abs/2104.00929)  
  Changying Hao, Liang Pang, Yanyan Lan, Yan Wang, Jiafeng Guo, Xueqi Cheng.
      - task: Counterfactual Story Generation
      - core: two-stage: sketch (uncorrelated background) and customize (counterfactual conditional); human evaluation scores...
1. Causal Effects of Linguistic Properties, NAACL, 2021. [[paper](https://arxiv.org/abs/2010.12919), [code](https://github.com/rpryzant/causal-text)]  
  Reid Pryzant, Dallas Card, Dan Jurafsky, Victor Veitch, Dhanya Sridhar.
   - core: discover causal effects of linguistic properties.
1. Everything Has a Cause: Leveraging Causal Inference in Legal Text Analysis, NAACL, 2021. [[paper](https://arxiv.org/abs/2104.09420) [code](https://github.com/xxxiaol/GCI)]  
  Xiao Liu, Da Yin, Yansong Feng, Yuting Wu, Dongyan Zhao.
1. Counterfactual VQA: A Cause-Effect Look at Language Bias, CVPR, 2020. [[paper](https://arxiv.org/pdf/2006.04315.pdf), [code](https://github.com/yuleiniu/cfvqa)]  
   Yulei Niu, Kaihua Tang, Hanwang Zhang, Zhiwu Lu, Xian-Sheng Hua, Ji-Rong Wen
      - core: subtract the direct effect from the total causal effect.
  
### To-Read-list 
- before
  1. On measurement bias in causal inference, UAI, 2010. [paper](http://ftp.cs.ucla.edu/pub/stat_ser/r357.pdf)  
Judea Pearl
- 2020
  1. Exploring Logically Dependent Multi-task Learning with Causal Inference, EMNLP, 2020. [paper](https://aclanthology.org/2020.emnlp-main.173.pdf)  
  Wenqing Chen ,Jidong Tian ,Liqiang Xiao ,Hao He ,Yaohui Jin.
  
- 2021 
  
  
  
  1. De-Confounded Variational Encoder-Decoder for Logical Table-to-Text Generation,  ACL, 2021. [paper](https://aclanthology.org/2021.acl-long.430.pdf)  
  Wenqing Chen ,Jidong Tian ,Yitian Li ,Hao He ,Yaohui Jin.
  1. Dependent Multi-Task Learning with Causal Intervention for Image Captioning, IJCAI, 2021. [paper](https://www.ijcai.org/proceedings/2021/0312.pdf)  
  Wenqing Chen ,Jidong Tian ,Caoyun Fan ,Hao He ,Yaohui Jin.
 