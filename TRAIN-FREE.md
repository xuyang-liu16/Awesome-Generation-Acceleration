<div align=center>

# Training-free Generation Acceleration

:loudspeaker: Collections of Awesome Training-free Generation Acceleration Resources.

</div>

## 📚 <span id="head1"> *Contents* </span>

- Training-free Generation Acceleration
  - [Stable Diffusion](#Training-free-Stable-Diffusion-Acceleration)
  - [Diffusion Transformer](#Training-free-Diffusion-Transformer-Acceleration)
  - [Auto-Regressive Generation](#Training-free-Auto-Regressive-Generation-Acceleration)


### Training-free Stable Diffusion Acceleration
Base modals: [Stable Diffusion](https://github.com/CompVis/stable-diffusion), [Stable Video Diffusion](https://github.com/Stability-AI/generative-models) and [Text2Video-Zero](https://github.com/Picsart-AI-Research/Text2Video-Zero).
  
- **[1] Token Merging for Fast Stable Diffusion**, CVPRW 2023.
  
  *Bolya, Daniel and Hoffman, Judy.*

  [[Paper](https://arxiv.org/abs/2303.17604)] [[Code](https://github.com/dbolya/tomesd)] ![](https://img.shields.io/badge/ToMe-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[2] AutoDiffusion: Training-Free Optimization of Time Steps and Architectures for Automated Diffusion Model Acceleration**, ICCV 2023.
  
  *Li, Lijiang and Li, Huixia and Zheng, Xiawu and Wu, Jie and Xiao, Xuefeng and Wang, Rui and Zheng, Min and Pan, Xin and Chao, Fei and Ji, Rongrong.*

  [[Paper](https://arxiv.org/abs/2309.10438)] [[Code](https://github.com/lilijiangg/AutoDiffusion)] ![](https://img.shields.io/badge/AutoDiffusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Neural_Architecture_Search-orange)

- **[3] Structural Pruning for Diffusion Models**, NeurIPS 2023.
  
  *Fang, Gongfan and Ma, Xinyin and Wang, Xinchao.*

  [[Paper](https://arxiv.org/abs/2305.10924)] [[Code](https://github.com/VainF/Diff-Pruning)] ![](https://img.shields.io/badge/Diff_Pruning-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Timestep_Pruning-orange)

- **[4] Faster Diffusion: Rethinking the Role of UNet Encoder in Diffusion Models**, NeurIPS 2024.
  
  *Li, Senmao and Hu, Taihang and Khan, Fahad Shahbaz and Li, Linxuan and Yang, Shiqi and Wang, Yaxing and Cheng, Ming-Ming and Yang, Jian.*

  [[Paper](https://arxiv.org/abs/2312.09608)] [[Code](https://github.com/hutaiHang/Faster-Diffusion)] ![](https://img.shields.io/badge/Faster_Diffusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Personalized_Generation-green) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[5] DeepCache: Accelerating Diffusion Models for Free**, CVPR 2024.
  
  *Ma, Xinyin and Fang, Gongfan and Wang, Xinchao.*

  [[Paper](https://arxiv.org/abs/2312.00858)] [[Code](https://github.com/horseee/DeepCache)] ![](https://img.shields.io/badge/DeepCache-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[6] Attention-Driven Training-Free Efficiency Enhancement of Diffusion Models**, CVPR 2024.
  
  *Wang, Hongjie and Liu, Difan and Kang, Yan and Li, Yijun and Lin, Zhe and Jha, Niraj K and Liu, Yuchen.*

  [[Paper](https://arxiv.org/abs/2405.05252)] [Code] ![](https://img.shields.io/badge/AT_EDM-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Pruning-orange)

- **[7] PFDiff: Training-free Acceleration of Diffusion Models through the Gradient Guidance of Past and Future**, arXiv 2024.
  
  *Guangyi Wang and Yuren Cai and Lijiang Li and Wei Peng and Songzhi Su.*

  [[Paper](https://arxiv.org/abs/2408.08822)] [Code] ![](https://img.shields.io/badge/PFDiff-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Sampling_Solver-orange)

- **[8] Token Fusion: Bridging the Gap between Token Pruning and Token Merging**, WACV 2024.
  
  *Kim, Minchul and Gao, Shangqian and Hsu, Yen-Chang and Shen, Yilin and Jin, Hongxia.*

  [[Paper](https://arxiv.org/abs/2312.01026)] [Code] ![](https://img.shields.io/badge/ToFu-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Token_Compression-orange)

- **[9] Agent Attention: On the Integration of Softmax and Linear Attention**, ECCV 2024.
  
  *Han, Dongchen and Ye, Tianzhu and Han, Yizeng and Xia, Zhuofan and Song, Shiji and Huang, Gao.*
  
  [[Paper](https://arxiv.org/abs/2312.01026)] [[Code](https://github.com/LeapLabTHU/Agent-Attention)] ![](https://img.shields.io/badge/Agent_Attention-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Linear_Attention-orange)

- **[10] T-GATE: Temporally Gating Attention to Accelerate Diffusion Model for Free!**, arXiv 2024.

  *Zhang, Wentian and Liu, Haozhe and Xie, Jinheng and Faccio, Francesco and Shou, Mike Zheng and Schmidhuber, J{\"u}rgen.*

  [[Paper](https://arxiv.org/abs/2404.02747v1)] [[Code](https://github.com/HaozheLiu-ST/T-GATE)] ![](https://img.shields.io/badge/T_GATE-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[11] Faster Diffusion via Temporal Attention Decomposition**, arXiv 2024.

  *Liu, Haozhe and Zhang, Wentian and Xie, Jinheng and Faccio, Francesco and Xu, Mengmeng and Xiang, Tao and Shou, Mike Zheng and Perez-Rua, Juan-Manuel and Schmidhuber, J{\"u}rgen}.*

  [[Paper](https://arxiv.org/abs/2404.02747v2)] [[Code](https://github.com/HaozheLiu-ST/T-GATE)] ![](https://img.shields.io/badge/T_GATEv2-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[12] ToDo: Token Downsampling for Efficient Generation of High-Resolution Images**, IJCAIw 2024.
  
  *Smith, Ethan and Saxena, Nayan and Saha, Aninda.*

  [[Paper](https://arxiv.org/abs/2402.13573)] [[Code](https://github.com/ethansmith2000/ImprovedTokenMerge)] ![](https://img.shields.io/badge/ToDo-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[13] Turbo: Informativity-Driven Acceleration Plug-In for Vision-Language Models**, ECCV 2024.
  
  *Ju, Chen and Wang, Haicheng and Li, Zeqian and Chen, Xu and Zhai, Zhonghua and Huang, Weilin and Xiao, Shuai.*

  [[Paper](https://arxiv.org/abs/2407.11717)] [Code] ![](https://img.shields.io/badge/Turbo-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Merging-orange)
  
- **[14] F<sup>3</sup>-Pruning: A Training-Free and Generalized Pruning Strategy towards Faster and Finer Text-to-Video Synthesis**, AAAI 2024.
  
  *Su, Sitong and Liu, Jianzhi and Gao, Lianli and Song, Jingkuan.*

  [[Paper](https://arxiv.org/abs/2312.03459)] [Code] ![](https://img.shields.io/badge/F3_Pruning-blue) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Token_Pruning-orange)

- **[15] Fast and Memory-Efficient Video Diffusion Using Streamlined Inference**, NeurIPS 2024.
  
  *Zheng Zhan and Yushu Wu and Yifan Gong and Zichong Meng and Zhenglun Kong and Changdi Yang and Geng Yuan and Pu Zhao and Wei Niu and Yanzhi Wang.*

  [[Paper](https://arxiv.org/abs/2411.01171)] [[Code](https://github.com/wuyushuwys/FMEDiffusion)] ![](https://img.shields.io/badge/Streamlined_Inference-blue) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Streamlined_Inference-orange)

- **[16] Importance-based Token Merging for Diffusion Models**, arXiv 2024.
  
  *Wu, Haoyu and Xu, Jingyi and Le, Hieu and Samaras, Dimitris.*

  [[Paper](https://arxiv.org/abs/2411.16720)] [Code] ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[17] ToMA: Token Merging with Attention For Diffusion Models**, OpenReview 2024.
  
  [[Paper](https://openreview.net/forum?id=xhtqgW5b93)] [[Code](https://openreview.net/forum?id=xhtqgW5b93)] ![](https://img.shields.io/badge/ToMA-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[18] Token Merging for Training-Free Semantic Binding in Text-to-Image Synthesis**, NeurIPS 2024.

  *Taihang Hu and Linxuan Li and Joost van de Weijer and Hongcheng Gao and Fahad Khan and Jian Yang and Ming-Ming Cheng and Kai Wang and Yaxing Wang.*

  [[Paper](https://arxiv.org/abs/2411.07132)] [[Code](https://github.com/hutaiHang/ToMe)] ![](https://img.shields.io/badge/ToMe-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[19] Cached Adaptive Token Merging: Dynamic Token Reduction and Redundant Computation Elimination in Diffusion Model**, arXiv 2024.

  *Omid Saghatchian and Atiyeh Gh. Moghadam and Ahmad Nickabadi.*

  [[Paper](https://arxiv.org/abs/2501.00946)] [[Code](https://github.com/omidiu/ca_tome)] ![](https://img.shields.io/badge/DaTo-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Pruning-orange) ![](https://img.shields.io/badge/Token_Caching-orange)

- **[20] Token Pruning for Caching Better: 9 Times Acceleration on Stable Diffusion for Free**, arXiv 2024.

  *Evelyn Zhang and Bang Xiao and Jiayi Tang and Qianli Ma and Chang Zou and Xuefei Ning and Xuming Hu and Linfeng Zhang.*

  [[Paper](https://arxiv.org/abs/2501.00375)] [[Code](https://github.com/EvelynZhang-epiclab/DaTo)] ![](https://img.shields.io/badge/DaTo-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Pruning-orange) ![](https://img.shields.io/badge/Token_Caching-orange)

- **[21] Noise Prediction Can Be Adaptively Skipped for Different Prompts Without Training**, NeurIPS 2024.

  *Hancheng Ye and Jiakang Yuan and Renqiu Xia and Xiangchao Yan and Tao Chen and Junchi Yan and Botian Shi and Bo Zhang.*

  [[Paper](https://arxiv.org/abs/2410.09873)] [[Code](https://github.com/Alpha-Innovator/AdaptiveDiffusion)] ![](https://img.shields.io/badge/AdaptiveDiffusion-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Feature_Caching-orange)

- **[22] Negative Token Merging: Image-based Adversarial Feature Guidance**, arXiv 2024.

  *Jaskirat Singh and Lindsey Li and Weijia Shi and Ranjay Krishna and Yejin Choi and Pang Wei Koh and Michael F. Cohen and Stephen Gould and Liang Zheng and Luke Zettlemoyer.*
  
  [[Paper](https://arxiv.org/abs/2412.01339)] [[Code](https://github.com/1jsingh/negtome)] ![](https://img.shields.io/badge/NegToMe-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Merging-orange)
  
  
### Training-free Diffusion Transformer Acceleration
Base modals: [DiT-XL](https://github.com/facebookresearch/DiT) for Image Generation, [PIXART-α](https://github.com/PixArt-alpha/PixArt-alpha) for Text2Image, [Open-Sora](https://github.com/hpcaitech/Open-Sora) and [Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan) for Text2Video.

- **[1] ∆-DiT: A Training-Free Acceleration Method Tailored for Diffusion Transformers**, arXiv 2024.
  
  *Chen, Pengtao and Shen, Mingzhu and Ye, Peng and Cao, Jianjian and Tu, Chongjun and Bouganis, Christos-Savvas and Zhao, Yiren and Chen, Tao.*

  [[Paper](https://arxiv.org/abs/2406.01125)] [Code] ![](https://img.shields.io/badge/∆_DiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[2] FORA: Fast-Forward Caching in Diffusion Transformer Acceleration**, arXiv 2024.
  
  *Selvaraju, Pratheba and Ding, Tianyu and Chen, Tianyi and Zharkov, Ilya and Liang, Luming.*

  [[Paper](https://arxiv.org/abs/2407.01425)] [[Code](https://github.com/prathebaselva/FORA)] ![](https://img.shields.io/badge/FORA-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[3] DiTFastAttn: Attention Compression for Diffusion Transformer Models**, NeurIPS 2024.

  *Yuan, Zhihang and Lu, Pu and Zhang, Hanling and Ning, Xuefei and Zhang, Linfeng and Zhao, Tianchen and Yan, Shengen and Dai, Guohao and Wang, Yu.*
  
  [[Paper](https://arxiv.org/abs/2406.08552)] [[Code](https://github.com/thu-nics/DiTFastAttn)] ![](https://img.shields.io/badge/DiTFastAttn-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Post_training_Compression-orange)

- **[4] Real-Time Video Generation with Pyramid Attention Broadcast**, arXiv 2024.

  *Xuanlei Zhao and Xiaolong Jin and Kai Wang and Yang You.*
  
  [[Paper](https://arxiv.org/abs/2408.12588)] [[Code](https://github.com/NUS-HPC-AI-Lab/VideoSys)] ![](https://img.shields.io/badge/PAB-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Attention_Optimization-orange)

- **[5] Accelerating Diffusion Transformers with Token-wise Feature Caching**, arXiv 2024.

  *Chang Zou and Xuyang Liu and Ting Liu and Siteng Huang and Linfeng Zhang.*
  
  [[Paper](https://arxiv.org/abs/2410.05317)] [[Code](https://github.com/Shenyi-Z/ToCa)] ![](https://img.shields.io/badge/ToCa-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[6] FasterCache: Training-Free Video Diffusion Model Acceleration with High Quality**, arXiv 2024.

  *Zhengyao Lv and Chenyang Si and Junhao Song and Zhenyu Yang and Yu Qiao and Ziwei Liu and Kwan-Yee K. Wong.*
  
  [[Paper](https://arxiv.org/abs/2410.19355)] [[Code](https://github.com/Vchitect/FasterCache)] ![](https://img.shields.io/badge/FasterCache-blue) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[7] Adaptive Caching for Faster Video Generation with Diffusion Transformers**, arXiv 2024.

  *Kumara Kahatapitiya and Haozhe Liu and Sen He and Ding Liu and Menglin Jia and Michael S. Ryoo and Tian Xie.*
  
  [[Paper](https://arxiv.org/abs/2411.02397)] [[Code](https://github.com/AdaCache-DiT/AdaCache)] ![](https://img.shields.io/badge/AdaCache-blue) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[8] HeadRouter: A Training-free Image Editing Framework for MM-DiTs by Adaptively Routing Attention Heads**, arXiv 2024.

  *Yu Xu and Fan Tang and Juan Cao and Yuxin Zhang and Xiaoyu Kong and Jintao Li and Oliver Deussen and Tong-Yee Lee.*
  
  [[Paper](https://arxiv.org/abs/2411.15034)] [[Code](https://github.com/ICTMCG/HeadRouter)] ![](https://img.shields.io/badge/HeadRouter-blue) ![](https://img.shields.io/badge/Image_Editing-green) ![](https://img.shields.io/badge/Head_Prunning-orange)

- **[9] Stable Flow: Vital Layers for Training-Free Image Editing**, arXiv 2024.

  *Omri Avrahami and Or Patashnik and Ohad Fried and Egor Nemchinov and Kfir Aberman and Dani Lischinski and Daniel Cohen-Or.*
  
  [[Paper](https://arxiv.org/abs/2411.14430)] [[Code](https://omriavrahami.com/stable-flow/)] ![](https://img.shields.io/badge/Stable_Flow-blue) ![](https://img.shields.io/badge/Image_Editing-green) ![](https://img.shields.io/badge/Layer_Prunning-orange)

- **[10] MD-DiT: Step-aware Mixture-of-Depths for Efficient Diffusion Transformers**, NeurIPSw 2024.

  *Mingzhu Shen, Pengtao Chen, Peng Ye, Guoxuan Xia, Tao Chen, Christos-Savvas Bouganis, Yiren Zhao.*

  [[Paper](https://openreview.net/forum?id=1jWhiakK7N)] [Code] ![](https://img.shields.io/badge/MD_DiT-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Cache_Mechanism-orange)

- **[11] ToMA: Token Merging with Attention For Diffusion Models**, OpenReview 2024.
  
  [[Paper](https://openreview.net/forum?id=xhtqgW5b93)] [[Code](https://openreview.net/forum?id=xhtqgW5b93)] ![](https://img.shields.io/badge/ToMA-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Merging-orange)

- **[12] Accelerating Diffusion Transformers with Dual Feature Caching**, arXiv 2024.

  *Chang Zou and Evelyn Zhang and Runlin Guo and Haohang Xu and Conghui He and Xuming Hu and Linfeng Zhang.*
  
  [[Paper](https://arxiv.org/abs/2410.05317)] [[Code](https://github.com/Shenyi-Z/DuCa)] ![](https://img.shields.io/badge/DuCa-blue) ![](https://img.shields.io/badge/Image_Generation-green) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Text2Video-green) ![](https://img.shields.io/badge/Token_Caching-orange)

- **[13] Timestep Embedding Tells: It's Time to Cache for Video Diffusion Model**, arXiv 2024.

  *Liu, Feng and Zhang, Shiwei and Wang, Xiaofeng and Wei, Yujie and Qiu, Haonan and Zhao, Yuzhong and Zhang, Yingya and Ye, Qixiang and Wan, Fang.*
  
  [[Paper](https://arxiv.org/abs/2411.19108)] [[Code](https://github.com/ali-vilab/TeaCache)] ![](https://img.shields.io/badge/TeaCache-blue) ![](https://img.shields.io/badge/Video_Generation-green) ![](https://img.shields.io/badge/Feature_Caching-orange)

- **[14] CAT Pruning: Cluster-Aware Token Pruning For Text-to-Image Diffusion Models**, NeurIPSw 2024.
  
  *Xinle Cheng, Zhuoming Chen, Zhihao Jia.*
  
  [[Paper](https://openreview.net/pdf/bf470617f541635cbde87fcc0ba3fdbddcef3db7.pdf)] [[Code](https://github.com/ada-cheng/CAT-Pruning)] ![](https://img.shields.io/badge/CAT_Pruning-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Token_Pruning-orange)
  

###  Training-free Auto-Regressive Generation Acceleration
Base modals: [Anole](https://github.com/GAIR-NLP/anole), [Lumina-mGPT](https://github.com/Alpha-VLLM/Lumina-mGPT) and [VAR](https://github.com/FoundationVision/VAR) for Text2Image.

- **[1] Accelerating Auto-regressive Text-to-Image Generation with Training-free Speculative Jacobi Decoding**, arXiv 2024.

  *Yao Teng and Han Shi and Xian Liu and Xuefei Ning and Guohao Dai and Yu Wang and Zhenguo Li and Xihui Liu.*

  [[Paper](https://arxiv.org/abs/2410.01699)] [Code] ![](https://img.shields.io/badge/SJD-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Parallel_Decoding_Mechanism-orange)

- **[2] ZipAR: Accelerating Autoregressive Image Generation through Spatial Locality**, arXiv 2024.

  *Yefei He and Feng Chen and Yuanyu He and Shaoxuan He and Hong Zhou and Kaipeng Zhang and Bohan Zhuang.*

  [[Paper](https://arxiv.org/abs/2412.04062)] [Code] ![](https://img.shields.io/badge/ZipAR-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Parallel_Decoding_Mechanism-orange)

- **[3] CoDe: Collaborative Decoding Makes Visual Auto-Regressive Modeling Efficient**, arXiv 2024.
  
  *Zigeng Chen and Xinyin Ma and Gongfan Fang and Xinchao Wang.*
  
  [[Paper](https://arxiv.org/abs/2411.17787)] [[Code](https://github.com/czg1225/CoDe)] ![](https://img.shields.io/badge/CoDe-blue) ![](https://img.shields.io/badge/Text2Image-green) ![](https://img.shields.io/badge/Parallel_Decoding_Mechanism-orange)
