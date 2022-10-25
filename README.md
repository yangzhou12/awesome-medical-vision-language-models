[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<!-- <hr /> -->

# <p align=center>`Awesome Medical Vison-Language Models`</p>

A curated list of awesome resources in medical vision-language models (**in chronological order**), inspired by the other awesome-initiatives. 

[An awesome list](https://github.com/zhjohnchan/awesome-vision-and-language-pretraining) on general vision-language pre-training.

<!-- We intend to regularly update the relevant latest papers and their open-source implementations on this page. If you find some overlooked papers, please open an issue or contact at fahad.shamshad3@gmail.com. -->

## Overview
- [Survey Papers](#survey)
- [Medical Vision-Language Pre-Training](#medical-vision-language-pre-training)
- [Vision-Language Models for Healthcare](#vision-language-models-for-healthcare)
    - [Classification](#classification)
    - [Medical Vision Question Answering](#classification)
    - [Medical Object Locolization and Anomaly Detection](#classification)
    - [Medical Image Segmentation](#classification)
    - [Medical Report Generation](#classification)
- [Explaination, Bias, Noise, and Robustness](#explaination-bias-noise-and-robustness)
- [Datasets](#datasets)
<!-- - [General Vision-Language Models](#general-vision-language-models) -->
<!-- - [Medical Image Reconstruction](#reconstruction) -->

# Survey

**Deep Multi-modal Fusion of Image and Non-image Data in Disease Diagnosis and Prognosis: A Review.** [Mar., 2022].<br>
*Can Cui, Haichun Yang, Yaohong Wang, Shilin Zhao, Zuhayr Asad, Lori A. Coburn, Keith T. Wilson, Bennett A. Landman, Yuankai Huo.*<br>
[[PDF](https://arxiv.org/abs/2203.15588)] 

**Beyond Medical Imaging: A Review of Multimodal Deep Learning in Radiology.** [Apr., 2022].<br>
*Lars HeiligerLars Heiliger, Anjany Sekuboyina, Bjoern Menze, Jan EggerJan Egger, Jens Kleesiek.*<br>
[[PDF](https://www.researchgate.net/profile/Jan-Egger-2/publication/358581125_Beyond_Medical_Imaging_A_Review_of_Multimodal_Deep_Learning_in_Radiology/links/620a1e5a7b05f82592ea5bda/Beyond-Medical-Imaging-A-Review-of-Multimodal-Deep-Learning-in-Radiology.pdf)] 

# Medical Vision-Language Pre-Training

  **Self-supervised Image-text Pre-training With Mixed Data In Chest X-rays.** [Mar., 2021].<br>
*Xiaosong Wang, Ziyue Xu, Leo Tam, Dong Yang, Daguang Xu.*<br>
 [[PDF](https://arxiv.org/pdf/2103.16022)] 

  **Multi-modal Understanding and Generation for Medical Images and Text via Vision-Language Pre-Training.** [May, 2021] [JBHI, 2022].<br>
*Jong Hak Moon, Hyungyung Lee, Woncheol Shin, Young-Hak Kim, Edward Choi.*<br>
 [[PDF](https://arxiv.org/abs/2105.11333)] [[Github](https://github.com/SuperSupermoon/MedViLL)]
 
  **Generalized radiograph representation learning via cross-supervision between images and free-text radiology reports.** [Oct., 2021] [Nature Machine Learning 2022].<br>
*Hong-Yu Zhou, Xiaoyu Chen, Yinghao Zhang, Ruibang Luo, Liansheng Wang, Yizhou Yu.*<br>
 [[PDF](https://www.nature.com/articles/s42256-021-00425-9)] [[Github](https://github.com/funnyzhou/refers)]

  **Clinical-BERT: Vision-Language Pre-training for Radiograph Diagnosis and Reports Generation.** [Jun., 2022] [AAAI, 2022].<br>
*Bin Yan, Mingtao Pei.*<br>
 [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/20204)] 

  **Vision-Language Pretraining Enables Radiographs and Reports to be Learned without Curation.** [Aug., 2022].<br>
*Sangjoon Park, Eun Sun Lee, Jeong Eun Lee, Jong Chul Ye.*<br>
 [[PDF](https://arxiv.org/abs/2208.05140)]
 
  **Multi-Modal Masked Autoencoders for Medical Vision-and-Language Pre-Training.** [Sep., 2022] [MICAI, 2022].<br>
*Zhihong Chen, Yuhao Du, Jinpeng Hu, Yang Liu, Guanbin Li, Xiang Wan, Tsung-Hui Chang.*<br>
 [[PDF](https://arxiv.org/abs/2209.07098)] [[Github](https://github.com/zhjohnchan/M3AE)]
 
  **Align, Reason and Learn: Enhancing Medical Vision-and-Language Pre-training with Knowledge.** [Sep., 2022] [ACM MM, 2022].<br>
*Zhihong Chen, Guanbin Li, Xiang Wan.*<br>
 [[PDF](https://arxiv.org/abs/2209.07118)] [[Github](https://github.com/zhjohnchan/ARL)]
 
  **Medical Image Understanding with Pretrained Vision Language Models: A Comprehensive Study.** [Sep., 2022].<br>
*Ziyuan Qin, Huahui Yi, Qicheng Lao, Kang Li.*<br>
 [[PDF](https://arxiv.org/abs/2209.15517)]
 
  **Expert-level detection of pathologies from unannotated chest X-ray images via self-supervised learning.** [Sep., 2022] [Nature Biomedical Engineering, 2022].<br>
*Ekin Tiu, Ellie Talius, Pujan Patel, Curtis P. Langlotz, Andrew Y. Ng, Pranav Rajpurkar.*<br>
 [[PDF](https://www.nature.com/articles/s41551-022-00936-9)] [[Github](https://github.com/rajpurkarlab/CheXzero)]
 
  **Multi-Granularity Cross-modal Alignment for Generalized Medical Visual Representation Learning.** [Oct., 2022] [NeurIPS, 2022].<br>
*Fuying Wang, Yuyin Zhou, Shujun Wang, Varut Vardhanabhuti, Lequan Yu.*<br>
 [[PDF](https://arxiv.org/abs/2210.06044)] [[Github](https://github.com/fuying-wang/MGCA)]

# Vision-Language Models for Healthcare

## Classification

   **Joint Modeling of Chest Radiographs and Radiology Reports for Pulmonary Edema Assessment.** [Aug., 2020] [MICCAI, 2020].<br>
*Geeticka Chauhan, Ruizhi Liao, William Wells, Jacob Andreas, Xin Wang, Seth Berkowitz, Steven Horng, Peter Szolovits, Polina Golland.*<br>
 [[PDF](https://arxiv.org/abs/2008.09884)] [[Github](https://github.com/RayRuizhiLiao/joint_chestxray)]  

   **BERTHop: An Effective Vision-and-Language Model for Chest X-ray Disease Diagnosis.** [Aug., 2021] [ICCV Workshop, 2021].<br>
*Masoud Monajatipoor, Mozhdeh Rouhsedaghat, Liunian Harold Li, Aichi Chien, C.-C. Jay Kuo, Fabien Scalzo, Kai-Wei Chang.*<br>
 [[PDF](https://arxiv.org/abs/2108.04938)] 
 
   **Improving Joint Learning of Chest X-Ray and Radiology Report by Word Region Alignment.** [Sep., 2021] [MLMI, 2021].<br>
*Zhanghexuan Ji, Mohammad Abuzar Shaikh, Dana Moukheiber, Sargur N Srihari, Yifan Peng, Mingchen Gao.*<br>
 [[PDF](https://doi.org/10.1007/978-3-030-87589-3_12)] [[Github](https://github.com/mshaikh2/JoImTeR_MLMI_2021)]  
 
   **GLoRIA: A Multimodal Global-Local Representation Learning Framework for Label-efficient Medical Image Recognition.** [Oct., 2021] [ICCV, 2021].<br>
*Masoud Monajatipoor, Mozhdeh Rouhsedaghat, Liunian Harold Li, Aichi Chien, C.-C. Jay Kuo, Fabien Scalzo, Kai-Wei Chang.*<br>
 [[PDF](https://doi.org/10.1109/ICCV48922.2021.00391)] [[Github](https://github.com/marshuang80/gloria)]  
 
   **ContIG: Self-supervised Multimodal Contrastive Learning for Medical Imaging with Genetics.** [Nov., 2021] [CVPR, 2022].<br>
*Masoud Monajatipoor, Mozhdeh Rouhsedaghat, Liunian Harold Li, Aichi Chien, C.-C. Jay Kuo, Fabien Scalzo, Kai-Wei Chang.*<br>
 [[PDF](https://arxiv.org/abs/2111.13424)] [[Github](https://github.com/HealthML/ContIG)] 

   **Breaking with Fixed Set Pathology Recognition through Report-Guided Contrastive Training.** [May, 2022] [MICAI, 2022].<br>
*Constantin Seibold, Simon Reiß, M. Saquib Sarfraz, Rainer Stiefelhagen, Jens Kleesiek.*<br>
 [[PDF](https://arxiv.org/abs/2205.07139)] [[Github](https://github.com/batmanlab/AGXNet)] 

   **RadTex: Learning Efficient Radiograph Representations from Text Reports.** [Aug., 2022] [MICAI Workshop, 2022].<br>
*Keegan Quigley, Miriam Cha, Ruizhi Liao, Geeticka Chauhan, Steven Horng, Seth Berkowitz, Polina Golland.*<br>
 [[PDF](https://arxiv.org/abs/2208.03218)] 

   **MedCLIP: Contrastive Learning from Unpaired Medical Images and Text.** [Oct., 2022] [EMNLP, 2022].<br>
*Zifeng Wang, Zhenbang Wu, Dinesh Agarwal, Jimeng Sun.*<br>
 [[PDF](https://arxiv.org/abs/2210.10163)]

## Medical Vision Question Answering

   **A Comparison of Pre-trained Vision-and-Language Models for Multimodal Representation Learning across Medical Images and Reports.** [Sep., 2020] [BIBM, 2020].<br>
*Yikuan Li, Hanyin Wang, Yuan Luo.*<br>
 [[PDF](https://arxiv.org/abs/2009.01523)] [[Github](https://github.com/YIKUAN8/Transformers-VQA)]
 
  **MMBERT: Multimodal BERT Pretraining for Improved Medical VQA.** (Short Paper) [Apr., 2021].<br>
*Yash Khare, Viraj Bagal, Minesh Mathew, Adithi Devi, U Deva Priyakumar, CV Jawahar.*<br>
 [[PDF](https://arxiv.org/abs/2104.01394)] [[Github](https://github.com/VirajBagal/MMBERT)]
 
   **MuVAM: A Multi-View Attention-based Model for Medical Visual Question Answering.** [Jul., 2021].<br>
*Haiwei Pan, Shuning He, Kejia Zhang, Bo Qu, Chunling Chen, Kun Shi.*<br>
 [[PDF](https://arxiv.org/abs/2107.03216)] 
 
   **Vision-Language Transformer for Interpretable Pathology Visual Question Answering.** [Mar., 2022] [JBHI, 2022].<br>
*Usman Naseem, Matloob Khushi, Jinman Kim.*<br>
 [[PDF](https://doi.org/10.1109/JBHI.2022.3163751)] 
 
   **AMAM: An Attention-based Multimodal Alignment Model for Medical Visual Question Answering.** [Sep., 2022] [KBS, 2022].<br>
*Haiwei Pan, Shuning He, Kejia Zhang, Bo Qu, Chunling Chen, Kun Shi.*<br>
 [[PDF](https://doi.org/10.1016/j.knosys.2022.109763)] 
 
   **Medical visual question answering based on question-type reasoning and semantic space constraint.** [Sep., 2022] [ARTMED, 2022].<br>
*Meiling Wang, Xiaohai He, Luping Liu, Linbo Qing, Honggang Chen, Yan Liu, Chao Ren.*<br>
 [[PDF](https://doi.org/10.1016/j.artmed.2022.102346)] 
 
   **A Bi-level representation learning model for medical visual question answering.** [Oct., 2022] [JBI, 2022].<br>
*Yong Li, Shaopei Long, Zhenguo Yang, Heng Weng, Kun Zeng, Zhenhua Huang, FuLee Wang, Tianyong Hao.*<br>
 [[PDF](https://doi.org/10.1016/j.jbi.2022.104183)] 

   **Caption-Aware Medical VQA via Semantic Focusing and Progressive Cross-Modality Comprehension.** [Oct., 2022] [ACM MM, 2022].<br>
*Fuze Cong, Shibiao Xu, Li Guo, Yinbing Tian.*<br>
 [[PDF](https://dl.acm.org/doi/abs/10.1145/3503161.3548122)] 
 
   **A Dual-Attention Learning Network with Word and Sentence Embedding for Medical Visual Question Answering.** [Oct., 2022].<br>
*Xiaofei Huang, Hongfang Gong.*<br>
 [[PDF](https://arxiv.org/abs/2210.00220)] 

## Medical Object Locolization and Anomaly Detection

   **Weakly supervised one-stage vision and language disease detection using large scale pneumonia and pneumothorax studies.** [Jul., 2020] [MICAI, 2020].<br>
*Leo K. Tam, Xiaosong Wang, Evrim Turkbey, Kevin Lu, Yuhong Wen, Daguang Xu.*<br>
 [[PDF](https://arxiv.org/abs/2007.15778)] 
 
   **Anatomy-Guided Weakly-Supervised Abnormality Localization in Chest X-rays.** [Jun., 2022] [MICAI, 2022].<br>
*Ke Yu, Shantanu Ghosh, Zhexiong Liu, Christopher Deible, Kayhan Batmanghelich.*<br>
 [[PDF](https://arxiv.org/abs/2206.12704)] [[Github](https://github.com/batmanlab/AGXNet)] 

   **Joint Learning of Localized Representations from Medical Images and Reports.** [Aug., 2022] [ECCV, 2022].<br>
*Philip Müller, Georgios Kaissis, Congyu Zou, Daniel Rueckert.*<br>
 [[PDF](https://arxiv.org/abs/2112.02889)] [[Github](https://github.com/philip-mueller/lovt)] 

   **Radiological Reports Improve Pre-training for Localized Imaging Tasks on Chest X-Rays.** [Sep., 2022] [MICAI, 2022].<br>
*Philip Müller, Georgios Kaissis, Congyu Zou, Daniel Rueckert.*<br>
 [[PDF](https://doi.org/10.1007/978-3-031-16443-9_62)]
 
   **Adapting Pretrained Vision-Language Foundational Models to Medical Imaging Domains.** [Oct., 2022].<br>
*Pierre Chambon, Christian Bluethgen, Curtis P. Langlotz, Akshay Chaudhari.*<br>
 [[PDF](https://arxiv.org/abs/2210.04133)] 

## Medical Image Segmentation

   **Making the Most of Text Semantics to Improve Biomedical Vision-Language Processing.** [Apr., 2022] [ECCV 2022].<br>
*Benedikt Boecking, Naoto Usuyama, Shruthi Bannur, Daniel C. Castro, Anton Schwaighofer, Stephanie Hyland, Maria Wetscherek, Tristan Naumann, Aditya Nori, Javier Alvarez-Valle, Hoifung Poon, Ozan Oktay.*<br>
 [[PDF](https://arxiv.org/abs/2204.09817)] [[Toolbox](https://hi-ml.readthedocs.io/en/latest/multimodal.html)] [[Dataset](https://www.physionet.org/content/ms-cxr/0.1/)]

   **LViT: Language meets Vision Transformer in Medical Image Segmentation.** [Jun., 2022].<br>
*Zihan Li, Yunxiang Li, Qingde Li, Puyang Wang, You Zhang, Dazhou Guo, Le Lu, Dakai Jin, Qingqi Hong.*<br>
 [[PDF](https://arxiv.org/abs/2206.14718)] [[Github](https://github.com/HUANGLIZI/LViT)]

## Medical Report Generation

   **Generating Radiology Reports via Memory-driven Transformer.** [Oct., 2020] [EMNLP, 2020].<br>
*Zhihong Chen, Yan Song, Tsung-Hui Chang, Xiang Wan.*<br>
 [[PDF](https://arxiv.org/abs/2010.16056)] 

   **Exploring and Distilling Posterior and Prior Knowledge for Radiology Report Generation.** [Jun., 2021] [CVPR, 2021].<br>
*Fenglin Liu, Xian Wu, Shen Ge, Wei Fan, Yuexian Zou.*<br>
 [[PDF](https://arxiv.org/abs/2106.06963)] 
 
   **Contrastive Attention for Automatic Chest X-ray Report Generation.** [Jun., 2021] [Findings of ACL, 2021].<br>
*Xuewei Ma, Fenglin Liu, Changchang Yin, Xian Wu, Shen Ge, Yuexian Zou, Ping Zhang, Xu Sun.*<br>
 [[PDF](https://arxiv.org/abs/2106.06963)] 

   **Competence-based Multimodal Curriculum Learning for Medical Report Generation.** [Aug., 2021] [ACL Oral, 2021].<br>
*Fenglin Liu, Shen Ge, Xian Wu.*<br>
 [[PDF](https://arxiv.org/abs/2206.14579)] 
 
   **AlignTransformer: Hierarchical Alignment of Visual Regions and Disease Tags for Medical Report Generation.** [Sep., 2021] [MICAI, 2021].<br>
*Di You, Fenglin Liu, Shen Ge, Xiaoxia Xie, Jing Zhang, Xian Wu.*<br>
 [[PDF](https://arxiv.org/abs/2203.10095)] 

   **Auto-Encoding Knowledge Graph for Unsupervised Medical Report Generation.** [Nov., 2021] [NeurIPS, 2021].<br>
*Fenglin Liu, Chenyu You, Xian Wu, Shen Ge, Sheng Wang, Xu Sun.*<br>
 [[PDF](https://arxiv.org/abs/2111.04318)] 

   **ChestXRayBERT: A Pretrained Language Model for Chest Radiology Report Summarization.** [Dec., 2021] [TMM, 2021].<br>
*Xiaoyan Cai, Sen Liu, Junwei Han, Libin Yang, Zhenguo Liu, Tianming Liu.*<br>
 [[PDF](https://doi.org/10.1109/TMM.2021.3132724)]

   **Retrieval-Based Chest X-Ray Report Generation Using a Pre-trained Contrastive Language-Image Model.** [Dec., 2021] [ML4H, 2021].<br>
*Mark Endo, Rayan Krishnan, Viswesh Krishna, Andrew Y. Ng, Pranav Rajpurkar.*<br>
 [[PDF](https://proceedings.mlr.press/v158/endo21a.html)] [[Github](https://github.com/rajpurkarlab/CXR-RePaiR)]
 
   **Knowledge matters: Chest radiology report generation with general and specific knowledge.** [Dec., 2021] [MIA, 2022].<br>
*Shuxin Yang, Xian Wu, Shen Ge, S Kevin Zhou, Li Xiao.*<br>
 [[PDF](https://arxiv.org/abs/2112.15009)] 

   **Radiology Report Generation with a Learned Knowledge Base and Multi-modal Alignment.** [Dec., 2021].<br>
*Shuxin Yang, Xian Wu, Shen Ge, S.Kevin Zhou, Li Xiao.*<br>
 [[PDF](https://arxiv.org/abs/2112.15011)]
 
   **Improving Chest X-Ray Report Generation by Leveraging Warm-Starting.** [Jan., 2022].<br>
*Aaron Nicolson, Jason Dowling, Bevan Koopman.*<br>
 [[PDF](https://arxiv.org/abs/2201.09405)] [[Github](https://github.com/aehrc/cvt2distilgpt2)]

   **Few-shot Structured Radiology Report Generation Using Natural Language Prompts.** [Mar., 2022].<br>
*Matthias Keicher, Kamilia Mullakaeva, Tobias Czempiel, Kristina Mach, Ashkan Khakzar, Nassir Navab.*<br>
 [[PDF](https://arxiv.org/abs/2203.15723)] 
 
   **A Self-Guided Framework for Radiology Report Generation.** [Jun., 2022] [MICAI, 2022].<br>
*Jun Li, Shibo Li, Ying Hu, Huiren Tao.*<br>
 [[PDF](https://arxiv.org/abs/2206.09378)] 
 
   **Cross-modal Prototype Driven Network for Radiology Report Generation.** [Jul., 2022] [ECCV, 2022].<br>
*Jun Wang, Abhir Bhalerao, Yulan He.*<br>
 [[PDF](https://arxiv.org/abs/2207.04818)] 
 
   **Attributed Abnormality Graph Embedding for Clinically Accurate X-Ray Report Generation.** [Jul., 2022].<br>
*Sixing Yan, William K. Cheung, Keith Chiu, Terence M. Tong, Charles K. Cheung, Simon See.*<br>
 [[PDF](https://arxiv.org/abs/2207.01208)] 
 
   **Prior Guided Transformer for Accurate Radiology Reports Generation.** [Aug., 2022] [JBHI, 2022].<br>
*Bin Yan, Mingtao Pei, Meng Zhao, Caifeng Shan, Zhaoxing Tian.*<br>
 [[PDF](https://doi.org/10.1109/JBHI.2022.3197162)] 
 
   **A Medical Semantic-Assisted Transformer for Radiographic Report Generation.** [Aug., 2022] [MICAI, 2022].<br>
*Zhanyu Wang, Mingkang Tang, Lei Wang, Xiu Li, Luping Zhou.*<br>
 [[PDF](https://arxiv.org/abs/2208.10358)] 

   **RepsNet: Combining Vision with Language for Automated Medical Reports.** [Sep., 2022] [MICAI, 2022].<br>
*Ajay Kumar Tanwani, Joelle Barral, Daniel Freedman.*<br>
 [[PDF](https://arxiv.org/abs/2209.13171)] 
 
   **An Inclusive Task-Aware Framework for Radiology Report Generation.** [Sep., 2022] [MICAI, 2022].<br>
*Lin Wang, Munan Ning, Donghuan Lu, Dong Wei, Yefeng Zheng, Jie Chen .*<br>
 [[PDF](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_54)] 
 
   **TranSQ: Transformer-Based Semantic Query for Medical Report Generation.** [Sep., 2022] [MICAI, 2022].<br>
*Ming Kong, Zhengxing Huang, Kun Kuang, Qiang Zhu, Fei Wu .*<br>
 [[PDF](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_58)] [[Github](https://github.com/zjukongming/TranSQ)]
 
   **JPG - Jointly Learn to Align: Automated Disease Prediction and Radiology Report Generation.** [Oct., 2022] [COLING, 2022].<br>
*Jingyi You, Dongyuan Li, Manabu Okumura, Kenji Suzuki.*<br>
 [[PDF](https://aclanthology.org/2022.coling-1.523/)] 
 
   **DeltaNet: Conditional Medical Report Generation for COVID-19 Diagnosis.** [Oct., 2022] [COLING, 2022].<br>
*Xian Wu, Shuxin Yang, Zhaopeng Qiu, Shen Ge, Yangtian Yan, Xingwang Wu, Yefeng Zheng, S. Kevin Zhou, Li Xiao.*<br>
 [[PDF](https://aclanthology.org/2022.coling-1.261/)] 

   **Improving Radiology Summarization with Radiograph and Anatomy Prompts.** [Oct., 2022].<br>
*Jinpeng Hu, Zhihong Chen, Yang Liu, Xiang Wan, Tsung-Hui Chang.*<br>
 [[PDF](https://arxiv.org/abs/2210.08303)] 

# Explaination, Bias, Noise, and Robustness

   **CheXpert++: Approximating the CheXpert labeler for Speed,Differentiability, and Probabilistic Output.** [Jun., 2020] [ML4H, 2020].<br>
*Matthew B. A. McDermott, Tzu Ming Harry Hsu, Wei-Hung Weng, Marzyeh Ghassemi, Peter Szolovits.*<br>
 [[PDF](https://arxiv.org/abs/2006.15229)] [[Github](https://github.com/mmcdermott/chexpertplusplus)] 
 
   **Contrastive Cross-Modal Pre-Training: A General Strategy for Small Sample Medical Imaging.** [Oct., 2020] [JBHI, 2022].<br>
*Gongbo Liang, Connor Greenwell, Yu Zhang, Xiaoqin Wang, Ramakanth Kavuluru, Nathan Jacobs.*<br>
 [[PDF](https://arxiv.org/abs/2010.03060)] 

   **VisualCheXbert: Addressing the discrepancy between radiology report labels and image labels.** [Apr., 2021] [CHIL, 2021].<br>
*Saahil Jain, Akshay Smit, Steven QH Truong, Chanh DT Nguyen, Minh-Thanh Huynh, Mudit Jain, Victoria A. Young, Andrew Y. Ng, Matthew P. Lungren, Pranav Rajpurkar.*<br>
 [[PDF](https://arxiv.org/abs/2102.11467)] [[Github](https://github.com/stanfordmlgroup/VisualCheXbert)] 
 
   **Effect of Radiology Report Labeler Quality on Deep Learning Models for Chest X-Ray Interpretation.** [Nov., 2021] [NeurIPS Workshop, 2021].<br>
*Saahil Jain, Akshay Smit, Andrew Y. Ng, Pranav Rajpurkar.*<br>
 [[PDF](https://arxiv.org/abs/2104.00793)]

   **Image Classification with Consistent Supporting Evidence.** [Dec., 2021] [ML4H, 2021].<br>
*Peiqi Wang, Ruizhi Liao, Daniel Moyer, Seth Berkowitz, Steven Horng, Polina Golland.*<br>
 [[PDF](https://arxiv.org/abs/2111.07048)] 
 
   **Using Multi-modal Data for Improving Generalizability and Explainability of Disease Classification in Radiology.** [Jul., 2022].<br>
*Pranav Agnihotri, Sara Ketabi, Khashayar (Ernest)Namdar, Farzad Khalvati.*<br>
 [[PDF](https://arxiv.org/abs/2207.14781)] 

   **Explaining Chest X-ray Pathologies in Natural Language.** [Jul., 2022] [MICAI, 2022].<br>
*Maxime Kayser, Cornelius Emde, Oana-Maria Camburu, Guy Parsons, Bartlomiej Papiez, Thomas Lukasiewicz.*<br>
 [[PDF](https://arxiv.org/abs/2207.04343)] [[Github](https://github.com/maximek3/MIMIC-NLE)] 
 
   **The Ability of Image-Language Explainable Models to Resemble Domain Expertise.** [Sep., 2022].<br>
*Petrus Werner, Anna Zapaishchykova, Ujjwal Ratan.*<br>
 [[PDF](https://arxiv.org/abs/2209.09310)] 

   **Improving Radiology Report Generation Systems by Removing Hallucinated References to Non-existent Priors.** [Oct., 2022].<br>
*Vignav Ramesh, Nathan Andrew Chi, Pranav Rajpurkar.*<br>
 [[PDF](https://arxiv.org/abs/2210.06340)] 
 
   **That's the Wrong Lung! Evaluating and Improving the Interpretability of Unsupervised Multimodal Encoders for Medical Data.** [Oct., 2022].<br>
*Denis Jered McInerney, Geoffrey Young, Jan-Willem van de Meent, Byron C. Wallace.*<br>
 [[PDF](https://arxiv.org/abs/2210.06565)] 
 
   **Evaluating Progress in Automatic Chest X-Ray Radiology Report Generation.** [Oct., 2022].<br>
*Feiyang Yu, Mark Endo, Rayan Krishnan, Ian Pan, Andy Tsai, Eduardo Pontes Reis, Eduardo Kaiser Ururahy Nunes Fonseca, Henrique Min Ho Lee, Zahra Shakeri Hossein Abad, Andrew Y. Ng, Curtis P. Langlotz, Vasantha Kumar Venugopal, Pranav Rajpurkar.*<br>
 [[PDF](https://doi.org/10.1101/2022.08.30.22279318)] 
 
   **Language over Labels: Contrastive Language Supervision Exceeds Purely Label-Supervised Classification Performance on Chest X-Rays.** [Oct., 2022] [AACL SRW, 2022].<br>
*Wiehe A., Schneider F., Blank S., Wang X., Zorn H., Biemann C.*<br>
 [[PDF](https://www.inf.uni-hamburg.de/en/inst/ab/lt/publications/wieheetal2022.pdf)] 

# Datasets

   **ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks on Weakly-Supervised Classification and Localization of Common Thorax Diseases.** [May, 2017].<br>
*Xiaosong Wang, Yifan Peng, Le Lu, Zhiyong Lu, Mohammadhadi Bagheri, Ronald M. Summers.*<br>
 [[PDF](https://arxiv.org/abs/1705.02315)] [[Url](https://nihcc.app.box.com/v/ChestXray-NIHCC)]

   **Radiology Objects in COntext (ROCO): A Multimodal Image Dataset.** [Sep., 2018] [MICAI Workshop, 2018].<br>
*O. Pelka, S. Koitka, J. Rückert, F. Nensa, C.M. Friedrich,.*<br>
 [[PDF](https://doi.org/10.1007/978-3-030-01364-6_20)] [[Github](https://github.com/razorx89/roco-dataset)]

   **MIMIC-CXR, a de-identified publicly available database of chest radiographs with free-text reports.** [Jan., 2019] [Scientific Data, 2019].<br>
*Alistair E. W. Johnson, Tom J. Pollard, Seth J. Berkowitz, Nathaniel R. Greenbaum, Matthew P. Lungren, Chih-ying Deng, Roger G. Mark, Steven Horng.*<br>
 [[PDF](https://www.nature.com/articles/s41597-019-0322-0)] [[Url](https://physionet.org/content/mimic-cxr/2.0.0/)]

   **MIMIC-CXR-JPG, a large publicly available database of labeled chest radiographs.** [Jan., 2019].<br>
*Alistair E. W. Johnson, Tom J. Pollard, Nathaniel R. Greenbaum, Matthew P. Lungren, Chih-ying Deng, Yifan Peng, Zhiyong Lu, Roger G. Mark, Seth J. Berkowitz, Steven Horng.*<br>
 [[PDF](https://arxiv.org/pdf/1901.07042.pdf)] [[Url](https://doi.org/10.13026/8360-t248)]

   **MIMIC-CXR-annotations.** [Jul, 2020].<br>
*Leo K. Tam, Xiaosong Wang, Evrim Turkbey, Kevin Lu, Yuhong Wen, Daguang Xu.*<br>
 [[PDF](https://arxiv.org/abs/2007.15778)] [[Github](https://github.com/leotam/MIMIC-CXR-annotations)]
 
   **MedICaT: A Dataset of Medical Images, Captions, and Textual References.** [Oct., 2020] [Findings of EMNLP, 2020].<br>
*Sanjay Subramanian, Lucy Lu Wang, Sachin Mehta, Ben Bogin, Madeleine van Zuylen, Sravanthi Parasa, Sameer Singh, Matt Gardner, and Hannaneh Hajishirzi.*<br>
 [[PDF](https://arxiv.org/abs/2010.06000)] [[Github](https://github.com/allenai/medicat)]

   **RadGraph: Extracting Clinical Entities and Relations from Radiology Reports.** [Jun., 2021] [NeurIPS, 2021].<br>
*Saahil Jain, Ashwin Agrawal, Adriel Saporta, Steven QH Truong, Du Nguyen Duong, Tan Bui, Pierre Chambon, Yuhao Zhang, Matthew P. Lungren, Andrew Y. Ng, Curtis P. Langlotz, Pranav Rajpurkar.*<br>
 [[PDF](https://arxiv.org/abs/2106.14463)] [[Url](https://physionet.org/content/radgraph/1.0.0/)]
 
   **Chest ImaGenome Dataset for Clinical Reasoning.** [Jul., 2021].<br>
*Joy T. Wu, Nkechinyere N. Agu, Ismini Lourentzou, Arjun Sharma, Joseph A. Paguio, Jasper S. Yao, Edward C. Dee, William Mitchell, Satyananda Kashyap, Andrea Giovannini, Leo A. Celi, Mehdi Moradi.*<br>
 [[PDF](https://arxiv.org/abs/2108.00316)] [[Url](https://doi.org/10.13026/wv01-y230)]
 
   **RadFusion: Benchmarking Performance and Fairness for Multimodal Pulmonary Embolism Detection from CT and EHR.** [Nov., 2021].<br>
*Yuyin Zhou, Shih-Cheng Huang, Jason Alan Fries, Alaa Youssef, Timothy J. Amrhein, Marcello Chang, Imon Banerjee, Daniel Rubin, Lei Xing, Nigam Shah, Matthew P. Lungren.*<br>
 [[PDF](https://arxiv.org/abs/2111.11665)] [[Url](https://stanfordaimi.azurewebsites.net/datasets/3a7548a4-8f65-4ab7-85fa-3d68c9efc1bd)]
 
   **DrugEHRQA: A Question Answering Dataset on Structured and Unstructured Electronic Health Records For Medicine Related Queries.** [May, 2022].<br>
*Jayetri Bardhan, Anthony Colas, Kirk Roberts, Daisy Zhe Wang.*<br>
 [[PDF](https://arxiv.org/abs/2205.01290)] [[Url](https://physionet.org/content/drugehrqa/1.0.0/)]
 
   **OVQA: A Clinically Generated Visual Question Answering Dataset.** [Jul., 2022] [SIGIR, 2022].<br>
*Yefan Huang, Xiaoli Wang, Feiyan Liu, Guofeng Huang.*<br>
 [[PDF](https://dl.acm.org/doi/abs/10.1145/3477495.3531724)] [[Url](http://47.94.174.82/)]
 
   **Detailed Annotations of Chest X-Rays via CT Projection for Report Understanding.** [Oct., 2022] [BMVC, 2022].<br>
*Constantin Seibold, Simon Reiß, Saquib Sarfraz, Matthias A. Fink, Victoria Mayer, Jan Sellner, Moon Sung Kim, Klaus H. Maier-Hein, Jens Kleesiek, Rainer Stiefelhagen.*<br>
 [[PDF](https://arxiv.org/abs/2210.03416)] [[Url](https://constantinseibold.github.io/paxray/)]
 
