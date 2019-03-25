*本系列为快速上手指南，不作过多讲解。*

---


进行此操作前，安卓开发需安装并Java环境，参考[http://www.runoob.com/w3cnote/android-tutorial-development-environment-build.html](http://www.runoob.com/w3cnote/android-tutorial-development-environment-build.html)

## 1.1 下载与安装
下载地址[：http://www.android-studio.org/index.php](http://www.android-studio.org/index.php)


选择适合平台版本的Android studio安装文件进行下载，安装。

## 1.2 启动配置 
首次安装或者重新配置，选择'Do not import setting'

![image](http://po1d0nnr5.bkt.clouddn.com/20180517171512579.png)

启动时出现下图，点cancel

![image](http://po1d0nnr5.bkt.clouddn.com/20180517171536214.png)

![image](http://po1d0nnr5.bkt.clouddn.com/20180517171623446.png)

根据提示一下步，其中一步需要下载SDK，如果前面选择Standard，则出现下图，SDK默认安装在C盘。如希望更改路径，在前面选择Custom

![image](http://po1d0nnr5.bkt.clouddn.com/20180517171653179.png)

![image](http://po1d0nnr5.bkt.clouddn.com/20180517171705458.png)

等待下载完成即可。

## 1.3 管理SDK
打开sdk manager ![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-152938.png)

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190311-170131.png)

一般只需下载最新的SDK就可以，不过有时导入的旧项目是使用较旧的SDK版本，所以根据需要下载。


## 1.4 管理模拟器

打开AVD Manager ![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-150030.png)

在这里根据需要创建并管理安卓模拟器，供开发过程中调试用。

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190311-170930.png)

## 1.5 创建一个Android工程

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-143150.png)

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-143620.png)

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-144931.png)

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-145124.png)

选择Empty Activity，下一步。

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-145523.png)

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-145818.png)

点击finish后，等待项目构建完成。

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-150538.png)

项目构建好了，点击绿色三角按钮试运行一下。

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-150815.png)

这里需要选择一个运行些应用的目标设备，可以是已通过USB连接的手机，可以是虚拟的设备，这里还没有，『Create New Virtual Device』创建一个新的模拟器。

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-151220.png)

选择一个设备型号，比较普遍的1080X1920的分辨率。
![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-151332.png)

选择一个较新的系统版本镜像，Download。
***如果电脑硬件架构不支持x86的话，尝试选择其他架构的镜像创建模拟器。不过推荐使用真机做开发调试，用模拟器实在是慢，很耗内存。***

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-151449.png)

等待镜像下载安装完成。

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-154911.png)

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190315-155039.png)

选择刚创建的模拟器，OK运行。

等待模拟器开机完成并自动运行应用。

![image](http://po1d0nnr5.bkt.clouddn.com/QQ20190311-155056.png)



*AS ERROR: x86 emulation currently requires hardware acceleration!报错解决傻瓜教程[https://blog.csdn.net/qq_38280242/article/details/81253278](https://blog.csdn.net/qq_38280242/article/details/81253278)*

***如果电脑硬件架构不支持x86的话，尝试选择其他架构的镜像创建模拟器。不过推荐使用真机做开发调试，用模拟器实在是慢，很耗内存。***



