# Concealed Object Segmentation in Terahertz Imagingvia Adversarial Learning-[link](https://www.sciencedirect.com/science/article/abs/pii/S0030402619304991)

****
Terahertz imaging (frequency between 0.1 to 10 THz) is a modern technique for public security check. Due to poor imaging quality, traditional machine vision methods often fail to detect concealed weapons in Terahertz samples, while modern instance segmentation approaches have complex multiple-stage concatenation and often hunger for massive and accurate training data. In this work, we realize a novel Conditional Generative Adversarial Nets (CGANs), named as Mask-CGANs to segment weapons in such a challenging imaging quality. The Mask-Generator network employs a “selected-connection U-Net” to restrain false alarms and speed up training convergence. The loss function takes reconstruction errors and sparse priors into consideration to preserve precise segmentation. Such a learning architecture works well with a small training dataset. Experiments show that the proposed model outperforms CGANs (more than 16–32% in Recall, Precision and Accuracy) and Mask-RCNN (more than 3–6%). Moreover, its testing speed (69.7 FPS) is fast enough to be implemented in a real-time security check system, which is 44 times faster than Mask-RCNN. In the experiments for mammographic mass segmentation on INBreast dataset, the Dice index of the proposed method is 91.29, surpasses the-state-of-the-art medical issue segmentation methods. The full implementation (based on TensorFlow) is available at https://github.com/JXPanzz/THz).
### Dataset
#### Dataset structure:
```
/THZ_dataset_seg_IMG
    /train
    /val
    /test
```
#### Download links:
- [Google drive](https://drive.google.com/drive/folders/1A6LiyWAvRmKIJN5yXQZ3HxZVwNEFz8uV?usp=sharing)
- [Baidu drive](https://pan.baidu.com/s/1MRPyeMtzCQRO5ydgX0rSHA)(Extraction code: x3od)
- [NUAA drive](https://pan.nuaa.edu.cn/share/5cb047f309049ba7f68ab9e1e0)

---

**If you find this dataset useful in your research, please consider citing:**

```
@article{LIANG20191104,
title = {Concealed object segmentation in terahertz imaging via adversarial learning},
journal = {Optik},
volume = {185},
pages = {1104-1114},
year = {2019},
author = {Dong Liang and Jiaxing Pan and Yang Yu and Huiyu Zhou}
}
```
