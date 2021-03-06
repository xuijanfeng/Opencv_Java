# 基于Java语言OpenCV开发
### 一、环境搭建
第一步：导入opencv-320.jar(注意jdk要1.8)<br>
第二步：复制opencv_java320.dll文件到jdk安装的bin目录(注意jdk要1.8以上)
### 二、知识点目录
> *注意：所有的Mat对象进行释放，防止OOM，即mat.release()*<br>
1. OpenCV_1_Read 使用OpenCV图像读取与保存<br>
2. OpenCV_2_Mat  Mat的初始化、读取、转换、遍历<br>
3. OpenCV_3_MatShow  Mat对象显示到BufferedImage<br>
4. OpenCV_4_ColorSpace  RGB色彩空间<br>
5. OpenCV_5_MatMath  MAT像素算术运算和逻辑<br>
6. OpenCV_6_FloodFill  ROI---Region of Interest区域与泛洪填充<br>
7. OpenCV_7_Convlution  均值模糊<br>
8. OpenCV_8_Gaussian  高斯模糊<br>
9. OpenCV_9_EPF  边缘保留滤波EPF<br>
10. OpenCV_10_Histogram  绘制图像直方图<br>
11. OpenCV_11_HistogramHist  直方图均衡化<br>
12. OpenCV_12_HistogramCompare  直方图的比较<br>
13. OpenCV_13_HistogramHistBack  直方图反向投影<br>
14. OpenCV_14_TemplateMatch  模板匹配<br>
15. OpenCV_15_BinaryImage  图像二值化<br>
16. OpenCV_16_BinaryAdapt  自适应阈值二值化<br>
17. OpenCV_17_BinaryBigImage  超大图像二值化<br>
18. OpenCV_18_Pyramid  图像金字塔<br>
19. OpenCV_19_PyramidBlend  图像金字塔融合<br>
20. OpenCV_20_MScaleTemplateMatch  多尺度模板匹配<br>
21. OpenCV_21_GradientSobel  图像梯度一阶倒数(索贝尔算子)<br>
22. OpenCV_22_GradientLapalian  图像梯度二阶倒数(拉普拉斯算子)<br>
23. OpenCV_23_Canny  Canny边缘提取<br>
24. OpenCV_24_HoughLine  直线检测---霍夫直线变换<br>
25. OpenCV_25_HoughCircle  圆检测<br>
26. OpenCV_26_FindContours  轮廓发现<br>
27. OpenCV_27_ContoursMeasure  图象测量<br>
28. OpenCV_28_DilateErode  图象形态学---腐蚀与膨胀<br>
29. OpenCV_29_OpenClose  图象形态学---开闭操作<br>
30. OpenCV_30_MorePH  其他形态学操作：顶帽、黑帽、基本梯度、内部梯度、外部梯度<br>
31. OpenCV_31_WaterShed  分水岭算法<br>
32. OpenCV_32_FaceDetect  人脸检测<br>
33. OpenCV_33_FaceSwap  人脸互换<br>
34. OpenCV_34_Skeleton  骨架提取<br>

---
![](/screenshot/changPixel.png "2-像素修改")
![](/screenshot/Mat_GUI.jpg "3-GUI显示")
![](/screenshot/Mat_HSV.jpg "4-HSV色彩空间")
![](/screenshot/Mat_bitwise_add.jpg "5-图像像素或操作")
![](/screenshot/Mat_bitwise_not.jpg "5-图像像素非操作")
![](/screenshot/Mat_FloodFill.jpg "6-泛洪填充")
![](/screenshot/Mat_Convlution.png "7-图像模糊美颜去噪")
![](/screenshot/Mat_Gaussian.jpg "8-高斯模糊")
![](/screenshot/Mat_BilateralFilter.jpg "9-双边模糊")
![](/screenshot/Mat_Histogram.jpg "10-直方图绘制")
![](/screenshot/Mat_equalizeHist.png "11-彩色图直方图均衡化")
![](/screenshot/Mat_CalcBackProject.jpg "13-直方图反向投影")
![](/screenshot/Mat_TemplateMatch.jpg "14-模板匹配")
![](/screenshot/Mat_Binary.jpg "15-图像二值化")
![](/screenshot/Mat_BinaryAdapt.jpg "16-自适应阈值二值化")
![](/screenshot/BinaryBigImage_resut.png "17-超大图二值化-分块")
![](/screenshot/BinaryBigImage1_resut.png "17-超大图二值化-结果")
![](/screenshot/Mat_Pyramid.jpg "18-拉普拉斯金字塔和高斯金字塔")
![](/screenshot/Mat_PyramidBlend.jpg "19-图像金字塔融合")
![](/screenshot/Mat_MScaleTemplateMatch.jpg "20-多尺度模板匹配")
![](/screenshot/Mat_Gradient.jpg "21-图像梯度一阶倒数")
![](/screenshot/Mat_GradientLapalian.jpg "22-图像梯度二阶倒数")
![](/screenshot/Mat_Canny.jpg "23-Canny边缘提取")
![](/screenshot/Mat_HoughLine.jpg "24-霍夫直线检测")
![](/screenshot/Mat_HoughCircle.jpg "25-霍夫圆检测")
![](/screenshot/Mat_FindContours_One.jpg "26-轮廓发现-第一种方法")
![](/screenshot/Mat_FindContours.jpg "26-轮廓发现-两种方法对比")
![](/screenshot/Mat_Arc_Area_1.jpg "27-图像周长、面积、垂心")
![](/screenshot/Mat_Arc_Area_2.jpg "27-图像周长、面积、垂心、拟合")
![](/screenshot/Mat_Open.jpg "29-开操作-消除小的干扰块")
![](/screenshot/Mat_Close.jpg "29-闭操作-填充小的洞")
![](/screenshot/Mat_DetectLine.jpg "29-线段提取")
![](/screenshot/Mat_RemoveLines.jpg "29-去干扰线条")
![](/screenshot/Mat_MorePH.jpg "30-形态学的梯度")
![](/screenshot/Mat_WaterShed.jpg "31-分水岭算法")
![](/screenshot/Mat_FaceDetect.jpg "32-人脸检测")
![](/screenshot/Mat_faceswap.png "33-人脸互换")
![](/screenshot/Mat_faceswap1.png "33-人脸互换")
