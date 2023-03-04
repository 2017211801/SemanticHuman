# Learning Semantic-Aware Disentangled Representation for Flexible 3D Human Body Editing
Xiaokun Sun, Qiao Feng, Xiongzheng Li, Jinsong Zhang, Yu-Kun Lai, Jingyu Yang, Kun Li. "Learning Semantic-Aware Disentangled Representation for Flexible 3D Human Body Editing". In Proc. CVPR, 2023.

# Overview
<p align="center">
<img src=/img1.png />
</p>

# Abstract
3D human body representation learning has received increasing attention in recent years. However, existing works cannot flexibly, controllably and accurately represent human bodies, limited by coarse semantics and unsatisfactory representation capability, particularly in the absence of supervised data. In this paper, we propose a human body representation with fine-grained semantics and high reconstruction-accuracy in an unsupervised setting. Specifically, we establish a correspondence between latent vectors and geometric measures of body parts by designing a part-aware skeleton-separated decoupling strategy, which facilitates controllable editing of human bodies by modifying the corresponding latent codes. With the help of a bone-guided auto-encoder and an orientation-adaptive weighting strategy, our representation can be trained in an unsupervised manner. With the geometrically meaningful latent space, it can be applied to a wide range of applications, from human body editing to latent code interpolation and shape style transfer. Experimental results on public datasets demonstrate the accurate reconstruction and flexible editing abilities of the proposed method. The code will be released for research purposes.

# Others
Coming soon

## Citation
If you find this code useful for your research, please use the following BibTeX entry.
```
@inproceedings{SemanticHuman,
  author = {Xiaokun Sun, Qiao Feng, Xiongzheng Li, Jinsong Zhang, Yu-Kun Lai, Jingyu Yang, Kun Li},
  title = {Learning Semantic-Aware Disentangled Representation for Flexible 3D Human Body Editing},
  booktitle = {CVPR},
  year={2023},
}
```
