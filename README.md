# Reading List

This repo contains papers for my research. The covered topics include (but not limited to): 
- Transfer learning & transferability
- Image Inpainting
- Self-Supervised Representation Learning
- GANs


---------
### Transfer Learning & Transferability
- **(06/2020)** [What makes instance discrimination good for transfer learning?](https://arxiv.org/abs/2006.06606)
- **(02/2020)** [LEEP: A New Measure to Evaluate Transferability of Learned Representations](https://arxiv.org/abs/2002.12462)
- **(02/2020)** [Skip Connections Matter: On the Transferability of Adversarial Examples Generated with ResNets](https://arxiv.org/abs/2002.05990)
- **(09/2019)** [Towards Understanding the Transferability of Deep Representation](https://arxiv.org/abs/1909.12031)
- **(08/2019)** [Transferability and Hardness of Supervised Classification Tasks](https://arxiv.org/abs/1908.08142)
- **(04/2019)** [Representation Similarity Analysis for Efficient Task taxonomy & Transfer Learning](https://arxiv.org/abs/1904.11740)
- **(12/2018)** [An Information-Theoretic Metric of Transferability for Task Transfer Learning](https://openreview.net/forum?id=BkxAUjRqY7)
- **(04/2018)** [Taskonomy: Disentangling Task Transfer Learning](https://arxiv.org/abs/1804.08328)

---------
### Image Inpainting
- **(12/2020)** [Large Scale Image Completion via Co-Modulated Generative Adversarial Networks](https://arxiv.org/pdf/2103.10428v1.pdf)
- **(11/2020)** [Image Inpainting with Learnable Feature Imputation](https://arxiv.org/pdf/2011.01077v1.pdf)
- **(09/2020)** [Texture Memory-Augmented Deep Patch-Based Image Inpainting](https://arxiv.org/pdf/2009.13240v1.pdf)
- **(10/2019)** [Free-Form Image Inpainting with Gated Convolution](https://arxiv.org/pdf/1806.03589.pdf)
  - gated convolution to learn dynamic feature selection
  - patch-based GAN discriminator (SN-PatchGAN)
- **(05/2019)** [Coherent Semantic Attention for Image Inpainting](https://arxiv.org/pdf/1905.12384v3.pdf)
- **(01/2019)** [EdgeConnect: Generative Image Inpainting with Adversarial Edge Learning](https://arxiv.org/pdf/1901.00212.pdf)
- **(12/2018)** [Image Inpainting for Irregular Holes Using Partial Convolutions](https://arxiv.org/abs/1804.07723)
  - inpainting independent of the hole initialization values and without any additional post- processing
  - inpainting with irregular masks: partial convolution layer
- **(10/2018)** [Image Inpainting via Generative Multi-column Convolutional Neural Networks](https://arxiv.org/abs/1810.08771)
  - generator with multiple parallel encoder-decoder branches
  - ID-MRF regularization in training phrase to address semantic structure matching
  - confidence driven reconstruction loss
- **(04/2018)** [Shift-Net: Image Inpainting via Deep Feature Rearrangement](https://arxiv.org/abs/1801.09392)
  - shift-connection layer: connect encoder feature of known regions to decoder features of missing regions
- **(03/2018)** [Generative Image Inpainting with Contextual Attention](https://arxiv.org/abs/1801.07892)
  - coarse-to-fine network architecture
  - contextual attention to attento to related features from spatially distant locations.
  - WGANS + spatially discounted reconstruction loss.
  - great literature review (including spatial attention)
- **(03/2018)** [Patch-Based Image Inpainting with Generative Adversarial Networks](https://arxiv.org/abs/1803.07422)
  - global GAN + patch GAN (Image-to-image translation with conditional adversarial networks)
  - great literature review of image inpainting
- **(11/2017)** [Deep Image Prior](https://arxiv.org/pdf/1711.10925v4.pdf)
- **(07/2017)** [Globally and Locally Consistent Image Completion](http://iizuka.cs.tsukuba.ac.jp/projects/completion/data/completion_sig2017.pdf)
  - completion network + global context discriminator + local context discriminator
- **(07/2017)** [Semantic Image Inpainting with Deep Generative Models](https://arxiv.org/pdf/1607.07539v3.pdf)
- **(11/2016)** [High-Resolution Image Inpainting using Multi-Scale Neural Patch Synthesis](https://arxiv.org/abs/1611.09969)
  - context-encoder architecture; content loss/constraint + local textual constraint
- **(11/2016)** [Context Encoders: Feature Learning by Inpainting](https://arxiv.org/abs/1604.07379)
  - encoder-decoder architecture; channel-wise fully connected layer; reconstruction loss + adverserial loss
- **(07/2009)** [PatchMatch: A Randomized Correspondence Algorithm for Structural Image Editing](https://dl.acm.org/doi/pdf/10.1145/1531326.1531330)
- **(07/2007)** [Scene Completion Using Millions of Photographs](http://graphics.cs.cmu.edu/projects/scene-completion/scene-completion.pdf)
- **(2001)** [Image Quilting for Texture Synthesis and Transfer](https://dl.acm.org/doi/pdf/10.1145/383259.383296)
- **(2001)** [Filling-In by Joint Interpolation of Vector Fields and Gray Levels](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=935036)
---------
### Self-Supervised Representation Learning
- **(02/2021)** [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020)
- **(09/2020)** [Bootstrap your own latent: A new approach to self-supervised Learning](https://arxiv.org/abs/2006.07733)
- **(09/2020)** [CURL: Contrastive Unsupervised Representations for Reinforcement Learning](https://arxiv.org/abs/2004.04136)
- **(07/2020)** [A Simple Framework for Contrastive Learning of Visual Representations](https://arxiv.org/abs/2002.05709)
- **(03/2020)** [Improved Baselines with Momentum Contrastive Learning](https://arxiv.org/abs/2003.04297)
- **(03/2020)** [Momentum Contrast for Unsupervised Visual Representation Learning](https://arxiv.org/abs/1911.05722)
- **(01/2019)** [Representation Learning with Contrastive Predictive Coding](https://arxiv.org/abs/1807.03748)
- **(05/2018)** [Unsupervised Feature Learning via Non-Parametric Instance-level Discrimination](https://arxiv.org/abs/1805.01978v1)
- **(04/2017)** [Split-Brain Autoencoders: Unsupervised Learning by Cross-Channel Predictio](https://arxiv.org/abs/1611.09842)
- **(04/2017)** [Adversarial Feature Learning](https://arxiv.org/abs/1605.09782)
- **(11/2016)** [Context Encoders: Feature Learning by Inpainting](https://arxiv.org/abs/1604.07379)
- **(01/2016)** [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434)
- **(07/2008)** [Extracting and composing robust features with denoising autoencoders](https://www.cs.toronto.edu/~larocheh/publications/icml-2008-denoising-autoencoders.pdf)

---------
## GAN: Generative Adversial Networks
