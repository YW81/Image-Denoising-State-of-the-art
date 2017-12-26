# Image Denoising State-of-the-art

A curated list of image denoising resources and a benchmark for image denoising approaches.

## State-of-the-art algorithms
#### Filter
 * BD3M [[Web]](http://www.cs.tut.fi/~foi/GCF-BM3D/) [[Code]](http://www.cs.tut.fi/~foi/GCF-BM3D/BM3D.zip) [[PDF]](http://www.cs.tut.fi/~foi/GCF-BM3D/SPIE08_deblurring.pdf)
   * Image restoration by sparse 3D transform-domain collaborative filtering (SPIE Electronic Imaging 2008), Dabov et al.
 * Activity-tuned Image Filtering [[PDF]](https://arxiv.org/pdf/1707.02637.pdf)
   * Local Activity-tuned Image Filtering for Noise Removal and Image Smoothing (Arxiv 2017), Lijun Zhao, Jie Liang, Huihui Bai, Lili Meng, Anhong Wang, and Yao Zhao.

#### Sparse Coding
 * KSVD [[Web]](http://www.cs.technion.ac.il/~ronrubin/software.html) [[Code]](https://github.com/jbhuang0604/SelfSimSR/tree/master/Lib/KSVD) [[PDF]](http://www.egr.msu.edu/~aviyente/elad06.pdf)
   * Image Denoising Via Sparse and Redundant Representations Over Learned Dictionaries (TIP2006), Elad et al.
 * NCSR [[Web]](http://www4.comp.polyu.edu.hk/~cslzhang/NCSR.htm) [[Code]](http://www4.comp.polyu.edu.hk/~cslzhang/code/NCSR.rar) [[PDF]](http://www4.comp.polyu.edu.hk/~cslzhang/paper/NCSR_TIP_final.pdf)
   * Nonlocally Centralized Sparse Representation for Image Restoration (TIP2012), Dong et al.
 * LSSC [[Web]](http://www.di.ens.fr/~fbach/) [Code] [[PDF]](http://www.di.ens.fr/~fbach/iccv09_mairal.pdf)
   * Non-local Sparse Models for Image Restoration (ICCV2009), Mairal et al.
 * GSR [[Web]](https://jianzhang.tech/projects/GSR/) [[Code]](http://csjianzhang.github.io/codes/GSR_Code_Package_3.0.zip) [[PDF]](http://csjianzhang.github.io/papers/TIP2014_single.pdf)
   * Group-based Sparse Representation for Image Restoration (TIP2014), Zhang et al.
  
#### Effective Prior
 * EPLL [[Web]](https://people.csail.mit.edu/danielzoran/) [[Code]](https://people.csail.mit.edu/danielzoran/epllcode.zip) [[PDF]](http://people.ee.duke.edu/~lcarin/EPLICCVCameraReady.pdf)
   * From Learning Models of Natural Image Patches to Whole Image Restoration (ICCV2011), Zoran et al.
 * GHP [[Web]][[Code]](https://github.com/tingfengainiaini/GHPBasedImageRestoration) [[PDF]](https://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Zuo_Texture_Enhanced_Image_2013_CVPR_paper.pdf)
   * Texture Enhanced Image Denoising via Gradient Histogram Preservation (CVPR2013), Zuo et al.
   
#### Low Rank
 * SAIST [[Web]](http://see.xidian.edu.cn/faculty/wsdong/wsdong_Publication.htm) [Code] [[PDF]](http://see.xidian.edu.cn/faculty/wsdong/Papers/Journal/TIP_LASSC.pdf)
   * Nonlocal image restoration with bilateral variance estimation: a low-rank approach (TIP2013), Dong et al.
 * WNNM [[Web]](https://sites.google.com/site/shuhanggu/home) [[Code]](http://www4.comp.polyu.edu.hk/~cslzhang/code/WNNM_code.zip) [[PDF]](https://pdfs.semanticscholar.org/6d55/6272625b672ba54b5ab3d9e6474088a4b78f.pdf)
   * Weighted Nuclear Norm Minimization with Application to Image Denoising (CVPR2014), Gu et al.
 * Multi-channel Weighted Nuclear Norm [[PDF]](https://arxiv.org/pdf/1705.09912.pdf)
   * Multi-channel Weighted Nuclear Norm Minimization for Real Color Image Denoising (Arxiv 2017), Jun Xu, Lei Zhang, David Zhang, and Xiangchu Feng.
   
#### Deep Learning
 * TNRD [[Web]](http://www.icg.tugraz.at/Members/Chenyunjin/about-yunjin-chen) [[Code]](https://www.dropbox.com/s/8j6b880m6ddxtee/TNRD-Codes.zip?dl=0) [[PDF]](https://arxiv.org/pdf/1508.02848.pdf)
   * Trainable nonlinear reaction diffusion: A flexible framework for fast and effective image restoration (TPAMI2016), Chen et al.
 * DnCNN [[Web]](https://github.com/cszn/DnCNN) [[PDF]](https://arxiv.org/pdf/1608.03981v1.pdf)
   * Beyond a Gaussian Denoiser: Residual Learning of Deep CNN for Image Denoising (TIP2017), Zhang et al.
 * DAAM [[Web]](https://arxiv.org/abs/1612.06508) [[PDF]](https://arxiv.org/pdf/1612.06508.pdf)
   * Deeply Aggregated Alternating Minimization for Image Restoration (Arxiv2016), Youngjung Kim et al.
 * Adversirial Denoising [[PDF]](https://arxiv.org/pdf/1708.00159.pdf)
   * Image Denoising via CNNs: An Adversarial Approach (Arxiv2017), Nithish Divakar, R. Venkatesh Babu.
 * Unrolled Optimization Deep Priors [[PDF]](https://arxiv.org/pdf/1705.08041.pdf)
   * Unrolled Optimization with Deep Priors (Arxiv2017), Steven Diamond, Vincent Sitzmann, Felix Heide, Gordon Wetzstein.
 * Wider Network [[PDF]](https://arxiv.org/pdf/1707.05414.pdf)
   * Going Wider with Convolution for Image Denoising (Arxiv2017), Peng Liu, Ruogu Fang.
 * Recurrent Inference Machines [[PDF]](https://arxiv.org/pdf/1706.04008.pdf)
   * Recurrent Inference Machines for Solving Inverse Problems, Patrick Putzky, Max Welling.
 * Learning Pixel-Distribution Prior [[PDF]](https://arxiv.org/pdf/1707.09135.pdf)
   * Learning Pixel-Distribution Prior with Wider Convolution for Image Denoising (Arxiv2017), Peng Liu, Ruogu Fang.
   
#### Combined with High-Level Tasks
 * Meets High-level Tasks [[PDF]](https://arxiv.org/pdf/1706.04284.pdf) [[Code]](https://github.com/wenbihan/DeepDenoising) 
   * When Image Denoising Meets High-Level Vision Tasks: A Deep Learning Approach (Arxiv2017), Ding Liu, Bihan Wen, Xianming Liu, Thomas S. Huang.
 * Class-Specific Denoising [[PDF]](https://arxiv.org/pdf/1706.02867.pdf)
   * Class-Specific Poisson Denoising By Patch-Based Importance Sampling (Arxiv2017), Milad Niknejad, Jose M. Bioucas-Dias, Mario A. T. Figueiredo.
   
#### Benchmark
 * Benchmark [[PDF]](https://arxiv.org/pdf/1707.01313.pdf)
   * Benchmarking Denoising Algorithms with Real Photographs (Arxiv2017), Tobias Plotz, Stefan Roth.
