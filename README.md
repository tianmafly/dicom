# dicom
dcmtk cecho cfind cmove cstore
# 一. 从零编程实现DICOM协议-代码实现

本专栏为DICOM协议-成像协议相关的代码实现，主要以本人自己写的DICOM解析引擎来讲解，后续也会加入一些开源框架的源码分析。

  DICOM协议相关原理部分在专栏从零讲解DICOM协议-成像协议中，本专栏为相应的代码实现。

本节最后部分有完整代码下载链接

  有人可能疑惑已经有了不少开源框架，为什么还要造轮子呢？
  
  确实基于开源框架可以解决大部分问题，但可能就是因为不了解DICOM底层实现，导致对小部分问题无从下手。经济基础决定上层建筑，底层原理决定上层应用。
  
  
  个人认为造轮子有如下好处：

  了解协议底层原理后，再看上层应用，知其所以然
  国内厂家对DICOM协议实现程度不同，部分系统和图像没有严格按照DICOM协议标准实现，导致时能遇到不标准DICOM图像，部分不稳定的开源框架无法解析，而开源框架往往实现复杂，难以定位排查问题，更不知如何修复bug

[从零编程实现DICOM协议-代码实现](https://blog.csdn.net/tianma2012/category_11479149.html)

[1 专栏介绍](https://blog.csdn.net/tianma2012/article/details/121347951)

[2 DICOM成像协议编码实现-主框架搭建](https://blog.csdn.net/tianma2012/article/details/121369605)

[3 DICOM成像协议编码实现-文件头解析](https://blog.csdn.net/tianma2012/article/details/121370057)

[4 DICOM成像协议编码实现-元数据组解析](https://blog.csdn.net/tianma2012/article/details/121392137)

[5 DICOM成像协议编码实现-数据组解析](https://blog.csdn.net/tianma2012/article/details/121392212)

[6 DICOM成像协议编码实现-读取元素](https://blog.csdn.net/tianma2012/article/details/121392536)

[7 DICOM成像协议编码实现-有损压缩和无损压缩解压](https://blog.csdn.net/tianma2012/article/details/121399729)

[8 DICOM成像协议编码实现-保存BMP图像](https://blog.csdn.net/tianma2012/article/details/121414417)

# 2. 从零讲解DICOM协议-成像协议
[从零讲解DICOM协议-成像协议](https://blog.csdn.net/tianma2012/category_11461074.html)

[1 我的DICOM学习之路](https://blog.csdn.net/tianma2012/article/details/121182403)

[2 DICOM协议简介及应用](https://blog.csdn.net/tianma2012/article/details/121188016)

[3 DICOM成像协议剖析](https://blog.csdn.net/tianma2012/article/details/121184531)

[4 DICOM成像协议实现思路](https://blog.csdn.net/tianma2012/article/details/121187922)

[5 DICOM图像CT值计算](https://blog.csdn.net/tianma2012/article/details/121190291)

[6 DICOM图像CT值转RGB](https://blog.csdn.net/tianma2012/article/details/121194603)

[7 DICOM图像的基本操作](https://blog.csdn.net/tianma2012/article/details/121215714)

[8 DICOM层级关系](https://blog.csdn.net/tianma2012/article/details/121220519)

[9 序列图像排序](https://blog.csdn.net/tianma2012/article/details/121221152)

[10 DICOM带有overlay覆盖层图像显示（一层覆盖层）](https://blog.csdn.net/tianma2012/article/details/121260823)

[11 DICOM带有overlay覆盖层图像显示（多层覆盖层）](https://blog.csdn.net/tianma2012/article/details/121274239)

[12 DICOM带有overlay覆盖层图像显示（原始数据）](https://blog.csdn.net/tianma2012/article/details/121280247)

[13 DICOM彩色图像](https://blog.csdn.net/tianma2012/article/details/121280318)
# 3. DICOM图像高级应用

[DICOM图像高级应用](https://blog.csdn.net/tianma2012/category_11488693.html)

[1. DICOM高级应用专栏介绍](https://blog.csdn.net/tianma2012/article/details/121436117)

[2. DICOM图像层级分类-DCMTK-工程搭建](https://blog.csdn.net/tianma2012/article/details/121443373)

[3. DICOM图像层级分类-DCMTK-数据字典避坑](https://blog.csdn.net/tianma2012/article/details/121449855)

[4. DICOM图像层级分类-DCMTK-元素读取](https://blog.csdn.net/tianma2012/article/details/121456467)

[5. DICOM图像层级分类-DCMTK-压缩图像PixelData读取](https://blog.csdn.net/tianma2012/article/details/121187922)

[6. DICOM图像显示-DCMTK-像素数据获取的三种方式和源码分析](https://blog.csdn.net/tianma2012/article/details/121529245)

[7. DICOM图像显示-DCMTK-像素数据的三次转换和源码分析](https://blog.csdn.net/tianma2012/article/details/121718687)

[8. DICOM图像显示-DCMTK-图像显示和源码分析](https://blog.csdn.net/tianma2012/article/details/121805195)

[9. DICOM图像显示-DCMTK-窗宽窗位调整和源码分析](https://blog.csdn.net/tianma2012/article/details/121848644)

[10. DICOM图像显示-DCMTK-旋转翻转和源码分析](https://blog.csdn.net/tianma2012/article/details/121944106)

[11. DICOM图像显示-DCMTK-overlay覆盖层处理和源码分析](https://blog.csdn.net/tianma2012/article/details/122026345)

[12. DICOM图像显示-DCMTK-dcm转图片jpeg、bmp、png](https://blog.csdn.net/tianma2012/article/details/122079988)

[13. DICOM图像显示-DCMTK-处理多帧图像](https://blog.csdn.net/tianma2012/article/details/122114819)

[14. DICOM图像显示-DCMTK-处理超声彩色图像](https://blog.csdn.net/tianma2012/article/details/122134167)

[15. DICOM图像显示-DCMTK-获取坐标点像素值](https://blog.csdn.net/tianma2012/article/details/122141396)

[16. DICOM图像显示-DCMTK-cda转dicom](https://blog.csdn.net/tianma2012/article/details/122158973)

[17. DICOM图像显示-DCMTK-stl转dicom](https://blog.csdn.net/tianma2012/article/details/122158417)

[18. DICOM图像显示-DCMTK-pdf转dicom](https://blog.csdn.net/tianma2012/article/details/122155386)

[19. DICOM图像显示-DCMTK-dicom转pdf](https://blog.csdn.net/tianma2012/article/details/122156100)

[20. DICOM图像显示-DCMTK-dicom转xml](https://blog.csdn.net/tianma2012/article/details/122156876)

[21. DICOM图像显示-DCMTK-xml转dicom](https://blog.csdn.net/tianma2012/article/details/122157525)

[22. DICOM图像层级分类-DCMTK-层级分类](https://blog.csdn.net/tianma2012/article/details/121464231)

[23. DICOM图像显示-DCMTK-image转dicom](https://blog.csdn.net/tianma2012/article/details/122184367)

[24. DICOM图像显示-DCMTK-转换 DICOM 文件编码](https://blog.csdn.net/tianma2012/article/details/122200877)

[25. DICOM图像显示-DCMTK-修改dicom文件](https://blog.csdn.net/tianma2012/article/details/122208274)

[26. DICOM图像显示-DCMTK-dcm转rle无损压缩](https://blog.csdn.net/tianma2012/article/details/122228337)
