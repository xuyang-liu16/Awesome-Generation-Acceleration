<div align=center>

# 𝙰𝚠𝚎𝚜𝚘𝚖𝚎 𝙳𝚒𝚏𝚏𝚞𝚜𝚒𝚘𝚗 𝙰𝚌𝚌𝚎𝚕𝚎𝚛𝚊𝚝𝚒𝚘𝚗

<p>


[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Maintenance](https://img.shields.io/badge/maintained%3F-yes-green.svg)](https://github.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Last Commit](https://img.shields.io/github/last-commit/xuyang-liu16/Awesome-Diffusion-Acceleration.svg?style=flat&color=orange)](https://github.com/xuyang-liu16/Awesome-Diffusion-Acceleration)

</p>

:loudspeaker: 𝙲𝚘𝚕𝚕𝚎𝚌𝚝𝚒𝚘𝚗 𝚘𝚏 𝙰𝚠𝚎𝚜𝚘𝚖𝚎 𝙳𝚒𝚏𝚏𝚞𝚜𝚒𝚘𝚗 𝙰𝚌𝚌𝚎𝚕𝚎𝚛𝚊𝚝𝚒𝚘𝚗 𝚁𝚎𝚜𝚘𝚞𝚛𝚌𝚎𝚜.

</div>


## Outline

- [Awesome-Diffusion-Acceleration](#awesome-diffusion-acceleration)
  - [Sampling Solver](#sampling-solver)
  - [Pruning](#pruning)
  - [Quantization](#quantization)
  - [Distillation](#distillation)
  - [Cache Mechanism](#cache-mechanism)
  - [Deployment Optimization](#deployment-optimization)
  - [Others](#others)
- [Training-free Diffusion Acceleration](#training-free-diffusion-acceleration)
  - [Stable Diffusion](#Training-free-Stable-Diffusion-Acceleration)
  - [Diffusion Transformer](#Training-free-Diffusion-Transformer-Acceleration)
  - [Auto-Regressive Generation](#Training-free-Auto-Regressive-Generation-Acceleration)


## Sampling Solver

- **[1] Denoising Diffusion Implicit Models**, ICLR 2021.
  
  *Song, Jiaming and Meng, Chenlin and Ermon, Stefano.*

  [[Paper](https://arxiv.org/pdf/2010.02502)] [[Code](https://github.com/ermongroup/ddim)] ![](https://img.shields.io/badge/DDIM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Fast_Sampling-orange)

- **[2] DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps**, NeurIPS 2022.
  
  *Lu, Cheng and Zhou, Yuhao and Bao, Fan and Chen, Jianfei and Li, Chongxuan and Zhu, Jun.*

  [[Paper](https://arxiv.org/pdf/2206.00927)] [[Code](https://github.com/LuChengTHU/dpm-solver)] ![](https://img.shields.io/badge/DPM_Solver-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Sampling_Solver-orange)

- **[3] DPM-Solver++: Fast Solver for Guided Sampling of Diffusion Probabilistic Models**, arXiv 2022.
  
  *Lu, Cheng and Zhou, Yuhao and Bao, Fan and Chen, Jianfei and Li, Chongxuan and Zhu, Jun.*

  [[Paper](https://arxiv.org/pdf/2211.01095)] [[Code](https://github.com/LuChengTHU/dpm-solver)] ![](https://img.shields.io/badge/DPM_Solver++-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Sampling_Solver-orange)
  
  

## Pruning

- **[1] Token Merging for Fast Stable Diffusion**, CVPRW 2023.
  
  *Bolya, Daniel and Hoffman, Judy.*

  [[Paper](https://arxiv.org/pdf/2303.17604)] [[Code](https://github.com/dbolya/tomesd)] ![](https://img.shields.io/badge/ToMe-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[2] Structural Pruning for Diffusion Models**, NeurIPS 2023.
  
  *Fang, Gongfan and Ma, Xinyin and Wang, Xinchao.*

  [[Paper](https://arxiv.org/pdf/2305.10924)] [[Code](https://github.com/VainF/Diff-Pruning)] ![](https://img.shields.io/badge/Diff_Pruning-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Timestep_Pruning-orange)

- **[3] Attention-Driven Training-Free Efficiency Enhancement of Diffusion Models**, CVPR 2024.
  
  *Wang, Hongjie and Liu, Difan and Kang, Yan and Li, Yijun and Lin, Zhe and Jha, Niraj K and Liu, Yuchen.*

  [[Paper](https://arxiv.org/pdf/2405.05252)] [Code] ![](https://img.shields.io/badge/AT_EDM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Pruning-orange)

- **[4] LAPTOP-Diff: Layer Pruning and Normalized Distillation for Compressing Diffusion Models**, arXiv 2024.
  
  *Zhang, Dingkun and Li, Sijia and Chen, Chen and Xie, Qingsong and Lu, Haonan.*

  [[Paper](https://arxiv.org/pdf/2404.11098)] [Code] ![](https://img.shields.io/badge/LAPTOP_Diff-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Layer_Pruning-orange)

- **[5] SparseDM: Toward Sparse Efficient Diffusion Models**, arXiv 2024.
  
  *Wang, Kafeng and Chen, Jianfei and Li, He and Mi, Zhenpeng and Zhu, Jun.*

  [[Paper](https://arxiv.org/pdf/2404.10445)] [Code] ![](https://img.shields.io/badge/SparseDM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Sparse_Finetuning-orange)

- **[6] Token Fusion: Bridging the Gap between Token Pruning and Token Merging**, WACV 2024.
  
  *Kim, Minchul and Gao, Shangqian and Hsu, Yen-Chang and Shen, Yilin and Jin, Hongxia.*

  [[Paper](https://arxiv.org/pdf/2312.01026)] [Code] ![](https://img.shields.io/badge/ToFu-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Compression-orange)

- **[7] Token Caching for Diffusion Transformer Acceleration**, arXiv 2024.

  *Jinming Lou and Wenyang Luo and Yufan Liu and Bing Li and Xinmiao Ding and Weiming Hu and Jiajiong Cao and Yuming Li and Chenguang Ma.*

  [[Paper](https://arxiv.org/pdf/2409.18523)] [Code] ![](https://img.shields.io/badge/TokenCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Compression-orange)


## Quantization

- **[1] Post-training Quantization on Diffusion Models**, CVPR 2023.
  
  *Shang, Yuzhang and Yuan, Zhihang and Xie, Bin and Wu, Bingzhe and Yan, Yan.*

  [[Paper](https://arxiv.org/pdf/2211.15736)] [[Code](https://github.com/42Shawn/PTQ4DM)] ![](https://img.shields.io/badge/PTQ4DM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Quantization_aware_Training-orange)

- **[2] Temporal Dynamic Quantization for Diffusion Models**, NeurIPS 2023.
  
  *So, Junhyuk and Lee, Jungwon and Ahn, Daehyun and Kim, Hyungjun and Park, Eunhyeok.*

  [[Paper](https://arxiv.org/pdf/2306.02316)] [Code] ![](https://img.shields.io/badge/TDQ-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange) ![](https://img.shields.io/badge/Quantization_aware_Training-orange)

- **[3] QVD: Post-training Quantization for Video Diffusion Models**, arXiv 2024.
  
  *Tian, Shilong and Chen, Hong and Lv, Chengtao and Liu, Yu and Guo, Jinyang and Liu, Xianglong and Li, Shengxi and Yang, Hao and Xie, Tao.*

  [[Paper](https://arxiv.org/pdf/2407.11585)] [Code] ![](https://img.shields.io/badge/TDQ-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange)

- **[4] VQ4DiT: Efficient Post-Training Vector Quantization for Diffusion Transformers**, arXiv 2024.

  *Deng, Juncan and Li, Shuaiting and Wang, Zeyu and Gu, Hong and Xu, Kedong and Huang, Kejie.*

  [[Paper](https://arxiv.org/pdf/2408.17131)] [Code] ![](https://img.shields.io/badge/VQ4DiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange)

- **[5] DiTAS: Quantizing Diffusion Transformers via Enhanced Activation Smoothing**, arXiv 2024.
  
  *Dong, Zhenyuan and Zhang, Sai Qian.*、

  [[Paper](https://arxiv.org/pdf/2409.07756)] [Code] ![](https://img.shields.io/badge/DiTAS-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange)

 - **[6] Q-dit: Accurate post-training quantization for diffusion transformers**, arXiv 2024.

   *Chen, Lei and Meng, Yuan and Tang, Chen and Ma, Xinzhu and Jiang, Jingyan and Wang, Xin and Wang, Zhi and Zhu, Wenwu.*

   [[Paper](https://arxiv.org/pdf/2406.17343)] [[Code](https://github.com/Juanerx/Q_DiT)] ![](https://img.shields.io/badge/Q_DiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange)




## Distillation

- **[1] Progressive Distillation for Fast Sampling of Diffusion Models**, ICLR 2022.

  *Salimans, Tim and Ho, Jonathan.*

  [[Paper](https://arxiv.org/pdf/2202.00512)] [Code] ![](https://img.shields.io/badge/Progressive_Distillation-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Step_Distillation-orange)
  
- **[2] SnapFusion: Text-to-Image Diffusion Model on Mobile Devices within Two Seconds**, NeurIPS 2023.
  
  *Li, Yanyu and Wang, Huan and Jin, Qing and Hu, Ju and Chemerys, Pavlo and Fu, Yun and Wang, Yanzhi and Tulyakov, Sergey and Ren, Jian.*

  [[Paper](https://arxiv.org/pdf/2306.00980)] [Code] ![](https://img.shields.io/badge/SnapFusion-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Step_Distillation-orange)

- **[3] BK-SDM: A Lightweight, Fast, and Cheap Version of Stable Diffusion**, ECCV 2024.
  
  *Kim, Bo-Kyeong and Song, Hyoung-Kyu and Castells, Thibault and Choi, Shinkook.*

  [[Paper](https://arxiv.org/pdf/2305.15798)] [[Code](https://github.com/Nota-NetsPresso/BK-SDM)] ![](https://img.shields.io/badge/BK_SDM-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Distillation_Pretraining-orange)


  

  
## Cache Mechanism

- **[1] Faster Diffusion: Rethinking the Role of UNet Encoder in Diffusion Models**, arXiv 2023.
  
  *Li, Senmao and Hu, Taihang and Khan, Fahad Shahbaz and Li, Linxuan and Yang, Shiqi and Wang, Yaxing and Cheng, Ming-Ming and Yang, Jian.*

  [[Paper](https://arxiv.org/pdf/2312.09608)] [[Code](https://github.com/hutaiHang/Faster-Diffusion)] ![](https://img.shields.io/badge/Faster_Diffusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Personalized_Generation-green) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)


- **[2] DeepCache: Accelerating Diffusion Models for Free**, CVPR 2024.
  
  *Ma, Xinyin and Fang, Gongfan and Wang, Xinchao.*

  [[Paper](https://arxiv.org/pdf/2312.00858)] [[Code](https://github.com/horseee/DeepCache)] ![](https://img.shields.io/badge/DeepCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[3] ∆-DiT: A Training-Free Acceleration Method Tailored for Diffusion Transformers**, arXiv 2024.
  
  *Chen, Pengtao and Shen, Mingzhu and Ye, Peng and Cao, Jianjian and Tu, Chongjun and Bouganis, Christos-Savvas and Zhao, Yiren and Chen, Tao.*

  [[Paper](https://arxiv.org/pdf/2406.01125)] [Code] ![](https://img.shields.io/badge/∆_DiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[4] FORA: Fast-Forward Caching in Diffusion Transformer Acceleration**, arXiv 2024.
  
  *Selvaraju, Pratheba and Ding, Tianyu and Chen, Tianyi and Zharkov, Ilya and Liang, Luming.*

  [[Paper](https://arxiv.org/pdf/2407.01425)] [[Code](https://github.com/prathebaselva/FORA)] ![](https://img.shields.io/badge/FORA-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[5] Learning-to-Cache: Accelerating Diffusion Transformer via Layer Caching**, NeurIPS 2024.
  
  *Ma, Xinyin and Fang, Gongfan and Mi, Michael Bi and Wang, Xinchao.*

  [[Paper](https://arxiv.org/pdf/2406.01733)] [[Code](https://github.com/horseee/learning-to-cache)] ![](https://img.shields.io/badge/L2C-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[6] Cache Me if You Can: Accelerating Diffusion Models through Block Caching**, CVPR 2024.

  *Wimbauer, Felix and Wu, Bichen and Schoenfeld, Edgar and Dai, Xiaoliang and Hou, Ji and He, Zijian and Sanakoyeu, Artsiom and Zhang, Peizhao and Tsai, Sam and Kohler, Jonas and others.*

  [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Wimbauer_Cache_Me_if_You_Can_Accelerating_Diffusion_Models_through_Block_CVPR_2024_paper.pdf)] [Code] ![](https://img.shields.io/badge/Block_Caching-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[7] Token Caching for Diffusion Transformer Acceleration**, arXiv 2024.

  *Jinming Lou and Wenyang Luo and Yufan Liu and Bing Li and Xinmiao Ding and Weiming Hu and Jiajiong Cao and Yuming Li and Chenguang Ma.*

  [[Paper](https://arxiv.org/pdf/2409.18523)] [Code] ![](https://img.shields.io/badge/TokenCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Compression-orange)

   
## Deployment Optimization

- **[1] DistriFusion: Distributed Parallel Inference for High-Resolution Diffusion Models**, CVPR 2024 Highlight.

  *Li, Muyang and Cai, Tianle and Cao, Jiaxin and Zhang, Qinsheng and Cai, Han and Bai, Junjie and Jia, Yangqing and Li, Kai and Han, Song.*

  [[Paper](https://arxiv.org/pdf/2402.19481)] [[Code](https://github.com/mit-han-lab/distrifuser)] ![](https://img.shields.io/badge/DistriFusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Deployment_Optimization-orange)
  

- **[2] PipeFusion: Displaced Patch Pipeline Parallelism for Inference of Diffusion Transformer Models**, arXiv 2024.

  *Wang, Jiannan and Fang, Jiarui and Li, Aoyu and Yang, PengCheng.*

  [[Paper](https://arxiv.org/pdf/2405.14430)] [[Code](https://github.com/PipeFusion/PipeFusion)] ![](https://img.shields.io/badge/PipeFusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Deployment_Optimization-orange)
  

- **[3] AsyncDiff: Parallelizing Diffusion Models by Asynchronous Denoising**, NeurIPS 2024.

  *Chen, Zigeng and Ma, Xinyin and Fang, Gongfan and Tan, Zhenxiong and Wang, Xinchao.*

  [[Paper](https://arxiv.org/pdf/2406.06911)] [[Code](https://github.com/czg1225/AsyncDiff)] ![](https://img.shields.io/badge/AsyncDiff-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Deployment_Optimization-orange)

  
## Others

- **[1] Efficient Diffusion Transformer with Step-wise Dynamic Attention Mediators**, ECCV 2024.

  *Yifan Pu and Zhuofan Xia and Jiayi Guo and Dongchen Han and Qixiu Li and Duo Li and Yuhui Yuan and Ji Li and Yizeng Han and Shiji Song and Gao Huang and Xiu Li.*

  [[Paper](https://arxiv.org/pdf/2408.05710)] [[Code](https://github.com/LeapLabTHU/Attention-Mediators)] ![](https://img.shields.io/badge/Attention_Mediators-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Model_Optimization-orange)



## Training-free Diffusion Acceleration

### 📌 Training-free Stable Diffusion Acceleration
Base modals: [Stable Diffusion](https://github.com/CompVis/stable-diffusion), [Stable Video Diffusion](https://github.com/Stability-AI/generative-models) and [Text2Video-Zero](https://github.com/Picsart-AI-Research/Text2Video-Zero).

- **[1] Denoising Diffusion Implicit Models**, ICLR 2021.
  
  *Song, Jiaming and Meng, Chenlin and Ermon, Stefano.*

  [[Paper](https://arxiv.org/pdf/2010.02502)] [[Code](https://github.com/ermongroup/ddim)] ![](https://img.shields.io/badge/DDIM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Fast_Sampling-orange)

- **[2] DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps**, NeurIPS 2022.
  
  *Lu, Cheng and Zhou, Yuhao and Bao, Fan and Chen, Jianfei and Li, Chongxuan and Zhu, Jun.*

  [[Paper](https://arxiv.org/pdf/2206.00927)] [[Code](https://github.com/LuChengTHU/dpm-solver)] ![](https://img.shields.io/badge/DPM_Solver-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Sampling_Solver-orange)

- **[3] DPM-Solver++: Fast Solver for Guided Sampling of Diffusion Probabilistic Models**, arXiv 2022.
  
  *Lu, Cheng and Zhou, Yuhao and Bao, Fan and Chen, Jianfei and Li, Chongxuan and Zhu, Jun.*

  [[Paper](https://arxiv.org/pdf/2211.01095)] [[Code](https://github.com/LuChengTHU/dpm-solver)] ![](https://img.shields.io/badge/DPM_Solver++-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Sampling_Solver-orange)
  
- **[4] Token Merging for Fast Stable Diffusion**, CVPRW 2023.
  
  *Bolya, Daniel and Hoffman, Judy.*

  [[Paper](https://arxiv.org/pdf/2303.17604)] [[Code](https://github.com/dbolya/tomesd)] ![](https://img.shields.io/badge/ToMe-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[5] AutoDiffusion: Training-Free Optimization of Time Steps and Architectures for Automated Diffusion Model Acceleration**, ICCV 2023.
  
  *Li, Lijiang and Li, Huixia and Zheng, Xiawu and Wu, Jie and Xiao, Xuefeng and Wang, Rui and Zheng, Min and Pan, Xin and Chao, Fei and Ji, Rongrong.*

  [[Paper](https://arxiv.org/pdf/2309.10438)] [[Code](https://github.com/lilijiangg/AutoDiffusion)] ![](https://img.shields.io/badge/AutoDiffusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Neural_Architecture_Search-orange)

- **[6] Structural Pruning for Diffusion Models**, NeurIPS 2023.
  
  *Fang, Gongfan and Ma, Xinyin and Wang, Xinchao.*

  [[Paper](https://arxiv.org/pdf/2305.10924)] [[Code](https://github.com/VainF/Diff-Pruning)] ![](https://img.shields.io/badge/Diff_Pruning-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Timestep_Pruning-orange)


- **[7] Faster Diffusion: Rethinking the Role of UNet Encoder in Diffusion Models**, arXiv 2023.
  
  *Li, Senmao and Hu, Taihang and Khan, Fahad Shahbaz and Li, Linxuan and Yang, Shiqi and Wang, Yaxing and Cheng, Ming-Ming and Yang, Jian.*

  [[Paper](https://arxiv.org/pdf/2312.09608)] [[Code](https://github.com/hutaiHang/Faster-Diffusion)] ![](https://img.shields.io/badge/Faster_Diffusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Personalized_Generation-green) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)


- **[8] DeepCache: Accelerating Diffusion Models for Free**, CVPR 2024.
  
  *Ma, Xinyin and Fang, Gongfan and Wang, Xinchao.*

  [[Paper](https://arxiv.org/pdf/2312.00858)] [[Code](https://github.com/horseee/DeepCache)] ![](https://img.shields.io/badge/DeepCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[9] Attention-Driven Training-Free Efficiency Enhancement of Diffusion Models**, CVPR 2024.
  
  *Wang, Hongjie and Liu, Difan and Kang, Yan and Li, Yijun and Lin, Zhe and Jha, Niraj K and Liu, Yuchen.*

  [[Paper](https://arxiv.org/pdf/2405.05252)] [Code] ![](https://img.shields.io/badge/AT_EDM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Pruning-orange)

- **[10] PFDiff: Training-free Acceleration of Diffusion Models through the Gradient Guidance of Past and Future**, arXiv 2024.
  
  *Guangyi Wang and Yuren Cai and Lijiang Li and Wei Peng and Songzhi Su.*

  [[Paper](https://arxiv.org/pdf/2408.08822)] [Code] ![](https://img.shields.io/badge/PFDiff-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Sampling_Solver-orange)

- **[11] Token Fusion: Bridging the Gap between Token Pruning and Token Merging**, WACV 2024.
  
  *Kim, Minchul and Gao, Shangqian and Hsu, Yen-Chang and Shen, Yilin and Jin, Hongxia.*

  [[Paper](https://arxiv.org/pdf/2312.01026)] [Code] ![](https://img.shields.io/badge/ToFu-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Compression-orange)

- **[12] Agent Attention: On the Integration of Softmax and Linear Attention**, ECCV 2024.
  
  *Han, Dongchen and Ye, Tianzhu and Han, Yizeng and Xia, Zhuofan and Song, Shiji and Huang, Gao.*
  
  [[Paper](https://arxiv.org/pdf/2312.01026)] [[Code](https://github.com/LeapLabTHU/Agent-Attention)] ![](https://img.shields.io/badge/Agent_Attention-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Linear_Attention-orange)

- **[13] T-GATE: Temporally Gating Attention to Accelerate Diffusion Model for Free!**, arXiv 2024.

  *Zhang, Wentian and Liu, Haozhe and Xie, Jinheng and Faccio, Francesco and Shou, Mike Zheng and Schmidhuber, J{\"u}rgen.*

  [[Paper](https://arxiv.org/pdf/2404.02747v1)] [[Code](https://github.com/HaozheLiu-ST/T-GATE)] ![](https://img.shields.io/badge/T_GATE-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[14] Faster Diffusion via Temporal Attention Decomposition**, arXiv 2024.

  *Liu, Haozhe and Zhang, Wentian and Xie, Jinheng and Faccio, Francesco and Xu, Mengmeng and Xiang, Tao and Shou, Mike Zheng and Perez-Rua, Juan-Manuel and Schmidhuber, J{\"u}rgen}.*

  [[Paper](https://arxiv.org/pdf/2404.02747v2)] [[Code](https://github.com/HaozheLiu-ST/T-GATE)] ![](https://img.shields.io/badge/T_GATEv2-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)
  
  

### 📌 Training-free Diffusion Transformer Acceleration
Base modals: [DiT-XL](https://github.com/facebookresearch/DiT) for Image Generation, [PIXART-α](https://github.com/PixArt-alpha/PixArt-alpha) for Text2Image, [Open-Sora](https://github.com/hpcaitech/Open-Sora) and [Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan) for Text2Video.
- **[1] ∆-DiT: A Training-Free Acceleration Method Tailored for Diffusion Transformers**, arXiv 2024.
  
  *Chen, Pengtao and Shen, Mingzhu and Ye, Peng and Cao, Jianjian and Tu, Chongjun and Bouganis, Christos-Savvas and Zhao, Yiren and Chen, Tao.*

  [[Paper](https://arxiv.org/pdf/2406.01125)] [Code] ![](https://img.shields.io/badge/∆_DiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[2] FORA: Fast-Forward Caching in Diffusion Transformer Acceleration**, arXiv 2024.
  
  *Selvaraju, Pratheba and Ding, Tianyu and Chen, Tianyi and Zharkov, Ilya and Liang, Luming.*

  [[Paper](https://arxiv.org/pdf/2407.01425)] [[Code](https://github.com/prathebaselva/FORA)] ![](https://img.shields.io/badge/FORA-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[3] DiTFastAttn: Attention Compression for Diffusion Transformer Models**, NeurIPS 2024.

  *Yuan, Zhihang and Lu, Pu and Zhang, Hanling and Ning, Xuefei and Zhang, Linfeng and Zhao, Tianchen and Yan, Shengen and Dai, Guohao and Wang, Yu.*
  
  [[Paper](https://arxiv.org/pdf/2406.08552)] [[Code](https://github.com/thu-nics/DiTFastAttn)] ![](https://img.shields.io/badge/DiTFastAttn-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Post_training_Compression-orange)

- **[4] Real-Time Video Generation with Pyramid Attention Broadcast**, arXiv 2024.

  *Xuanlei Zhao and Xiaolong Jin and Kai Wang and Yang You.*
  
  [[Paper](https://arxiv.org/pdf/2408.12588)] [[Code](https://github.com/NUS-HPC-AI-Lab/VideoSys)] ![](https://img.shields.io/badge/PAB-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Attention_Optimization-orange)


### 📌 Training-free Auto-Regressive Generation Acceleration
Base modals: [Anole](https://github.com/GAIR-NLP/anole) and [Lumina-mGPT](https://github.com/Alpha-VLLM/Lumina-mGPT) for Text2Image.

- **[1] Accelerating Auto-regressive Text-to-Image Generation with Training-free Speculative Jacobi Decoding**, arXiv 2024.

  *Yao Teng and Han Shi and Xian Liu and Xuefei Ning and Guohao Dai and Yu Wang and Zhenguo Li and Xihui Liu.*

  [[Paper](https://arxiv.org/pdf/2410.01699)] [Code] ![](https://img.shields.io/badge/SJD-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Parallel_Decoding_Mechanism-orange)



  


## Contact
:mailbox: For any question, please contact [Xuyang Liu](mailto:liuxuyang@stu.scu.edu.cn).
