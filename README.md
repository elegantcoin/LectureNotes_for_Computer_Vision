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
    - Linux （可以参考`pyimagesearch`上的大佬[`Adrian Rosebrock`](https://www.pyimagesearch.com/),他的深度学习的书也不错） （`make -j4`的`4`就是编译用几个核，多核可以加快安装过程）

## :fire: 2. OpenCV基础知识
- 1.图像和矩阵：
    - `OPenCV`中使用的`BGR`的形式，注意和平常用的`RGB`是反过来的，要转换一下，不然颜色通道可能会弄反。
    - 注意图像还有`YUV420`等其他格式。
- 2.基本对象类型：
    - Mat, Vec3b, Vec, Scalar, Point, Size, Rect, RotatedRect 等类

## :fire: 3. 基本图形用户界面
- 1.`Qt`用户界面。当前最新貌似是`Qt5`(Python3, OpenCV4,Qt5)?
- 2.`destroyAllWindows`删除所有`Qt`界面
- 3.`Qt`有工具栏、图像区域、状态栏三部分。
- 4.`OpenGL`

## :fire: 4. Histogram and Filters（直方图和滤波器）
- 1.`cv2.calcHist(images,channels,mask,histSize,ranges)`绘制直方图。
- 2.`cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)`将图像转换为灰阶，可以绘制灰阶直方图。
- 3.`Lomography`效果，我感觉相机也有，但是我几乎都不用这个。`LUT`（S型函数，让暗值更暗、亮值更亮，实现高对比） 
- 4.颜色直方图：用`cv2.split(image)`把颜色通道提取出来，分别绘制直方图。
- 5.图像均衡器：`cv2.equalizeHist(image)`

## :fire: 5. 自动光学检查、对象分割和检测
- 1.
- 2.
- 3.
- 4.
- 5.
- 6.
- 7.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.
- 2.

## :fire: Appendix A. 面试问题
- 1.`SVM`
- 2.决策树的优缺点
- 3.`L1`、`L2`正则的区别
    - 权重惩罚不一样
- 4.`ResNet` `DetNet`的原理
- 5.梯度下降、牛顿法的区别
    - 用不用`海森矩阵`信息，一阶、二阶
- 6.`Faster-RNN` （`RPN`） ，将`ROI`标记为前景或背景。抛弃背景`anchors`区域，而前景对象传播到`ROI Pooling`模块。 
- 7.`FPN`（`Feature pyramid Network`）
- 8.目标检测，`one-stage`、`two-stage`
- 9.`BP`（`Back Propagation`） 正向、反向传播 
- 10.`Poling`、梯度消失、过拟
- 11.`NMS`（`Non-Maximum Suppression`）非极大值抑制  IoU
- 12.`SSD` `SENet` `Focal Loss`
- 13.`BN`层 （`Batch Normalization`） 白化，太多层，容易早停，高层分布变化大   M Std 归一化处理
- 14.
- 4.
- 4.
- 4.
- 4.
- 4.
- 4.
- 4.
- 4.
- 4.
- 4.
- 4.
- 4.
- 4.
- 4.
- 4.
- 4.

