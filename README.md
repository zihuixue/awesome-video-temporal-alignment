# Awesome Video Temporal Alignment [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
> A curated list of resources related to video temporal alignment

Video temporal alignment refers to the task of finding correspondences across multiple videos, or between videos and narrations. 
It is commonly used as a pretext task in video self-supervised learning and finds applications in temporal action localization, few-shot learning, etc.

Contributions are welcome! Feel free to open an issue or send an email to sherryxue@utexas.edu for any suggestions or paper additions.

## Table of Contents

* [Papers](#papers)
    * [Video-Video alignment](#video_align)
    * [Video-Text alignment](#video_text_align)

* [Techniques](#techniques)
    * Temporal Cycle Consistency (TCC)
    * Dynamic Time Warping (DTW)
    * Optimal Transport (OT)

[//]: # (* [Datasets]&#40;#datasets&#41;)

## <a name="papers"></a> Papers

### <a name="video_align"></a> Video-Video Alignment
> For fine-grained video representation learning

[//]: # (* **paper title** <br>)

[//]: # (*author name* <br>)

[//]: # (x, 20xx. [[Paper]]&#40;&#41;[[Website]]&#40;&#41;[[Code]]&#40;&#41;)

* **Temporal Cycle-Consistency Learning** <br>
*Debidatta Dwibedi, Yusuf Aytar, Jonathan Tompson, Pierre Sermanet, and Andrew Zisserman* <br>
CVPR, 2019. [[Paper]](https://arxiv.org/abs/1904.07846)[[Website]](https://sites.google.com/view/temporal-cycle-consistency)[[Code]](https://github.com/google-research/google-research/tree/master/tcc)

* **Aligning Videos in Space and Time** <br>
*Senthil Purushwalkam, Tian Ye, Saurabh Gupta, Abhinav Gupta* <br>
ECCV, 2020. [[Paper]](https://arxiv.org/abs/2007.04515)

* **Learning by Aligning Videos in Time** <br>
*Sanjay Haresh, Sateesh Kumar, Huseyin Coskun, Shahram Najam Syed, Andrey Konin, Muhammad Zeeshan Zia, Quoc-Huy Tran* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/abs/2103.17260) 

* **Representation Learning via Global Temporal Alignment and Cycle-Consistency** <br>
*Isma Hadji, Konstantinos G. Derpanis, Allan D. Jepson* <br>
CVPR, 2021. [[Paper]](https://arxiv.org/abs/2105.05217)[[Code]](https://github.com/hadjisma/VideoAlignment)

* **Drop-DTW: Aligning Common Signal Between Sequences While Dropping Outliers** <br>
*Nikita Dvornik, Isma Hadji, Konstantinos G. Derpanis, Animesh Garg, Allan D. Jepson* <br>
NeurIPS, 2021. [[Paper]](https://arxiv.org/abs/2108.11996)[[Code]](https://github.com/SamsungLabs/Drop-DTW)

* **Learning to Align Sequential Actions in the Wild** <br>
*Weizhe Liu, Bugra Tekin, Huseyin Coskun, Vibhav Vineet, Pascal Fua, Marc Pollefeys* <br>
CVPR, 2022. [[Paper]](https://arxiv.org/abs/2111.09301)[[Code]](https://github.com/weizheliu/VAVA)

* **Context-Aware Sequence Alignment using 4D Skeletal Augmentation** <br>
*Taein Kwon, Bugra Tekin, Siyu Tang, Marc Pollefeys* <br>
CVPR, 2022. [[Paper]](https://arxiv.org/abs/2204.12223)[[Website]](https://taeinkwon.com/projects/casa/)[[Code]](https://github.com/taeinkwon/casa)

> For few-shot learning
* **Few-Shot Video Classification via Temporal Alignment** <br>
*Kaidi Cao, Jingwei Ji, Zhangjie Cao, Chien-Yi Chang, Juan Carlos Niebles* <br>
CVPR, 2020. [[Paper]](https://arxiv.org/abs/1906.11415)[[Code]](https://github.com/wangzehui20/OTAM-Video-via-Temporal-Alignment)

* **TA2N: Two-Stage Action Alignment Network for Few-shot Action Recognition** <br>
*Shuyuan Li, Huabin Liu, Rui Qian, Yuxi Li, John See, Mengjuan Fei, Xiaoyuan Yu, Weiyao Lin* <br>
AAAI, 2022. [[Paper]](https://arxiv.org/abs/2107.04782)[[Code]](https://github.com/R00Kie-Liu/TA2N)

* **Motion-Modulated Temporal Fragment Alignment Network for Few-Shot Action Recognition** <br>
*Jiamin Wu, Tianzhu Zhang, Zhe Zhang, Feng Wu, Yongdong Zhang* <br>
CVPR, 2022. [[Paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Wu_Motion-Modulated_Temporal_Fragment_Alignment_Network_for_Few-Shot_Action_Recognition_CVPR_2022_paper.html)[[Website]]()[[Code]]()

### <a name="video_text_align"></a> Video-Text Alignment

* **D3TW: Discriminative Differentiable Dynamic Time Warping for Weakly Supervised Action Alignment and Segmentation** <br>
*Chien-Yi Chang, De-An Huang, Yanan Sui, Li Fei-Fei, Juan Carlos Niebles* <br>
CVPR, 2019. [[Paper]](https://arxiv.org/abs/1901.02598)

* **Temporal Alignment Networks for long-term Video** <br>
*Tengda Han, Weidi Xie, Andrew Zisserman* <br>
CVPR, 2022. [[Paper]](https://arxiv.org/abs/2204.02968)[[Website]](https://www.robots.ox.ac.uk/~vgg/research/tan/)[[Code]](https://github.com/TengdaHan/TemporalAlignNet)

* **TempCLR: Temporal Alignment Representation with Contrastive Learning** <br>
*Yuncong Yang, Jiawei Ma, Shiyuan Huang, Long Chen, Xudong Lin, Guangxing Han, Shih-Fu Chang* <br>
ICLR, 2023. [[Paper]](https://arxiv.org/abs/2212.13738)[[Code]](https://github.com/yyuncong/TempCLR)

[//]: # (https://paperswithcode.com/task/video-alignment/codeless)