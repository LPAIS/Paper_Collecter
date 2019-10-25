# Title: An End-to-End Trainable Neural Network for Image-based Sequence Recognition and Its Application to Scene Text Recognition 
 + Referrer: HJ, Level: 10
 + Reasons: One of the most popular framework, CNN+RNN+CTC (CRNN), is proposed in this paper.
 + Proceedings or Journal: TPAMI
 + [PDF Link](https://arxiv.org/pdf/1507.05717.pdf)  
 + [Code (Torch7)](https://github.com/bgshih/crnn) [Code (Pytorch)](https://github.com/meijieru/crnn.pytorch)
 + Organization: HUST
 + Authors: Baoguang Shi, Xiang Bai and Cong Yao
 
# Contributions
 + It is end-to-end trainable, in contrast to most of the existing algorithms whose components are separately trained and tuned. 
 + It naturally handles sequences in arbitrary lengths, involving no character segmentation or horizontal scale normalization.
 + It is not confined to any predefined lexicon and achieves remarkable performances in both lexicon-free and lexicon-based scene text recognition tasks. 
 + It generates an effective yet much smaller model, which is more practical for real-world application scenarios.
 
# DataSets
 + IIIT-5K, Street View Text (SVT) and ICDAR datasets
 ## Results
 ![The results of CRNN in several datasets.](Images/CRNN_results.png)
 
 
# Comments
 This paper introduces a new framework for sequence labelling. The proposed approach is end-to-end trainable and is very elegant. Furthermore, it achieves good results on relevant datasets.
