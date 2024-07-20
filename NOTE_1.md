#  图像格式
## 图像格式 
    I422 
    I420
    I444
    主要是有 YUYV UYVY NV12 NV21 RGB
## 图像尺寸
    设计到图像宽高

## 图像通道
    YUYV UYVY 1个通道
    NV12 NV21 2个通道

## 关于PITCH
    图像两行之间的差值

## 图像布局
    以 2 * 2 图像为例：
        YUYV 或 UYVY:
        YUYV YUYV 
        YUYV YUYV 
        其中，单个像素的表示方法为YUYV或 UYVY；

        NV12或NV21
        Y Y
        Y Y
        UV UV
        其中，Y为图像的灰度样式；UV为颜色分量；将颜色分量和UV分量布局在两片空间中。

## 
        