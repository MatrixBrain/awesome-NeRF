# Awesome Neural Radiance Fields [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome neural radiance fields (NeRF) papers.

## Contributing

[Submit a pull request](./submit-pr.md)


## Table of Contents

* Papers
* Datasets
* Talks
* Blogs
* Links

## Papers

|Year|Conf|Code|Title|
|:-:|:-:|:-:|:-:|
|2020|ECCV|[TF](https://github.com/bmild/nerf) [Torch](https://github.com/yenchenlin/nerf-pytorch)|[NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://dl.acm.org/doi/pdf/10.1145/3503250)|

### Survey

### General

|Year|Conf|Code|Title|
|:-:|:-:|:-:|:-:|
|2022|CVPR||[Ray Priors through Reprojection: Improving Neural Radiance Fields for Novel View Extrapolation](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_Ray_Priors_Through_Reprojection_Improving_Neural_Radiance_Fields_for_Novel_CVPR_2022_paper.pdf)|
|2022|CVPR|[Torch](https://github.com/Xharlie/pointnerf)|[Point-NeRF: Point-based Neural Radiance Fields](https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_Point-NeRF_Point-Based_Neural_Radiance_Fields_CVPR_2022_paper.pdf)|
|2022|CVPR||[Ref-NeRF: Structured View-Dependent Appearance for Neural Radiance Fields](https://openaccess.thecvf.com/content/CVPR2022/papers/Verbin_Ref-NeRF_Structured_View-Dependent_Appearance_for_Neural_Radiance_Fields_CVPR_2022_paper.pdf)|
|2022|CVPR||[Urban Radiance Fields](https://openaccess.thecvf.com/content/CVPR2022/papers/Rematas_Urban_Radiance_Fields_CVPR_2022_paper.pdf)|
|2022|CVPR|[Torch](https://github.com/idiap/GeoNeRF)|[GeoNeRF: Generalizing NeRF with Geometry Priors](https://openaccess.thecvf.com/content/CVPR2022/papers/Johari_GeoNeRF_Generalizing_NeRF_With_Geometry_Priors_CVPR_2022_paper.pdf)|
|2022|CVPR||[HDR-NeRF: High Dynamic Range Neural Radiance Fields](https://openaccess.thecvf.com/content/CVPR2022/papers/Huang_HDR-NeRF_High_Dynamic_Range_Neural_Radiance_Fields_CVPR_2022_paper.pdf)|
|2022|CVPR||[NeRFReN: Neural Radiance Fields with Reflections](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_NeRFReN_Neural_Radiance_Fields_With_Reflections_CVPR_2022_paper.pdf)|
|2022|CVPR|[Torch](https://github.com/VITA-Group/Aug-NeRF)|[Aug-NeRF: Training Stronger Neural Radiance Fields with Triple-Level Physically-Grounded Augmentations](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_Aug-NeRF_Training_Stronger_Neural_Radiance_Fields_With_Triple-Level_Physically-Grounded_Augmentations_CVPR_2022_paper.pdf)|

### Training & Inference Efficiency

|Year|Conf|Code|Title|
|:-:|:-:|:-:|:-:|
|2022|CVPR|[Torch](https://github.com/lwwu2/diver-rt)|[DIVeR: Real-time and Accurate Neural Radiance Fields with Deterministic Integration for Volume Rendering](https://openaccess.thecvf.com/content/CVPR2022/papers/Wu_DIVeR_Real-Time_and_Accurate_Neural_Radiance_Fields_With_Deterministic_Integration_CVPR_2022_paper.pdf)|
|2022|CVPR||[Fourier PlenOctrees for Dynamic Radiance Field Rendering in Real-time](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_Fourier_PlenOctrees_for_Dynamic_Radiance_Field_Rendering_in_Real-Time_CVPR_2022_paper.pdf)|
|2022|CVPR|[Torch](https://github.com/sunset1995/DirectVoxGO)|[Direct Voxel Grid Optimization: Super-fast Convergence for Radiance Fields Reconstruction](https://openaccess.thecvf.com/content/CVPR2022/papers/Sun_Direct_Voxel_Grid_Optimization_Super-Fast_Convergence_for_Radiance_Fields_Reconstruction_CVPR_2022_paper.pdf)|
|2022|CVPR|[Torch](https://github.com/dvlab-research/EfficientNeRF)|[EfficientNeRF – Efficient Neural Radiance Fields](https://openaccess.thecvf.com/content/CVPR2022/papers/Hu_EfficientNeRF__Efficient_Neural_Radiance_Fields_CVPR_2022_paper.pdf)|
|2022|CVPR||[Mip-NeRF 360: Unbounded Anti-Aliased Neural Radiance Fields](https://openaccess.thecvf.com/content/CVPR2022/papers/Barron_Mip-NeRF_360_Unbounded_Anti-Aliased_Neural_Radiance_Fields_CVPR_2022_paper.pdf)|

### Editing

|Year|Conf|Code|Title|
|:-:|:-:|:-:|:-:|
|2022|CVPR||[NeRF-Editing: Geometry Editing of Neural Radiance Fields](https://openaccess.thecvf.com/content/CVPR2022/papers/Yuan_NeRF-Editing_Geometry_Editing_of_Neural_Radiance_Fields_CVPR_2022_paper.pdf)|
|2022|CVPR||[RigNeRF: Fully Controllable Neural 3D Portraits](https://openaccess.thecvf.com/content/CVPR2022/papers/Athar_RigNeRF_Fully_Controllable_Neural_3D_Portraits_CVPR_2022_paper.pdf)|

### Few Shot

|Year|Conf|Code|Title|
|:-:|:-:|:-:|:-:|
|2022|CVPR||[Dense Depth Priors for Neural Radiance Fields from Sparse Input Views](https://openaccess.thecvf.com/content/CVPR2022/papers/Roessle_Dense_Depth_Priors_for_Neural_Radiance_Fields_From_Sparse_Input_CVPR_2022_paper.pdf)|
|2022|CVPR|[TF](https://m-niemeyer.github.io/regnerf)|[RegNeRF: Regularizing Neural Radiance Fields for View Synthesis from Sparse Inputs](https://openaccess.thecvf.com/content/CVPR2022/papers/Niemeyer_RegNeRF_Regularizing_Neural_Radiance_Fields_for_View_Synthesis_From_Sparse_CVPR_2022_paper.pdf)|
|2022|CVPR|[Project Page](https://sirwyver.github.io/AutoRF/)|[AutoRF: Learning 3D Object Radiance Fields from Single View Observation](https://openaccess.thecvf.com/content/CVPR2022/papers/Muller_AutoRF_Learning_3D_Object_Radiance_Fields_From_Single_View_Observations_CVPR_2022_paper.pdf)|
|2022|CVPR|[Torch](https://github.com/mjmjeong/InfoNeRF)|[InfoNeRF: Ray Entropy Minimization for Few-Shot Neural Volume Rendering](https://openaccess.thecvf.com/content/CVPR2022/papers/Kim_InfoNeRF_Ray_Entropy_Minimization_for_Few-Shot_Neural_Volume_Rendering_CVPR_2022_paper.pdf)|
|2022|CVPR|[Torch](https://github.com/dunbar12138/DSNeRF)|[Depth-supervised NeRF: Fewer Views and Faster Training for Free](https://openaccess.thecvf.com/content/CVPR2022/papers/Deng_Depth-Supervised_NeRF_Fewer_Views_and_Faster_Training_for_Free_CVPR_2022_paper.pdf)|

### Generalization

|Year|Conf|Code|Title|
|:-:|:-:|:-:|:-:|
|2022|CVPR|[Code](https://github.com/cassiePython/CLIPNeRF)|[CLIP-NeRF: Text-and-Image Driven Manipulation of Neural Radiance Fields](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_CLIP-NeRF_Text-and-Image_Driven_Manipulation_of_Neural_Radiance_Fields_CVPR_2022_paper.pdf)|
|2022|CVPR|[Torch](https://github.com/MrTornado24/FENeRF)|[FENeRF: Face Editing in Neural Radiance Fields](https://openaccess.thecvf.com/content/CVPR2022/papers/Sun_FENeRF_Face_Editing_in_Neural_Radiance_Fields_CVPR_2022_paper.pdf)|
|2022|CVPR|[Project Page](https://ubc-vision.github.io/lolnerf/)|[LOLNeRF: Learn from One Look](https://openaccess.thecvf.com/content/CVPR2022/papers/Rebain_LOLNerf_Learn_From_One_Look_CVPR_2022_paper.pdf)|
|2022|CVPR||[CoNeRF: Controllable Neural Radiance Fields](https://openaccess.thecvf.com/content/CVPR2022/papers/Kania_CoNeRF_Controllable_Neural_Radiance_Fields_CVPR_2022_paper.pdf)|
|2022|CVPR||[StylizedNeRF: Consistent 3D Scene Stylization as Stylized NeRF via 2D-3D Mutual Learning](https://openaccess.thecvf.com/content/CVPR2022/papers/Huang_StylizedNeRF_Consistent_3D_Scene_Stylization_As_Stylized_NeRF_via_2D-3D_CVPR_2022_paper.pdf)|
|2022|CVPR|[Torch](https://github.com/CrisHY1995/headnerf)|[HeadNeRF: A Real-time NeRF-based Parametric Head Model](https://openaccess.thecvf.com/content/CVPR2022/papers/Hong_HeadNeRF_A_Real-Time_NeRF-Based_Parametric_Head_Model_CVPR_2022_paper.pdf)|
|2022|CVPR|[Torch](https://github.com/primecai/Pix2NeRF)|[Pix2NeRF: Unsupervised Conditional π-GAN for Single Image to NeuralRadiance Fields Translation](https://openaccess.thecvf.com/content/CVPR2022/papers/Cai_Pix2NeRF_Unsupervised_Conditional_p-GAN_for_Single_Image_to_Neural_Radiance_CVPR_2022_paper.pdf)|

### Image Restoration

|Year|Conf|Code|Title|
|:-:|:-:|:-:|:-:|
|2022|CVPR|[Project Page](https://noise-aware-nerf.github.io/)|[NAN: Noise-Aware NeRFs for Burst-Denoising](https://openaccess.thecvf.com/content/CVPR2022/papers/Pearl_NAN_Noise-Aware_NeRFs_for_Burst-Denoising_CVPR_2022_paper.pdf)|
|2022|CVPR||[NeRF in the Dark: High Dynamic Range View Synthesis from Noisy Raw Images](https://openaccess.thecvf.com/content/CVPR2022/papers/Mildenhall_NeRF_in_the_Dark_High_Dynamic_Range_View_Synthesis_From_CVPR_2022_paper.pdf)|
|2022|CVPR|[Torch](https://github.com/limacv/Deblur-NeRF)|[Deblur-NeRF: Neural Radiance Fields from Blurry Images](https://openaccess.thecvf.com/content/CVPR2022/papers/Ma_Deblur-NeRF_Neural_Radiance_Fields_From_Blurry_Images_CVPR_2022_paper.pdf)|

### Large-Scale Scene

|Year|Conf|Code|Title|
|:-:|:-:|:-:|:-:|
|2022|CVPR|[Code](https://github.com/jetd1/NeRFusion)|[NeRFusion: Fusing Radiance Fields for Large-Scale Scene Reconstruction](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhang_NeRFusion_Fusing_Radiance_Fields_for_Large-Scale_Scene_Reconstruction_CVPR_2022_paper.pdf)|
|2022|CVPR||[Mega-NeRF: Scalable Construction of Large-Scale NeRFs for Virtual Fly-Throughs](https://openaccess.thecvf.com/content/CVPR2022/papers/Turki_Mega-NERF_Scalable_Construction_of_Large-Scale_NeRFs_for_Virtual_Fly-Throughs_CVPR_2022_paper.pdf)|
|2022|CVPR||[Block-NeRF: Scalable Large Scene Neural View Synthesis](https://openaccess.thecvf.com/content/CVPR2022/papers/Tancik_Block-NeRF_Scalable_Large_Scene_Neural_View_Synthesis_CVPR_2022_paper.pdf)|
|2022|CVPR|[Torch](https://github.com/rover-xingyu/Ha-NeRF)|[Hallucinated Neural Radiance Fields in the Wild](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_Hallucinated_Neural_Radiance_Fields_in_the_Wild_CVPR_2022_paper.pdf)|

### Human

|Year|Conf|Code|Title|
|:-:|:-:|:-:|:-:|
|2022|CVPR||[Structured Local Radiance Fields for Human Avatar Modeling](https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_Structured_Local_Radiance_Fields_for_Human_Avatar_Modeling_CVPR_2022_paper.pdf)|
|2022|CVPR|[Code](https://github.com/pfnet-research/surface-aligned-nerf)|[Surface-Aligned Neural Radiance Fields for Controllable 3D Human Synthesis](https://openaccess.thecvf.com/content/CVPR2022/papers/Xu_Surface-Aligned_Neural_Radiance_Fields_for_Controllable_3D_Human_Synthesis_CVPR_2022_paper.pdf)|
|2022|CVPR|[Torch](https://github.com/chungyiweng/humannerf)|[HumanNeRF: Free-viewpoint Rendering of Moving People from Monocular Video](https://openaccess.thecvf.com/content/CVPR2022/papers/Weng_HumanNeRF_Free-Viewpoint_Rendering_of_Moving_People_From_Monocular_Video_CVPR_2022_paper.pdf)|
|2022|CVPR||[DoubleField: Bridging the Neural Surface and Radiance Fields for High-fidelity Human Reconstruction and Rendering](https://openaccess.thecvf.com/content/CVPR2022/papers/Shao_DoubleField_Bridging_the_Neural_Surface_and_Radiance_Fields_for_High-Fidelity_CVPR_2022_paper.pdf)|


### Others
|Year|Conf|Code|Title|
|:-:|:-:|:-:|:-:|
|2022|CVPR|[Project Page](https://www.kecl.ntt.co.jp/people/kaneko.takuhiro/projects/ar-nerf/)|[AR-NeRF: Unsupervised Learning of Depth and Defocus Effects from Natural Images with Aperture Rendering Neural Radiance Fields](https://openaccess.thecvf.com/content/CVPR2022/papers/Kaneko_AR-NeRF_Unsupervised_Learning_of_Depth_and_Defocus_Effects_From_Natural_CVPR_2022_paper.pdf)|


## Datasets

## Talks

## Blogs

## Links
