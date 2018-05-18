视频分析理解
https://blog.csdn.net/wzmsltw/article/details/70239000 论文
数据集：

1.
http://crcv.ucf.edu/data/UCF101.php
UCF101:来源为YouTube视频，共计101类动作，13320段视频。共有5个大类的动作：1)人-物交互；2)肢体运动；3)人-人交互；4)弹奏乐器；5)运动。
2.
http://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/#Downloads
HMDB51:来源为YouTube视频，共计51类动作，约7000段视频。
3.
骨架数据库，比如MSR Action 3D，HDM05，SBU Kinect Interaction Dataset
4.
面向行为识别与定位的视频数据集SLAC
http://slac.csail.mit.edu/


5.
TwentyBN 建立手势动作的 Jester 数据集。（数据来源： Moritz Mueller-Freitag 的 Medium）

6.
Google 公布了原子视觉动作（AVA）数据集

7.
MIT IBM Watson AI Lab 公布了一个视频数据集 Moments in Time Dataset

附：一些行为识别公开数据库汇总

1.HMDB51

来源为YouTube视频，共计51类动作，约7000段视频。数据库主页为：HMDB: a large human motion database

2. KTH人体行为数据库

该数据库包括6类行为（walking,jogging, running, boxing, hand waving, hand clapping）,是由25个不同的人执行的，分别在四个场景下，一共有599段视频。背景相对静止。正确率需要达到95.5%以上才能够发文章。下载地址：http://www.nada.kth.se/cvap/actions/

3. INRIA XMAX多视角视频库

该数据库从五个视角获得，一共11个人执行14种行为。室内四个方向和头顶一共安装5个摄像头。另外背景和光照基本不变。下载地址：http://4drepository.inrialpes.fr/public/viewgroup/6

4. UCF Sports 数据库

该视频包括150段关于体育的视频，一共有13个动作。实验室采用留一交叉验证法。2011年cvpr有几篇都用这个数据库，正确率要达到87%才能发文章。下载地址：http://vision.eecs.ucf.edu/data.html

5. Hollywood 人体行为库

该数据库包括8类行为。这些都是电影中的片段。 下载地址：http://www.di.ens.fr/~laptev/actions/hollywood2/

6. Olympic sports dataset

该数据库有16种行为，783段视频。现在的正确率大约在75%左右。下载地址：http://vision.stanford.edu/Datasets/OlympicSports/

7. 谷歌AVA dataset

是YouTube上提取的被标注的80个原子动作。共5.8万个片段，包含握手、踢腿、拥抱、接吻、喝酒、玩乐器、散步等日常活动。下载地址：https://research.google.com/ava/

算法模型
https://github.com/facebookresearch/DetectAndTrack
DeepMask+SharpMask：https://github.com/facebookresearch/deepmask
MultiPathNet：https://github.com/facebookresearch/multipathnet
演示：https://www.facebook.com/aidemos/

1] DeepMask: Learning to Segment Object Candidates. Pedro O. Pinheiro, Ronan Collobert, Piotr Dollár (NIPS 2015)
[2] SharpMask: Learning to Refine Object Segments. Pedro O. Pinheiro, Tsung-Yi Lin, Ronan Collobert, Piotr Dollàr (ECCV 2016)
[3] MultiPathNet: A Multipath Network for Object Detection. Sergey Zagoruyko, Adam Lerer, Tsung-Yi Lin, Pedro O. Pinheiro, Sam Gross, Soumith Chintala, Piotr Dollár (BMVC 2016)




