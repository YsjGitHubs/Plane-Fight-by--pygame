# Plane Fight！（by pygame）
第一次小组作业：pygame实现的飞机大战

**注：pygame暂时只支持python3.4 32位版本以下的，安装文件已上传到pygame and python3.4 install file 文件夹里面**

### 小组成员

**组长：毛俊杰**

**组员：张苏月、王晶、张彩妮、王骞卉、马梦媛**

**素材设计：张苏月**

设计流程：
### 对游戏的大体框架进行分析：

1.游戏的窗口主题部分

2.游戏的我方飞机部分

3.游戏的敌方飞机部分

4.游戏的子弹部分

5.游戏的补给部分

6.游戏的素材资源存放部分

***
### 素材包主要有三个部分：
1.游戏的图片素材

2.游戏的音效素材

3.游戏的字体素材

***
### 具体需求：
1.子弹的射击效果

2.飞机的爆炸效果

3.补给包的掉落效果

4.计分效果

5.子弹升级和核弹清屏效果

6.敌方飞机速度逐渐增大效果

7.敌方飞机逐渐出现高血量飞机效果

8.游戏结束提示效果


***

## **程序设计**
**由上述分析可知，代码量较大较复杂，而且需要图形化界面，所以我们采用pygame图形库来开发，并进行模块式开发**

**游戏的基本设定：**
>敌方共有大中小3款飞机，分为高中低三种速度

>子弹的射程并非全屏，而大概是屏幕长度的80%

>消灭小飞机需要1发子弹，中飞机大概8发，打飞机需要20发

>每消灭一架飞机得1000分，中飞机6000分，大飞机10000分

>每过30s有一个随机的道具补给，分为两种道具，全屏核弹，双弹道子弹

>限定：
>全屏炸弹最多只能存放3颗，双弹道子弹可以维持18s的效果

>难度提升：
>游戏根据分数来逐步提高难度，难度的提高表现：飞机的数量增多以及速度加快

>对原版微信飞机大战的改进：

>中飞机和打飞机进行血槽显示，降低了游戏难度；

>我方有3条生命，每次被消灭，复活后有3s的无敌时间

>对历史最高分数进行记录


**未完成部分：**

飞机生命医疗补给包

无敌10s护盾

敌方飞机射击


**这些内容将在以后进行增加.........**

***
### 游戏效果
 ![alt text](https://github.com/schrodingercatss/Plane-Fight-by--pygame/blob/master/images/20171202162449.png)
 
 
 ![alt text](https://github.com/schrodingercatss/Plane-Fight-by--pygame/blob/master/images/20171202162502.png)




