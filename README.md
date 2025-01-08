<div align=center>

# 🎨 Awesome Generation Acceleration 🚀

<p>


[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![papercount](https://img.shields.io/badge/paper_count-60+-pink)
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg)](https://github.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Last Commit](https://img.shields.io/github/last-commit/xuyang-liu16/Awesome-Diffusion-Acceleration.svg?style=flat&color=orange)](https://github.com/xuyang-liu16/Awesome-Diffusion-Acceleration)
[![GitHub](https://img.shields.io/github/stars/xuyang-liu16/Awesome-Generation-Acceleration.svg?style=social)](https://github.com/xuyang-liu16/Awesome-Generation-Acceleration.git)  
👐👐 If you would like to contribute to this repository, feel free to email me at `liuxuyang@stu.scu.edu.cn`! 👐👐

</p>


</div>

## 🔥 <span id="head1"> *News* </span>

* `2024/12/24` 🤗🤗 We release an open-sourse repo "[Awesome-Token-Reduction-for-Model-Compression](https://github.com/xuyang-liu16/Awesome-Token-Reduction-for-Model-Compression)", which collects recent awesome token reduction papers! Feel free to contribute your suggestions!

* `2024/12/19` 💥💥 We introduce "[Token-wise Generation Acceleration](TOKEN-WISE.md)", offering comprehensive methods for accelerating generative models from the perspective of **tokens**!

* `2024/12/05` 💥💥 We introduce "[Training-free Generation Acceleration](TRAIN-FREE.md)", offering comprehensive methods for accelerating Stable Diffusion, Diffusion Transformers, and Auto-Regressive models **without training**!

* `2024/10/12` 🚀🚀 We release our work [ToCa](https://arxiv.org/abs/2410.05317) about accelerating DiT models for FREE, which achieves nearly lossless acceleration of **1.51×** on FLUX, **1.93×** on PixArt-α, and **2.36×** on OpenSora! [Code](https://github.com/Shenyi-Z/ToCa) is now available!

* `2024/07/15` 🤗🤗 We release an open-sourse repo "[Awesome-Generation-Acceleration](https://github.com/xuyang-liu16/Awesome-Generation-Acceleration)", which collects recent awesome generation accleration papers! Feel free to contribute your suggestions!


## 📚 <span id="head1"> *Contents* </span>

- [Awesome Generation Acceleration](README.md)
  - [Fast Sampling](#fast-sampling)
  - [Pruning](#pruning)
  - [Quantization](#quantization)
  - [Distillation](#distillation)
  - [Cache Mechanism](#cache-mechanism)
  - [Deployment Optimization](#deployment-optimization)
- [Training-free Generation Acceleration](TRAIN-FREE.md)
- [Token-wise Generation Acceleration](TOKEN-WISE.md)
    
 
## 💬 <span id="head1"> *Keywords* </span>
![](https://img.shields.io/badge/Abbreviation-blue) ![](https://img.shields.io/badge/Application-green) ![](https://img.shields.io/badge/Mechanism-orange) 

## 📝 <span id="head1"> *Papers* </span>

### Fast Sampling

- **[1] Denoising Diffusion Implicit Models**, ICLR 2021.
  
  *Song, Jiaming and Meng, Chenlin and Ermon, Stefano.*

  [[Paper](https://arxiv.org/abs/2010.02502)] [[Code](https://github.com/ermongroup/ddim)] ![](https://img.shields.io/badge/DDIM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Fast_Sampling-orange)

- **[2] DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps**, NeurIPS 2022.
  
  *Lu, Cheng and Zhou, Yuhao and Bao, Fan and Chen, Jianfei and Li, Chongxuan and Zhu, Jun.*

  [[Paper](https://arxiv.org/abs/2206.00927)] [[Code](https://github.com/LuChengTHU/dpm-solver)] ![](https://img.shields.io/badge/DPM_Solver-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Sampling_Solver-orange)

- **[3] DPM-Solver++: Fast Solver for Guided Sampling of Diffusion Probabilistic Models**, arXiv 2022.
  
  *Lu, Cheng and Zhou, Yuhao and Bao, Fan and Chen, Jianfei and Li, Chongxuan and Zhu, Jun.*

  [[Paper](https://arxiv.org/abs/2211.01095)] [[Code](https://github.com/LuChengTHU/dpm-solver)] ![](https://img.shields.io/badge/DPM_Solver++-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Sampling_Solver-orange)

- **[4] Jump Your Steps: Optimizing Sampling Schedule of Discrete Diffusion Models**, arXiv 2022.
  
  *Yong-Hyun Park and Chieh-Hsin Lai and Satoshi Hayakawa and Yuhta Takida and Yuki Mitsufuji.*

  [[Paper](https://arxiv.org/abs/2410.07761#page=8.39)] [Code] ![](https://img.shields.io/badge/JYS-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Step_Skipping-orange)

- **[5] AdaDiff: Adaptive Step Selection for Fast Diffusion**, arXiv 2023.

  *Hui Zhang, Zuxuan Wu, Zhen Xing, Jie Shao, Yu-Gang Jiang.*
  
  [[Paper](https://arxiv.org/abs/2311.14768)] [Code] ![](https://img.shields.io/badge/AdaDiff-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Step_Selection-orange)

- **[6] DuoDiff: Accelerating Diffusion Models with a Dual-Backbone Approach**, arXiv 2024.
  
  *Daniel Gallo Fernández, Rǎzvan-Andrei Matişan, Alejandro Monroy Muñoz, Ana-Maria Vasilcoiu, Janusz Partyka, Tin Hadži Veljković, Metod Jazbec.*

  [[Paper](https://arxiv.org/abs/2410.09633)] [Code] ![](https://img.shields.io/badge/DuoDiff-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Exiting_by_Networks-orange)

- **[7] SwiftEdit: Lightning Fast Text-Guided Image Editing via One-Step Diffusion**, arXiv 2024.
  
  *Trong-Tung Nguyen and Quang Nguyen and Khoi Nguyen and Anh Tran and Cuong Pham.*

  [[Paper](https://arxiv.org/abs/2412.04301)] [Code] ![](https://img.shields.io/badge/SwiftEdit-blue) ![](https://img.shields.io/badge/Image_Editing-green) ![](https://img.shields.io/badge/One_Step_Diffusion-orange)
  
  

### Pruning

- **[1] Token Merging for Fast Stable Diffusion**, CVPRW 2023.
  
  *Bolya, Daniel and Hoffman, Judy.*

  [[Paper](https://arxiv.org/abs/2303.17604)] [[Code](https://github.com/dbolya/tomesd)] ![](https://img.shields.io/badge/ToMe-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[2] Structural Pruning for Diffusion Models**, NeurIPS 2023.
  
  *Fang, Gongfan and Ma, Xinyin and Wang, Xinchao.*

  [[Paper](https://arxiv.org/abs/2305.10924)] [[Code](https://github.com/VainF/Diff-Pruning)] ![](https://img.shields.io/badge/Diff_Pruning-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Timestep_Pruning-orange)

- **[3] Attention-Driven Training-Free Efficiency Enhancement of Diffusion Models**, CVPR 2024.
  
  *Wang, Hongjie and Liu, Difan and Kang, Yan and Li, Yijun and Lin, Zhe and Jha, Niraj K and Liu, Yuchen.*

  [[Paper](https://arxiv.org/abs/2405.05252)] [Code] ![](https://img.shields.io/badge/AT_EDM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Pruning-orange)

- **[4] LAPTOP-Diff: Layer Pruning and Normalized Distillation for Compressing Diffusion Models**, arXiv 2024.
  
  *Zhang, Dingkun and Li, Sijia and Chen, Chen and Xie, Qingsong and Lu, Haonan.*

  [[Paper](https://arxiv.org/abs/2404.11098)] [Code] ![](https://img.shields.io/badge/LAPTOP_Diff-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Layer_Pruning-orange)

- **[5] SparseDM: Toward Sparse Efficient Diffusion Models**, arXiv 2024.
  
  *Wang, Kafeng and Chen, Jianfei and Li, He and Mi, Zhenpeng and Zhu, Jun.*

  [[Paper](https://arxiv.org/abs/2404.10445)] [Code] ![](https://img.shields.io/badge/SparseDM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Sparse_Finetuning-orange)

- **[6] Token Fusion: Bridging the Gap between Token Pruning and Token Merging**, WACV 2024.
  
  *Kim, Minchul and Gao, Shangqian and Hsu, Yen-Chang and Shen, Yilin and Jin, Hongxia.*

  [[Paper](https://arxiv.org/abs/2312.01026)] [Code] ![](https://img.shields.io/badge/ToFu-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Compression-orange)

- **[7] Token Caching for Diffusion Transformer Acceleration**, arXiv 2024.

  *Jinming Lou and Wenyang Luo and Yufan Liu and Bing Li and Xinmiao Ding and Weiming Hu and Jiajiong Cao and Yuming Li and Chenguang Ma.*

  [[Paper](https://arxiv.org/abs/2409.18523)] [Code] ![](https://img.shields.io/badge/TokenCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Compression-orange)

- **[8] Dynamic Diffusion Transformer**, arXiv 2024.

  *Wangbo Zhao and Yizeng Han and Jiasheng Tang and Kai Wang and Yibing Song and Gao Huang and Fan Wang and Yang You.*

  [[Paper](https://arxiv.org/abs/2410.03456)] [[Code](https://github.com/NUS-HPC-AI-Lab/Dynamic-Diffusion-Transformer)] ![](https://img.shields.io/badge/DyDiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Compression-orange)

- **[9] ToDo: Token Downsampling for Efficient Generation of High-Resolution Images**, IJCAIw 2024.
  
  *Smith, Ethan and Saxena, Nayan and Saha, Aninda.*

  [[Paper](https://arxiv.org/abs/2402.13573)] [[Code](https://github.com/ethansmith2000/ImprovedTokenMerge)] ![](https://img.shields.io/badge/ToDo-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[10] Turbo: Informativity-Driven Acceleration Plug-In for Vision-Language Models**, ECCV 2024.
  
  *Ju, Chen and Wang, Haicheng and Li, Zeqian and Chen, Xu and Zhai, Zhonghua and Huang, Weilin and Xiao, Shuai.*

  [[Paper](https://arxiv.org/abs/2407.11717)] [Code] ![](https://img.shields.io/badge/Turbo-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[11] F<sup>3</sup>-Pruning: A Training-Free and Generalized Pruning Strategy towards Faster and Finer Text-to-Video Synthesis**, AAAI 2024.
  
  *Su, Sitong and Liu, Jianzhi and Gao, Lianli and Song, Jingkuan.*

  [[Paper](https://arxiv.org/abs/2312.03459)] [Code] ![](https://img.shields.io/badge/F3_Pruning-blue) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Token_Pruning-orange)
  
- **[12] DiP-GO: A Diffusion Pruner via Few-step Gradient Optimization**, NeurIPS 2024.
  
  *Zhu, Haowei and Tang, Dehua and Liu, Ji and Lu, Mingjie and Zheng, Jintu and Peng, Jinzhang and Li, Dong and Wang, Yu and Jiang, Fan and Tian, Lu and others.*

  [[Paper](https://arxiv.org/abs/2410.16942)] [Code] ![](https://img.shields.io/badge/DiP_GO-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Layer_Pruning-orange)

- **[13] U-DiTs: Downsample Tokens in U-Shaped Diffusion Transformers**, NeurIPS 2024.

  *Yuchuan Tian and Zhijun Tu and Hanting Chen and Jie Hu and Chao Xu and Yunhe Wang.*
  
  [[Paper](https://arxiv.org/abs/2405.02730)] [[Code](https://github.com/YuchuanTian/U-DiT)] ![](https://img.shields.io/badge/U_DiTs-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Compression-orange)

- **[14] Importance-based Token Merging for Diffusion Models**, arXiv 2024.
  
  *Wu, Haoyu and Xu, Jingyi and Le, Hieu and Samaras, Dimitris.*

  [[Paper](https://arxiv.org/abs/2411.16720)] [Code] ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[15] HeadRouter: A Training-free Image Editing Framework for MM-DiTs by Adaptively Routing Attention Heads**, arXiv 2024.

  *Yu Xu and Fan Tang and Juan Cao and Yuxin Zhang and Xiaoyu Kong and Jintao Li and Oliver Deussen and Tong-Yee Lee.*
  
  [[Paper](https://arxiv.org/abs/2411.15034)] [[Code](https://github.com/ICTMCG/HeadRouter)] ![](https://img.shields.io/badge/HeadRouter-blue) ![](https://img.shields.io/badge/Image_Editing-green) ![](https://img.shields.io/badge/Head_Prunning-orange)

- **[16] Stable Flow: Vital Layers for Training-Free Image Editing**, arXiv 2024.

  *Omri Avrahami and Or Patashnik and Ohad Fried and Egor Nemchinov and Kfir Aberman and Dani Lischinski and Daniel Cohen-Or.*
  
  [[Paper](https://arxiv.org/abs/2411.14430)] [[Code](https://omriavrahami.com/stable-flow/)] ![](https://img.shields.io/badge/Stable_Flow-blue) ![](https://img.shields.io/badge/Image_Editing-green) ![](https://img.shields.io/badge/Layer_Prunning-orange)
  
- **[17] TinyFusion: Diffusion Transformers Learned Shallow**, arXiv 2024.

  *Fang, Gongfan and Li, Kunjun and Ma, Xinyin and Wang, Xinchao.*
  
  [[Paper](https://arxiv.org/abs/2412.01199)] [[Code](https://github.com/VainF/TinyFusion)] ![](https://img.shields.io/badge/TinyFusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Layer_Prunning-orange)

- **[18] Diffusion Model Compression for Image-to-Image Translation**, ACCV 2024.

  *Kim, Geonung and Kim, Beomsu and Park, Eunhyeok and Cho, Sunghyun.*
  
  [[Paper](https://arxiv.org/abs/2401.17547)] [[Code](https://github.com/KIMGEONUNG/ID-compression)] ![](https://img.shields.io/badge/ID_Compression-blue) ![](https://img.shields.io/badge/Image2Image-green) ![](https://img.shields.io/badge/Layer_Prunning-orange) ![](https://img.shields.io/badge/Time_Step_Optimization-orange) 

- **[1９] FlexDiT: Dynamic Token Density Control for Diffusion Transformer**, arXiv 2024.

  *Shuning Chang and Pichao Wang and Jiasheng Tang and Yi Yang.*
  
  [[Paper](https://arxiv.org/abs/2412.06028)] [[Code](https://github.com/changsn/FlexDiT)] ![](https://img.shields.io/badge/FlexDiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Token_Prunning-orange)

- **[20] AsymRnR: Video Diffusion Transformers Acceleration with Asymmetric Reduction and Restoration**, arXiv 2024.

  *AsymRnR: Video Diffusion Transformers Acceleration with Asymmetric Reduction and Restoration.*
  
  [[Paper](https://arxiv.org/abs/2412.11706)] [Code] ![](https://img.shields.io/badge/AsymRnR-blue) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Token_Reduction-orange)

- **[21] ToMA: Token Merging with Attention For Diffusion Models**, OpenReview 2024.
  
  [[Paper](https://openreview.net/forum?id=xhtqgW5b93)] [[Code](https://openreview.net/forum?id=xhtqgW5b93)] ![](https://img.shields.io/badge/ToMA-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[22] KOALA: Empirical Lessons Toward Memory-Efficient and Fast Diffusion Models for Text-to-Image Synthesis**, NeurIPS 2024.

  *Youngwan Lee, Kwanyong Park, Yoorhim Cho, Yong-Ju Lee, Sung Ju Hwang.*
  
  [[Paper](https://arxiv.org/abs/2312.04005)] [[Code](https://github.com/youngwanLEE/sdxl-koala)] ![](https://img.shields.io/badge/KOALA-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Layer_Prunning-orange) ![](https://img.shields.io/badge/Distillation_Pretraining-orange)

- **[23] Token Merging for Training-Free Semantic Binding in Text-to-Image Synthesis**, NeurIPS 2024.

  *Taihang Hu and Linxuan Li and Joost van de Weijer and Hongcheng Gao and Fahad Khan and Jian Yang and Ming-Ming Cheng and Kai Wang and Yaxing Wang.*

  [[Paper](https://arxiv.org/abs/2411.07132)] [[Code](https://github.com/hutaiHang/ToMe)] ![](https://img.shields.io/badge/ToMe-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[24] Layer- and Timestep-Adaptive Differentiable Token Compression Ratios for Efficient Diffusion Transformers**, arXiv 2024.

  *Haoran You and Connelly Barnes and Yuqian Zhou and Yan Kang and Zhenbang Du and Wei Zhou and Lingzhi Zhang and Yotam Nitzan and Xiaoyang Liu and Zhe Lin and Eli Shechtman and Sohrab Amirghodsi and Yingyan Celine Lin.*
  
   [[Paper](https://arxiv.org/abs/2412.16822)] [[Code](https://github.com/GATECH-EIC/DiffRatio-MoD)] ![](https://img.shields.io/badge/DiffRatio_MoD-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Pruning-orange)

- **[25] Cached Adaptive Token Merging: Dynamic Token Reduction and Redundant Computation Elimination in Diffusion Model**, arXiv 2024.

  *Omid Saghatchian and Atiyeh Gh. Moghadam and Ahmad Nickabadi.*

  [[Paper](https://arxiv.org/abs/2501.00946)] [[Code](https://github.com/omidiu/ca_tome)] ![](https://img.shields.io/badge/DaTo-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Pruning-orange) ![](https://img.shields.io/badge/Token_Caching-orange)

- **[26] Token Pruning for Caching Better: 9 Times Acceleration on Stable Diffusion for Free**, arXiv 2024.

  *Evelyn Zhang and Bang Xiao and Jiayi Tang and Qianli Ma and Chang Zou and Xuefei Ning and Xuming Hu and Linfeng Zhang.*

  [[Paper](https://arxiv.org/abs/2501.00375)] [[Code](https://github.com/EvelynZhang-epiclab/DaTo)] ![](https://img.shields.io/badge/DaTo-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Pruning-orange) ![](https://img.shields.io/badge/Token_Caching-orange)
  

### Quantization

- **[1] Post-training Quantization on Diffusion Models**, CVPR 2023.
  
  *Shang, Yuzhang and Yuan, Zhihang and Xie, Bin and Wu, Bingzhe and Yan, Yan.*

  [[Paper](https://arxiv.org/abs/2211.15736)] [[Code](https://github.com/42Shawn/PTQ4DM)] ![](https://img.shields.io/badge/PTQ4DM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Quantization_aware_Training-orange)

- **[2] Temporal Dynamic Quantization for Diffusion Models**, NeurIPS 2023.
  
  *So, Junhyuk and Lee, Jungwon and Ahn, Daehyun and Kim, Hyungjun and Park, Eunhyeok.*

  [[Paper](https://arxiv.org/abs/2306.02316)] [Code] ![](https://img.shields.io/badge/TDQ-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange) ![](https://img.shields.io/badge/Quantization_aware_Training-orange)

- **[3] QVD: Post-training Quantization for Video Diffusion Models**, arXiv 2024.
  
  *Tian, Shilong and Chen, Hong and Lv, Chengtao and Liu, Yu and Guo, Jinyang and Liu, Xianglong and Li, Shengxi and Yang, Hao and Xie, Tao.*

  [[Paper](https://arxiv.org/abs/2407.11585)] [Code] ![](https://img.shields.io/badge/TDQ-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange)

- **[4] VQ4DiT: Efficient Post-Training Vector Quantization for Diffusion Transformers**, arXiv 2024.

  *Deng, Juncan and Li, Shuaiting and Wang, Zeyu and Gu, Hong and Xu, Kedong and Huang, Kejie.*

  [[Paper](https://arxiv.org/abs/2408.17131)] [Code] ![](https://img.shields.io/badge/VQ4DiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange)

- **[5] DiTAS: Quantizing Diffusion Transformers via Enhanced Activation Smoothing**, arXiv 2024.
  
  *Dong, Zhenyuan and Zhang, Sai Qian.*、

  [[Paper](https://arxiv.org/abs/2409.07756)] [Code] ![](https://img.shields.io/badge/DiTAS-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange)

 - **[6] Q-dit: Accurate post-training quantization for diffusion transformers**, arXiv 2024.

   *Chen, Lei and Meng, Yuan and Tang, Chen and Ma, Xinzhu and Jiang, Jingyan and Wang, Xin and Wang, Zhi and Zhu, Wenwu.*

   [[Paper](https://arxiv.org/abs/2406.17343)] [[Code](https://github.com/Juanerx/Q_DiT)] ![](https://img.shields.io/badge/Q_DiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange)

 - **[7] SVDQunat: Absorbing Outliers by Low-Rank Components for 4-Bit Diffusion Models**, arXiv 2024.

   *Muyang Li and Yujun Lin and Zhekai Zhang and Tianle Cai and Xiuyu Li and Junxian Guo and Enze Xie and Chenlin Meng and Jun-Yan Zhu and Song Han.*

   [[Paper](https://arxiv.org/abs/2411.05007)] [[Code](https://github.com/mit-han-lab/nunchaku)] ![](https://img.shields.io/badge/SVDQunat-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange)




### Distillation

- **[1] Progressive Distillation for Fast Sampling of Diffusion Models**, ICLR 2022.

  *Salimans, Tim and Ho, Jonathan.*

  [[Paper](https://arxiv.org/abs/2202.00512)] [Code] ![](https://img.shields.io/badge/Progressive_Distillation-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Step_Distillation-orange)
  
- **[2] SnapFusion: Text-to-Image Diffusion Model on Mobile Devices within Two Seconds**, NeurIPS 2023.
  
  *Li, Yanyu and Wang, Huan and Jin, Qing and Hu, Ju and Chemerys, Pavlo and Fu, Yun and Wang, Yanzhi and Tulyakov, Sergey and Ren, Jian.*

  [[Paper](https://arxiv.org/abs/2306.00980)] [Code] ![](https://img.shields.io/badge/SnapFusion-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Step_Distillation-orange)

- **[3] BK-SDM: A Lightweight, Fast, and Cheap Version of Stable Diffusion**, ECCV 2024.
  
  *Kim, Bo-Kyeong and Song, Hyoung-Kyu and Castells, Thibault and Choi, Shinkook.*

  [[Paper](https://arxiv.org/abs/2305.15798)] [[Code](https://github.com/Nota-NetsPresso/BK-SDM)] ![](https://img.shields.io/badge/BK_SDM-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Distillation_Pretraining-orange)

- **[4] Accelerating Diffusion Models with One-to-Many Knowledge Distillation**, arXiv 2024.
  
  *Linfeng Zhang and Kaisheng Ma.*

  [[Paper](https://arxiv.org/abs/2410.04191)] [Code] ![](https://img.shields.io/badge/O2MKD-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/New_Distillation_Paradigm-orange)

- **[5] Relational Diffusion Distillation for Efficient Image Generation**, ACM MM 2024.
  
  *Weilun Feng and Chuanguang Yang and Zhulin An and Libo Huang and Boyu Diao and Fei Wang and Yongjun Xu.*
  
  [[Paper](https://arxiv.org/abs/2410.07679)] [[Code](https://github.com/cantbebetter2/RDD)] ![](https://img.shields.io/badge/RDD-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Step_Distillation-orange)

- **[6] Accelerating Video Diffusion Models via Distribution Matching**, arXiv 2024.
  
  *Yuanzhi Zhu and Hanshu Yan and Huan Yang and Kai Zhang and Junnan Li.*
  
  [[Paper](https://arxiv.org/abs/2412.05899)] [Code] ![](https://img.shields.io/badge/AnimateDiff-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Step_Distillation-orange)

- **[7] From Slow Bidirectional to Fast Causal Video Generators**, arXiv 2024.
  
  *Yin, Tianwei and Zhang, Qiang and Zhang, Richard and Freeman, William T and Durand, Fredo and Shechtman, Eli and Huang, Xun.*
  
  [[Paper](https://arxiv.org/abs/2412.07772)] [[Code](https://causvid.github.io/)] ![](https://img.shields.io/badge/DMD-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Distribution_Matching_Distillation-orange)

- **[8] SnapGen: Taming High-Resolution Text-to-Image Models for Mobile Devices with Efficient Architectures and Training**, arXiv 2024.
  
  *Dongting Hu and Jierun Chen and Xijie Huang and Huseyin Coskun and Arpit Sahni and Aarush Gupta and Anujraaj Goyal and Dishani Lahiri and Rajesh Singh and Yerlan Idelbayev and Junli Cao and Yanyu Li and Kwang-Ting Cheng and S. -H. Gary Chan and Mingming Gong and Sergey Tulyakov and Anil Kag and Yanwu Xu and Jian Ren.*
  
  [[Paper](https://arxiv.org/abs/2412.09619)] [Code] ![](https://img.shields.io/badge/SnapGen-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Step_Distillation-orange)

- **[9] Inference-Time Diffusion Model Distillation**, arXiv 2024.
  
  *Geon Yeong Park and Sang Wan Lee and Jong Chul Ye.*
  
  [[Paper](https://arxiv.org/abs/2412.08871)] [[Code](https://github.com/geonyeong-park/inference_distillation)] ![](https://img.shields.io/badge/Distillation++-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Inference_Distillation-orange)


  
### Cache Mechanism

- **[1] Faster Diffusion: Rethinking the Role of UNet Encoder in Diffusion Models**, NeurIPS 2024.
  
  *Li, Senmao and Hu, Taihang and Khan, Fahad Shahbaz and Li, Linxuan and Yang, Shiqi and Wang, Yaxing and Cheng, Ming-Ming and Yang, Jian.*

  [[Paper](https://arxiv.org/abs/2312.09608)] [Code](https://github.com/hutaiHang/Faster-Diffusion)] ![](https://img.shields.io/badge/Faster_Diffusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Personalized_Generation-green) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[2] DeepCache: Accelerating Diffusion Models for Free**, CVPR 2024.
  
  *Ma, Xinyin and Fang, Gongfan and Wang, Xinchao.*

  [[Paper](https://arxiv.org/abs/2312.00858)] [[Code](https://github.com/horseee/DeepCache)] ![](https://img.shields.io/badge/DeepCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[3] ∆-DiT: A Training-Free Acceleration Method Tailored for Diffusion Transformers**, arXiv 2024.
  
  *Chen, Pengtao and Shen, Mingzhu and Ye, Peng and Cao, Jianjian and Tu, Chongjun and Bouganis, Christos-Savvas and Zhao, Yiren and Chen, Tao.*

  [[Paper](https://arxiv.org/abs/2406.01125)] [Code] ![](https://img.shields.io/badge/∆_DiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[4] FORA: Fast-Forward Caching in Diffusion Transformer Acceleration**, arXiv 2024.
  
  *Selvaraju, Pratheba and Ding, Tianyu and Chen, Tianyi and Zharkov, Ilya and Liang, Luming.*

  [[Paper](https://arxiv.org/abs/2407.01425)] [[Code](https://github.com/prathebaselva/FORA)] ![](https://img.shields.io/badge/FORA-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[5] Learning-to-Cache: Accelerating Diffusion Transformer via Layer Caching**, NeurIPS 2024.
  
  *Ma, Xinyin and Fang, Gongfan and Mi, Michael Bi and Wang, Xinchao.*

  [[Paper](https://arxiv.org/abs/2406.01733)] [[Code](https://github.com/horseee/learning-to-cache)] ![](https://img.shields.io/badge/L2C-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[6] Cache Me if You Can: Accelerating Diffusion Models through Block Caching**, CVPR 2024.

  *Wimbauer, Felix and Wu, Bichen and Schoenfeld, Edgar and Dai, Xiaoliang and Hou, Ji and He, Zijian and Sanakoyeu, Artsiom and Zhang, Peizhao and Tsai, Sam and Kohler, Jonas and others.*

  [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Wimbauer_Cache_Me_if_You_Can_Accelerating_Diffusion_Models_through_Block_CVPR_2024_paper.abs)] [Code] ![](https://img.shields.io/badge/Block_Caching-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[7] Token Caching for Diffusion Transformer Acceleration**, arXiv 2024.

  *Jinming Lou and Wenyang Luo and Yufan Liu and Bing Li and Xinmiao Ding and Weiming Hu and Jiajiong Cao and Yuming Li and Chenguang Ma.*

  [[Paper](https://arxiv.org/abs/2409.18523)] [Code] ![](https://img.shields.io/badge/TokenCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Compression-orange)

- **[8] HarmoniCa: Harmonizing Training and Inference for Better Feature Cache in Diffusion Transformer Acceleration**, arXiv 2024.

  *Yushi Huang and Zining Wang and Ruihao Gong and Jing Liu and Xinjie Zhang and Jun Zhang.*

  [[Paper](https://arxiv.org/abs/2410.01723)] [Code] ![](https://img.shields.io/badge/HarmoniCa-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Compression-orange)

- **[9] Accelerating Diffusion Transformers with Token-wise Feature Caching**, arXiv 2024.

  *Chang Zou and Xuyang Liu and Ting Liu and Siteng Huang and Linfeng Zhang.*
  
  [[Paper](https://arxiv.org/abs/2410.05317)] [[Code](https://github.com/Shenyi-Z/ToCa)] ![](https://img.shields.io/badge/ToCa-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Token_Caching-orange)

- **[10] FasterCache: Training-Free Video Diffusion Model Acceleration with High Quality**, arXiv 2024.

  *Zhengyao Lv and Chenyang Si and Junhao Song and Zhenyu Yang and Yu Qiao and Ziwei Liu and Kwan-Yee K. Wong.*
  
  [[Paper](https://arxiv.org/abs/2410.19355)] [[Code](https://github.com/Vchitect/FasterCache)] ![](https://img.shields.io/badge/FasterCache-blue) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[11] Adaptive Caching for Faster Video Generation with Diffusion Transformers**, arXiv 2024.

  *Kumara Kahatapitiya and Haozhe Liu and Sen He and Ding Liu and Menglin Jia and Michael S. Ryoo and Tian Xie.*
  
  [[Paper](https://arxiv.org/abs/2411.02397)] [[Code](https://github.com/AdaCache-DiT/AdaCache)] ![](https://img.shields.io/badge/AdaCache-blue) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[1２] Ca2-VDM: Efficient Autoregressive Video Diffusion Model　with Causal Generation and Cache Sharing**, arXiv 2024.

  *Kaifeng Gao and Jiaxin Shi and Hanwang Zhang and Chunping Wang and Jun Xiao and Long Chen.*
  
  [[Paper](https://arxiv.org/abs/2411.16375)] [[Code](https://github.com/Dawn-LX/CausalCache-VDM/)] ![](https://img.shields.io/badge/Ca2_VDM-blue) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[13] Accelerating Vision Diffusion Transformers with Skip Branches**, arXiv 2024.

  *Guanjie Chen and Xinyu Zhao and Yucheng Zhou and Tianlong Chen and Cheng Yu.*
  
  [[Paper](https://arxiv.org/abs/2411.17616)] [[Code](https://github.com/OpenSparseLLMs/Skip-DiT)] ![](https://img.shields.io/badge/Skip_DiT-blue) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[14] MD-DiT: Step-aware Mixture-of-Depths for Efficient Diffusion Transformers**, NeurIPSw 2024.

  *Mingzhu Shen, Pengtao Chen, Peng Ye, Guoxuan Xia, Tao Chen, Christos-Savvas Bouganis, Yiren Zhao.*

  [[Paper](https://openreview.net/forum?id=1jWhiakK7N)] [Code] ![](https://img.shields.io/badge/MD_DiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[15] E-CAR: Efficient Continuous Autoregressive Image Generation via Multistage Modelings**, arXiv 2024.

  *Zhihang Yuan and Yuzhang Shang and Hanling Zhang and Tongcheng Fang and Rui Xie and Bingxin Xu and Yan Yan and Shengen Yan and Guohao Dai and Yu Wang.*

  [[Paper](https://arxiv.org/abs/2412.14170)] [Code] ![](https://img.shields.io/badge/E_CAR-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[16] Accelerating Diffusion Transformers with Dual Feature Caching**, arXiv 2024.

  *Chang Zou and Evelyn Zhang and Runlin Guo and Haohang Xu and Conghui He and Xuming Hu and Linfeng Zhang.*
  
  [[Paper](https://arxiv.org/abs/2410.05317)] [[Code](https://github.com/Shenyi-Z/DuCa)] ![](https://img.shields.io/badge/DuCa-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Token_Caching-orange)

- **[17] Cached Adaptive Token Merging: Dynamic Token Reduction and Redundant Computation Elimination in Diffusion Model**, arXiv 2024.

  *Omid Saghatchian and Atiyeh Gh. Moghadam and Ahmad Nickabadi.*

  [[Paper](https://arxiv.org/abs/2501.00946)] [[Code](https://github.com/omidiu/ca_tome)] ![](https://img.shields.io/badge/DaTo-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Pruning-orange) ![](https://img.shields.io/badge/Token_Caching-orange)

- **[18] Token Pruning for Caching Better: 9 Times Acceleration on Stable Diffusion for Free**, arXiv 2024.

  *Evelyn Zhang and Bang Xiao and Jiayi Tang and Qianli Ma and Chang Zou and Xuefei Ning and Xuming Hu and Linfeng Zhang.*

  [[Paper](https://arxiv.org/abs/2501.00375)] [[Code](https://github.com/EvelynZhang-epiclab/DaTo)] ![](https://img.shields.io/badge/DaTo-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Pruning-orange) ![](https://img.shields.io/badge/Token_Caching-orange)

   
### Deployment Optimization

- **[1] DistriFusion: Distributed Parallel Inference for High-Resolution Diffusion Models**, CVPR 2024 Highlight.

  *Li, Muyang and Cai, Tianle and Cao, Jiaxin and Zhang, Qinsheng and Cai, Han and Bai, Junjie and Jia, Yangqing and Li, Kai and Han, Song.*

  [[Paper](https://arxiv.org/abs/2402.19481)] [[Code](https://github.com/mit-han-lab/distrifuser)] ![](https://img.shields.io/badge/DistriFusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Deployment_Optimization-orange)
  

- **[2] PipeFusion: Displaced Patch Pipeline Parallelism for Inference of Diffusion Transformer Models**, arXiv 2024.

  *Wang, Jiannan and Fang, Jiarui and Li, Aoyu and Yang, PengCheng.*

  [[Paper](https://arxiv.org/abs/2405.14430)] [[Code](https://github.com/PipeFusion/PipeFusion)] ![](https://img.shields.io/badge/PipeFusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Deployment_Optimization-orange)
  

- **[3] AsyncDiff: Parallelizing Diffusion Models by Asynchronous Denoising**, NeurIPS 2024.

  *Chen, Zigeng and Ma, Xinyin and Fang, Gongfan and Tan, Zhenxiong and Wang, Xinchao.*

  [[Paper](https://arxiv.org/abs/2406.06911)] [[Code](https://github.com/czg1225/AsyncDiff)] ![](https://img.shields.io/badge/AsyncDiff-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Deployment_Optimization-orange)

- **[4] Fast and Memory-Efficient Video Diffusion Using Streamlined Inference**, NeurIPS 2024.
  
  *Zheng Zhan and Yushu Wu and Yifan Gong and Zichong Meng and Zhenglun Kong and Changdi Yang and Geng Yuan and Pu Zhao and Wei Niu and Yanzhi Wang.*

  [[Paper](https://arxiv.org/abs/2411.01171)] [[Code](https://github.com/wuyushuwys/FMEDiffusion)] ![](https://img.shields.io/badge/Streamlined_Inference-blue) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Streamlined_Inference-orange)

- **[5] Partially Conditioned Patch Parallelism for Accelerated Diffusion Model Inference**, arXiv 2024.
  
  *XiuYu Zhang and Zening Luo and Michelle E. Lu.*

  [[Paper](https://arxiv.org/abs/2412.02962)] [Code] ![](https://img.shields.io/badge/PCPP-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Patch_Parallelism-orange)



## 📌 Citation

Please consider giving a star ⭐ and citing 📝 this repository if you find it useful.

```bibtex
@misc{xuyang2024acceleration,
  author={Xuyang Liu},
  title = {Awesome-Generation-Acceleration},
  year = {2024},
  url = {https://github.com/xuyang-liu16/Awesome-Generation-Acceleration},
}
```

## 🧑‍💻 Contribution

👏 Thanks to these contributors for this excellent work！

<a href="https://github.com/xuyang-liu16/Awesome-Generation-Acceleration/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=xuyang-liu16/Awesome-Generation-Acceleration" />
</a>

