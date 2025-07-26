# Awesome-MI-EEG-Classification

[https://github.com/ZealousG/Awesome-MI-EEG](https://github.com/ZealousG/Awesome-MI-EEG)

# 数据集

这里包含了相关的数据集下载和文档：

[数据集简称] 数据集全称 [数据下载] 

- [模型简称] 以官方给出的或常用名为准等为准
- [Docs] 对数据集描述的相关描述
- [Data, label] 数据集下载地址，部分数据集的label和Data是分开的，有时提供多个下载地址。

[**IV1**] BCI Competition IV Dataset 1 [[Docs](https://www.bbci.de/competition/iv/desc_1.html)] [[Data](https://www.bbci.de/competition/iv/download/index.html?agree=yes&submit=Submit), [labels](https://www.bbci.de/competition/iv/results/index.html#labels)]

[**IV2a**]  BCI Competition IV Dataset 2a [[Docs](https://www.bbci.de/competition/iv/desc_2a.pdf)] [[Data](https://www.bbci.de/competition/download/competition_iv/BCICIV_2a_gdf.zip), [labels](https://www.bbci.de/competition/iv/results/ds2a/true_labels.zip)] [[Data2](https://github.com/bregydoc/bcidatasetIV2a)] 

[**IV2b**] BCI Competition IV Dataset 2b [[Docs](https://www.bbci.de/competition/iv/desc_2b.pdf)] [[Data](https://www.bbci.de/competition/download/competition_iv/BCICIV_2b_gdf.zip), [labels](https://www.bbci.de/competition/iv/results/ds2b/true_labels.zip)]

# 模型

## 单受试运动想象分类模型

这里收集了针对单受试者中的运动想象脑电分类模型，给出了：

[年份-月份] [模型简称] 论文名称 [Code连接1][Code连接2]

- [年份-月份] arxiv 以v1版本日期为准，期刊论文以收稿日期为准
- [模型简称] 以论文中给出的或GitHub中仓库名等为准
- [Code] 可能会有多种实现，论文名称后紧跟的一般是官方实现，非官方实现会标注；默认为PyTorch版本，非pytorch版本会标注

[2025-06-26] [**DBConformer**] [DBConformer: Dual-Branch Convolutional Transformer for EEG Decoding](https://arxiv.org/abs/2506.21140) **[[Code](https://github.com/wzwvv/DBConformer)]**

[2025-01-24] [**GPFMTL**] [Gated parallel feature fusion multi-task learning for motor imagery EEG classification](https://www.sciencedirect.com/science/article/abs/pii/S0957417425022961) **[[Code](https://github.com/Henrywang621/GPFMTL-for-MI-EEG-classification)]**

[2024-09-18] [**DMSACNN**] [DMSACNN: Deep Multiscale Attentional Convolutional  Neural Network for EEG-Based Motor Decoding](https://ieeexplore.ieee.org/document/10906446) **[[Code](https://github.com/xingxin-99/DMSANet)]**

[2024-09-06] [**TMSANet**] [TMSA-Net:A novel attention mechanism for improved motor imagery EEG signal processing](https://www.sciencedirect.com/science/article/pii/S1746809424012473) **[[Code](https://github.com/Whit3Zhao/TMSA-Net)]**

[2024-09-06] [**MixNet**] [MixNet: Joining Force of Classical and Modern  Approaches Toward the Comprehensive Pipeline  in Motor Imagery EEG Classification](https://arxiv.org/abs/2409.04104) **[[Code(TensorFlow)](https://github.com/Max-Phairot-A/MixNet)]**

[2024-07-03] [**SSTDPN**] [A spatial–spectral and temporal dual prototype network for motor imagery brain–computer interface](https://arxiv.org/abs/2407.03177) **[[Code](https://github.com/hancan16/SST-DPN)]**

[2024-06-30] [**SNNforMI**] [A lightweight spiking neural network for EEG-based motor imagery classification](https://www.sciencedirect.com/science/article/abs/pii/S0893608025006215) **[[Code](https://github.com/Zhr1110/SnnForMI)]**

[2024-04-25] [**EEGDeformer**] [EEG-Deformer: A Dense Convolutional Transformer for Brain-computer Interfaces](https://arxiv.org/abs/2405.00719) **[[Code](https://github.com/yi-ding-cs/EEG-Deformer)]**

[2024-02-04] [**CTNet**] [CTNet: A convolutional transformer network for EEG-based motor imagery classification](https://www.nature.com/articles/s41598-024-71118-7) **[[Code](https://github.com/snailpt/CTNet)]**

[2024-01-28] [**FACTNet**] [FACT-Net: A Frequency Adapter CNN With Temporal-Periodicity Inception for Fast and Accurate MI-EEG Decoding](https://ieeexplore.ieee.org/document/10755982) **[[Code](https://github.com/Ktn1ga/EEG_FACT)]**

[2024-01-01] [**STGF**] [ST-GF: Graph-based Fusion of Spatial and  Temporal Features for EEG Motor Imagery  Decoding](https://ieeexplore.ieee.org/abstract/document/10822062) [[Code](https://github.com/guadawcz/ST-GF)]

[2023-09-11] [**EEGSimpleConv**] [A Strong and Simple Deep Learning Baseline  for BCI Motor Imagery Decoding](https://arxiv.org/abs/2309.07159) **[[Code](https://github.com/elouayas/EEGSimpleConv)]**

[2023-08-20] [**EISATCFusion**] [EISATC-Fusion: Inception Self-Attention  Temporal Convolutional Network Fusion  for Motor Imagery EEG Decoding](https://ieeexplore.ieee.org/document/10480732) **[[Code](https://github.com/LiangXiaohan506/EISATC-Fusion)]**

[2023-06-03] [**DoNet**] [Model and Data Dual-Driven Double-Point  Observation Network for Ultra-Short MI  EEG Classification](https://ieeexplore.ieee.org/document/10495129) **[[Code](https://github.com/Niu7750/DoNet/tree/main)]**

[2023-09-08] [**EEGProgress**] [EEGProgress: A fast and lightweight progressive convolution architecture for EEG classification](https://www.sciencedirect.com/science/article/abs/pii/S0010482523013665) **[[Code](https://github.com/OrangeP0P/EEGProgress)]**

[2023-05-17] [**ADFCNN**] [ADFCNN: Attention-Based Dual-Scale Fusion  Convolutional Neural Network for Motor  Imagery Brain–Computer Interface](https://ieeexplore.ieee.org/document/10356088) **[[Code](https://github.com/UM-Tao/ADFCNN-MI)]**

[2023-07-04] [**TSFCNet**] [A Multi-Domain Convolutional Neural Network  for EEG-Based Motor Imagery Decoding](https://ieeexplore.ieee.org/document/10275093) **[[Code](https://github.com/hongyizhi/TSFCNet)]**

[2023-01-14] [**EEGCDILNet**] [EEG-CDILNet: a lightweight and accurate CNN network using circular dilated convolution for motor imagery classification](https://iopscience.iop.org/article/10.1088/1741-2552/acee1f) **[[Code](https://github.com/xionghuiYu/EEG_CDILNet)]**

[2022-09-20] [**EEGConformer**] [EEG Conformer: Convolutional Transformer for EEG Decoding and Visualization](https://ieeexplore.ieee.org/document/9991178) **[[Code](https://github.com/eeyhsong/EEG-Conformer)]**

[2022-08-11] [**IFNet**] [IFNet: An Interactive Frequency Convolutional  Neural Network for Enhancing Motor  Imagery Decoding From EEG](https://ieeexplore.ieee.org/document/10070810) **[[Code](https://github.com/Jiaheng-Wang/IFNet)]**

[2022-05-05] [**FBMSNet**] [FBMSNet: A Filter-Bank Multi-Scale  Convolutional Neural Network for EEG-Based  Motor Imagery Decoding](https://ieeexplore.ieee.org/document/9837422) **[[Code](https://github.com/Want2Vanish/FBMSNet)]**

[2021-03-17] [**FBCNet**] [FBCNet: A Multi-view Convolutional Neural Network for Brain-Computer Interface](https://arxiv.org/abs/2104.01233) [[Code](https://github.com/ravikiran-mane/FBCNet)]

[2017-03-15] [**ShallowConvNet**] [Deep learning with convolutional neural networks for EEG decoding and visualization](https://arxiv.org/abs/1703.05051) [[Code](https://github.com/braindecode/braindecode/blob/master/braindecode/models/shallow_fbcsp.py)]

[2016-11-23] [**EEGNet**] [EEGNet: A Compact Convolutional Network for EEG-based Brain-Computer Interfaces](https://arxiv.org/abs/1611.08024) [[Code](https://github.com/aliasvishnu/EEGNet)]

[2008-09-26] [**FBCSP**] [Filter Bank Common Spatial Pattern (FBCSP) in Brain-Computer Interface](https://ieeexplore.ieee.org/document/4634130) [[Code(unofficial)](https://github.com/orvindemsy/BCICIV2a-FBCSP)]

## 开源模型库

这里给出了相关的模型zoo：

[模型简称] 论文名称 [Code][Docs]

- [模型简称] 以论文中给出的或GitHub中仓库名等为准
- [Code] Github仓库
- [Docs] 具体的指南文件

**[BrainDecode]** [Deep learning with convolutional neural networks for EEG decoding and visualization](https://arxiv.org/abs/1703.05051) [[Code](https://github.com/braindecode/braindecode/tree/master)] [[Docs](https://braindecode.org/dev/index.html)]

[**EEGModels**] the Army Research Laboratory (ARL) EEGModels Project [[Code](https://github.com/vlawhern/arl-eegmodels)]

# 基础库

实现以上库，常用的一些依赖库：

[模型简称] 论文名称 [Code][Docs]

- [模型简称] 以论文中给出的或GitHub中仓库名等为准
- [Code] Github仓库
- [Docs] 具体的指南文件

[**MNE**] [MEG and EEG data analysis with MNE-Python](https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2013.00267/full) [[Code](https://github.com/mne-tools)][[Docs](https://mne.tools/stable/index.html#)]
