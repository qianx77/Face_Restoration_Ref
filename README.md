# Paper and Code
Inspired by sczhou [Awesome-Face-Restoration](https://github.com/sczhou/Awesome-Face-Restoration) and TaoWangzj [Awesome-Face-Restoration](https://github.com/TaoWangzj/Awesome-Face-Restoration).

## Recommend
Several popular methods that perform well in my own test data.

|Year<div style="width:20px">|Pub<div style="width:60px">|Abbreviation<div style="width:45px">|Recommend<div style="width:45px">|
|:---:|:----:|:----:|:----:|
|2021|CVPR|GFPGAN v1.4|⭐️⭐️⭐️⭐️⭐️|
|2022|NeurIPS|CodeFormer|⭐️⭐️⭐️⭐️⭐️|
|2021|CVPR|GPEN|⭐️⭐️⭐️|

## Blind Face Restoration (Image) 
### Geometric Prior
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:600px">|Links<div style="width:100px">|Arch<div style="width:45px">|Abbreviation<div style="width:45px">|
|:---:|:----:|:----:|:----:|:----:|:----:|
|2018|CVPR|FSRNet: End-to-End Learning Face Super-Resolution with Facial Priors|[[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_FSRNet_End-to-End_Learning_CVPR_2018_paper.pdf)\]\[[code](https://github.com/tyshiwo/FSRNet)]|CNN|FSRNet|
|2021|TPAMI|Face Restoration via Plug-and-Play 3D Facial Priors|\[[paper](https://www.zora.uzh.ch/id/eprint/214478/1/ZORA214478.pdf)]\[code]|CNN|-|
|2021|CVPR|Progressive Semantic-Aware Style Transformation for Blind Face Restoration|\[[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_Progressive_Semantic-Aware_Style_Transformation_for_Blind_Face_Restoration_CVPR_2021_paper.pdf)]\[[code](https://github.com/chaofengc/PSFRGAN)]|GAN|PSFRGAN|
|2023|TNNLS|Multi-prior learning via neural architecture search for blind face restoration|\[[paper](https://Arxiv.org/pdf/2206.13962.pdf)]\[[code](https://github.com/YYJ1anG/MFPSNet)]|CNN|MFPSNet|
|2022|CVPR|Blind Face Restoration via Integrating Face Shape and Generative Priors|\[[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhu_Blind_Face_Restoration_via_Integrating_Face_Shape_and_Generative_Priors_CVPR_2022_paper.pdf)]~~\[[code](https://github.com/TencentYoutuResearch/BFR-SGPN)]~~|GAN|SGPN|
### Reference Prior
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:600px">|Links<div style="width:100px">|Arch<div style="width:45px">|Abbreviation<div style="width:45px">|
|:---:|:----:|:----:|:----:|:----:|:----:|
|2018|ECCV|Learning Warped Guidance for Blind Face Restoration|[[paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Xiaoming_Li_Learning_Warped_Guidance_ECCV_2018_paper.pdf)]\[[code](https://github.com/csxmli2016/GFRNet)]|CNN|GFRNet|
|2020|ECCV|Blind Face Restoration via Deep Multi-scale Component Dictionaries|\[[paper](https://Arxiv.org/pdf/2008.00418)]\[[code](https://github.com/csxmli2016/DFDNet)]|CNN|DFDNet|
|2020|CVPR|Enhanced Blind Face Restoration with Multi-Exemplar Images <br>and Adaptive Spatial Feature Fusion|\[[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Blind_Face_Restoration_With_Multi-Exemplar_Images_and_Adaptive_Spatial_CVPR_2020_paper.pdf)]\[[code](https://github.com/csxmli2016/ASFFNet)]|CNN|ASFFNet|
|2022|TPAMI|Learning Dual Memory Dictionaries for Blind Face Restoration|\[[paper](https://arxiv.org/pdf/2210.08160.pdf)]\[[code](https://github.com/csxmli2016/DMDNet)]|CNN|DMDNet|
|2022|ACM|MyStyle: A Personalized Generative Prior|\[[paper](https://dl.acm.org/doi/pdf/10.1145/3550454.3555436)]~~\[code]~~|GAN|MyStyle|
|2023|arXiv|Personalized Restoration via Dual-Pivot Tuning|\[[paper](https://arxiv.org/abs/2312.17234)]\[[code](https://github.com/personalized-restoration/personalized-restoration)]|Diffusion|Dual-Pivot Tuning|
|2024|arXiv|InstantRestore: Single-Step Personalized Face Restoration with Shared-Image Attention|\[[paper](https://arxiv.org/pdf/2412.06753)]\[[code](https://github.com/snap-research/InstantRestore)]|Diffusion|InstantRestore|
|2024|CVPR|PFStorer: Personalized Face Restoration and Super-Resolution|\[[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Varanka_PFStorer_Personalized_Face_Restoration_and_Super-Resolution_CVPR_2024_paper.pdf)]~~\[code]~~|Diffusion|PFStorer|
|2024|arXiv|RestorerID: Towards Tuning-Free Face Restoration with ID Preservation|\[[paper](https://arxiv.org/pdf/2411.14125)]\[[code](https://github.com/YingJiacheng/RestorerID)]|Diffusion|RestorerID|
|2024|arXiv|Overcoming False Illusions in Real-World Face Restoration with Multi-Modal GuidedDiffusion Model|\[[paper](https://arxiv.org/pdf/2410.04161)]~~\[code]~~|Diffusion|MGFR|
|2024|arXiv|Copy or Not? Reference-Based Face Image Restoration with Fine Details|\[[paper](https://jianwang-cmu.github.io/25Refine/main.pdf)]\[[code](https://github.com/RefineFIR/RefineFIR)]|Diffusion|RefineFIR|
|2024|Sensors|PDGrad: Guiding Diffusion Model for Reference-Based Blind Face Restoration with Pivot Direction Gradient Guidance|\[[paper](https://www.mdpi.com/1424-8220/24/22/7112)]~~\[code]~~|Diffusion|PDGrad|
|2024|CVPR|Restoration by Generation with Constrained Priors|\[[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Ding_Restoration_by_Generation_with_Constrained_Priors_CVPR_2024_paper.pdf)]\[[code](https://github.com/adobe-research/gen2res)]|Diffusion|gen2res|
|2024|WACV|ENTED: Enhanced Neural Texture Extraction and Distribution for Reference-based Blind Face Restoration|\[[paper](https://openaccess.thecvf.com/content/WACV2024/papers/Lau_ENTED_Enhanced_Neural_Texture_Extraction_and_Distribution_for_Reference-Based_Blind_WACV_2024_paper.pdf)]~~\[code]~~|Diffusion|ENTED|
|2025|AAAI|FaceMe: Robust Blind Face Restoration with Personal Identification|\[[paper](https://arxiv.org/pdf/2501.05177)]\[[code](https://github.com/modyu-liu/FaceMe)]|Diffusion|FaceMe|
### Generative Prior (good)
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:600px">|Links<div style="width:100px">|Arch<div style="width:45px">|Abbreviation<div style="width:45px">|
|:---:|:----:|:----:|:----:|:----:|:----:|
|2020|MM|HiFaceGAN: Face Renovation via Collaborative Suppression and Replenishment|\[[paper](https://Arxiv.org/pdf/2005.05005.pdf)]\[[code](https://github.com/Lotayou/Face-Renovation)]|GAN|HiFaceGAN|
|2020|CVPR|Image Processing Using Multi-Code GAN Prior|\[[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Gu_Image_Processing_Using_Multi-Code_GAN_Prior_CVPR_2020_paper.pdf)]\[[code](https://github.com/genforce/mganprior)]|GAN|mGANprior|
|2021|CVPR|Towards Real-World Blind Face Restoration with Generative Facial Prior|\[[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Towards_Real-World_Blind_Face_Restoration_With_Generative_Facial_Prior_CVPR_2021_paper.pdf)]\[[code](https://xinntao.github.io/projects/gfpgan)]|GAN|GFPGAN|
|2021|CVPR|GAN Prior Embedded Network for Blind Face Restoration in the Wild|\[[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_GAN_Prior_Embedded_Network_for_Blind_Face_Restoration_in_the_CVPR_2021_paper.pdf)]\[[code](https://github.com/yangxy/GPEN)]|GAN|GPEN|
|2022|CVPR|Blind Face Restoration via Integrating Face Shape and Generative Priors|\[[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhu_Blind_Face_Restoration_via_Integrating_Face_Shape_and_Generative_Priors_CVPR_2022_paper.pdf)]\[code]|GAN|SGPN|
|2022|CVPR|GCFSR: a Generative and Controllable Face Super Resolution Method Without Facial and GAN Priors|\[[paper](https://arxiv.org/pdf/2203.08444.pdf)]\[[code](https://github.com/hejingwenhejingwen/GCFSR)]|GAN|GCFSR|
|2022|AAAI|Panini-Net: GAN Prior Based Degradation-Aware Feature Interpolation for Face Restoration|\[[paper](https://arxiv.org/pdf/2203.08444.pdf)]\[[code](https://github.com/jianzhangcs/panini)]|GAN|Panini-Net|
|2022|Arxiv|FaceFormer: Scale-aware Blind Face Restoration with Transformers|\[[paper](https://Arxiv.org/pdf/2207.09790.pdf)]\[code]|ViT|FaceFormer|
|2022|Arxiv|Blind Face Restoration: Benchmark Datasets and a Baseline Model|\[[paper](https://arxiv.org/pdf/2206.03697.pdf)]\[[code](https://github.com/bitzpy/blind-face-restoration-benchmark-datasets-and-a-baseline-model)]|ViT|STUNet|
|2023|CVPR|TFRGAN: Leveraging Text Information for Blind Face Restoration with Extreme Degradation|\[[paper](https://openaccess.thecvf.com/content/CVPR2023W/MULA/papers/Xie_TFRGAN_Leveraging_Text_Information_for_Blind_Face_Restoration_With_Extreme_CVPRW_2023_paper.pdf)]\[code]|GAN|TFRGAN|
|2023|TCSVT|DEAR-GAN: Degradation-Aware Face Restoration With GAN Prior|\[[paper](https://ieeexplore.ieee.org/abstract/document/10044117)]\[code]|GAN|DEAR-GAN|
|2023|ACMMM|Exploring Correlations in Degraded Spatial Identity Features for Blind Face Restoration|\[[paper](https://dl.acm.org/doi/abs/10.1145/3581783.3611782)]\[code]|GAN|MemGAN|
|2023|FSP|Degradation Learning and Skip-Transformer for Blind Face Restoration|\[[paper](https://www.frontiersin.org/articles/10.3389/frsip.2023.1106465/full)]\[code]|GAN|-|
|2023|ACMMM|Exploring Correlations in Degraded Spatial Identity Features for Blind Face Restoration|\[[paper](https://dl.acm.org/doi/abs/10.1145/3581783.3611782)]\[code]|GAN|-|
|2024|AAAI|Blind Face Restoration under Extreme Conditions: Leveraging 3D-2D Prior Fusion for Superior Structural and Texture Recovery|\[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/27889/27803)]\[code]|GAN|FREx|
### Vector Quantized Codebook Prior (good)
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:600px">|Links<div style="width:100px">|Arch<div style="width:45px">|Abbreviation<div style="width:45px">|
|:---:|:----:|:----:|:----:|:----:|:----:|
|2022|CVPR|RestoreFormer: High-Quality Blind Face Restoration <br> from Undegraded Key-Value Pairs|\[[paper](https://Arxiv.org/pdf/2201.06374.pdf)]\[[code](https://github.com/wzhouxiff/RestoreFormer)]|ViT|RestoreFormer|
|2022|NeurIPS|Towards Robust Blind Face Restoration with Codebook Lookup Transformer|\[[paper](https://Arxiv.org/pdf/2206.11253.pdf)]\[[code](https://github.com/sczhou/CodeFormer)]|ViT|CodeFormer|
|2022|ECCV|VQFR: Blind Face Restoration with Vector-Quantized Dictionary and Parallel Decoder|\[[paper](https://Arxiv.org/pdf/2205.06803.pdf)]\[[code](https://github.com/TencentARC/VQFR)]|CNN|VQFR|
|2023|TPAMI|RestoreFormer++: Towards Real-World Blind Face Restoration from Undegraded Key-Value Pairs|\[[paper](https://Arxiv.org/pdf/2205.06803.pdf)]\[[code](https://github.com/wzhouxiff/RestoreFormerPlusPlus)]|ViT|RestoreFormer++|
|2022|CVPR|Rethinking Deep Face Restoration|\[[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhao_Rethinking_Deep_Face_Restoration_CVPR_2022_paper.pdf)]\[code]|GAN|-|
|2024|ICLR|Dual Associated Encoder for Face Restoration|\[[paper](https://arxiv.org/pdf/2308.07314)]\[[code](https://github.com/LIAGM/DAEFR)]|ViT|DAEFR|
### Diffusion Prior
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:600px">|Links<div style="width:100px">|Arch<div style="width:45px">|Abbreviation<div style="width:45px">|
|:---:|:----:|:----:|:----:|:----:|:----:|
|2022|Arxiv|Difface: Blind Face Restoration with Diffused Error Contraction|\[[paper](https://arxiv.org/pdf/2212.06512.pdf?trk=public_post_comment-text)]\[[code](https://github.com/zsyOAOA/DifFace)]|Diffusion|DifFace|
|2023|CVPR|DR2: Diffusion-based Robust Degradation Remover for Blind Face Restoration|\[[paper](https://arxiv.org/abs/2303.06885)]\[[code](https://github.com/Kaldwin0106/DR2_Drgradation_Remover)]|Diffusion|DR2|
|2023|WACV|AT-DDPM: Restoring Faces degraded by Atmospheric Turbulence using Denoising Diffusion Probabilistic Models|\[[paper](https://openaccess.thecvf.com/content/WACV2023/papers/Nair_AT-DDPM_Restoring_Faces_Degraded_by_Atmospheric_Turbulence_Using_Denoising_Diffusion_WACV_2023_paper.pdf)]\[[code](https://github.com/Nithin-GK/AT-DDPM)]|Diffusion|AT-DDPM|
|2023|ACMMM|DiffBFR: Bootstrapping Diffusion Model for Blind Face Restoration|\[[paper](https://dl.acm.org/doi/pdf/10.1145/3581783.3611731)]\[code]|Diffusion|DiffBFR|
|2023|NeurIPS|PGDiff: Guiding Diffusion Models for Versatile Face Restoration via Partial Guidance|\[[paper](https://dl.acm.org/doi/pdf/10.1145/3581783.3611731)]\[[code](https://github.com/pq-yang/PGDiff)]|Diffusion|PGDiff|
|2024|TCSVT|Towards Real-World Blind Face Restoration with Generative Diffusion Prior|\[[paper](https://arxiv.org/pdf/2312.15736.pdf)]\[[code](https://github.com/chenxx89/BFRffusion)]|Diffusion|BFRffusion|
|2024|WACV|Diffuse and Restore: A Region-Adaptive Diffusion Model for Identity-Preserving Blind Face Restoration|\[[paper](https://openaccess.thecvf.com/content/WACV2024/papers/Suin_Diffuse_and_Restore_A_Region-Adaptive_Diffusion_Model_for_Identity-Preserving_Blind_WACV_2024_paper.pdf)]\[code]|Diffusion|-|
|2024|ECCV|DiffBIR: Towards Blind Image Restoration with Generative Diffusion Prior|\[[paper](https://arxiv.org/pdf/2308.15070)]\[[code](https://github.com/XPixelGroup/DiffBIR)]|Diffusion|DiffBIR|
|2024|NeurIPS|One-Step Effective Diffusion Network for Real-World Image Super-Resolution|\[[paper](https://arxiv.org/pdf/2406.08177)]\[[code](https://github.com/cswry/OSEDiff)]|Diffusion|OSEDiff|
|2024|Arxiv|OSDFace: One-Step Diffusion Model for Face Restoration|\[[paper](https://arxiv.org/abs/2411.17163)]\[[code](https://github.com/jkwang28/OSDFace)]|Diffusion|OSDFace|

### Others
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:600px">|Links<div style="width:100px">|Arch<div style="width:45px">|Abbreviation<div style="width:45px">|
|:---:|:----:|:----:|:----:|:----:|:----:|
|2023|ICCV|Towards Authentic Face Restoration with Iterative Diffusion Models and Beyond|\[[paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhao_Towards_Authentic_Face_Restoration_with_Iterative_Diffusion_Models_and_Beyond_ICCV_2023_paper.pdf)]~~\[code]~~|Diffusion|IDM|
|2024|CVPR|WaveFace: Authentic Face Restoration with Efficient Frequency Recovery|\[[paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Miao_WaveFace_Authentic_Face_Restoration_with_Efficient_Frequency_Recovery_CVPR_2024_paper.pdf)]~~\[code]~~|Diffusion|WaveFace|
|2024|Arxiv|CLR-Face: Conditional Latent Refinement for Blind Face Restoration Using Score-Based Diffusion Models|\[[paper](https://arxiv.org/abs/2402.06106)]~~\[code]~~|Diffusion|CLR-Face|
|2024|WACV|Diffuse and Restore: A Region-Adaptive Diffusion Model for Identity-Preserving Blind Face Restoration|\[[paper](https://openaccess.thecvf.com/content/WACV2024/papers/Suin_Diffuse_and_Restore_A_Region-Adaptive_Diffusion_Model_for_Identity-Preserving_Blind_WACV_2024_paper.pdf)]~~\[code]~~|Diffusion|Diffuse and Restore|
|2024|arXiv|AuthFace: Towards Authentic Blind Face Restoration with Face-oriented Generative Diffusion Prior|\[[paper](https://arxiv.org/pdf/2410.09864)]\[[code](https://github.com/EthanLiang99/AuthFace)]|Diffusion|AuthFace|
|2025|Arxiv|InfoBFR: Real-World Blind Face Restoration via Information Bottleneck|\[[paper](https://arxiv.org/pdf/2501.15443)]~~\[code]~~|Diffusion|InfoBFR|
|2025|WACV|Towards Unsupervised Blind Face Restoration using Diffusion Prior|\[[paper](https://arxiv.org/pdf/2410.04618)]\[[code](https://github.com/SamsungLabs/DT-BFR)]|Diffusion|DT-BFR|

## Blind Face Restoration (Video) 
|Year<div style="width:20px">|Pub<div style="width:60px">|Title<div style="width:600px">|Links<div style="width:100px">|Arch<div style="width:45px">|Abbreviation<div style="width:45px">|
|:---:|:----:|:----:|:----:|:----:|:----:|
|2023|Arxiv |FLAIR: A Conditional Diffusion Framework with Applications to Face Video Restoration|\[[paper](https://arxiv.org/pdf/2311.15445)]\[code]|Diffusion|FLAIR|
|2024|IJCAI|Beyond Alignment: Blind Video Face Restoration via Parsing-Guided Temporal-Coherent Transformer|\[[paper](https://arxiv.org/abs/2404.13640)]\[[code](https://github.com/kepengxu/PGTFormer)]|ViT|PGTFormer|
|2024|ECCV |KEEP: Kalman-Inspired Feature Propagation for Video Face Super-Resolution|\[[paper](https://arxiv.org/abs/2408.05205)]\[[code](https://github.com/jnjaby/KEEP)]|ViT|KEEP|
|2024|TIP |Analysis and Benchmarking of Extending Blind Face Image Restoration to Videos|\[[paper](https://arxiv.org/pdf/2410.11828)]~~\[[code](https://wzhouxiff.github.io/projects/FIR2FVR/FIR2FVR)]~~|General|-|


## Datasets
### Image Face Dataset
| Dataset | Resolution | Description |
| :---: | :---: | :----------    |
| [FFHQ](https://github.com/NVlabs/ffhq-dataset) | 1024 x 1024 | 7,0000 high-quality face images (usually used for training) |
| [CelebA-HQ](https://github.com/nperraud/download-celebA-HQ) | 1024 x 1024 | 3,0000 high-quality face images (usually used for evaluation) |
| [CelebAMask-HQ](https://github.com/switchablenorms/CelebAMask-HQ) | 512 x 512 | 3,0000 face images with 19 facial classes |
| [CelebRef-HQ](https://github.com/csxmli2016/DMDNet#celebref-hq-dataset) | 512 x 512 | high-quality face images with multiple same-identity references |
| [EFHQ](https://vinairesearch.github.io/EFHQ/) | 512 x 512 | Multi-purpose ExtremePose-Face-HQ dataset |

### Video Face Dataset
| Dataset | Description |
| :---: | :----------    |
| [TalkingHead-1KH](https://github.com/tcwang0509/TalkingHead-1KH)  | 500k video clips, of which about 80k are greater than 512x512 resolution |
| [VFHQ](https://liangbinxie.github.io/projects/vfhq)  | 16,000 high-fidelity clips of diverse interview scenarios |
| [CelebV-HQ](https://liangbinxie.github.io/projects/vfhq)  | 35,666 video clips involving 15,653 identities and 83 manually labeled facial attributes|

