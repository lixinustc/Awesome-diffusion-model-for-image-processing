<p align="center">
  <img src="./figures/framework.png" alt="image" style="width:1000px;">
</p>


**Purpose**: We aim to provide a summary of diffusion model-based image processing, including restoration, enhancement, coding, and quality assessment. More papers will be summarized.

[Xin Li](http://home.ustc.edu.cn/~lixin666/), [Yulin Ren](https://scholar.google.com/citations?hl=en&user=234Nza8AAAAJ), [Xin Jin](http://home.ustc.edu.cn/~jinxustc/), [Bingchen Li] (https://scholar.google.com/citations?user=qHeWjNwAAAAJ&hl=zh-CN), [Xijun Wang](),
[Cuiling Lan](https://scholar.google.com/citations?user=XZugqiwAAAAJ&hl=en), [Xingrui Wang](https://scholar.google.com.hk/citations?user=cZEGgJ0AAAAJ&hl=zh-CN), [Wenjun Zeng](https://scholar.google.com/citations?user=_cUfvYQAAAAJ&hl=en), [Xinchao Wang](https://scholar.google.com/citations?user=w69Buq0AAAAJ&hl=en), [Zhibo Chen](https://scholar.google.com/citations?user=1ayDJfsAAAAJ&hl=en)

University of Science and Technology of China (USTC), National University of Singapore (NUS), Microsoft Research Asia (MSRA), Eastern Institute of Technology (EIT) 

**Brief intro**: The survey for diffusion model-based IR has been released.

[![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2308.09388v1.pdf)   ![visitors](https://visitor-badge.laobi.icu/badge?page_id=lixinustc/Awesome-diffusion-model-for-image-processing)

## :bookmark: News!!!
- [x] 2023-09-19: **Updated new related works before 15/09/2023 in this GitHub.**
- [x] 2023-11-24: **Updated new related works before 10/11/2023 in this GitHub.**
- [x] 2023-12-25: **Updated new related works before 25/12/2023 in this GitHub.**
- [x] 2024-01-25: **Updated new related works before 25/01/2024 in this GitHub.**
- [x] 2024-03-25: **Updated new related works before 25/03/2024 in this GitHub.**
- [x] 2024-04-25: **Updated new related works before 25/04/2024 in this GitHub.**
- [x] 2024-06-25: **Updated new related works before 25/06/2024 in this GitHub.**
- [x] 2024-08-25: **Updated new related works before 25/08/2024 in this GitHub.**
- [x] 2024-10-25: **Updated new related works before 25/10/2024 in this GitHub.**
- [x] 2024-12-25: **Updated new related works before 25/12/2024 in this GitHub.**

**📌 About new works.** If you want to incorporate your studies (e.g., the link of paper or project) on diffusion model-based image processing in this repository. Welcome to raise an issue or email us. We will incorporate it into this repository and our survey report as soon as possible. 


## 🌟  Features
- [x] **Survey for diffusion model-based Image Restoration** ([Arxiv version](https://arxiv.org/pdf/2308.09388v1.pdf) is released) 
- [x] **Summary for diffusion model-based Image/Video Compression**
- [x] **Summary for diffusion model-based Quality Assessment**



## Diffusion model-based Image Restoration/Enhancement
### Table of contents
<!-- - [Survey paper](#survey-paper)
- [Table of contents](#table-of-contents) -->
- [Diffusion model for Image Super resolution](#image-super-resolution)
- [Diffusion model for Image Restoration](#image-restoration)
- [Diffusion model for Image Inpainting](#image-inpainting)
- [Diffusion model for Image Shadow Removal](#image-shadow-removal)
- [Diffusion model for Image Denoising](#image-denoising)
- [Diffusion model for Image Dehazing](#image-dehazing)
- [Diffusion model for Image Deblurring](#image-deblurring)
- [Diffusion model for Medical IR](#medical-restoration-mrict)
- [Diffusion model for Low-Light Enchancement](#low-light-enchancement)
- [Diffusion model for other tasks](#other-tasks)
- [Benchmark Datasets](#benchmark-datasets)
- [Diffusion model for Image/video compression](#compression)
- [Diffusion model for Image/video quality assessment](#IQA)
  <!-- - [Recommended Datasets](#recommended-datasets)
  - [All Datasets](#all-datasets) -->

### Image Super-Resolution
|Models| Paper | First Author | Training Way | Venue | Topic | Project |
| :-- | :---: | :--: | :--: |:--:|:--:| :--: |
|SR3| [Image super-resolution via iterative refinement](https://ieeexplore.ieee.org/document/9887996x) | Chitwan Saharia | Supervised |TPAMI2022 | Super-resolution | [![Stars](https://img.shields.io/github/stars/Janspiry/Image-Super-Resolution-via-Iterative-Refinement.svg?style=social&label=Star)](https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement) |
|SRDiff|[SRDiff: Single Image Super-Resolution with Diffusion Probabilistic Models](https://arxiv.org/abs/2104.14951) | Haoying Li | Supervised | Neurocomputing 2022 | Super-resolution | [![Stars](https://img.shields.io/github/stars/LeiaLi/SRDiff.svg?style=social&label=Star)](https://github.com/LeiaLi/SRDiff) |
|SDE-SR| [Face super-resolution using stochastic differential equations](https://arxiv.org/abs/2209.12064) | Marcelo dos Santos | Supervised | SIBGRAPI 2022 | Super-resolution | [![Stars](https://img.shields.io/github/stars/marcelowds/sr-sde.svg?style=social&label=Star)](https://github.com/marcelowds/sr-sde) |
|IDM| [Implicit diffusion models for continuous super-resolution](https://openaccess.thecvf.com/content/CVPR2023/papers/Gao_Implicit_Diffusion_Models_for_Continuous_Super-Resolution_CVPR_2023_paper.pdf) | Sicheng Gao | Supervised | CVPR2023 | Super-resolution | [![Stars](https://img.shields.io/github/stars/Ree1s/IDM.svg?style=social&label=Star)](https://github.com/Ree1s/IDM) |
|PromptSR| [Image Super-Resolution with Text Prompt Diffusion](https://arxiv.org/abs/2311.14282) | Zheng Chen | Supervised | Preprint'23 | Super-resolution | [![Stars](https://img.shields.io/github/stars/zhengchen1999/PromptSR.svg?style=social&label=Star)](https://github.com/zhengchen1999/PromptSR) |
|DiffIR| [DiffIR: Efficient diffusion model for image restoration](https://arxiv.org/abs/2303.09472) | Bin Xia | Supervised | ICCV 2023 | Super-resolution | [![Stars](https://img.shields.io/github/stars/Zj-BinXia/DiffIR.svg?style=social&label=Star)](https://github.com/Zj-BinXia/DiffIR) |
|CDM| [Cascaded Diffusion Models for High Fidelity Image Generation](https://arxiv.org/abs/2106.15282) | Jonathan Ho | Supervised | J.Mach.Learn.Res 2022 | Super-resolution | |
|StableSR| [Exploiting diffusion prior for real-world image super-resolution](https://arxiv.org/abs/2305.07015) | Jianyi Wang | Supervised | Preprint'23 | Real-World Super-resolution | [![Stars](https://img.shields.io/github/stars/IceClear/StableSR.svg?style=social&label=Star)](https://github.com/IceClear/StableSR)|
|ResShift| [ResShift: Efficient Diffusion Model for Image Super-resolution by Residual Shifting](https://arxiv.org/pdf/2307.12348.pdf) | Zongsheng Yue | Supervised | NeurIPS 2023 | Real-World Super-resolution | [![Stars](https://img.shields.io/github/stars/zsyOAOA/ResShift.svg?style=social&label=Star)](https://github.com/zsyOAOA/ResShift)|
|DFOSD| [Distillation-Free One-Step Diffusion for Real-World Image Super-Resolution](https://arxiv.org/pdf/2410.04224) | Jianze Li | Supervised | Preprint'24 | Real-World Super-resolution | [![Stars](https://img.shields.io/github/stars/JianzeLi-114/DFOSD.svg?style=social&label=Star)](https://github.com/JianzeLi-114/DFOSD)|
|ECDP| [Efficient Conditional Diffusion Model with Probability Flow Sampling for Image Super-resolution](https://arxiv.org/abs/2404.10688) | Yutao Yuan | Supervised | AAAI 2024 | Super-resolution |  [![Stars](https://img.shields.io/github/stars/Yuan-Yutao/ECDP.svg?style=social&label=Star)](https://github.com/Yuan-Yutao/ECDP) |
|ClearSR| [ClearSR: Latent Low-Resolution Image Embeddings Help Diffusion-Based Real-World Super Resolution Models See Clearer](https://arxiv.org/abs/2410.14279) | Yuhao Wan | Supervised | Preprint' 2024 | Real-World Super-resolution ||
|SinSR| [SinSR: Diffusion-Based Image Super-Resolution in a Single Step](https://arxiv.org/abs/2311.14760) | Yufei Wang | Supervised | CVPR 2024 | Real-World Super-resolution | [![Stars](https://img.shields.io/github/stars/wyf0912/SinSR.svg?style=social&label=Star)](https://github.com/wyf0912/SinSR)|
|TextDiff| [TextDiff: Mask-Guided Residual Diffusion Models for Scene Text Image Super-Resolution](https://arxiv.org/abs/2308.06743) | Baolin Liu | Supervised | Preprint'23 | Super-resolution | [![Stars](https://img.shields.io/github/stars/Lenubolim/TextDiff.svg?style=social&label=Star)](https://github.com/Lenubolim/TextDiff) |
|PASD| [Pixel-Aware Stable Diffusion for Realistic Image Super-resolution and Personalized Stylization](https://arxiv.org/abs/2308.14469) | Tao Yang | Supervised |Preprint'23 | Super-resolution | [![Stars](https://img.shields.io/github/stars/yangxy/pasd.svg?style=social&label=Star)](https://github.com/yangxy/pasd) |
|CCSR| [Improving the Stability of Diffusion Models for Content Consistent Super-Resolution](https://arxiv.org/abs/2401.00877) | Lingchen Sun | Supervised | Preprint'23 | Super-resolution | [![Stars](https://img.shields.io/github/stars/csslc/CCSR.svg?style=social&label=Star)](https://github.com/csslc/CCSR) |
|EDiffSR| [EDiffSR: An Efficient Diffusion Probabilistic Model for Remote Sensing Image Super-Resolution](https://arxiv.org/abs/2310.19288) | Yi Xiao | Supervised | IEEE TGRS | Super-resolution | [![Stars](https://img.shields.io/github/stars/XY-boy/EDiffSR.svg?style=social&label=Star)](https://github.com/XY-boy/EDiffSR) |
|SeeSR| [SeeSR: Towards Semantics-Aware Real-World Image Super-Resolution](https://arxiv.org/pdf/2311.16518) | Rongyuan Wu | Supervised | Preprint'23 | Super-resolution | [![Stars](https://img.shields.io/github/stars/cswry/SeeSR.svg?style=social&label=Star)](https://github.com/cswry/SeeSR) |
|CoSeR| [CoSeR: Bridging Image and Language for Cognitive Super-Resolution](https://arxiv.org/abs/2311.16512) | Haoze Sun | Supervised | CVPR 2024 | Super-resolution | [![Stars](https://img.shields.io/github/stars/VINHYU/CoSeR.svg?style=social&label=Star)](https://github.com/VINHYU/CoSeR) |
|BI-DiffSR| [Binarized Diffusion Model for Image Super-Resolution](https://arxiv.org/abs/2406.05723) | Zheng Chen | Supervised | NeurIPS 2024 | Super-resolution | [![Stars](https://img.shields.io/github/stars/zhengchen1999/BI-DiffSR.svg?style=social&label=Star)](https://github.com/zhengchen1999/BI-DiffSR) |
|DoSSR| [Taming Diffusion Prior for Image Super-Resolution with Domain Shift SDEs](https://arxiv.org/abs/2409.17778) | Qinpeng Cui | Supervised | NeurIPS 2024 | Super-resolution | [![Stars](https://img.shields.io/github/stars/QinpengCui/DoSSR.svg?style=social&label=Star)](https://github.com/QinpengCui/DoSSR) |
|DaLPSR| [DaLPSR: Leverage Degradation-Aligned Language Prompt for Real-World Image Super-Resolution](https://arxiv.org/abs/2406.16477) | Aiwen Jiang | Supervised | Preprint'24 | Super-resolution | |
|FDDiff| [Frequency-Domain Refinement with Multiscale Diffusion for Super Resolution](https://arxiv.org/abs/2405.10014) | Xingjian Wang | Supervised | Preprint'24 | Super-resolution | |
|PartDiff| [PartDiff: Image Super-resolution with Partial Diffusion Models](https://arxiv.org/abs/2307.11926) | Kai Zhao | Supervised | Preprint'23 | Super-resolution | |
|DeeDSR| [DeeDSR: Towards Real-World Image Super-Resolution via Degradation-Aware Stable Diffusion](https://arxiv.org/abs/2404.00661) | Chunyang Bi | Supervised | Preprint'24 | (Real-World) Super-resolution | |
|TDDSR| [TDDSR: SINGLE-STEP DIFFUSION WITH TWO DISCRIMINATORS FOR SUPER RESOLUTION](https://arxiv.org/abs/2410.07663) | Sohwi Kim | Supervised | Preprint'24 | Super-resolution | |
|DiT-SR| [Effective Diffusion Transformer Architecture for Image Super-Resolution](https://arxiv.org/html/2409.19589) | Kun Cheng | Supervised | Preprint'24 | Super-resolution | |
|SR3+| [Denoising diffusion probabilistic models for robust image super-resolution in the wild](https://arxiv.org/abs/2302.07864) | Hshmat Sahak | Supervised | Preprint'23 | (Real-World) Super-resolution | |
|DKP| [A Dynamic Kernel Prior Model for Unsupervised Blind Image Super-Resolution](https://arxiv.org/pdf/2404.15620v2) | Zhixiong Yang | Supervised | CVPR 2024 | (Real-World) Super-resolution |  [![Stars](https://img.shields.io/github/stars/XYLGroup/DKP.svg?style=social&label=Star)](https://github.com/XYLGroup/DKP) |
|Diwa| [Waving Goodbye to Low-Res: A Diffusion-Wavelet Approach for Image Super-Resolution](https://arxiv.org/abs/2304.01994) | Brian Moser | Supervised | Preprint'23 | Super-resolution | [![Stars](https://img.shields.io/github/stars/Brian-Moser/diwa.svg?style=social&label=Star)](https://github.com/Brian-Moser/diwa) |
|YODA| [YODA: You Only Diffuse Areas. An Area-Masked Diffusion Approach For Image Super-Resolution](https://arxiv.org/pdf/2308.07977v1.pdf) | Brian B. Moser | Supervised | Preprint'23 | Super-resolution | |
|CDPMSR| [CDPMSR: Conditional Diffusion Probabilistic Models for Single Image Super-Resolution](https://arxiv.org/abs/2302.12831) | Axi Niu | Supervised | Preprint'23 | Super-resolution | |
|ACDPMSR| [ACDMSR: Accelerated Conditional Diffusion Models for Single Image Super-Resolution](https://arxiv.org/abs/2307.00781) | Axi Niu | Supervised | Preprint'23|Super-resolution| |
|ResDiff| [ResDiff: Combining cnn and diffusion model for image superresolution](https://arxiv.org/abs/2303.08714) | Shuyao Shang | Supervised | Preprint'23 | Super-resolution | |
|OSEDiff| [One-Step Effective Diffusion Network for Real-World Image Super-Resolution](https://arxiv.org/abs/2406.08177) | Rongyuan Wu | Supervised | Preprint'24 | Super-resolution | |
|DiffTSR| [Diffusion-based Blind Text Image Super-Resolution](https://arxiv.org/abs/2312.08886) | Yuzhe Zhang | Supervised | CVPR 2024 | Super-resolution |  |
|SAM-DiffSR| [SAM-DiffSR: Structure-Modulated Diffusion Model for Image Super-Resolution](https://arxiv.org/abs/2402.17133) | Chengcheng Wang | Supervised | Preprint'24 | Super-resolution |  [![Stars](https://img.shields.io/github/stars/lose4578/SAM-DiffSR.svg?style=social&label=Star)](https://github.com/lose4578/SAM-DiffSR) |
|BlindDiff| [BlindDiff: Empowering Degradation Modelling in Diffusion Models for Blind Image Super-Resolution](https://arxiv.org/abs/2403.10211) | Feng Li | Supervised | Preprint'24 | Super-resolution |  [![Stars](https://img.shields.io/github/stars/lifengcs/BlindDiff.svg?style=social&label=Star)](https://github.com/lifengcs/BlindDiff) |
|XPSR| [XPSR: Cross-modal Priors for Diffusion-based Image Super-Resolution](https://arxiv.org/abs/2403.05049) | Yunpeng Qu | Supervised | Preprint'24 | Super-resolution |  [![Stars](https://img.shields.io/github/stars/qyp2000/XPSR.svg?style=social&label=Star)](https://github.com/qyp2000/XPSR) |
|--| [Text-guided Explorable Image Super-resolution](https://arxiv.org/abs/2403.01124) | Kanchana Vaishnavi Gandikota | Zero-Shot | Preprint'24 | Super-resolution ||
|--| [Image Super-resolution Via Latent Diffusion: A Sampling-space Mixture Of Experts And Frequency-augmented Decoder Approach](https://arxiv.org/pdf/2310.12004v2.pdf) | Feng Luo | Supervised | Preprint'23 | Super-resolution | [![Stars](https://img.shields.io/github/stars/tencent-ailab/Frequency_Aug_VAE_MoESR.svg?style=social&label=Star)](https://github.com/tencent-ailab/Frequency_Aug_VAE_MoESR) |
|--| [Solving Diffusion ODEs with Optimal Boundary Conditions for Better Image Super-Resolution](https://arxiv.org/abs/2305.15357) | Yiyang Ma | Supervised | Preprint'23 | Super-resolution |  |

### Image Restoration
| Model | Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :---: | :--: | :--: |:--: | :--: |
|Palette| [Palette: Image-toimage diffusion models](https://arxiv.org/abs/2111.05826) | Chitwan Saharia | Supervised | SIGGRAPH 2022 | Multi-task Restoration | [![Stars](https://img.shields.io/github/stars/Janspiry/Palette-Image-to-Image-Diffusion-Models.svg?style=social&label=Star)](https://github.com/Janspiry/Palette-Image-to-Image-Diffusion-Models) |
|Refusion| [Refusion: Enabling large-size realistic image restoration with latent-space diffusion models](https://arxiv.org/abs/2304.08291) | Ziwei Luo | Supervised | CVPRW 2023 | Multi-task Restoration | [![Stars](https://img.shields.io/github/stars/Algolzw/image-restoration-sde.svg?style=social&label=Star)](https://github.com/Algolzw/image-restoration-sde) |
|SUPIR|[Scaling Up to Excellence: Practicing Model Scaling for Photo-Realistic Image Restoration In the Wild](https://arxiv.org/abs/2401.13627) | Fanghua Yu | Supervised | CVPR 2024 | Image Restoration | [![Stars](https://img.shields.io/github/stars/Fanghua-Yu/SUPIR.svg?style=social&label=Star)](https://github.com/Fanghua-Yu/SUPIR) |
|Weather-Diff| [Restoring vision in adverse weather conditions with patch-based denoising diffusion models](https://arxiv.org/abs/2207.14626) | Ozan Özdenizci | Supervised | TPAMI2022 | Multi-task Restoration | [![Stars](https://img.shields.io/github/stars/IGITUGraz/WeatherDiffusion.svg?style=social&label=Star)](https://github.com/IGITUGraz/WeatherDiffusion) |
|IR-SDE| [Image Restoration with Mean-Reverting Stochastic Differential Equations](https://arxiv.org/abs/2301.11699) | Ziwei Luo | Supervised | ICML 2023 | Multi-task Restoration | [![Stars](https://img.shields.io/github/stars/Algolzw/image-restoration-sde.svg?style=social&label=Star)](https://github.com/Algolzw/image-restoration-sde) |
|DAVI| [Diffusion Prior-Based Amortized Variational Inference for Noisy Inverse Problems](https://www.arxiv.org/abs/2407.16125) | Sojin Lee | Supervised | ECCV 2024 | Multi-task Restoration | [![Stars](https://img.shields.io/github/stars/mlvlab/DAVI.svg?style=social&label=Star)](https://github.com/mlvlab/DAVI) |
|SUD^2| [SUD ˆ2: Supervision by denoising diffusion models for image reconstruction](https://arxiv.org/abs/2303.09642) | Matthew A. Chan | Supervised | Preprint'23 | Multi-task Restoration | |
|InDI| [Inversion by direct iteration: An alternative to denoising diffusion for image restoration](https://arxiv.org/abs/2303.11435) | Mauricio Delbracio | Supervised | Preprint'22 | Multi-task Restoration | |
|AdaptBIR| [AdaptBIR: Adaptive Blind Image Restoration with latent diffusion prior for higher fidelity](https://www.sciencedirect.com/science/article/pii/S0031320324004102) | Yingqi Liu | Supervised | Pattern Recognition 24 | Image Restoration ||
|ILVR|[ILVR: Conditioning method for denoising diffusion probabilistic models](https://openaccess.thecvf.com/content/ICCV2021/papers/Choi_ILVR_Conditioning_Method_for_Denoising_Diffusion_Probabilistic_Models_ICCV_2021_paper.pdf) | Jooyoung Choi | Zero-Shot | ICCV2021 | Image Restoration | [![Stars](https://img.shields.io/github/stars/jychoi118/ilvr_adm.svg?style=social&label=Star)](https://github.com/jychoi118/ilvr_adm) |
|CCDF|[Come-closer-diffusefaster: Accelerating conditional diffusion models for inverse problems through stochastic contraction](https://openaccess.thecvf.com/content/CVPR2022/papers/Chung_Come-Closer-Diffuse-Faster_Accelerating_Conditional_Diffusion_Models_for_Inverse_Problems_Through_Stochastic_CVPR_2022_paper.pdf) | Hyungjin Chung | Zero-Shot | CVPR2022 | Multi-task Restoration | |
|SNIPS|[SNIPS: Solving noisy inverse problems stochastically](https://arxiv.org/abs/2105.14951) | Bahjat Kawa | Zero-Shot | NeurIPS 2021 | Multi-task Restoration | [![Stars](https://img.shields.io/github/stars/bahjat-kawar/snips_torch.svg?style=social&label=Star)](https://github.com/bahjat-kawar/snips_torch)|
|DDRM|[Denoising diffusion restoration models](https://arxiv.org/abs/2201.11793) | Bahjat Kawar | Zero-Shot | ICLR2022 | Multi-task Restoration | [![Stars](https://img.shields.io/github/stars/bahjat-kawar/ddrm.svg?style=social&label=Star)](https://github.com/bahjat-kawar/ddrm) |
|DDNM|[Zero-Shot image restoration using denoising diffusion null-space model](https://arxiv.org/abs/2212.00490) | Yinhuai Wang | Zero-Shot | ICLR2023 | Multi-task Restoration | [![Stars](https://img.shields.io/github/stars/wyhuai/DDNM.svg?style=social&label=Star)](https://github.com/wyhuai/DDNM) |
|DPS|[Diffusion Posterior Sampling for General Noisy Inverse Problems](https://arxiv.org/abs/2209.14687) | Hyungjin Chung | Zero-Shot | ICLR 2023 | Multi-task Restoration |  [![Stars](https://img.shields.io/github/stars/DPS2022/diffusion-posterior-sampling.svg?style=social&label=Star)](https://github.com/DPS2022/diffusion-posterior-sampling) |
|DiffPIR|[Denoising diffusion models for plug-and-play image restoration](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/papers/Zhu_Denoising_Diffusion_Models_for_Plug-and-Play_Image_Restoration_CVPRW_2023_paper.pdf) | Yuanzhi Zhu | Zero-Shot | CVPR 2023 | Multi-task Restoration | [![Stars](https://img.shields.io/github/stars/yuanzhi-zhu/DiffPIR.svg?style=social&label=Star)](https://github.com/yuanzhi-zhu/DiffPIR) |
|DPPS| [Diffusion Posterior Proximal Sampling for Image Restoration](https://arxiv.org/abs/2402.16907) | Hongjie Wu | Zero-Shot | ACMM 2024 Oral | Multi-task Restoration | [![Stars](https://img.shields.io/github/stars/74587887/DPPS_code.svg?style=social&label=Star)](https://github.com/74587887/DPPS_code) |
|DiracDiffusion|[DiracDiffusion: Denoising and incremental reconstruction with assured data-consistency](https://arxiv.org/abs/2303.14353) | Zalan Fabian | Zero-Shot | Preprint' 23 | Multi-task Restoration | |
|IIGDM|[Pseudoinverse-guided diffusion models for inverse problems](https://openreview.net/forum?id=9_gsMA8MRKQ) | Jiaming Song | Zero-Shot | ICLR 2023 | Multi-task Restoration | |
|GDP| [Generative diffusion prior for unified image restoration and enhancement](https://openaccess.thecvf.com/content/CVPR2023/papers/Fei_Generative_Diffusion_Prior_for_Unified_Image_Restoration_and_Enhancement_CVPR_2023_paper.pdf) | Ben Fei | Zero-Shot | CVPR2023 | Multi-task Restoration | [![Stars](https://img.shields.io/github/stars/Fayeben/GenerativeDiffusionPrior.svg?style=social&label=Star)](https://github.com/Fayeben/GenerativeDiffusionPrior) |
|RED-Diff|[A variational perspective on solving inverse problems with diffusion models](https://arxiv.org/abs/2305.04391) | Morteza Mardani | Zero-Shot | PrePrint'23 |Multi-task Restoration| [![Stars](https://img.shields.io/github/stars/NVlabs/RED-diff.svg?style=social&label=Star)](https://github.com/NVlabs/RED-diff) |
|DeqIR|[Deep Equilibrium Diffusion Restoration with Parallel Sampling](https://arxiv.org/abs/2311.11600) | Jiezhang Cao | Zero-Shot | CVPR 2024 |Multi-task Restoration| [![Stars](https://img.shields.io/github/stars/caojiezhang/DeqIR.svg?style=social&label=Star)](https://github.com/caojiezhang/DeqIR) |
|SaFaRI|[Spatial-and-Frequency-aware Restoration method for Images based on Diffusion Models](https://arxiv.org/abs/2401.17629) | Kyungsung Lee | Zero-Shot | PrePrint'24 |Multi-task Restoration| |
|OmniSSR|[OmniSSR: Zero-Shot Omnidirectional Image Super-Resolution using Stable Diffusion Model](https://arxiv.org/abs/2404.10312) | Runyi Li | Zero-Shot | Preprint'24 | Blind Restoration | |
|DriftRec|[DriftRec: Adapting diffusion models to blind image restoration tasks](https://arxiv.org/abs/2211.06757) | Simon Welker | Supervised | Preprint'22 | Blind Restoration | |
|DR2|[DR2: Diffusion-based robust degradation remover for blind face restoration](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_DR2_Diffusion-Based_Robust_Degradation_Remover_for_Blind_Face_Restoration_CVPR_2023_paper.pdf) | Zhixin Wang | Zero-Shot | CVPR2023 | Blind Face Restoration | [![Stars](https://img.shields.io/github/stars/Kaldwin0106/DR2_Drgradation_Remover.svg?style=social&label=Star)](https://github.com/Kaldwin0106/DR2_Drgradation_Remover) |
|PFStorer|[PFStorer: Personalized Face Restoration and Super-Resolution](https://arxiv.org/abs/2403.08436) | Tuomas Varanka | Supervised | Preprint'24 | Blind Face Restoration | |
|DiffBFR|[DiffBFR: Bootstrapping diffusion model towards blind face restoration](https://arxiv.org/abs/2305.04517) | Xinmin Qiu | Supervised | Preprint'23 | Blind Face Restoration | |
|DifFace|[DifFace: Blind face restoration with diffused error contraction](https://arxiv.org/abs/2212.06512) | Zongsheng Yu | Zero-Shot | PrePrint'23 | Blind Restoration | [![Stars](https://img.shields.io/github/stars/zsyOAOA/DifFace.svg?style=social&label=Star)](https://github.com/zsyOAOA/DifFace) |
|--|[Towards Unsupervised Blind Face Restoration using Diffusion Prior](https://arxiv.org/abs/2410.04618) | Tianshu Kuai | Supervised | PrePrint'24 | Blind Restoration ||
|GibbsDDRM|[GibbsDDRM: A partially collapsed gibbs sampler for solving blind inverse problems with denoising diffusion restoration](https://arxiv.org/abs/2301.12686) | Naoki Murata | Zero-Shot | ICML 2023 | Blind Restoration | [![Stars](https://img.shields.io/github/stars/sony/gibbsddrm.svg?style=social&label=Star)](https://github.com/sony/gibbsddrm) |
|ADIR|[ADIR: Adaptive diffusion for image reconstruction](https://arxiv.org/abs/2212.03221) | Shady Abu-Hussein | Zero-Shot | PrePrint'22 | Blind Restoration | |
|PSLD|[Solving Linear Inverse Problems Provably via Posterior Sampling with Latent Diffusion Models](https://arxiv.org/abs/2307.00619) | Litu Rout | Zero-Shot | PrePrint'23 | Image Restoration | [![Stars](https://img.shields.io/github/stars/LituRout/PSLD.svg?style=social&label=Star)](https://github.com/LituRout/PSLD) |
|IDM|[Towards Authentic Face Restoration with Iterative Diffusion Models and Beyond](https://arxiv.org/abs/2307.08996) | Yang Zhao| Supervised | ICCV 2023 | Face Restoration ||
|DiffBIR|[DiffBIR: Towards Blind Image Restoration with Generative Diffusion Prior](https://arxiv.org/abs/2308.15070) | Xinqi Lin | Supervised | Preprint' 2023 | Image Restoration |[![Stars](https://img.shields.io/github/stars/XPixelGroup/DiffBIR.svg?style=social&label=Star)](https://github.com/XPixelGroup/DiffBIR)|
|RDDM|[Residual Denoising Diffusion Models](https://arxiv.org/abs/2308.13712) | Jiawei Liu | Supervised | Preprint' 2023 | Image Restoration |[![Stars](https://img.shields.io/github/stars/nachifur/RDDM.svg?style=social&label=Star)](https://github.com/nachifur/RDDM)|
|C2F-DFT|[Learning A Coarse-to-Fine Diffusion Transformer for Image Restoration](https://arxiv.org/abs/2308.08730) | Liyan Wang | Supervised | Preprint' 2023 | Image Restoration |[![Stars](https://img.shields.io/github/stars/wlydlut/c2f-dft.svg?style=social&label=Star)](https://github.com/wlydlut/c2f-dft)|
|Diff-Plugin|[Diff-Plugin: Revitalizing Details for Diffusion-based Low-level tasks](https://arxiv.org/abs/2403.00644) | Yuhao Liu | Supervised | CVPR 2024 | All-in-one Restoration | [![Stars](https://img.shields.io/github/stars/yuhaoliu7456/Diff-Plugin.svg?style=social&label=Star)](https://github.com/yuhaoliu7456/Diff-Plugin/) |
|DDPG|[Image Restoration by Denoising Diffusion Models with Iteratively Preconditioned Guidance](https://arxiv.org/abs/2312.16519) | Tomer Garber | Zero-Shot| CVPR 2024 | Image Restoration | [![Stars](https://img.shields.io/github/stars/tirer-lab/DDPG.svg?style=social&label=Star)](https://github.com/tirer-lab/DDPG) |
|DiffUIR|[Selective Hourglass Mapping for Universal Image Restoration Based on Diffusion Model](https://arxiv.org/pdf/2403.11157) | Dian Zheng | Supervised | CVPR 2024 | Image Restoration | [![Stars](https://img.shields.io/github/stars/iSEE-Laboratory/DiffUIR.svg?style=social&label=Star)](https://github.com/iSEE-Laboratory/DiffUIR) |
|DMPlug|[DMPlug: A Plug-in Method for Solving Inverse Problems with Diffusion Models](https://arxiv.org/abs/2405.16749) | Hengkang Wang | Supervised | NeurIPS 2024 | Image Restoration | [![Stars](https://img.shields.io/github/stars/sun-umn/DMPlug.svg?style=social&label=Star)](https://github.com/sun-umn/DMPlug) |
|MPerceiver|[Multimodal Prompt Perceiver: Empower Adaptiveness, Generalizability and Fidelity for All-in-One Image Restoration](https://arxiv.org/abs/2312.02918) | Yuang Ai | Supervised | CVPR 2024 | All-in-one Restoration | |
|MCGdiff|[Monte Carlo guided Diffusion for Bayesian linear inverse problems](https://arxiv.org/abs/2308.07983) | Gabriel Cardoso | Zero-Shot | Preprint' 2023 | Image Restoration ||
|PromptFix|[PromptFix: You Prompt and We Fix the Photo](https://arxiv.org/html/2405.16785v1) | Yongsheng Yu | Supervised | Preprint' 2024 | Image Restoration | [![Stars](https://img.shields.io/github/stars/yeates/PromptFix.svg?style=social&label=Star)](https://github.com/yeates/PromptFix)|
|AutoDIR|[AutoDIR: Automatic All-in-One Image Restoration with Latent Diffusion](https://arxiv.org/abs/2310.10123) | Yitong Jiang | Supervised | Preprint' 2023 | Image Restoration ||
|DiffLoss|[Using diffusion model as constraint: Empower Image Restoration Network Training with Diffusion Model](https://arxiv.org/abs/2406.19030) | Jiangtong Tan | Supervised | Preprint' 2024 | Image Restoration ||
|ZeroAIR|[Exploiting Diffusion Priors for All-in-One Image Restoration](https://arxiv.org/abs/2312.02197) | Yuanbiao Gou | Supervised | Preprint' 2023 | Image Restoration ||
|FastDiffusionEM|[Fast Diffusion EM: a diffusion model for blind inverse problems with application to deconvolution](https://arxiv.org/abs/2309.00287) | Charles Laroche | Supervised | WACV 2024 | Blind Image Restoration ||
|P2L|[PROMPT-TUNING LATENT DIFFUSION MODELS FOR INVERSE PROBLEMS](https://arxiv.org/pdf/2310.01110v1.pdf) | Hyungjin Chung | Supervised | Preprint' 2023 | Image Restoration ||
|JCDM|[Joint Conditional Diffusion Model for Image Restoration with Mixed Degradations](https://arxiv.org/abs/2404.07770) | Yufeng Yue | Supervised | Preprint' 2024 | Image Restoration ||
|DACLIP-IR|[Photo-Realistic Image Restoration in the Wild with Controlled Vision-Language Models](https://arxiv.org/pdf/2404.09732) | Ziwei Luo | Supervised | Preprint' 2024 | Image Restoration |[![Stars](https://img.shields.io/github/stars/Algolzw/daclip-uir.svg?style=social&label=Star)](https://github.com/Algolzw/daclip-uir)|
|MoE-DiffIR|[MoE-DiffIR: Task-customized Diffusion Priors for Universal Compressed Image Restoration](https://arxiv.org/abs/2407.10833) | Yulin Ren | Supervised | ECCV 2024 | Image Restoration |[![Stars](https://img.shields.io/github/stars/renyulin-f/MoE-DiffIR.svg?style=social&label=Star)](https://github.com/renyulin-f/MoE-DiffIR)|
|Noise-DA|[Denoising as Adaptation: Noise-Space Domain Adaptation for Image Restoration](https://arxiv.org/abs/2406.18516) | Kang Liao | Supervised | Preprint' 2024 | Image Restoration |[![Stars](https://img.shields.io/github/stars/KangLiao929/Noise-DA.svg?style=social&label=Star)](https://github.com/KangLiao929/Noise-DA/)|
|T^3^-DiffWeather|[Teaching Tailored to Talent: Adverse Weather Restoration via Prompt Pool and Depth-Anything Constraint](https://arxiv.org/abs/2409.15739) | Sixiang Chen | Supervised | ECCV 2024 | Adverse Weather Restoration |[![Stars](https://img.shields.io/github/stars/Ephemeral182/ECCV24_T3-DiffWeather.svg?style=social&label=Star)](https://github.com/Ephemeral182/ECCV24_T3-DiffWeather)|
|VSPBFR|[Visual Style Prompt Learning Using Diffusion Models for Blind Face Restoration](https://arxiv.org/abs/2412.21042) | Wanglong Lu | Supervised | Preprint' 24 | Blind Face Restoration |[![Stars](https://img.shields.io/github/stars/LonglongaaaGo/VSPBFR.svg?style=social&label=Star)](https://github.com/LonglongaaaGo/VSPBFR)|
|ReviveDiff|[ReviveDiff: A Universal Diffusion Model for Restoring Images in Adverse Weather Conditions](https://arxiv.org/abs/2409.18932) | Wenfeng Huang | Supervised | Preprint' 24 | Adverse Weather Restoration ||
|GenDeg|[GenDeg: Diffusion-Based Degradation Synthesis for Generalizable All-in-One Image Restoration](https://arxiv.org/abs/2411.17687) | Sudarshan Rajagopalan | Supervised | Preprint' 24 | All in one Image Restoration ||
|Diff-Restorer|[Diff-Restorer: Unleashing Visual Prompts for Diffusion-based Universal Image Restoration](https://arxiv.org/abs/2407.03636) | Yuhong Zhang | Supervised | Preprint' 24 | Image Restoration ||
|Res-Captioner|[Beyond Pixels: Text Enhances Generalization in Real-World Image Restoration](https://arxiv.org/abs/2412.00878) | Haoze Sun | Supervised | Preprint' 2024 | Image Restoration ||
|--|[Diffusion Posterior Proximal Sampling for Image Restoration](https://arxiv.org/abs/2402.16907) | Hongjie Wu | Zero-Shot | Preprint'24 | Multi-task Restoration | |
|--|[Multiscale Structure Guided Diffusion for Image Deblurring](https://arxiv.org/abs/2212.01789) | Mengwei Ren | Supervised | Preprint'22 | Blind Restoration | |
|--|[Synthesizing realistic image restoration training pairs: A diffusion approach](https://arxiv.org/abs/2303.06994) | Tao Yang | Supervised | Preprint'22 | Blind Restoration | |

### Image Inpainting
|Model| Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :---: | :--: | :--: |:--: | :--: |
|RePaint| [RePaint: Inpainting using denoising diffusion probabilistic models](https://openaccess.thecvf.com/content/CVPR2022/papers/Lugmayr_RePaint_Inpainting_Using_Denoising_Diffusion_Probabilistic_Models_CVPR_2022_paper.pdf) | Andreas Lugmayr  | Zero-Shot | CVPR2022 | Image Inpainting | [![Stars](https://img.shields.io/github/stars/andreas128/RePaint.svg?style=social&label=Star)](https://github.com/andreas128/RePaint) | 
|CoPaint| [Towards coherent image inpainting using denoising diffusion implicit models](https://arxiv.org/abs/2304.03322) | Guanhua Zhang | Zero-Shot | PrePrint'23 | Image Inpainting | [![Stars](https://img.shields.io/github/stars/UCSB-NLP-Chang/CoPaint.svg?style=social&label=Star)](https://github.com/UCSB-NLP-Chang/CoPaint) |
|PVA| [Personalized Face Inpainting with Diffusion Models by Parallel Visual Attention](https://arxiv.org/abs/2312.03556) | Jianjin Xu | Zero-Shot | PrePrint'23 | Image Inpainting | |

### Image Shadow Removal 
| Model| Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :---: | :--: | :--: |:--: | :--: |
| BCDiff | [Boundary-Aware Divide and Conquer: A Diffusion-based Solution for Unsupervised Shadow Removal](https://openaccess.thecvf.com/content/ICCV2023/papers/Guo_Boundary-Aware_Divide_and_Conquer_A_Diffusion-Based_Solution_for_Unsupervised_Shadow_ICCV_2023_paper.pdf) | Lanqing Guo | Unsupervised | ICCV 2023 | Image Shadow Removal | | 
|ShadowDiffusion| [Shadowdiffusion: When degradation prior meets diffusion model for shadow removal](https://openaccess.thecvf.com/content/CVPR2023/papers/Guo_ShadowDiffusion_When_Degradation_Prior_Meets_Diffusion_Model_for_Shadow_Removal_CVPR_2023_paper.pdf) | Lanqing Guo | Supervised | CVPR2023 | Image Shadow Removal |[![Stars](https://img.shields.io/github/stars/GuoLanqing/ShadowDiffusion.svg?style=social&label=Star)](https://github.com/GuoLanqing/ShadowDiffusion) |
|DeS3| [DeS3: Attention-driven Self and Soft Shadow Removal using ViT Similarity and Color Convergence](https://arxiv.org/abs/2211.08089) | Yeying Jin | Supervised | AAAI'24 | Image Shadow Removal |[![Stars](https://img.shields.io/github/stars/jinyeying/DeS3_Deshadow.svg?style=social&label=Star)](https://github.com/jinyeying/DeS3_Deshadow) |
|Diff-Shadow| [Diff-Shadow: Global-guided Diffusion Model for Shadow Removal](https://www.arxiv.org/abs/2407.16214) | Jinting Luo | Supervised | Preprint'24 | Image Shadow Removal | |
|LFG-Diffusion| [Latent Feature-Guided Diffusion Models for Shadow Removal](https://openaccess.thecvf.com/content/WACV2024/html/Mei_Latent_Feature-Guided_Diffusion_Models_for_Shadow_Removal_WACV_2024_paper.html) | Kangfu Mei | Supervised | WACV 2024 | Image Shadow Removal | |
|Deshadow-Anything| [Deshadow-Anything: When Segment Anything Model Meets Zero-Shot shadow removal](https://arxiv.org/pdf/2309.11715v1.pdf) | Xiao Feng Zhang | Supervised | Preprint'23 | Image Shadow Removal | |

### Image Denoising
| Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :--: | :--: |:--: | :--: |
| [Diffusion model for generative image denoising](https://arxiv.org/abs/2302.02398) | Yutong Xie | Supervised | Preprint'23 | Image Denoising | |
|[Score-Based Diffusion Models as Principled Priors for Inverse Imaging](https://arxiv.org/abs/2304.11751) | Berthy T. Feng | Zero-Shot | ICCV 2023 | Image Denoising, Image Deblurring | [![Stars](https://img.shields.io/github/stars/berthyf96/score_prior.svg?style=social&label=Star)](https://github.com/berthyf96/score_prior) |
| [Real-World Denoising via Diffusion Model](https://arxiv.org/abs/2305.04457) | Cheng Yang | Supervised | PrePrint'23 | Image Denoising| |

### Image Dehazing
|Model|Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :---: | :--: | :--: |:--: | :--: |
|HazeDDPM|[High-quality Image Dehazing with Diffusion Model](https://arxiv.org/abs/2308.11949) | Hu Yu | Supervised | Preprint'23 | Image Dehazing | |
|--|[Frequency Compensated Diffusion Model for Real-scene Dehazing](https://arxiv.org/abs/2308.10510) | Jing Wang | Supervised | Preprint'23 | Image Dehazing | |

### Image Deblurring
| Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :--: | :--: |:--: | :--: |
| [Deblurring via stochastic refinement](https://openaccess.thecvf.com/content/CVPR2022/papers/Whang_Deblurring_via_Stochastic_Refinement_CVPR_2022_paper.pdf) | Jay Whang| Supervised | CVPR2022 | Image Deblurring | |
|[Score-Based Diffusion Models as Principled Priors for Inverse Imaging](https://arxiv.org/abs/2304.11751) | Berthy T. Feng | Zero-Shot | ICCV 2023 | Image Denoising, Image Deblurring | [![Stars](https://img.shields.io/github/stars/berthyf96/score_prior.svg?style=social&label=Star)](https://github.com/berthyf96/score_prior) |
|BlindDPS:[Parallel diffusion models of operator and image for blind inverse problems](https://openaccess.thecvf.com/content/CVPR2023/papers/Chung_Parallel_Diffusion_Models_of_Operator_and_Image_for_Blind_Inverse_CVPR_2023_paper.pdf) | Hyungjin Chung | Zero-Shot | CVPR2023 | Blind Deblurring | [![Stars](https://img.shields.io/github/stars/BlindDPS/blind-dps.svg?style=social&label=Star)](https://github.com/BlindDPS/blind-dps) |
|HI-Diff:[Hierarchical Integration Diffusion Model for Realistic Image Deblurring](https://arxiv.org/abs/2305.12966) | Zheng Chen | Supervised | Prepreint'23 | Image Deblurring |[![Stars](https://img.shields.io/github/stars/zhengchen1999/HI-Diff.svg?style=social&label=Star)](https://github.com/zhengchen1999/HI-Diff)|
|Swintormer:[Efficient Image Deblurring Networks based on Diffusion Models](https://arxiv.org/abs/2401.05907) | Kang Chen | Supervised | Prepreint'24 | Image Deblurring |[![Stars](https://img.shields.io/github/stars/bnm6900030/swintormer.svg?style=social&label=Star)](https://github.com/bnm6900030/swintormer)|

### Medical Restoration (MRI,CT)
|Model| Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :---: | :--: | :--: |:--: | :--: |
|MCG| [Improving diffusion models for inverse problems using manifold constraints](https://arxiv.org/abs/2206.00941) | Hyungjin Chung | Zero-Shot | NeurIPS 2022 | CT Reconstruction | [![Stars](https://img.shields.io/github/stars/HJ-harry/MCG_diffusion.svg?style=social&label=Star)](https://github.com/HJ-harry/MCG_diffusion) |
|--| [Solving inverse problems in medical imaging with score-based generative models](https://arxiv.org/abs/2111.08005) | Yang Song | Zero-Shot | ICLR 2022 | CT Reconstruction | |
|AdaDiff|[Adaptive diffusion priors for accelerated mri reconstruction](https://arxiv.org/abs/2207.05876) | Alper Güngör | Supervised | Preprint'23 | MRI Reconstruction | [![Stars](https://img.shields.io/github/stars/icon-lab/AdaDiff.svg?style=social&label=Star)](https://github.com/icon-lab/AdaDiff) |
|HFS-SDE|[High-Frequency Space Diffusion Models for Accelerated MRI](https://arxiv.org/abs/2208.05481) | Chentao Cao | Supervised | Preprint'22 | MRI Reconstruction | |
|SWORD|[Stage-by-stage Wavelet Optimization Refinement Diffusion Model for Sparse-View CT Reconstruction](https://arxiv.org/abs/2308.15942) | Kai Xu | Supervised | Preprint'23 | MRI Reconstruction | [![Stars](https://img.shields.io/github/stars/yqx7150/sword.svg?style=social&label=Star)](https://github.com/yqx7150/sword) |
|FDB|[Learning Fourier-Constrained Diffusion Bridges for MRI Reconstruction](https://arxiv.org/pdf/2308.01096.pdf) | Muhammad U. Mirza | Supervised | Preprint'23 | MRI Reconstruction | [![Stars](https://img.shields.io/github/stars/icon-lab/FDB.svg?style=social&label=Star)](https://github.com/icon-lab/FDB) |

### Low-Light Enchancement
|Model|Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :---: | :--: | :--: |:--: | :--: |
|PyDiff|[Pyramid Diffusion Models For Low-light Image Enhancement](https://arxiv.org/abs/2305.10028) | Dewei Zhou | Supervised | Preprint'23 | Low-light Enhancemnent | [![Stars](https://img.shields.io/github/stars/limuloo/PyDIff.svg?style=social&label=Star)](https://github.com/limuloo/PyDIff) |
|LightenDiffusion|[LightenDiffusion: Unsupervised Low-Light Image Enhancement with Latent-Retinex Diffusion Models](https://arxiv.org/abs/2407.08939) | Hai Jiang | Supervised | ECCV 2024 | Low-light Enhancemnent |  [![Stars](https://img.shields.io/github/stars/JianghaiSCU/LightenDiffusion.svg?style=social&label=Star)](https://github.com/JianghaiSCU/LightenDiffusion) |
|DiffLL|[Lowlight image enhancement with wavelet-based diffusion models](https://arxiv.org/abs/2306.00306) | Hai Jiang | Supervised | Preprint'23 | Low-light Enhancemnent | [![Stars](https://img.shields.io/github/stars/JianghaiSCU/Diffusion-Low-Light.svg?style=social&label=Star)](https://github.com/JianghaiSCU/Diffusion-Low-Light) |
|ExploreDiffusion|[ExposureDiffusion: Learning to Expose for Low-light Image Enhancement](https://arxiv.org/abs/2307.07710) | Yufei Wang | Supervised | ICCV 2023 | Low-light Enhancemnent |  [![Stars](https://img.shields.io/github/stars/wyf0912/ExposureDiffusion.svg?style=social&label=Star)](https://github.com/wyf0912/ExposureDiffusion) |
|Diff-Retinex|[Rethinking Low-light Image Enhancement with A Generative Diffusion Model](https://arxiv.org/abs/2308.13164) | Xunpeng Yi | Supervised | ICCV 2023 | Low-light Enhancemnent | |
|CLE Diffusion|[CLE Diffusion: Controllable Light Enhancement Diffusion Model](https://arxiv.org/abs/2308.06725) | Yuyang Yin | Supervised | Preprint'23 | Low-light Enhancemnent |[![Stars](https://img.shields.io/github/stars/YuyangYin/CLEDiffusion.svg?style=social&label=Star)](https://github.com/YuyangYin/CLEDiffusion) |
|DiffLLE|[DiffLLE: Diffusion-guided Domain Calibration for Unsupervised Low-light Image Enhancement](https://arxiv.org/abs/2308.09279) | Shuzhou Yang | Supervised | Preprint'23 | Low-light Enhancemnent | |
|LLDiffusion|[LLDiffusion: Learning Degradation Representations in Diffusion Models for Low-Light Image Enhancement](https://arxiv.org/abs/2307.14659) | Tao Wang | Supervised | Preprint'23 | Low-light Enhancemnent |  [![Stars](https://img.shields.io/github/stars/TaoWangzj/LLDiffusion.svg?style=social&label=Star)](https://github.com/TaoWangzj/LLDiffusion) |
|Entropy-SDE|[Equipping Diffusion Models with Differentiable Spatial Entropy for Low-Light Image Enhancement](https://arxiv.org/abs/2404.09735) | Wenyi Lian | Supervised | CVPRW 2024 | Low-light Enhancemnent |  [![Stars](https://img.shields.io/github/stars/shermanlian/spatial-entropy-loss.svg?style=social&label=Star)](https://github.com/shermanlian/spatial-entropy-loss) |

### Other tasks
|Model|Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :---: | :--: | :--: |:--: | :--: |
|RainDiffusion|[RainDiffusion: When Unsupervised Learning Meets Diffusion Models for Real-world Image Deraining](https://arxiv.org/abs/2301.09430) | Mingqiang Wei | Supervised | Preprint'23 | Image Deraining| |
|GaussianSR|[GaussianSR: 3D Gaussian Super-Resolution with 2D Diffusion Priors](https://arxiv.org/abs/2406.10111) | Xiqian Yu | Supervised | Preprint'24 | 3D Gaussian Super-resolution| |
|DIffSteISR|[DIffSteISR: Harnessing Diffusion Prior for Superior Real-world Stereo Image Super-Resolution](https://arxiv.org/abs/2408.07516) | Yuanbo Zhou | Supervised | Preprint'24 | Stereo Image Super-Resolution | |
|DiffGAR|[DiffGAR: Model-agnostic restoration from generative artifacts using image-to-image diffusion models](https://arxiv.org/abs/2210.08573) | Yueqin Yin | Supervised | Preprint'22 | Generative Artifacts Removal | |
|HSR-Diff|[HSR-Diff: Hyperspectral Image Super-Resolution via Conditional Diffusion Models](https://arxiv.org/abs/2306.12085) | Chanyue Wu | Supervised | Preprint'23 | hyperspectral images super-resolution | |
|DMGASR|[Enhancing Hyperspectral Images via Diffusion Model and Group-Autoencoder Super-resolution Network](https://arxiv.org/abs/2402.17285) | Zhaoyang Wang | Supervised | Preprint'24 | hyperspectral images super-resolution | |
|DRUS|[Ultrasound Image Reconstruction with Denoising Diffusion Restoration Models](https://arxiv.org/abs/2307.15990) | Yuxin Zhang | Zero-Shot | Preprint'23 | Ultrasound Image Reconstruction | [![Stars](https://img.shields.io/github/stars/yuxin-zhang-jasmine/drus-v1.svg?style=social&label=Star)](https://github.com/yuxin-zhang-jasmine/drus-v1) |
|PromptRR|[PromptRR: Diffusion Models as Prompt Generators for Single Image Reflection Removal](https://arxiv.org/abs/2402.02374) | Tao Wang | Supervised | Preprint'24 | Image Reflection Removal | |
|--| [Jpeg artifact correction using denoising diffusion restoration models](https://arxiv.org/abs/2209.11888) | Bahjat Kawar| Zero-Shot | NeurIPS 2022 | JPEG Artifacts Removal | [![Stars](https://img.shields.io/github/stars/bahjat-kawar/ddrm-jpeg.svg?style=social&label=Star)](https://github.com/bahjat-kawar/ddrm-jpeg) |
|--|[Improved Diffusion-based Image Colorization via Piggybacked Models](https://arxiv.org/abs/2304.11105) | Hanyuan Liu | Zero-Shot | PrePrint'23 | Image Colorization | [![Stars](https://img.shields.io/github/stars/hyliu/piggyback-color.svg?style=social&label=Star)](https://github.com/hyliu/piggyback-color) |

### Benchmark Datasets
|Dataset|Task|Usage|Year|
|:----:|:----:|:----:|:----:|
|[DIV2K](https://data.vision.ee.ethz.ch/cvl/DIV2K)|Image Super-resolution|Training,Testing|2017|
|[Flickr2K](https://www.kaggle.com/datasets/daehoyang/flickr2k)|Image Super-resolution|Training|2017|
|[Set5](https://people.rennes.inria.fr/Aline.Roumy//publi/12bmvc_Bevilacqua_lowComplexitySR.pdf)|Image Super-resolution|Testing|2012|
|[Set14](https://link.springer.com/chapter/10.1007/978-3-642-27413-8_47)|Image Super-resolution|Testing|2012|
|[BSD100](https://ieeexplore.ieee.org/document/937655)|Image Super-resolution|Testing|2012|
|[Manga109](https://arxiv.org/abs/1510.04389)|Image Super-resolution|Testing|2015|
|[Urban100](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Huang_Single_Image_Super-Resolution_2015_CVPR_paper.pdf)|Image Super-resolution|Testing|2015|
|[OST300](https://github.com/ternaus/lsun_2017)|Image Super-resolution|Testing|2018|
|[DIV8K](https://ieeexplore.ieee.org/document/9021973)|Image Super-resolution|Training,Testing|2019|
|[RealSR](https://arxiv.org/abs/1904.00523)|Image Super-resolution|Training,Testing|2019|
|[DRealSR](https://arxiv.org/abs/2008.01928)|Image Super-resolution|Training,Testing|2020|
|[GoPro](https://openaccess.thecvf.com/content_cvpr_2017/papers/Nah_Deep_Multi-Scale_Convolutional_CVPR_2017_paper.pdf)|Image Deblurring|Training,Testing|2017|
|[HIDE](https://openaccess.thecvf.com/content_ICCV_2019/papers/Shen_Human-Aware_Motion_Deblurring_ICCV_2019_paper.pdf)|Image Deblurring|Training,Testing|2019|
|[RealBlur](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700188.pdf)|Image Deblurring|Training,Testing|2020|
|[Kodak](https://r0k.us/graphics/kodak/)|Image Denoising|Testing|1999|
|[CBSD68](https://ieeexplore.ieee.org/document/937655)|Image Denoising|Testing|2001|
|[McMaster](https://www4.comp.polyu.edu.hk/~cslzhang/paper/NAT_CDM_JEI.pdf)|Image Denoising|Testing|2011|
|[ImageNet](https://arxiv.org/abs/1409.0575)|Image Classification|Training,Testing|2010|
|[ImageNet1k](https://arxiv.org/abs/1409.0575)|Image Classification|Testing|2020|
|[LSUN](https://arxiv.org/abs/1506.03365)|Image Classification|Training,Testing|2015|
|[Places365](https://arxiv.org/abs/1909.02410)|Image Classification|Training,Testing|2019|
|[LFW](http://vis-www.cs.umass.edu/lfw/lfw.pdf)|Face Generation|Training|2008|
|[FFHQ](https://openaccess.thecvf.com/content_CVPR_2019/papers/Karras_A_Style-Based_Generator_Architecture_for_Generative_Adversarial_Networks_CVPR_2019_paper.pdf)|Face Generation|Training|2019|
|[Celeba-HQ](https://arxiv.org/abs/1710.10196)|Face Generation|Training|2018|
|[AFHQ](https://openaccess.thecvf.com/content_CVPR_2020/papers/Choi_StarGAN_v2_Diverse_Image_Synthesis_for_Multiple_Domains_CVPR_2020_paper.pdf)|Face Generation|Training|2020|
|[CelebA](https://openaccess.thecvf.com/content_iccv_2015/papers/Liu_Deep_Learning_Face_ICCV_2015_paper.pdf)|Face Generation|Training|2015|
|[ISTD](https://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Stacked_Conditional_Generative_CVPR_2018_paper.pdf)|Image Shadow Removal|Training,Testing|2018|
|[SRD](https://openaccess.thecvf.com/content_cvpr_2017/papers/Qu_DeshadowNet_A_Multi-Context_CVPR_2017_paper.pdf)|Image Shadow Removal|Training,Testing|2017|
|[CSD](https://ieeexplore.ieee.org/abstract/document/8492363/)|Image Desnowing|Training,Testing|2021|
|[Snow100k](https://arxiv.org/abs/1708.04512)|Image Desnowing|Training,Testing|2017|
|[SRRS](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660749.pdf)|Image Desnowing|Training,Testing|2020|
|[RainDrop](https://openaccess.thecvf.com/content_cvpr_2018/papers/Qian_Attentive_Generative_Adversarial_CVPR_2018_paper.pdf)|Image Deraining|Training|2018|
|[RainDropClarity](https://arxiv.org/abs/2407.16957)|Image Deraining|Training,Testing|2024|
|[Outdoor-Rain](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Heavy_Rain_Image_Restoration_Integrating_Physics_Model_and_Conditional_Adversarial_CVPR_2019_paper.pdf)|Image Deraining|Training,Testing|2019|
|[DDN-data](https://openaccess.thecvf.com/content_cvpr_2017/papers/Fu_Removing_Rain_From_CVPR_2017_paper.pdf)|Image Deraining|Training,Testing|2017|
|[SPA-data](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Spatial_Attentive_Single-Image_Deraining_With_a_High_Quality_Real_Rain_CVPR_2019_paper.pdf)|Image Deraining|Training,Testing|2019|
|[Rain100H](https://arxiv.org/abs/1609.07769)|Image Deraining|Training,Testing|2017|
|[Rain100L](https://arxiv.org/abs/1609.07769)|Image Deraining|Training,Testing|2017|
|[Haze-4K](https://arxiv.org/pdf/2108.02934.pdf)|Image Dehazing|Training|2021|
|[Dense-Haze](https://arxiv.org/pdf/1904.02904.pdf)|Image Dehazing|Training|2019|
|[RESIDE](https://arxiv.org/pdf/1712.04143.pdf)|Image Dehazing|Training|2019|


## Diffusion model-based Image/Video Compression
<a id="compression"></a>
|Model| Paper | First Author | Venue | Topic | Project |
| :--- | :---: | :---: | :--: | :--: |:--: |
|DiffC| [Lossy Compression with Gaussian Diffusion](https://arxiv.org/abs/2206.08889) | Lucas Theisl | Preprint'22 | Lossy Image Compression | |
|CDC| [Lossy Image Compression with Conditional Diffusion Models](https://arxiv.org/abs/2209.06950) | Ruihan Yang | NeurIPS 2023 | Lossy Image Compression | [![Stars](https://img.shields.io/github/stars/buggyyang/cdc_compression.svg?style=social&label=Star)](https://github.com/buggyyang/cdc_compression)|
|CorrDiff| [Correcting Diffusion-Based Perceptual Image Compression with Privileged End-to-End Decoder](https://arxiv.org/abs/2404.04916) | Yiyang Ma |  ICML 2024 | Image Compression | |
|I<sup>2</sup>VC| [I2VC: A Unified Framework for Intra- & Inter-frame Video Compression](https://arxiv.org/abs/2405.14336) | Meiqin Liu | NeurIPS2024 submission | Video Compression |[![Stars](https://img.shields.io/github/stars/GYukai/I2VC.svg?style=social&label=Star)](https://github.com/GYukai/I2VC)|
| DiffEIC | [Towards Extreme Image Compression with Latent Feature Guidance and Diffusion Prior](https://arxiv.org/abs/2404.18820) | Zhiyuan Li | IEEE TCSVT | Lossy Image Compression | |
|PSC| [Zero-Shot Image Compression with Diffusion-Based Posterior Sampling](https://arxiv.org/abs/2407.09896) | Noam Elata | Preprint'24 | Lossy Image Compression | |
|DIRAC| [A Residual Diffusion Model for High Perceptual Quality Codec Augmentation](https://arxiv.org/abs/2301.05489) | Noor Fathima Ghouse | Preprint'23 | Image Compression | |
|HFD| [High-Fidelity Image Compression with Score-based Generative Models](https://arxiv.org/abs/2305.18231) | Emiel Hoogeboom | Preprint'23 | Lossy Image Compression | |
| PerCo | [Towards image compression with perfect realism at ultra-low bitrates](https://arxiv.org/abs/2310.10325) | Marl` ene Careil | ICLR 2024 | Lossy Image Compression | |
|PIC| [Text + Sketch: Image Compression at Ultra Low Rates](https://arxiv.org/abs/2307.01944) | Eric Lei | ICML 2023 workshop  | Lossy Image Compression | |
|| [Idempotence and Perceptual Image Compression](https://arxiv.org/abs/2401.08920) | Tongda Xu | ICLR2024 | Lossy Image Compression | [![Stars](https://img.shields.io/github/stars/tongdaxu/idempotence-and-perceptual-image-compression.svg?style=social&label=Star)](https://github.com/tongdaxu/idempotence-and-perceptual-image-compression) |
|--| [Lossy Image Compression with Foundation Diffusion Models](https://arxiv.org/abs/2404.08580) | Lucas Relic | Preprint'24 | Image Compression | |
|--| [Extreme Generative Image Compression by Learning Text Embedding from Diffusion Models](https://arxiv.org/abs/2211.07793) | Zhihong Pan | Preprint'22 | Image Compression | |

# Diffusion model-based Image/Video quality assessment
<a id="IQA"></a>
|Model| Paper | First Author | Venue | Topic | Project |
| :--- | :---: | :---: | :--: | :--: |:--: |
|DifFIQA| [DifFIQA: Face Image Quality Assessment Using Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2305.05768) | Žiga Babnik | Preprint'23 | Image quality assessment |[![Stars](https://img.shields.io/github/stars/LSIbabnikz/DifFIQA.svg?style=social&label=Star)](https://github.com/LSIbabnikz/DifFIQA)|
|PFD-IQA| [Feature Denoising Diffusion Model for Blind Image Quality Assessment](https://arxiv.org/abs/2401.11949) | Xudong Li | Preprint'24 | Image quality assessment | |
|DP-IQA| [DP-IQA: Utilizing Diffusion Prior for Blind Image Quality Assessment in the Wild](https://arxiv.org/abs/2405.19996) | Honghao Fu | Preprint'24 | Image quality assessment |[![Stars](https://img.shields.io/github/stars/RomGai/DP-IQA.svg?style=social&label=Star)](https://github.com/RomGai/DP-IQA)|
|GenzIQA| [GenzIQA: Generalized Image Quality Assessment using Prompt-Guided Latent Diffusion Models](https://arxiv.org/abs/2406.04654) | Diptanu De | Preprint'24 | Image quality assessment ||
|DiffV<sup>2</sup>IQA</span>| [Diffusion Model Based Visual Compensation Guidance and Visual Difference Analysis for No-Reference Image Quality Assessment](https://arxiv.org/abs/2402.14401) | Zhaoyang Wang | Preprint'24 | Image quality assessment ||

## Cite US
If this work is helpful to you, we expect you can cite this work and star this repo. Thanks.
```
@article{li2023diffusion,
  title={Diffusion Models for Image Restoration and Enhancement--A Comprehensive Survey},
  author={Li, Xin and Ren, Yulin and Jin, Xin and Lan, Cuiling and Wang, Xingrui and Zeng, Wenjun and Wang, Xinchao and Chen, Zhibo},
  journal={arXiv preprint arXiv:2308.09388},
  year={2023}
}
```


 <p align="center">
  <a href="https://star-history.com/#lixinustc/Awesome-diffusion-model-for-image-processing&Date">
    <img src="https://api.star-history.com/svg?repos=lixinustc/Awesome-diffusion-model-for-image-processing&type=Date" alt="Star History Chart">
  </a>
</p>
