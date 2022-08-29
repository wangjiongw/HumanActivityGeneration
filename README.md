# HumanActivityGeneration

Materials for human action generation

Diffusion models | VQVAE

## Contents

- [HumanActivityGeneration](#humanactivitygeneration)
  - [Contents](#contents)
  - [References](#references)
  - [Image Generation](#image-generation)
  - [Video Generation](#video-generation)
  - [Text2Motion](#text2motion)
    - [Datasets](#datasets)
  - [Dance Generation](#dance-generation)
    - [Datasets](#datasets-1)

---

## References

- 54、Diffusion Model扩散模型理论与完整PyTorch代码详细解读 [[Bilibili]](https://www.bilibili.com/video/BV1b541197HX?from=search&seid=1294797900935775585&spm_id_from=333.337.0.0&vd_source=5488316887e189ecd5e1f2cf52edaccf)
- Awesome-Diffusion-Models [[Github]](https://github.com/heejkoo/Awesome-Diffusion-Models/blob/main/README.md)
- Understanding Diffusion Models: A Unified Perspective [[Paper]](https://arxiv.org/pdf/2208.11970.pdf)

## Image Generation

**DDPM**: Denoising Diffusion Probabilistic Models [[Paper]](https://proceedings.neurips.cc/paper/2020/hash/4c5bcfec8584af0d967f1ab10179ca4b-Abstract.html)

**DDIM**: Improved Denoising Diffusion Probabilistic Models (NeurIPS-21) [[Paper]](https://proceedings.mlr.press/v139/nichol21a.html)

Diffusion Models Beat GANs on Image Synthesis [[Paper]](https://arxiv.org/abs/2105.05233)

Improved Denoising Diffusion Probabilistic Models (ICLR2021) [[Paper]](https://arxiv.org/abs/2102.09672) [[Code]](https://github.com/openai/improved-diffusion)

**VQDiffusion:** Vector Quantized Diffusion Model for Text-to-Image Synthesis(CVPR2022) [[Code]](https://github.com/microsoft/VQ-Diffusion) [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Gu_Vector_Quantized_Diffusion_Model_for_Text-to-Image_Synthesis_CVPR_2022_paper.html)  [[Video]](https://www.bilibili.com/video/BV13Y4y1r7CH?from=search&seid=7677516310805155031&spm_id_from=333.337.0.0&vd_source=5488316887e189ecd5e1f2cf52edaccf)

> 为了解决diffusion速度慢，需要上千次的迭代才能生成最终的结果。提出了改进方案：通过 VQVAE 降低 inference 的图像尺寸

## Video Generation

Diffusion Models for Video Prediction and Infilling  [[Paper]](https://arxiv.org/abs/2206.07696)

MCVD: Masked Conditional Video Diffusion for Prediction, Generation, and Interpolation  以前或者后视频帧作为条件去预测所需要的视频帧 [[Code]](https://github.com/voletiv/mcvd-pytorch) [[Paper]](http://128.84.4.18/abs/2205.09853)

Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion(CVPR202) [[Code]](https://github.com/Gutianpei/MID) [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Gu_Stochastic_Trajectory_Prediction_via_Motion_Indeterminacy_Diffusion_CVPR_2022_paper.html)

> 通过diffusion model预测trajectory

## Text2Motion

### Datasets

- **BABEL**: Bodies, Action and Behavior with English Labels [[Project]](https://babel.is.tue.mpg.de/) [[Paper]](https://arxiv.org/pdf/2106.09696.pdf) [[Code]](https://github.com/abhinanda-punnakkal/BABEL)

- **KIT** Motion-Language Dataset [[Project]](https://motion-database.humanoids.kit.edu/)

- **HumanML3D**
  Generating Diverse and Natural 3D Human Motions from Text  (CVPR2022) [[Code]](https://github.com/EricGuo5513/text-to-motion) [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Guo_Generating_Diverse_and_Natural_3D_Human_Motions_From_Text_CVPR_2022_paper.html)

Generating Diverse and Natural 3D Human Motions from Text  (CVPR2022) [[Code]](https://github.com/EricGuo5513/text-to-motion) [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Guo_Generating_Diverse_and_Natural_3D_Human_Motions_From_Text_CVPR_2022_paper.html)

TM2T: Stochastic and Tokenized Modeling for the Reciprocal Generation of 3D Human Motions and Texts (ECCV2022) [[Code]](https://github.com/EricGuo5513/TM2T) [[Paper]](https://arxiv.org/abs/2207.01696)

Diverse Dance Synthesis via Keyframes with Transformer Controllers [[Paper]](https://arxiv.org/abs/2207.05906)

TEMOS: Generating diverse human motions from textual descriptions (ECCV 2022 (Oral)) [[Code]](https://github.com/Mathux/TEMOS) [[Paper]](https://arxiv.org/abs/2204.14109)      

## Dance Generation

### Datasets

- **AIST++**: AI Choreographer: Music Conditioned 3D Dance Generation with AIST++ [[Paper]](https://arxiv.org/abs/2101.08779) [[Project]](https://google.github.io/aistplusplus_dataset/index.html) [[Code]](https://github.com/google/aistplusplus_api)
- **BRACE**:

A Brand New Dance Partner: Music-Conditioned Pluralistic Dancing Controlled by Multiple Dance Genres (CVPR2022)  [[Code]](https://github.com/jw09191/MNET) [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Kim_A_Brand_New_Dance_Partner_Music-Conditioned_Pluralistic_Dancing_Controlled_by_CVPR_2022_paper.html)

Bailando: 3D Dance Generation by Actor-Critic GPT with Choreographic Memory (CVPR2022) [[Code]](https://github.com/lisiyao21/Bailando) [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Siyao_Bailando_3D_Dance_Generation_by_Actor-Critic_GPT_With_Choreographic_Memory_CVPR_2022_paper.html) [[Video]](https://www.bilibili.com/video/BV1zW4y167oT?from=search&seid=10529527414460118364&spm_id_from=333.337.0.0)

Collaborative Neural Rendering using Anime Character Sheets [[Paper]](https://arxiv.org/abs/2207.05378) [[Code]](https://github.com/megvii-research/CoNR)

---


Based on the Survey from [Yupei's Repo](https://github.com/YupeiLin2388/Paper-Diffusion-T2M)
