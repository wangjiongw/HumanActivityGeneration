# HumanActivityGeneration
Materials for human action generation


### Datasets
- BABEL: Bodies, Action and Behavior with English Labels [[project]](https://babel.is.tue.mpg.de/) [[paper]](https://arxiv.org/pdf/2106.09696.pdf) [[code]](https://github.com/abhinanda-punnakkal/BABEL)

- KIT Motion-Language Dataset

- HumanML3D
  Generating Diverse and Natural 3D Human Motions from Text  (CVPR2022) [[code]](https://github.com/EricGuo5513/text-to-motion) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Guo_Generating_Diverse_and_Natural_3D_Human_Motions_From_Text_CVPR_2022_paper.html)


## diffusion

### 理论

DDPM (NeurIPS-20) [Denoising Diffusion Probabilistic Models](https://proceedings.neurips.cc/paper/2020/hash/4c5bcfec8584af0d967f1ab10179ca4b-Abstract.html)

DDIM(NeurIPS-21)：[Improved Denoising Diffusion Probabilistic Models](https://proceedings.mlr.press/v139/nichol21a.html)

参考视频: [54、Diffusion Model扩散模型理论与完整PyTorch代码详细解读](https://www.bilibili.com/video/BV1b541197HX?from=search&seid=1294797900935775585&spm_id_from=333.337.0.0&vd_source=5488316887e189ecd5e1f2cf52edaccf)

### Application

Stochastic Trajectory Prediction via Motion Indeterminacy Diffusion(CVPR202):通过diffusion model预测trajectory [[code]](https://github.com/Gutianpei/MID) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Gu_Stochastic_Trajectory_Prediction_via_Motion_Indeterminacy_Diffusion_CVPR_2022_paper.html)

*[VQDiffusion]* Vector Quantized Diffusion Model for Text-to-Image Synthesis(CVPR2022) :为了解决diffusion速度慢，需要上千次的迭代才能生成最终的结果。提出了改进方案：通过 VQVAE 降低 inference 的图像尺寸 [[github]](https://github.com/microsoft/VQ-Diffusion) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Gu_Vector_Quantized_Diffusion_Model_for_Text-to-Image_Synthesis_CVPR_2022_paper.html)  [[video]](https://www.bilibili.com/video/BV13Y4y1r7CH?from=search&seid=7677516310805155031&spm_id_from=333.337.0.0&vd_source=5488316887e189ecd5e1f2cf52edaccf)


### Video Generation

Diffusion Models for Video Prediction and Infilling  [[paper]](https://arxiv.org/abs/2206.07696)

MCVD: Masked Conditional Video Diffusion for Prediction, Generation, and Interpolation  以前或者后视频帧作为条件去预测所需要的视频帧 [[code]](https://github.com/voletiv/mcvd-pytorch) [[paper]](http://128.84.4.18/abs/2205.09853)

## Text2Motion

Generating Diverse and Natural 3D Human Motions from Text  (CVPR2022) [[code]](https://github.com/EricGuo5513/text-to-motion) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Guo_Generating_Diverse_and_Natural_3D_Human_Motions_From_Text_CVPR_2022_paper.html)

TM2T: Stochastic and Tokenized Modeling for the Reciprocal Generation of 3D Human Motions and Texts (ECCV2022)  [[code]](https://github.com/EricGuo5513/TM2T) [[paper]](https://arxiv.org/abs/2207.01696)

Diverse Dance Synthesis via Keyframes with Transformer Controllers    [[paper]](https://arxiv.org/abs/2207.05906)

TEMOS: Generating diverse human motions from textual descriptions[ECCV 2022 (Oral)]()           [[Code]](https://github.com/Mathux/TEMOS) [[Paper]](https://arxiv.org/abs/2204.14109)      

### Music2Dance

A Brand New Dance Partner: Music-Conditioned Pluralistic Dancing Controlled by Multiple Dance Genres(CVPR2022)  [[code]](https://github.com/jw09191/MNET) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Kim_A_Brand_New_Dance_Partner_Music-Conditioned_Pluralistic_Dancing_Controlled_by_CVPR_2022_paper.html)

Bailando: 3D Dance Generation by Actor-Critic GPT with Choreographic Memory (CVPR2022) [[code]](https://github.com/lisiyao21/Bailando) [[paper]  ](https://openaccess.thecvf.com/content/CVPR2022/html/Siyao_Bailando_3D_Dance_Generation_by_Actor-Critic_GPT_With_Choreographic_Memory_CVPR_2022_paper.html)[[vedio]](https://www.bilibili.com/video/BV1zW4y167oT?from=search&seid=10529527414460118364&spm_id_from=333.337.0.0)
