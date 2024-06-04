# Advancing Text-Driven Chest X-Ray Generation with Policy-Based Reinforcement Learning
#### Early Accepted @ MICCAI 2024 
We will release the code soon. Stay tuned!

[[Project Page]](https://micv-yonsei.github.io/cxrl2024/) [[arXiv]](https://arxiv.org/pdf/2403.06516)  
<br>
![image](https://github.com/MICV-yonsei/EAGLE/assets/44921488/ea9a3c60-e697-4613-91da-23da921373dc)
> #### **Advancing Text-Driven Chest X-Ray Generation with Policy-Based Reinforcement Learning**<be>  
>International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI) 2024  
>Woojung Han*, Chanyoung Kim*, Dayun Ju, Yumin Shim, Seong Jae Hwang  
>Yonsei University
### Abstract
Recent advances in text-conditioned image generation diffusion models have begun paving the way for new opportunities in modern medical domain, in particular, generating Chest X-rays (CXRs) from diagnostic reports. Nonetheless, to further drive the diffusion models to generate CXRs that faithfully reflect the complexity and diversity of real data, it has become evident that a nontrivial learning approach is needed. In light of this, we propose **CXRL**, a framework motivated by the potential of reinforcement learning (RL). Specifically, we integrate a policy gradient RL approach with well-designed multiple distinctive CXR-domain specific reward models. This approach guides the diffusion denoising trajectory, achieving precise CXR posture and pathological details. Here, considering the complex medical image environment, we present "RL with Comparative Feedback" (RLCF) for the reward mechanism, a human-like comparative evaluation that is known to be more effective and reliable in complex scenarios compared to direct evaluation. Our CXRL framework includes jointly optimizing learnable adaptive condition embeddings (ACE) and the image generator, enabling the model to produce more accurate and higher perceptual CXR quality. Our extensive evaluation of the MIMIC-CXR-JPG dataset demonstrates the effectiveness of our RL-based tuning approach. Consequently, our CXRL generates pathologically realistic CXRs, establishing a new standard for generating CXRs with high fidelity to real-world clinical scenarios.

## Citation
If you found this code useful, please cite the following paper:  
```
@InProceedings{2024cxrl,
    author    = {Han, Woojung and Kim, Chanyoung and Ju, Dayun and Shim, Yumin and Hwang, Seong Jae},
    title     = {Advancing Text-Driven Chest X-Ray Generation with Policy-Based Reinforcement Learning},
    booktitle = {International Conference on Medical Image Computing and Computer-Assisted Intervention},
    year      = {2024},
    organization={Springer}
}
```
