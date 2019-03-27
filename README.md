# Domain Adaptation
Detailed resources on unsupervised domain adapation(DA). It includes related papers and the codes. As you see, the list is also not comprehensive. You can pull requests as you will.

# Conference Papers

- **CLAN**: Taking A Closer Look at Domain Shift: Category-level Adversaries for Semantics Consistent Domain Adaptation [[CVPR2019]](https://arxiv.org/pdf/1809.09478.pdf)
- **SWD**: Sliced Wasserstein Discrepancy for Unsupervised Domain Adaptation [[CVPR2019]](https://arxiv.org/pdf/1903.04064.pdf)
- **Dhouib's**: Revisiting ($\epsilon$, $\gamma$, $\tau$)-similarity learning for domain adaptation [[NeurIPS2018]](http://papers.nips.cc/paper/7969-revisiting-epsilon-gamma-tau-similarity-learning-for-domain-adaptation.pdf)
- **CDAN**: Conditional Adversarial Domain Adaptation [[NeurIPS2018]](http://papers.nips.cc/paper/7436-conditional-adversarial-domain-adaptation.pdf)
- **Magliacane's**: Domain Adaptation by Using Causal Inference to Predict Invariant Conditional Distributions [[NeurIPS2018]](http://papers.nips.cc/paper/8282-domain-adaptation-by-using-causal-inference-to-predict-invariant-conditional-distributions.pdf)
- **Co-DA**: Co-regularized Alignment for Unsupervised Domain Adaptation [[NeurIPS2018]](http://papers.nips.cc/paper/8146-co-regularized-alignment-for-unsupervised-domain-adaptation.pdf)
- **JDDA**：Joint Domain Alignment and Discriminative Feature Learning for Unsupervised Deep Domain Adaptation [[arXiv 3 Nov 2018]](https://arxiv.org/pdf/1808.09347.pdf)
- **PADA**: Partial Adversarial Domain Adaptation [[ECCV2018]](http://openaccess.thecvf.com/content_ECCV_2018/html/Zhangjie_Cao_Partial_Adversarial_Domain_ECCV_2018_paper.html) [[Pytorch(Official)]](https://github.com/thuml/PADA)
- **GAKT**: Graph Adaptive Knowledge Transfer for Unsupervised Domain Adaptation [[ECCV2018]](http://openaccess.thecvf.com/content_ECCV_2018/html/Zhengming_Ding_Graph_Adaptive_Knowledge_ECCV_2018_paper.html)
- **Kang's**: Deep Adversarial Attention Alignment for Unsupervised Domain Adaptation: the Benefit of Target Expectation Maximization [[ECCV2018]](http://openaccess.thecvf.com/content_ECCV_2018/html/Guoliang_Kang_Deep_Adversarial_Attention_ECCV_2018_paper.html)
- **MEDA**: Visual Domain Adaptation with Manifold Embedded Distribution Alignment [[ACM MM2018]](https://arxiv.org/abs/1807.07258) [[Matlab(Official)]](https://github.com/jindongwang/transferlearning/tree/master/code/traditional/MEDA#meda-manifold-embedded-distribution-alignment)
- **CyCADA**: Cycle Consistent Adversarial Domain Adaptation [[ICML2018]](http://proceedings.mlr.press/v80/hoffman18a/hoffman18a.pdf) [[Pytorch(Official)]](https://github.com/jhoffman/cycada_release)
- **MSTN**: Learning Semantic Representations for Unsupervised Domain Adaptation [[ICML2018]](http://proceedings.mlr.press/v80/xie18c/xie18c.pdf) [[Tensorflow(Official)]](https://github.com/Mid-Push/Moving-Semantic-Transfer-Network)
- **DeppJDOT**: DeepJDOT: Deep Joint Distribution Optimal Transport for Unsupervised Domain Adaptation [[arXiv 27 Mar 2018]](https://arxiv.org/pdf/1803.10081.pdf) [[ECCV2018]](http://openaccess.thecvf.com/content_ECCV_2018/html/Bharath_Bhushan_Damodaran_DeepJDOT_Deep_Joint_ECCV_2018_paper.html)
- **Saito's**: Open Set Domain Adaptation by Backpropagation [[arXiv 27 Apr 2018]](https://arxiv.org/abs/1804.10427)  [[ECCV2018]](http://openaccess.thecvf.com/content_ECCV_2018/html/Kuniaki_Saito_Adversarial_Open_Set_ECCV_2018_paper.html) [[TensorFlow]](https://github.com/Mid-Push/Open_set_domain_adaptation) [[Pytorch]](https://github.com/YU1ut/openset-DA)
- **CPUA**: Simple Domain Adaptation with Class Prediction Uncertainty Alignment [[ICML2018 Poster]](https://arxiv.org/abs/1804.04448)
- **I2IAdapt**: Image to Image Translation for Domain Adaptation [[CVPR2018]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Murez_Image_to_Image_CVPR_2018_paper.pdf)
- **PDA**: Importance Weighted Adversarial Nets for Partial Domain Adaptation [[CVPR2018]](https://arxiv.org/abs/1803.09210)
- **MCD_DA**: Maximum Classifier Discrepancy for Unsupervised Domain Adaptation [[CVPR2018]](https://arxiv.org/abs/1712.02560) [[Pytorch(Official)]](https://github.com/mil-tokyo/MCD_DA)
- **RPTDA**: Residual Parameter Transfer for Deep Domain Adaptation [[CVPR2018]](https://arxiv.org/abs/1711.07714)
- **DIFA**: Adversarial Feature Augmentation for Unsupervised Domain Adaptation [[CVPR2018]](https://arxiv.org/abs/1711.08561) [[TensorFlow 1.3(Official)]](https://github.com/ricvolpi/adversarial-feature-augmentation)
- **SAN**: Partial Transfer Learning with Selective Adversarial Networks [[CVPR2018]](https://arxiv.org/abs/1707.07901)[[paper weekly]](http://www.paperweekly.site/papers/1388)
- **DupGAN**: Duplex Generative Adversarial Network for Unsupervised Domain Adaptation [[CVPR2018]](http://vipl.ict.ac.cn/uploadfile/upload/2018041610083083.pdf) [[Pytorch 0.1(Official)]](http://vipl.ict.ac.cn/view_database.php?id=6)
- **GTA**: Generate To Adapt: Aligning Domains using Generative Adversarial Networks [[CVPR2018]](https://arxiv.org/abs/1704.01705) [[Pytorch(Official)]](https://github.com/yogeshbalaji/Generate_To_Adapt)
- **SimNet**: Unsupervised Domain Adaptation with Similarity Learning [[CVPR2018]](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/1887.pdf)
- **KWC,KOT**: Aligning Infinite-Dimensional Covariance Matrices in Reproducing Kernel Hilbert Spaces for Domain Adaptation [[CVPR2018]](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/3383.pdf)
- **DCTN**: Deep Cocktail Network: Multi-source Unsupervised Domain Adaptation with Category Shift [[CVPR2018]](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/1880.pdf)
- **iCAN**: Collaborative and Adversarial Network for Unsupervised Domain Adaptation [[CVPR2018]](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/1410.pdf)
- **RAAN**: Re-Weighted Adversarial Adaptation Network for Unsupervised Domain Adaptation [[CVPR2018]](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/1224.pdf)
- **MADA**: Multi-Adversarial Domain Adaptation [[AAAI2018]](http://ise.thss.tsinghua.edu.cn/~mlong/doc/multi-adversarial-domain-adaptation-aaai18.pdf) [[Caffe(Official)]](https://github.com/thuml/MADA)
- **WDGRL**: Wasserstein Distance Guided Representation Learning for Domain Adaptation [[AAAI2018]](https://arxiv.org/abs/1707.01217) [[Tensorflow 1.3.0(Official)]](https://github.com/RockySJ/WDGRL) [[Pytorch]](https://github.com/jvanvugt/pytorch-domain-adaptation)
- **DIRT-T**: A DIRT-T Approach to Unsupervised Domain Adaptation [[ICLR2018]](https://openreview.net/forum?id=H1q-TM-AW) [[Tensorflow(Official)]](https://github.com/RuiShu/dirt-t)
- **MT**: Self-ensembling for Visual Domain Adaptation [[ICLR2018]](https://openreview.net/pdf?id=rkpoTaxA-) [[Pytorch(Official)]](https://github.com/Britefury/self-ensemble-visual-domain-adapt/)
- **CCN**: Learning to Cluster in Order to Transfer Across Domains and Tasks [[ICLR2018]](https://openreview.net/pdf?id=ByRWCqvT-)
- **MECA**: Minimal-Entropy Correlation Alignment for Unsupervised Deep Domain Adaptation [[ICLR2018]](https://openreview.net/forum?id=rJWechg0Z) [[Tensorflow(Official)]](https://github.com/pmorerio/minimal-entropy-correlation-alignment)
- **ATI**: Open Set Domain Adaptation [[ICCV2017]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Busto_Open_Set_Domain_ICCV_2017_paper.pdf) [[Matlab(Official)]](https://github.com/Heliot7/open-set-da)
- **AutoDIAL**: Automatic DomaIn Alignment Layers [[ICCV2017]](https://www.computer.org/csdl/proceedings/iccv/2017/1032/00/1032f077.pdf) [[Caffe(Official)]](https://github.com/ducksoup/autodial)
- **DA<sub>assoc</sub>**: Associative Domain Adaptation [[ICCV2017]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Haeusser_Associative_Domain_Adaptation_ICCV_2017_paper.pdf)[[Tensorflow(Official)]](https://github.com/haeusser/learning_by_association)
- **TAISL**: When Unsupervised Domain Adaptation Meets Tensor Representations [[ICCV2017]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Lu_When_Unsupervised_Domain_ICCV_2017_paper.pdf) [[Matlab(Official)]](https://github.com/poppinace/TAISL)
- **CCSA**: Unified Deep Supervised Domain Adaptation and Generalization [[ICCV2017]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Motiian_Unified_Deep_Supervised_ICCV_2017_paper.pdf) [[Keras(Official)]](https://github.com/samotiian/CCSA)
- **UNIT**: Unsupervised Image-to-Image Translation Networks [[NIPS2017]](https://papers.nips.cc/paper/6672-unsupervised-image-to-image-translation-networks.pdf) [[Pytorch(Official)]](https://github.com/mingyuliutw/UNIT)
- **Luo's**: Label Efficient Learning of Transferable Representations acrosss Domains and Tasks [[NIPS2017]](http://vision.stanford.edu/pdf/luo2017nips.pdf) [[Project]](http://alan.vision/nips17_website/)
- **JDOT**: Joint Distribution Optimal Transportation for Domain Adaptation [[NIPS2017]](http://papers.nips.cc/paper/6963-joint-distribution-optimal-transportation-for-domain-adaptation.pdf) [[Python(Official)]](https://github.com/rflamary/JDOT)
- **FADA**: Few-Shot Adversarial Domain Adaptation [[NIPS2017]](https://papers.nips.cc/paper/7244-few-shot-adversarial-domain-adaptation.pdf)
- **ADDA**: Adversarial Discriminative Domain Adaptation [[CVPR2017]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Tzeng_Adversarial_Discriminative_Domain_CVPR_2017_paper.pdf)  [[Tensorflow(Official)]](https://github.com/erictzeng/adda) [[Pytorch]](https://github.com/corenel/pytorch-adda) [[Pytorch]](https://github.com/jvanvugt/pytorch-domain-adaptation)
- **PixelDA**: Unsupervised Pixel–Level Domain Adaptation with Generative Adversarial Networks [[CVPR2017]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Bousmalis_Unsupervised_Pixel-Level_Domain_CVPR_2017_paper.pdf) [[Tensorflow(Official)]](https://github.com/tensorflow/models/tree/master/research/domain_adaptation) [[Pytorch]](https://github.com/vaibhavnaagar/pixelDA_GAN)
- **JGSA**: Joint Geometrical and Statistical Alignment for Visual Domain Adaptation [[CVPR2017]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_Joint_Geometrical_and_CVPR_2017_paper) [[Matlab(Official)]](https://www.uow.edu.au/~jz960/)
- **ILS**: Learning an Invariant Hilbert Space for Domain Adaptation [[CVPR2017]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Herath_Learning_an_Invariant_CVPR_2017_paper.pdf) [[Matlab(Official)]](https://bitbucket.org/sherath/ils/src)
- **DAH**: Deep Hashing Network for Unsupervised Domain Adaptation [[CVPR2017]](http://openaccess.thecvf.com/content_cvpr_2017/supplemental/Venkateswara_Deep_Hashing_Network_2017_CVPR_supplemental.pdf) [[Matlab(Official)]](https://github.com/hemanthdv/da-hash)
- **Wu's**: A Compact DNN: Approaching GoogLeNet-Level Accuracy of Classification and Domain Adaptation [[CVPR2017]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Wu_A_Compact_DNN_CVPR_2017_paper.pdf)
- **WDAN**: Mind the Class Weight Bias: Weighted Maximum Mean Discrepancy for Unsupervised Domain Adaptation [[CVPR2017]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yan_Mind_the_Class_CVPR_2017_paper.pdf) [[Caffe(Official)]](https://github.com/yhldhit/WMMD-Caffe)
- **JAN**: Deep Transfer Learning with Joint Adaptation Networks [[ICML2017]](proceedings.mlr.press/v70/long17a/long17a.pdf) [[Pytorch 0.2.0_3(Official)]](https://github.com/thuml/Xlearn)
- **ATDA**: Asymmetric Tri-training for Unsupervised Domain Adaptation [[ICML2017]](proceedings.mlr.press/v70/saito17a/saito17a.pdf) [[Tensorflow(Official)]](https://github.com/ksaito-ut/atda) [[Tensorflow]](https://github.com/vtddggg/ATDA) [[Pytorch]](https://github.com/corenel/pytorch-atda)
- **AdaBN**: Revisiting Batch Normalization For Practical Domain Adaptation [[ICLR2017]](https://openreview.net/pdf?id=BJuysoFeg) [[PR2018]](http://winsty.net/papers/adabn.pdf)
- **DSN**: Domain Separation Networks [[NIPS2016]](http://papers.nips.cc/paper/6254-domain-separation-networks) [[Tensorflow(Official)]](https://github.com/tensorflow/models/tree/master/research/domain_adaptation/domain_separation) [[Pytorch]](https://github.com/fungtion/DSN)
- **Sener's**: Learning Transferrable Representations for Unsupervised Domain Adaptation [[NIPS2016]](http://papers.nips.cc/paper/6360-learning-transferrable-representations-for-unsupervised-domain-adaptation)
- **RTN**: Unsupervised Domain Adaptation with Residual Transfer Networks [[NIPS2016]](https://papers.nips.cc/paper/6110-unsupervised-domain-adaptation-with-residual-transfer-networks.pdf)
- **DRCN**: Deep Reconstruction-Classification Networks for Unsupervised Domain Adaptation [[ECCV2016]](https://arxiv.org/abs/1607.03516) [[Tensorflow 1.0.1(Official)]](https://github.com/ghif/drcn) [[Pytorch]](https://github.com/fungtion/DRCN)
- **Deep CORAL**: Deep CORAL: Correlation Alignment for Deep Domain Adaptation [[ECCV2016]](https://arxiv.org/pdf/1607.01719.pdf) [[C(Official)]](https://github.com/VisionLearningGroup/CORAL) [[Pytorch 0.2]](https://github.com/SSARCandy/DeepCORAL)
- **RevGrad**: Unsupervised Domain Adaptation by Backpropagation [[ICML2015]](http://proceedings.mlr.press/v37/ganin15.pdf) [[Caffe(Official)]](https://github.com/ddtm/caffe/tree/grl) [[Tensorflow]](https://github.com/shucunt/domain_adaptation) [[Pytorch]](https://github.com/jvanvugt/pytorch-domain-adaptation)

# Journal Papers

- **Wang's survey**: Deep visual domain adaptation: A survey [[arXiv 25 Apr 2018]](https://arxiv.org/abs/1802.03601) [[NeuroCompu]](https://www.sciencedirect.com/science/article/pii/S0925231218306684/pdfft?md5=011fcc27c88a40c9e7c88918ba8cc1b2&pid=1-s2.0-S0925231218306684-main.pdf)
- **GsDsDL**: Learning Domain-shared Group-sparse Representation for Unsupervised Domain Adaptation [[PR2018]](https://www.sciencedirect.com/sdfe/pdf/download/read/noindex/pii/S0031320318301614/1-s2.0-S0031320318301614-main.pdf)
- **AdaBN**: Revisiting Batch Normalization For Practical Domain Adaptation [[ICLR2017]](https://openreview.net/pdf?id=BJuysoFeg) [[PR2018]](http://winsty.net/papers/adabn.pdf)
- **LDADA**: An Embarrassingly Simple Approach to Visual Domain Adaptation [[TIP2018]](https://ieeexplore.ieee.org/document/8325317/) [[Matlab(Official)]](https://github.com/poppinace/ldada)
- **DICD**: Domain Invariant and Class Discriminative Feature Learning for Visual Domain Adaptation [[TIP2018]](https://ieeexplore.ieee.org/document/8362753/)
- **HDANA**: Heterogeneous Domain Adaptation Network Based on Autoencoder [[JPDC2018]](https://www.sciencedirect.com/science/article/pii/S0743731517301922)
- **DKTL**: Domain Class Consistency Based Transfer Learning For Image Classiﬁcation Across Domains [[InforSci2017]](https://www.sciencedirect.com/sdfe/pdf/download/read/noindex/pii/S0020025516313159/1-s2.0-S0020025516313159-main.pdf)
- **Ding's**: Deep Domain Generalization With Structured Low-Rank Constraint [[TIP2017]](ieeexplore.ieee.org/iel7/83/4358840/08053784.pdf)
- **Venkateswara's survey**: Deep-Learning Systems for Domain Adaptation in Computer Vision: Learning Transferable Feature Representations [[SP Magazine]](https://ieeexplore.ieee.org/document/8103149/)
- **BSWDA**: Beyond Sharing Weights for Deep Domain Adaptation [[TPAMI2016]](https://www.computer.org/csdl/trans/tp/preprint/08310033.pdf)
- **SCA**: Scatter Component Analysis: A Uniﬁed Framework for Domain Adaptation and Domain Generalization [[TPAMI2016]](https://www.computer.org/csdl/trans/tp/2017/07/07542175.pdf)
- **DME**: Distribution-Matching Embedding for Visual Domain Adaptation [[JMLR2016]](www.jmlr.org/papers/volume17/15-207/15-207.pdf)
- **DANN**: Domain-Adversarial Training of Neural Networks [[JMLR2016]](http://www.jmlr.org/papers/volume17/15-239/15-239.pdf) [[Tensorflow(Official)]](https://github.com/pumpikano/tf-dann) [[Pytorch]](https://github.com/fungtion/DANN) [[Pytorch]](https://github.com/GRAAL-Research/domain_adversarial_neural_network)
- **LSCDA**: Unsupervised Domain Adaptation With Label and Structural Consistency [[TIP2016]](https://ieeexplore.ieee.org/iel7/83/7581012/07569007.pdf)
- **FLDA**: Feature-Level Domain Adaptation [[JMLR2016]](http://www.jmlr.org/papers/volume17/15-206/15-206.pdf) [[Matlab(Official)]](https://github.com/wmkouw/flda) [[Python(Official)]](https://github.com/wmkouw/libTLDA)

# arXiv Papers

- **GDAN**: Causal Generative Domain Adaptation Networks [[arXiv 28 Jun 2018]](https://arxiv.org/pdf/1804.04333.pdf)
- **M-ADDA**: M-ADDA: Unsupervised Domain Adaptation with Deep Metric Learning [[arXiv 6 Jul 2018]](https://arxiv.org/pdf/1807.02552.pdf) [[Pytorch(Official)]](https://github.com/IssamLaradji/M-ADDA)
- **FAN**: Factorized Adversarial Networks for Unsupervised Domain Adaptation [[arXiv 4 Jun 2018]](https://arxiv.org/pdf/1806.01376.pdf)
- **DiDA**: DiDA: Disentangled Synthesis for Domain Adaptation [[arXiv 21 Mar 2018]](https://arxiv.org/pdf/1805.08019.pdf)
- **ARTNs**: Unsupervised Domain Adaptation with Adversarial Residual Transform Networks [[arXiv 25 Apr 2018]](https://arxiv.org/abs/1804.09578)
- **CMD**: Robust Unsupervised Domain Adaptation for Neural Networks via Moment Alignment [[arXiv 28 Mar 2018]](https://arxiv.org/pdf/1711.06114.pdf) [[Keras(Official)]](https://github.com/wzell/mann)
- **CDAAE**: Cross-Domain Adversarial Auto-Encoder[[arXiv 17 Apr 2018]](https://arxiv.org/pdf/1804.06078.pdf)
- **CPUA**: Simple Domain Adaptation with Class Prediction Uncertainty Alignment[[arXiv 12 Apr 2018]](https://arxiv.org/pdf/1804.04448.pdf)
- **Tran's**: Joint Pixel and Feature-level Domain Adaptation in the Wild[[arXiv 28 Feb 2018]](https://arxiv.org/pdf/1803.00068.pdf)
- **InvAuto**: Invertible Autoencoder for domain adaptation[[arXiv 10 Feb 2018]](https://arxiv.org/pdf/1802.06869.pdf)

# Other Resources

- [transferlearning](https://github.com/jindongwang/transferlearning)
- [awsome-domain-adaptation](https://github.com/zhaoxin94/awsome-domain-adaptation)
- [awesome-transfer-learning](https://github.com/artix41/awesome-transfer-learning)