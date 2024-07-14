# Awesome-Diffusion-Acceleration [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

:loudspeaker: Collection of awesome diffusion acceleration resources.

## Outline

- [Awesome-Diffusion-Acceleration](#awesome-diffusion-acceleration)
  - [Pruning-based Diffusion Acceleration](#pruning-based-diffusion-acceleration)
  - [Quantization-based Diffusion Acceleration](#quantization-based-diffusion-acceleration)
  - [Distillation-based Diffusion Acceleration](#distillation-based-diffusion-acceleration)
  - [Cache-based Diffusion Acceleration](#cache-based-diffusion-acceleration)
  - [Training-free Diffusion Acceleration](#training-free-diffusion-acceleration)


## Pruning-based Diffusion Acceleration
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


## Quantization-based Diffusion Acceleration

- **[1] Post-training Quantization on Diffusion Models**, CVPR 2023.
  
  *Shang, Yuzhang and Yuan, Zhihang and Xie, Bin and Wu, Bingzhe and Yan, Yan.*

  [[Paper](https://arxiv.org/pdf/2211.15736)] [[Code](https://github.com/42Shawn/PTQ4DM)] ![](https://img.shields.io/badge/PTQ4DM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange)

- **[2] Temporal Dynamic Quantization for Diffusion Models**, NeurIPS 2023.
  
  *So, Junhyuk and Lee, Jungwon and Ahn, Daehyun and Kim, Hyungjun and Park, Eunhyeok.*

  [[Paper](https://arxiv.org/pdf/2306.02316)] [Code] ![](https://img.shields.io/badge/TDQ-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Post_training_Quantization-orange)


## Distillation-based Diffusion Acceleration
  
- **[1] SnapFusion: Text-to-Image Diffusion Model on Mobile Devices within Two Seconds**, NeurIPS 2023.
  
  *Li, Yanyu and Wang, Huan and Jin, Qing and Hu, Ju and Chemerys, Pavlo and Fu, Yun and Wang, Yanzhi and Tulyakov, Sergey and Ren, Jian.*

  [[Paper](https://arxiv.org/pdf/2306.00980)] [Code] ![](https://img.shields.io/badge/SnapFusion-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Step_Distillation-orange)

- **[2] BK-SDM: A Lightweight, Fast, and Cheap Version of Stable Diffusion**, ECCV 2024.
  
  *Kim, Bo-Kyeong and Song, Hyoung-Kyu and Castells, Thibault and Choi, Shinkook.*

  [[Paper](https://arxiv.org/pdf/2305.15798)] [[Code](https://github.com/Nota-NetsPresso/BK-SDM)] ![](https://img.shields.io/badge/BK_SDM-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Distillation_Pretraining-orange)
  
## Cache-based Diffusion Acceleration

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
- **[1] Token Merging for Fast Stable Diffusion**, CVPRW 2023.
  
  *Bolya, Daniel and Hoffman, Judy.*

  [[Paper](https://arxiv.org/pdf/2303.17604)] [[Code](https://github.com/dbolya/tomesd)] ![](https://img.shields.io/badge/ToMe-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[2] AutoDiffusion: Training-Free Optimization of Time Steps and Architectures for Automated Diffusion Model Acceleration**, ICCV 2023.
  
  *Li, Lijiang and Li, Huixia and Zheng, Xiawu and Wu, Jie and Xiao, Xuefeng and Wang, Rui and Zheng, Min and Pan, Xin and Chao, Fei and Ji, Rongrong.*

  [[Paper](https://arxiv.org/pdf/2309.10438)] [[Code](https://github.com/lilijiangg/AutoDiffusion)] ![](https://img.shields.io/badge/AutoDiffusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Neural_Architecture_Search-orange)

- **[3] Structural Pruning for Diffusion Models**, NeurIPS 2023.
  
  *Fang, Gongfan and Ma, Xinyin and Wang, Xinchao.*

  [[Paper](https://arxiv.org/pdf/2305.10924)] [[Code](https://github.com/VainF/Diff-Pruning)] ![](https://img.shields.io/badge/Diff_Pruning-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Timestep_Pruning-orange)


- **[4] Faster Diffusion: Rethinking the Role of UNet Encoder in Diffusion Models**, arXiv 2023.
  
  *Li, Senmao and Hu, Taihang and Khan, Fahad Shahbaz and Li, Linxuan and Yang, Shiqi and Wang, Yaxing and Cheng, Ming-Ming and Yang, Jian.*

  [[Paper](https://arxiv.org/pdf/2312.09608)] [[Code](https://github.com/hutaiHang/Faster-Diffusion)] ![](https://img.shields.io/badge/Faster_Diffusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Personalized_Generation-green) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)


- **[5] DeepCache: Accelerating Diffusion Models for Free**, CVPR 2024.
  
  *Ma, Xinyin and Fang, Gongfan and Wang, Xinchao.*

  [[Paper](https://arxiv.org/pdf/2312.00858)] [[Code](https://github.com/horseee/DeepCache)] ![](https://img.shields.io/badge/DeepCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[6] Attention-Driven Training-Free Efficiency Enhancement of Diffusion Models**, CVPR 2024.
  
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
