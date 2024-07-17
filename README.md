# Awesome-Diffusion-Acceleration [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

:loudspeaker: Collection of awesome diffusion acceleration resources.

## Outline

- [Awesome-Diffusion-Acceleration](#awesome-diffusion-acceleration)
  - [Sampling Solver](#sampling-solver)
  - [Pruning](#pruning)
  - [Quantization](#quantization)
  - [Distillation](#distillation)
  - [Cachec Mechanism](#cache-mechanism)
- [Training-free Diffusion Acceleration](#training-free-diffusion-acceleration)


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


## Quantization

- **[1] Post-training Quantization on Diffusion Models**, CVPR 2023.
  
  *Shang, Yuzhang and Yuan, Zhihang and Xie, Bin and Wu, Bingzhe and Yan, Yan.*

  [[Paper](https://arxiv.org/pdf/2211.15736)] [[Code](https://github.com/42Shawn/PTQ4DM)] ![](https://img.shields.io/badge/PTQ4DM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange)

- **[2] Temporal Dynamic Quantization for Diffusion Models**, NeurIPS 2023.
  
  *So, Junhyuk and Lee, Jungwon and Ahn, Daehyun and Kim, Hyungjun and Park, Eunhyeok.*

  [[Paper](https://arxiv.org/pdf/2306.02316)] [Code] ![](https://img.shields.io/badge/TDQ-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange) ![](https://img.shields.io/badge/Quantization_aware_Training-orange)

- **[3] QVD: Post-training Quantization for Video Diffusion Models**, arXiv 2024.
  
  *Tian, Shilong and Chen, Hong and Lv, Chengtao and Liu, Yu and Guo, Jinyang and Liu, Xianglong and Li, Shengxi and Yang, Hao and Xie, Tao.*

  [[Paper](https://arxiv.org/pdf/2407.11585)] [Code] ![](https://img.shields.io/badge/TDQ-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange) 



## Distillation
  
- **[1] SnapFusion: Text-to-Image Diffusion Model on Mobile Devices within Two Seconds**, NeurIPS 2023.
  
  *Li, Yanyu and Wang, Huan and Jin, Qing and Hu, Ju and Chemerys, Pavlo and Fu, Yun and Wang, Yanzhi and Tulyakov, Sergey and Ren, Jian.*

  [[Paper](https://arxiv.org/pdf/2306.00980)] [Code] ![](https://img.shields.io/badge/SnapFusion-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Step_Distillation-orange)

- **[2] BK-SDM: A Lightweight, Fast, and Cheap Version of Stable Diffusion**, ECCV 2024.
  
  *Kim, Bo-Kyeong and Song, Hyoung-Kyu and Castells, Thibault and Choi, Shinkook.*

  [[Paper](https://arxiv.org/pdf/2305.15798)] [[Code](https://github.com/Nota-NetsPresso/BK-SDM)] ![](https://img.shields.io/badge/BK_SDM-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Distillation_Pretraining-orange)

  
## Cachec Mechanism

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

- **[5] Learning-to-Cache: Accelerating Diffusion Transformer via Layer Caching**, arXiv 2024.
  
  *Ma, Xinyin and Fang, Gongfan and Mi, Michael Bi and Wang, Xinchao.*

  [[Paper](https://arxiv.org/pdf/2406.01733)] [Code] ![](https://img.shields.io/badge/L2C-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)


## Training-free Diffusion Acceleration

### :pushpin: Training-free Stable Diffusion Acceleration
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



### :pushpin: Training-free Diffusion Transformer Acceleration
Base modals: [DiT-XL](https://github.com/facebookresearch/DiT) and [PIXART-α](https://github.com/PixArt-alpha/PixArt-alpha).
- **[1] ∆-DiT: A Training-Free Acceleration Method Tailored for Diffusion Transformers**, arXiv 2024.
  
  *Chen, Pengtao and Shen, Mingzhu and Ye, Peng and Cao, Jianjian and Tu, Chongjun and Bouganis, Christos-Savvas and Zhao, Yiren and Chen, Tao.*

  [[Paper](https://arxiv.org/pdf/2406.01125)] [Code] ![](https://img.shields.io/badge/∆_DiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[2] FORA: Fast-Forward Caching in Diffusion Transformer Acceleration**, arXiv 2024.
  
  *Selvaraju, Pratheba and Ding, Tianyu and Chen, Tianyi and Zharkov, Ilya and Liang, Luming.*

  [[Paper](https://arxiv.org/pdf/2407.01425)] [[Code](https://github.com/prathebaselva/FORA)] ![](https://img.shields.io/badge/FORA-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

## Contact
:mailbox: For any question, please contact [Xuyang Liu](mailto:liuxuyang@stu.scu.edu.cn).
