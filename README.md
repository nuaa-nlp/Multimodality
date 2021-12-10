# Multimodality
Papers, Datasets, Codes about Multimodality

## Paper

### Vision-Language Pre-Training
1. **VLMO: Unified Vision-Language Pre-Training with Mixture-of-Modality-Experts**  *Wenhui Wang, Hangbo Bao, Li Dong, Furu Wei* [[pdf]](https://arxiv.org/pdf/2111.02358.pdf)
2. **Multi-Grained Vision Language Pre-Training: Aligning Texts with Visual Concepts**  *Yan Zeng, Xinsong Zhang, Hang Li* [[pdf]](https://arxiv.org/pdf/2111.08276.pdf)
3. **Masked Autoencoders Are Scalable Vision Learners**  *Kaiming He, Xinlei Chen, Saining Xie, Yanghao Li, Piotr Dollár, Ross Girshick* [[pdf]](https://arxiv.org/pdf/2111.06377.pdf)

### Vision-and-Language Navigation
1. 

### Dialogue-System
1. **Multi-Modal Open-Domain Dialogue**  *Kurt Shuster, Eric Michael Smith, Da Ju, Jason Weston* [[pdf]](https://arxiv.org/pdf/2010.01082.pdf)
2. **Multimodal Dialogue Response Generation**  *Qingfeng Sun, Yujing Wang, Can Xu, Kai Zheng, Yaming Yang, Huang Hu, Fei Xu, Jessica Zhang, Xiubo Geng, Daxin Jiang*  [[pdf]](https://arxiv.org/pdf/2110.08515.pdf)
3. **Reason first, then respond:Modular Generation for Knowledge-infused Dialogue**  *Leonard Adolphs, Kurt Shuster, Jack Urbanek, Arthur Szlam, Jason Weston* [[pdf]](https://arxiv.org/pdf/2111.05204.pdf)

### Prompt
1. **CPT: COLORFUL PROMPT TUNING FOR PRE-TRAINED VISION-LANGUAGE MODELS**  *Yuan Yao, Ao Zhang, Zhengyan Zhang, Zhiyuan Liu, Tat-Seng Chua, Maosong Sun* [[pdf]](https://arxiv.org/pdf/2109.11797.pdf)
2. **Multimodal Few-Shot Learning with Frozen Language Models**  *Maria Tsimpoukelli, Jacob Menick, Serkan Cabi, S. M. Ali Eslami, Oriol Vinyals, Felix Hill* [[pdf]](https://papers.nips.cc/paper/2021/file/01b7575c38dac42f3cfb7d500438b875-Paper.pdf)

### TOP Conference Paper About Multi-Modal Dialog
##### **ACL**
|ID|Paper|Author|Conference|
|-|-|-|-|
|1|[Mind Your Outliers! Investigating the Negative Impact of Outliers on Active Learning for Visual Question Answering](https://arxiv.org/pdf/2107.02331.pdf)|Siddharth Karamcheti, Ranjay Krishna, Li Fei-Fei and Christopher Manning|ACL2021|
|2|[TicketTalk: Toward human-level performance with end-to-end, transaction-based dialog systems](https://arxiv.org/pdf/2012.12458.pdf)|Bill Byrne, Karthik Krishnamoorthi, Saravanan Ganesh and Mihir Kale|ACL2021|
|3|[PhotoChat: A Human-Human Dialogue Dataset With Photo Sharing Behavior For Joint Image-Text Modeling](https://arxiv.org/pdf/2108.01453.pdf)|Xiaoxue Zang, Lijuan Liu, Maria Wang, Yang Song, Hao Zhang and Jindong Chen|ACL2021|
|4|[Maria: A Visual Experience Powered Conversational Agent](https://arxiv.org/pdf/2105.13073.pdf)|Zujie Liang, Huang Hu, Can Xu, Chongyang Tao, Xiubo Geng, Yining Chen, Fan Liang and Daxin Jiang|ACL2021|
|5|[MMGCN: Multimodal Fusion via Deep Graph Convolution Network for Emotion Recognition in Conversation](https://arxiv.org/pdf/2107.06779.pdf)|Jingwen Hu, Yuchen Liu, Jinming Zhao and Qin Jin|ACL2021|
|6|[How do people talk about images?A study on open-domain conversation on images](https://openreview.net/pdf?id=bRVvxrjkLM)|Anonymous ACL submission|-|
|7|[Zero-Shot Visual Grounding of Referring Utterances in Dialogue](https://openreview.net/pdf?id=JcxhaCjSlGz)|Anonymous ACL submission|-|
|8|[When did you become so smart, oh wise one?! Sarcasm Explanation in Multi-modal Multi-party Dialogues](https://openreview.net/pdf?id=eJUGH5CaCJK)|Anonymous ACL submission|-|
|9|[Tackling Situated Multi-Modal Task-Oriented Dialogs with a Single Transformer Model](https://openreview.net/pdf?id=NajekV9uBas)|Anonymous ACL submission|-|
|10|[Co-VQA : Answering by Interactive Sub Question Sequence](https://openreview.net/pdf?id=8s9M2_HIF-j)|Anonymous ACL submission|-|


## Datasets
|ID|NAME|Description|Paper|Conference|
|:---:|:---:|:---:|:---:|:---:|
| 1 | [LAION-40](https://laion.ai/laion-400-open-dataset/) | Multi-Model | | |
| 2 | [IEMOCAP](https://sail.usc.edu/iemocap/) | Multi-Model emotion | [IEMOCAP: interactive emotional dyadic motion capture database. Lang Resources & Evaluation](https://sail.usc.edu/publications/files/bussolre2008.pdf) | |
| 3 | [MELD](https://affective-meld.github.io/) | Multi-Model emotion | [MELD: A Multimodal Multi-Party Dataset for Emotion Recognition in Conversation](https://arxiv.org/pdf/1810.02508.pdf) | |
| 4 | [CH-SIMS](https://drive.google.com/drive/folders/1E5kojBirtd5VbfHsFp6FYWkQunk73Nsv) | Multi-Model emotion | [CH-SIMS: A Chinese Multimodal Sentiment Analysis Dataset with Fine-grained Annotations of Modality](https://aclanthology.org/2020.acl-main.343.pdf) | |
| 5 | [SEMAINE](https://semaine-db.eu/DailyDialog) | Multi-Model emotion | [The SEMAINE Database: Annotated Multimodal Records of Emotionally Colored Conversations between a Person and a Limited Agent](https://ieeexplore.ieee.org/abstract/document/5959155) | |
| 6 | [COCO](https://cocodataset.org/#download) | Multi-Model Retrieval| [Microsoft COCO Captions Data Collection and Evaluation Server](https://arxiv.org/pdf/1504.00325.pdf) | |
| 7 | [IAPR TC-12](https://www.imageclef.org/photodata) | Multi-Model Retrieval | [The IAPR Benchmark: A New Evaluation Resource for Visual Information Systems](https://www.cs.brandeis.edu/~marc/misc/proceedings/lrec-2006/workshops/W02/RealFinalOntoImage2006-2.pdf#page=13) | LREC |
| 8 | [Conceptual Captions Dataset](https://github.com/google-research-datasets/conceptual-captions) | Multi-Model Retrieval | [Conceptual captions: A cleaned, hypernymed, image alt-text dataset for automatic image captioning](https://aclanthology.org/P18-1238.pdf) | |
| 9 | [OpenViDial](https://github.com/ShannonAI/OpenViDial) | Multi-Model Dialogue| [OpenViDial: A Large-Scale, Open-Domain Dialogue Dataset with Visual Contexts](https://arxiv.org/pdf/2012.15015.pdf) | |



## Codes

