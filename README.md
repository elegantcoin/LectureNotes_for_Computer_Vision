# LectureNotes_for_Computer_Vision

<p align="center">
    <a href="https://github.com/elegantcoin/LectureNotes_for_Computer_Vision"><img src="https://img.shields.io/badge/status-updating-brightgreen.svg"></a>
    <a href="https://github.com/python/cpython"><img src="https://img.shields.io/badge/Python-3.7-FF1493.svg"></a>
    <a href="https://github.com/elegantcoin/LectureNotes_for_Computer_Vision"><img src="https://img.shields.io/badge/platform-Windows%7CLinux%7CmacOS-660066.svg"></a>
    <a href="https://opensource.org/licenses/mit-license.php"><img src="https://badges.frapsoft.com/os/mit/mit.svg"></a>
    <a href="https://github.com/elegantcoin/LectureNotes_for_Computer_Vision/stargazers"><img src="https://img.shields.io/github/stars/elegantcoin/LectureNotes_for_Computer_Vision.svg?logo=github"></a>
    <a href="https://github.com/elegantcoin/LectureNotes_for_Computer_Vision/network/members"><img src="https://img.shields.io/github/forks/elegantcoin/LectureNotes_for_Computer_Vision.svg?color=blue&logo=github"></a>
    <a href="https://www.python.org/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" align="right" height="48" width="48" ></a>
</p>
<br />

## :fire: 1. 了解OpenCV

- 1.`OpenCV`的`imgproc`模块提供了很多基本函数，可以用来轻松处理图像。
- 2.高级的图像处理算法如：构化森林的边缘检测、域变换滤波器、自适应流形滤波器 用到了`ximgproc`模块。
- 3.`highgui`模块,界面操作，可以查看图像处理的中间过程，用到`waitKey()`，还可以缩放保存图像。
- 4.视频处理模块`videostab`,可以对拍摄视频抖动校准。
- 5.`3D`模块，强大的算法可以利用`calib3d`计算`2D`图像下物体的`3D`位置
- 6.`特征提取`的`features2d`模块：主要的算法有 - 算法包括尺度不变特征变换（Scale Invariant Feature Transform，SIFT）、加速鲁棒特征（Speeded Up Robust Features，SURF）和加速分段测试特征（Features From Accelerated Segment Test，FAST）。
- 7.`对象检测`的`objdetect`模块:可以使用预训练模型+ `Caffe`轻松实现实时对象检测
- 8.`机器学习`的`ml`模块：贝叶斯分类器（Bayes classifier）、KNN（k-nearest neighbor），支持向量机（support vector machine，SVM）、决策树（decision tree）、神经网络（neural network）以及最近领域搜索算法。
- 9.`形状分析`的`shape`模块。
- 10.`人脸识别`的`face`模块。目标识别，检测，跟踪。注意区别`recognition` 和 `detection`。
- 11.安装
    - Windows
    - MacOS
    - Linux （可以参考`pyimagesearch`上的大佬[`Adrian Rosebrock`](https://www.pyimagesearch.com/)） （`make -j4`的`4`就是编译用几个核，多核可以加快安装过程）

## :fire: 2. OpenCV基础知识
- 1.图像和矩阵。
