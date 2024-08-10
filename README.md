# Noisy-Correspondence Learning Summary (Updating)
A new research **direction** of label noise learning. Noisy correspondence learning aims to eliminate the negative impact of the mismatched pairs (e.g., false positives/negatives) instead of annotation errors in several tasks.

We mark works contributed by ourselves with ⭐.

*This repository now is maintained by [Mouxing Yang](https://mouxingyang.github.io/), [Yijie Lin](https://lin-yijie.github.io/), and [Yang Qin](https://qinyang-cs.github.io/). We hope more AI-workers join us and thank [all contributors](https://github.com/QinYang79/Noisy-Correspondence-Summary/graphs/contributors)!*  
## Tasks

|||
|-|-|
|  [Image-Text Matching/Retrieval](#image-text-matchingretrieval)   |  [Vision-Language Pre-training](#vision-language-pre-training) |
|  [Re-identification](#re-identification)                          |  [Video-Text Learning](#video-text-learning)                   |
|  [Image Captioning](#image-captioning)                            |  [Image Contrastive Learning](#image-contrastive-learning)     |
|  [Graph Matching ](#graph-matching)                               |  [Visual-Audio Learning](#visual-audio-learning)               |
|  [Machine Reading Comprehension](#machine-reading-comprehension)  |  [Dense Retrieval](#dense-retrieval)                           |
|  [Multi-View Clustering](#multi-view-clustering)                  |    |
|||
 
 
## Image-Text Matching/Retrieval

#### 2024

- `[2024 ACMMM]` **$\text{PC}^2$: Pseudo-Classification Based Pseudo-Captioning for Noisy Correspondence Learning in Cross-Modal Retrieval**  
*Yue Duan, Zhangxuan Gu, Zhenzhe Ying, Lei Qi, Changhua Meng, Yinghuan Shi*   
[[paper]](https://arxiv.org/abs/2408.01349)
[[code]](https://github.com/alipay/PC2-NoiseofWeb)


- `[2024 SIGIR]` **UGNCL: Uncertainty-Guided Noisy Correspondence Learning for Efficient Cross-Modal Matching**  
*Quanxing Zha, Xin Liu, Yiu-ming Cheung, Xing Xu, Nannan Wang, Jianjia Cao*   
[[paper]](https://dl.acm.org/doi/abs/10.1145/3626772.3657806)
[[code]](https://github.com/qxzha/UGNCL)


- `[2024 IJCV]` **⭐Learning with Noisy Correspondence**  
*Zhenyu Huang, Peng Hu, Guocheng Niu, Xinyan Xiao, Jiancheng Lv, Xi Peng*   
[[paper]](https://link.springer.com/article/10.1007/s11263-024-02064-0)

- `[2024 TOIS]` **Breaking Through the Noisy Correspondence: A Robust Model for Image-Text Matching**   
*Haitao Shi, Meng Liu, Xiaoxuan Mu, Xuemeng Song, Yupeng Hu, Liqiang Nie*  
[[paper]](https://dl.acm.org/doi/abs/10.1145/3662732) 

- `[2024 ICASSP]` **NAC: Mitigating Noisy Correspondence in Cross-Modal Matching Via Neighbor Auxiliary Corrector**  
*Yuqing Li, Haoming Huang, Jian Xu, Shao-Lun Huang*  
[[paper]](https://ieeexplore.ieee.org/abstract/document/10448059) 


- `[2024 CVPR]` **Robust Noisy Correspondence Learning with Equivariant Similarity Consistency**  
*Yuchen Yang, Likai Wang, Erkun Yang, Cheng Deng*  
[[paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Yang_Robust_Noisy_Correspondence_Learning_with_Equivariant_Similarity_Consistency_CVPR_2024_paper.pdf)


- `[2024 CVPR]` **Mitigating Noisy Correspondence by Geometrical Structure Consistency Learning**  
*Zihua Zhao, Mengxi Chen, Tianjie Dai, Jiangchao Yao, Bo han, Ya Zhang, Yanfeng Wang*    
[[paper]](https://arxiv.org/abs/2405.16996)
[[code]](https://github.com/MediaBrain-SJTU/GSC)

- `[2024 CVPR]` **Learning to Rematch Mismatched Pairs for Robust Cross-Modal Retrieval**  
*Haochen Han, Qinghua Zheng, Guang Dai, Minnan Luo, Jingdong Wang*  
[[paper]](https://arxiv.org/html/2403.05105v1)
[[code]](https://github.com/hhc1997/L2RM)

- `[2024 CVPR]` **Mitigating Noisy Correspondence by Geometrical Structure Consistency Learning**  
*Zihua Zhao, Mengxi Chen, Tianjie Dai, Jiangchao Yao, Bo Han, Ya Zhang, Yanfeng Wang*   
[[paper]](https://cvpr.thecvf.com/Conferences/2024/AcceptedPapers)

- `[2024 CVPR]` **Robust Noisy Correspondence Learning with Equivariant Similarity Consistency**  
*Yuchen Yang, Erkun Yang, Likai Wang, Cheng Deng*  
 [[paper]](https://cvpr.thecvf.com/Conferences/2024/AcceptedPapers)

- `[2024 Arxiv]` **REPAIR: Rank Correlation and Noisy Pair Half-replacing with Memory for Noisy Correspondence**  
*Ruochen Zheng, Jiahao Hong, Changxin Gao, Nong Sang*  
[[paper]](https://arxiv.org/abs/2403.08224) 

- `[2024 TIP]` **⭐Cross-modal Retrieval with Noisy Correspondence via Consistency Refining and Mining**  
*Xinran Ma, Mouxing Yang, Yunfan Li, Peng Hu, Jiancheng Lv, Xi Peng*  
[[paper]](http://pengxi.me/wp-content/uploads/2024/03/Cross-modal-Retrieval-with-Noisy-Correspondence-via-Consistency-Refining-and-Mining.pdf)
[[code]](https://github.com/XLearning-SCU/2024-TIP-CREAM)

- `[2024 AAAI]` **Noisy Correspondence Learning with Self-Reinforcing Errors Mitigation**  
*Zhuohang Dang, Minnan Luo, Chengyou Jia, Guang Dai, Xiaojun Chang, Jingdong Wang*  
[[paper]](https://arxiv.org/pdf/2312.16478.pdf)

- `[2024 AAAI]` **Negative Pre-aware for Noisy Cross-modal Matching**  
*Xu Zhang, Hao Li, Mang Ye*  
[[paper]](https://arxiv.org/pdf/2312.05777.pdf)
[[code]](https://github.com/ZhangXu0963/NPC)

#### 2023

- `[2023 NeurIPS]` **⭐Cross-modal Active Complementary Learning with Self-refining Correspondence**  
*Yang Qin and Yuan Sun and Dezhong Peng and Joey Tianyi Zhou and Xi Peng and Peng Hu*  
[[paper]](https://openreview.net/pdf?id=UBBeUjTja8)
[[code]](https://github.com/QinYang79/CRCL)

- `[2023 TPAMI]` **⭐Cross-Modal Retrieval with Partially Mismatched Pairs**  
*Peng Hu, Zhenyu Huang, Dezhong Peng, Xu Wang, Xi Peng*  
[[paper]](http://pengxi.me/wp-content/uploads/2023/03/Cross-Modal_Retrieval_with_Partially_Mismatched_Pairs.pdf)
[[code]](https://github.com/penghu-cs/RCL)

- `[2023 TMM]` **Integrating Language Guidance Into Image-Text Matching for Correcting False Negatives**  
*Zheng Li, Caili Guo, IEEE, Zerun Feng, Jenq-Neng Hwang, Zhongtian Du*  
[[paper]](https://ieeexplore.ieee.org/abstract/document/10081045)

- `[2023 TMM]` **Learning From Noisy Correspondence With Tri-Partition for Cross-Modal Matching**  
*Feng, Zerun and Zeng, Zhimin and Guo, Caili and Li, Zheng and Hu, Lin*  
[[paper]](https://ieeexplore.ieee.org/abstract/document/10258402)

- `[2023 CVPR]` **BiCro: Noisy Correspondence Rectification for Multi-modality Data via Bi-directional Cross-modal Similarity Consistency**  
*Shuo Yang, Zhapan XU, Kai Wang, Yang You, Hongxun Yao, Tongliang Liu, Min Xu*  
[[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Yang_BiCro_Noisy_Correspondence_Rectification_for_Multi-Modality_Data_via_Bi-Directional_Cross-Modal_CVPR_2023_paper.html)
[[code]](https://github.com/xu5zhao/BiCro)


- `[2023 CVPR]` **MSCN: Noisy Correspondence Learning with Meta Similarity Correction**  
*Han, Haochen and Miao, Kaiyao and Zheng, Qinghua and Luo, Minnan*  
[[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Han_Noisy_Correspondence_Learning_With_Meta_Similarity_Correction_CVPR_2023_paper.html)
[[code]](https://github.com/hhc1997/MSCN)

#### 2022

- `[2022 ACMMM]` **⭐Deep Evidential Learning with Noisy Correspondence for Cross-Modal Retrieval**  
*Qin, Yang and Peng, Dezhong and Peng, Xi and Wang, Xu and Hu, Peng*  
[[paper]](https://dl.acm.org/doi/abs/10.1145/3503161.3547922)
[[code]](https://github.com/QinYang79/DECL)

#### 2021
- `[2021 NeurIPS Oral]` **⭐Learning with Noisy Correspondence for Cross-modal Matching**  
*Huang, Zhenyu and Niu, Guocheng and Liu, Xiao and Ding, Wenbiao and Xiao, Xinyan and Wu, Hua and Peng, Xi*  
[[paper]](https://proceedings.neurips.cc/paper/2021/file/f5e62af885293cf4d511ceef31e61c80-Paper.pdf)
[[code]](https://github.com/XLearning-SCU/2021-NeurIPS-NCR)

##  Vision-Language Pre-training
- `[2023 AAAI]` **NLIP: Noise-Robust Language-Image Pre-training**   
*Runhui Huang, Yanxin Long, Jianhua Han, Hang Xu, Xiwen Liang, Chunjing Xu, Xiaodan Liang*  
[[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25172)

- `[2022 CVPR]` **Robust Cross-Modal Representation Learning with Progressive Self-Distillation** 
*Andonian, Alex and Chen, Shixing and Hamid, Raffay*  
[[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Andonian_Robust_Cross-Modal_Representation_Learning_With_Progressive_Self-Distillation_CVPR_2022_paper.pdf)

- `[2022 ICML]` **Blip: Bootstrapping Language-image Pre-training for Unified Vision-language Understanding and Generation**  
Li, Junnan and Li, Dongxu and Xiong, Caiming and Hoi, Steven*  
[[paper]](https://proceedings.mlr.press/v162/li22n/li22n.pdf)
[[code]](https://github.com/salesforce/BLIP)

- `[2021 NeurIPS Spotlight]` **Align before Fuse: Vision and Language Representation Learning with Momentum Distillation**  
*Junnan Li, Ramprasaath Selvaraju, Akhilesh Gotmare, Shafiq Joty, Caiming Xiong, Steven Chu Hong Hoi*  
[[paper]](https://proceedings.neurips.cc/paper_files/paper/2021/file/505259756244493872b7709a8a01b536-Paper.pdf)
[[code]](https://github.com/salesforce/ALBEF)

## Re-identification

- `[2024 CVPR]` **⭐Noisy-Correspondence Learning for Text-to-Image Person Re-identification**  
*Qin, Yang and Chen, Yingke and Peng, Dezhong and Peng, Xi and Zhou, Joey Tianyi and Hu, Peng*  
[[paper]](https://arxiv.org/abs/2308.09911)
[[code]](https://github.com/QinYang79/RDE)


- `[2024 IJCV]` **⭐Robust Object Re-identification with Coupled Noisy Labels**  
*Mouxing Yang, Zhenyu Huang, Xi Peng*  
[[paper]](https://pengxi.me/wp-content/uploads/2024/01/Manuscript.pdf)
[[code]](https://github.com/XLearning-SCU/2024-IJCV-LCNL)


- `[2024 EAAI]` **Modality Blur and Batch Alignment Learning for Twin Noisy Labels-based Visible–infrared Person Re-identification**  
*Song Wu, Shihao Shan, Guoqiang Xiao, Michael S. Lew, Xinbo Gao*  
[[paper]](https://www.sciencedirect.com/science/article/pii/S0952197624001489)
[[code]]( https://github.com/SWU-CS-MediaLab/MBBA)

- `[2022 CVPR]` **⭐Learning With Twin Noisy Labels for Visible-Infrared Person Re-Identification**  
*Mouxing Yang, Zhenyu Huang, Peng Hu, Taihao Li, Jiancheng Lv, Xi Peng*  
[[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_Learning_With_Twin_Noisy_Labels_for_Visible-Infrared_Person_Re-Identification_CVPR_2022_paper.pdf)
[[code]](https://github.com/XLearning-SCU/2022-CVPR-DART)



## Video-Text Learning


- `[2024 ICLR Oral]` **⭐Multi-granularity Correspondence Learning from Long-term Noisy Videos**  
*Yijie Lin, Jie Zhang, Zhenyu Huang, Jia Liu, Zujie Wen, Xi Peng*  
[[paper]](https://lin-yijie.github.io/projects/Norton/)
[[code]](https://github.com/XLearning-SCU/2024-ICLR-Norton)

- `[2024 Arxiv]` **A Strong Baseline for Temporal Video-Text Alignment**  
*Li, Zeqian and Chen, Qirui and Han, Tengda and Zhang, Ya and Wang, Yanfeng and Xie, Weidi*  
[[paper]](https://arxiv.org/pdf/2312.14055.pdf)

- `[2023 TMM]` **Robust Video-Text Retrieval Via Noisy Pair Calibration**  
*Zhang, Huaiwen and Yang, Yang and Qi, Fan and Qian, Shengsheng and Xu, Changsheng*  
[[paper]](https://ieeexplore.ieee.org/abstract/document/10024790) 

- `[2021 ICCV]` **Crossclr: Cross-modal Contrastive Learning for Multi-modal Video Representations**  
  *Zolfaghari, Mohammadreza and Zhu, Yi and Gehler, Peter and Brox, Thomas*  
  [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Zolfaghari_CrossCLR_Cross-Modal_Contrastive_Learning_for_Multi-Modal_Video_Representations_ICCV_2021_paper.pdf)

- `[2022 CVPR Oral]` **Temporal Alignment Networks for Long-term Video**  
*Han, Tengda and Xie, Weidi and Zisserman, Andrew*  
[[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Han_Temporal_Alignment_Networks_for_Long-Term_Video_CVPR_2022_paper.pdf)
[[code]](https://www.robots.ox.ac.uk/~vgg/research/tan/)

- `[2021 EMNLP]` **Videoclip: Contrastive Pre-training for Zero-shot Video-text Understanding**
*Xu, Hu and Ghosh, Gargi and Huang, Po-Yao and Okhonko, Dmytro and Aghajanyan, Armen and Metze, Florian and Zettlemoyer, Luke and Feichtenhofer, Christoph*  
[[paper]](https://arxiv.org/pdf/2109.14084.pdf)
[[code]](https://github.com/facebookresearch/fairseq/tree/main/examples/MMPT)

## Image Captioning

- `[2024 AAAI]` **Noise-Aware Image Captioning with Progressively Exploring Mismatched Words** 
*Zhongtian Fu, Kefei Song, Luping Zhou, Yang Yang*  
[[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29097)
[[code]](https://github.com/njustkmg/NIC)

- `[2022 CVPR]` **Noise-aware Learning from Web-crawled Image-Text Data for Image Captioning**  
*Wooyoung Kang, Jonghwan Mun, Sungjun Lee, Byungseok Roh*  
[[paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Kang_Noise-Aware_Learning_from_Web-Crawled_Image-Text_Data_for_Image_Captioning_ICCV_2023_paper.pdf)
[[code]](https://github.com/kakaobrain/noc)

## Image Contrastive Learning

- `[2022 CVPR]` **Robust contrastive learning against noisy views**  
*Ching-Yao Chuang, R Devon Hjelm, Xin Wang, Vibhav Vineet, Neel Joshi, Antonio Torralba, Stefanie Jegelka, Yale Song*  
[[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Chuang_Robust_Contrastive_Learning_Against_Noisy_Views_CVPR_2022_paper.pdf)
[[code]](https://github.com/chingyaoc/RINCE)

## Graph Matching 

- `[2024 TIP]` **⭐Cross-modal Retrieval with Noisy Correspondence via Consistency Refining and Mining**  
*Xinran Ma, Mouxing Yang, Yunfan Li, Peng Hu, Jiancheng Lv, Xi Peng*  
[[paper]](http://pengxi.me/wp-content/uploads/2024/03/Cross-modal-Retrieval-with-Noisy-Correspondence-via-Consistency-Refining-and-Mining.pdf)
[[code]](https://github.com/XLearning-SCU/2024-TIP-CREAM)
- `[2023 ICCV]` **⭐Graph Matching with Noisy Correspondence**  
*Lin, Yijie and Yang, Mouxing and Yu, Jun and Hu, Peng and Zhang, Changqing and Peng, Xi*  
[[paper]](https://arxiv.org/pdf/2212.04085.pdf)
[[code]](https://github.com/Lin-Yijie/Graph-Matching-Networks)

## Visual-Audio Learning

- `[2024 TMM]` **Noise-Tolerant Learning for Audio-Visual Action Recognition**  
*Haochen Han, Qinghua Zheng, Minnan Luo, Kaiyao Miao, Feng Tian and Yan Chen*  
[[paper]](https://arxiv.org/pdf/2205.07611)

## Machine Reading Comprehension

- `[2023 AAAI]` **⭐Robust domain adaptation for machine reading comprehension**  
*Jiang, Liang and Huang, Zhenyu and Liu, Jia and Wen, Zujie and Peng, Xi*  
[[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25974)


## Dense Retrieval

- `[2023 EMNLP Findings]` **Noisy Pair Corrector for Dense Retrieval**  
*Hang Zhang, Yeyun Gong, Xingwei He, Dayiheng Liu, Daya Guo, Jiancheng Lv, Jian Guo*  
[[paper]](https://arxiv.org/pdf/2311.03798.pdf)


## Multi-View Clustering 

- `[2024 TKDE]` **⭐Robust Multi-View Clustering with Noisy Correspondence**  
*Yuan Sun, Yang Qin, Yongxiang Li, Dezhong Peng, Xi Peng, Peng Hu*  
 
- `[2024 AAAI]` **⭐Decoupled Contrastive Multi-view Clustering with High-order Random Walks**  
*Yiding Lu, Yijie Lin, Mouxing Yang, Dezhong Peng, Peng Hu, Xi Peng*  
[[paper]](http://pengxi.me/wp-content/uploads/2024/02/Decoupled_Contrastive_Multi_View_Clustering_with_High_Order_Random_Walks.pdf)
[[code]](https://github.com/XLearning-SCU/2024-AAAI-DIVIDE)

- `[2022 TPAMI]` **⭐Robust Multi-View Clustering With Incomplete Information**  
*Mouxing Yang, Yunfan Li, Peng Hu, Jinfeng Bai, Jiancheng Lv, Xi Peng*  
[[paper]](https://ieeexplore.ieee.org/abstract/document/9723577)
[[code]](https://github.com/XLearning-SCU/2022-TPAMI-SURE)

- `[2021 CVPR]` **⭐Partially View-aligned Representation Learning with Noise-robust Contrastive Loss**   
*Mouxing Yang, Yunfan Li, Zhenyu Huang, Zitao Liu, Peng Hu, Xi Peng*  
[[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Partially_View-Aligned_Representation_Learning_With_Noise-Robust_Contrastive_Loss_CVPR_2021_paper.pdf)
[[code]](https://github.com/XLearning-SCU/2021-CVPR-MvCLN)

- `[2020 NeurIPS Oral]` **⭐Partially View-aligned Clustering**  
*Zhenyu Huang, Peng Hu, Joey Tianyi Zhou, Jiancheng Lv, and Xi Peng*  
[[paper]](https://proceedings.neurips.cc/paper/2020/file/1e591403ff232de0f0f139ac51d99295-Paper.pdf)
[[code]](https://github.com/XLearning-SCU/2020-NIPS-PVC)
