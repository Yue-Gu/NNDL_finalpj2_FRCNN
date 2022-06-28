# NNDL_finalpj2_FRCNN
code for final project problem 2

代码与期中作业https://github.com/Yue-Gu/NNDL_midtermpj2_FRCNN/
基本一致，针对三个小问题，只需要进行如下修改：

(a)随机初始化：model_path = '', pretrained = False, Freeze_Train = False
(b)(c)在对应net文件夹中修改下载路径，选择imagenet和coco对应的网络权重，之后pretrained修改为True即可。按照题目要求，不需要进行freeze train，但经过尝试，freeze train表现更好，训练更快。
