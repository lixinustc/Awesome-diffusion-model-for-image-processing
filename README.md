<p align="center">
  <img src="./figures/framework.png" alt="image" style="width:1000px;">
</p>


**Purpose**: We aim to provide a summary of diffusion model-based image processing, including restoration, enhancement, coding, and quality assessment. More papers will be summarized.

[Xin Li](http://home.ustc.edu.cn/~lixin666/), [Yulin Ren](), [Xin Jin](http://home.ustc.edu.cn/~jinxustc/), [Cuiling Lan](https://scholar.google.com/citations?user=XZugqiwAAAAJ&hl=en), [Xingrui Wang](), [Wenjun Zeng](https://scholar.google.com/citations?user=_cUfvYQAAAAJ&hl=en), [Xinchao Wang](https://scholar.google.com/citations?user=w69Buq0AAAAJ&hl=en), [Zhibo Chen](https://scholar.google.com/citations?user=1ayDJfsAAAAJ&hl=en)

University of Science and Technology of China (USTC), National University of Singapore (NUS), Microsoft Research Asia (MSRA), Eastern Institute of Technology (EIT) 

**Brief intro**: The survey for diffusion model-based IR has been released.

[![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2308.09388v1.pdf)




## 🌟  Features
- [x] **Survey for diffusion model-based Image Restoration** (Arxiv version is released) 
- [ ] Summary for diffusion model-based Image/Video Compression
- [ ] Summary for diffusion model-based Quality Assessment


## Diffusion model-based Image Restoration/Enhancement
### Table of contents
<!-- - [Survey paper](#survey-paper)
- [Table of contents](#table-of-contents) -->
- [Diffusion model for Image Super resolution](#image-super-resolution)
- [Diffusion model for Image Denoising](#image-denosing)
- [Diffusion model for Image Deblurring](#image-deblurring)
- [Diffusion model for Image Inpainting](#image-inpainting)
- [Diffusion model for Image Shadow Removal](#image-shadow-removal)
- [Diffusion model for Image Restoration](#image-restoration)
- [Diffusion model for Medical IR](#medical-restoration-mrict)
- [Diffusion model for other tasks](#other-tasks)
- [Benchmark Datasets](#benchmark-datasets)
  <!-- - [Recommended Datasets](#recommended-datasets)
  - [All Datasets](#all-datasets) -->

### Image Super-Resolution
| Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :--: | :--: |:--: | :--: |
| [Image super-resolution via iterative refinement](https://ieeexplore.ieee.org/document/9887996x) | Chitwan Saharia | Supervised |TPAMI2022 | Super-resolution | [Github](https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement) |
| [Srdiff: Single image superresolution with diffusion probabilistic models](https://arxiv.org/abs/2104.14951) | Haoying Li | Supervised | Neurocomputing 2022 | Super-resolution | [Github](https://github.com/LeiaLi/SRDiff) |
| [CDPMSR: Conditional Diffusion Probabilistic Models for Single Image Super-Resolution](https://arxiv.org/abs/2302.12831c) | Axi Niu | Supervised | Preprint'23 | Super-resolution | |
| [Resdiff: Combining cnn and diffusion model for image superresolution](https://arxiv.org/abs/2303.08714) | Shuyao Shang | Supervised | Preprint'23 | Super-resolution | |
| [Face super-resolution using stochastic differential equations](https://arxiv.org/abs/2209.12064) | Marcelo dos Santos | Supervised | SIBGRAPI 2022 | Super-resolution | [Github](https://github.com/marcelowds/sr-sde) |
| [Implicit diffusion models for continuous super-resolution](https://openaccess.thecvf.com/content/CVPR2023/papers/Gao_Implicit_Diffusion_Models_for_Continuous_Super-Resolution_CVPR_2023_paper.pdf) | Sicheng Gao | Supervised | CVPR2023 | Super-resolution | [Github](https://github.com/Ree1s/IDM) |
| [Diffir: Efficient diffusion model for image restoration](https://arxiv.org/abs/2303.09472) | Bin Xia | Supervised | Preprint'23 | Super-resolution | |
| [Cascaded Diffusion Models for High Fidelity Image Generation](https://arxiv.org/abs/2106.15282) | Jonathan Ho | Supervised | J.Mach.Learn.Res.2022 | Super-resolution | |
| [Exploiting diffusion prior for real-world image super-resolution](https://arxiv.org/abs/2305.07015) | Jianyi Wang | Supervised | Preprint'23 | Blind Restoration | [Github](https://github.com/IceClear/StableSR)|
| [Denoising diffusion probabilistic models for robust image super-resolution in the wild](https://arxiv.org/abs/2302.07864) | Hshmat Sahak | Supervised | Preprint'23 | Real-World Super-resolution | |
### Image Denosing
| Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :--: | :--: |:--: | :--: |
| [Diffusion model for generative image denoising](https://arxiv.org/abs/2302.02398) | Yutong Xie | Supervised | Preprint'23 | Image Denoising | |
| [Score-Based Diffusion Models as Principled Priors for Inverse Imaging](https://arxiv.org/abs/2304.11751) | Berthy T. Feng | Zero-shot | PrePrint'23 | Image Denoising, Image Deblurring | |
### Image Deblurring
| Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :--: | :--: |:--: | :--: |
| [Deblurring via stochastic refinement](https://openaccess.thecvf.com/content/CVPR2022/papers/Whang_Deblurring_via_Stochastic_Refinement_CVPR_2022_paper.pdf) | Jay Whang| Supervised | CVPR2022 | Image Deblurring | |
| [Score-Based Diffusion Models as Principled Priors for Inverse Imaging](https://arxiv.org/abs/2304.11751) | Berthy T. Feng | Zero-shot | PrePrint'23 | Image Denoising, Image Deblurring | |
| [Parallel diffusion models of operator and image for blind inverse problems](https://openaccess.thecvf.com/content/CVPR2023/papers/Chung_Parallel_Diffusion_Models_of_Operator_and_Image_for_Blind_Inverse_CVPR_2023_paper.pdf) | Hyungjin Chung | Zero-shot | CVPR2023 | Blind Restoration | [Github](https://github.com/BlindDPS/blind-dps) |
### Image Inpainting
| Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :--: | :--: |:--: | :--: |
| [Repaint: Inpainting using denoising diffusion probabilistic models](https://openaccess.thecvf.com/content/CVPR2022/papers/Lugmayr_RePaint_Inpainting_Using_Denoising_Diffusion_Probabilistic_Models_CVPR_2022_paper.pdf) | Andreas Lugmayr  | Zero-shot | CVPR2022 | Image Inpainting | [Github](https://github.com/andreas128/RePaint) | 
| [Towards coherent image inpainting using denoising diffusion implicit models](https://arxiv.org/abs/2304.03322) | Guanhua Zhang | Zero-shot | PrePrint'23 | Image Inpainting | [Github](https://github.com/UCSB-NLP-Chang/CoPaint) |
### Image Shadow Removal 
| Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :--: | :--: |:--: | :--: |
| [DeS3: Attention-driven Self and Soft Shadow Removal using ViT Similarity and Color Convergence](https://arxiv.org/abs/2211.08089) | Yeying Jin | Supervised | Preprint'23 | Image Shadow Removal | |
| [Shadowdiffusion: When degradation prior meets diffusion model for shadow removal](https://openaccess.thecvf.com/content/CVPR2023/papers/Guo_ShadowDiffusion_When_Degradation_Prior_Meets_Diffusion_Model_for_Shadow_Removal_CVPR_2023_paper.pdf) | Lanqing Guo | Supervised | CVPR2023 | Image Shadow Removal |[Github](https://github.com/GuoLanqing/ShadowDiffusion) |
### Image Restoration
| Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :--: | :--: |:--: | :--: |
| [Palette: Image-toimage diffusion models](https://arxiv.org/abs/2111.05826) | Chitwan Saharia | Supervised | SIGGRAPH 2022 | Multi-task Restoration | [Github](https://github.com/Janspiry/Palette-Image-to-Image-Diffusion-Models) |
| [Refusion: Enabling large-size realistic image restoration with latent-space diffusion models](https://arxiv.org/abs/2304.08291) | Ziwei Luo | Supervised | CVPRW 2023 | Multi-task Restoration | |
| [Inversion by direct iteration: An alternative to denoising diffusion for image restoration](https://arxiv.org/abs/2303.11435) | Mauricio Delbracio | Supervised | Preprint'22 | Multi-task Restoration | |
| [Restoring vision in adverse weather conditions with patch-based denoising diffusion models](https://arxiv.org/abs/2207.14626) | Ozan Özdenizci | Supervised | TPAMI2022 | Multi-task Restoration | [Github](https://github.com/IGITUGraz/WeatherDiffusion) |
| [Image Restoration with Mean-Reverting Stochastic Differential Equations](https://arxiv.org/abs/2301.11699) | Ziwei Luo | Supervised | ICML 2023 | Multi-task Restoration | [Github](https://github.com/Algolzw/image-restoration-sde) |
| [Sud ˆ2: Supervision by denoising diffusion models for image reconstruction](https://arxiv.org/abs/2303.09642) | Matthew A. Chan | Supervised | Preprint'23 | Multi-task Restoration | |
| [Ilvr: Conditioning method for denoising diffusion probabilistic models](https://openaccess.thecvf.com/content/ICCV2021/papers/Choi_ILVR_Conditioning_Method_for_Denoising_Diffusion_Probabilistic_Models_ICCV_2021_paper.pdf) | Jooyoung Choi | Zero-shot | ICCV2021 | Image Restoration | [Github](https://github.com/jychoi118/ilvr_adm) |
| [Come-closer-diffusefaster: Accelerating conditional diffusion models for inverse problems through stochastic contraction](https://openaccess.thecvf.com/content/CVPR2022/papers/Chung_Come-Closer-Diffuse-Faster_Accelerating_Conditional_Diffusion_Models_for_Inverse_Problems_Through_Stochastic_CVPR_2022_paper.pdf) | Hyungjin Chung | Zero-shot | CVPR2022 | Multi-task Restoration | |
| [Snips: Solving noisy inverse problems stochastically](https://arxiv.org/abs/2105.14951) | Bahjat Kawa | Zero-shot | NeurIPS 2021 | Multi-task Restoration | [Github](https://github.com/bahjat-kawar/snips_torch)|
| [Denoising diffusion restoration models](https://arxiv.org/abs/2201.11793) | Bahjat Kawar | Zero-shot | ICLR2022 | Multi-task Restoration | [Github](https://github.com/bahjat-kawar/ddrm) |
| [Zero-shot image restoration using denoising diffusion null-space model](https://arxiv.org/abs/2212.00490) | Yinhuai Wang | Zero-shot | ICLR2023 | Multi-task Restoration | [Github](https://github.com/wyhuai/DDNM) |
| [Diffusion Posterior Sampling for General Noisy Inverse Problems](https://arxiv.org/abs/2209.14687) | Hyungjin Chung | Zero-shot | ICLR 2023 | Multi-task Restoration | [Github](https://github.com/DPS2022/diffusion-posterior-sampling) |
| [Diracdiffusion: Denoising and incremental reconstruction with assured data-consistency](https://arxiv.org/abs/2303.14353) | Zalan Fabian | Zero-shot | NeurIPS 2022 | Multi-task Restoration | |
| [Pseudoinverse-guided diffusion models for inverse problems](https://openreview.net/forum?id=9_gsMA8MRKQ) | Jiaming Song | Zero-shot | ICLR 2023 | Multi-task Restoration | |
| [Generative diffusion prior for unified image restoration and enhancement](https://openaccess.thecvf.com/content/CVPR2023/papers/Fei_Generative_Diffusion_Prior_for_Unified_Image_Restoration_and_Enhancement_CVPR_2023_paper.pdf) | Ben Fei | Zero-shot | CVPR2023 | Multi-task Restoration | [Github](https://github.com/Fayeben/GenerativeDiffusionPrior) |
| [Denoising diffusion models for plug-and-play image restoration](https://openaccess.thecvf.com/content/CVPR2023W/NTIRE/papers/Zhu_Denoising_Diffusion_Models_for_Plug-and-Play_Image_Restoration_CVPRW_2023_paper.pdf) | Yuanzhi Zhu | Zero-shot | CVPR 2023 | Multi-task Restoration | [Github](https://github.com/yuanzhi-zhu/DiffPIR) |
| [A variational perspective on solving inverse problems with diffusion models](https://arxiv.org/abs/2305.04391) | Morteza Mardani | Zero-shot | PrePrint'22 |Multi-task Restoration| |
| [Multiscale Structure Guided Diffusion for Image Deblurring](https://arxiv.org/abs/2212.01789) | Mengwei Ren | Supervised | Preprint'22 | Blind Restoration | |
| [Driftrec: Adapting diffusion models to blind image restoration tasks](https://arxiv.org/abs/2211.06757) | Simon Welker | Supervised | Preprint'22 | Blind Restoration | |
| [Dr2: Diffusion-based robust degradation remover for blind face restoration](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_DR2_Diffusion-Based_Robust_Degradation_Remover_for_Blind_Face_Restoration_CVPR_2023_paper.pdf) | Zhixin Wang | Zero-shot | CVPR2023 | Blind Face Restoration | |
| [Diffbfr: Bootstrapping diffusion model towards blind face restoration](https://arxiv.org/abs/2305.04517) | Xinmin Qiu | Supervised | Preprint'23 | Blind Face Restoration | |
| [Difface: Blind face restoration with diffused error contraction](https://arxiv.org/abs/2212.06512) | Zongsheng Yu | Zero-shot | PrePrint'23 | Blind Restoration | [Github](https://github.com/zsyOAOA/DifFace) |
| [Gibbsddrm: A partially collapsed gibbs sampler for solving blind inverse problems with denoising diffusion restoration](https://arxiv.org/abs/2301.12686) | Naoki Murata | Zero-shot | PrePrint'23 | Blind Restoration | |
| [Adir: Adaptive diffusion for image reconstruction](https://arxiv.org/abs/2212.03221) | Shady Abu-Hussein | Zero-shot | PrePrint'22 | Blind Restoration | |
| [Synthesizing realistic image restoration training pairs: A diffusion approach](https://arxiv.org/abs/2303.06994) | Tao Yang | Supervised | Preprint'22 | Blind Restoration | |
### Medical Restoration (MRI,CT)
| Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :--: | :--: |:--: | :--: |
| [Improving diffusion models for inverse problems using manifold constraints](https://arxiv.org/abs/2206.00941) | Hyungjin Chung | Zero-shot | NeurIPS 2022 | CT Reconstruction | [Github](https://github.com/HJ-harry/MCG_diffusion) |
| [Solving inverse problems in medical imaging with score-based generative models](https://arxiv.org/abs/2111.08005) | Yang Song | Zero-shot | ICLR 2022 | CT Reconstruction | |
| [Adaptive diffusion priors for accelerated mri reconstruction](https://arxiv.org/abs/2207.05876) | Alper Güngör | Supervised | Preprint'23 | MRI Reconstruction | |
| [High-Frequency Space Diffusion Models for Accelerated MRI](https://arxiv.org/abs/2208.05481) | Chentao Cao | Supervised | Preprint'22 | MRI Reconstruction | |
### Other tasks
| Paper | First Author | Training Way | Venue | Topic | Project |
| :--- | :---: | :--: | :--: |:--: | :--: |
| [Jpeg artifact correction using denoising diffusion restoration models](https://arxiv.org/abs/2209.11888) | Bahjat Kawar| Zero-shot | NeurIPS 2022 | JPEG Artifacts Removal | [Github](https://github.com/bahjat-kawar/ddrm-jpeg) |
| [Improved Diffusion-based Image Colorization via Piggybacked Models](https://arxiv.org/abs/2304.11105) | Hanyuan Liu | Zero-shot | PrePrint'23 | Image Colorization | [Github](https://github.com/hyliu/piggyback-color) |
| [Pyramid Diffusion Models For Low-light Image Enhancement](https://arxiv.org/abs/2305.10028) | Dewei Zhou | Supervised | Preprint'23 | Low-light Enhancemnent | [Github](https://github.com/limuloo/PyDIff) |
| [Lowlight image enhancement with wavelet-based diffusion models](https://arxiv.org/abs/2306.00306) | Hai Jiang | Supervised | Preprint'23 | Low-light Enhancemnent | |
| [RainDiffusion: When Unsupervised Learning Meets Diffusion Models for Real-world Image Deraining](https://arxiv.org/abs/2301.09430) | Mingqiang Wei | Supervised | Preprint'23 | Image Deraining| |
| [Diffgar: Model-agnostic restoration from generative artifacts using image-to-image diffusion models](https://arxiv.org/abs/2210.08573) | Yueqin Yin | Supervised | Preprint'22 | Generative Artifacts Removal | |
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
|[Outdoor-Rain](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Heavy_Rain_Image_Restoration_Integrating_Physics_Model_and_Conditional_Adversarial_CVPR_2019_paper.pdf)|Image Deraining|Training,Testing|2019|
|[DDN-data](https://openaccess.thecvf.com/content_cvpr_2017/papers/Fu_Removing_Rain_From_CVPR_2017_paper.pdf)|Image Deraining|Training,Testing|2017|
|[SPA-data](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Spatial_Attentive_Single-Image_Deraining_With_a_High_Quality_Real_Rain_CVPR_2019_paper.pdf)|Image Deraining|Training,Testing|2019|
|[Rain100H](https://arxiv.org/abs/1609.07769)|Image Deraining|Training,Testing|2017|
|[Rain100L](https://arxiv.org/abs/1609.07769)|Image Deraining|Training,Testing|2017|
|[Haze-4K](https://arxiv.org/pdf/2108.02934.pdf)|Image Dehazing|Training|2021|
|[Dense-Haze](https://arxiv.org/pdf/1904.02904.pdf)|Image Dehazing|Training|2019|
|[RESIDE](https://arxiv.org/pdf/1712.04143.pdf)|Image Dehazing|Training|2019|
