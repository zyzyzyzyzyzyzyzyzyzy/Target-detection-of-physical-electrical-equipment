# Target-detection-of-physical-electrical-equipment
任务
==
* 基于Focs目标检测算法完成中学物理器材的检测与安卓端的部署（平台暂定红米k30pro手机）
检测目标为正确的识别物理实验器材的种类与位置，使用pycharm与anaconda管理代码与环境，
pytorch框架训练模型，端侧部署框架暂定使用腾讯开源推理框架ncnn。

* 场景：室内光照充足

数据集
==

* 训练集：5320张

* 测试集：1330张

* 图片分辨率：416*416

* 类别数：7 Switch，Light，Resistance，Voltmeter，Ammeter，Battery，Battery bay

评价指标
==
* map@0.5：0.95 越高越好

不出现误检，与漏检情况

* fps：1s能处理多少张图片


 

