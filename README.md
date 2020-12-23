# VITON-flask

![20200118004320.png](https://raw.githubusercontent.com/GrayXu/Online-Storage/master/img/20200118004320.png)![20200118004342.png](https://raw.githubusercontent.com/GrayXu/Online-Storage/master/img/20200118004342.png)![20200118004359.png](https://raw.githubusercontent.com/GrayXu/Online-Storage/master/img/20200118004359.png)

A multi-stage virtual try-on deep neural networks based on [JPP-Net and CP-VTON](#References). We provide **SIMPLE and EASY-to-handle API** on upper level, and combine some traditional image processing methods.

Feature:
- Fast **Human_Image + Cloth_Image = Gen_Image**, put on a specified upper clothes for specified people.
- Web and Backend response service on *Flask*

# How to use

CPU Mode: `Model(.., use_cuda = False)`

# References

Model designs are based on JPP-Net & CPVTON, and their open-source repo on Github.  

[**VITON**: An Image-based Virtual Try-on Network](https://arxiv.org/abs/1711.08447v1),Xintong Han, Zuxuan Wu, Zhe Wu, Ruichi Yu, Larry S. Davis. **CVPR 2018**

[(**CP-VTON**) Toward Characteristic-Preserving Image-based Virtual Try-On Networks](https://arxiv.org/abs/1807.07688), Bochao Wang, Huabin Zheng, Xiaodan Liang, Yimin Chen, Liang Lin, Meng Yang. **ECCV 2018**

[(**JPP-Net**) Look into Person: Joint Body Parsing & Pose Estimation Network and A New Benchmark](https://arxiv.org/abs/1804.01984), Xiaodan Liang, Ke Gong, Xiaohui Shen, Liang Lin, **T-PAMI 2018**.
