# MOCO
该仓库包括在cifar-10数据集上训练得到的模型文件，以及运行日志，并提供了两个notebook以供运行</p>
## 下载权重文件
在moco_cifar10_demo.ipynb训练后，会产生模型权重文件，该文件放置在cache-2025-03-28-03-24-48-moco文件夹下</p>
我们权重文件的提供下载链接：链接: <https://pan.baidu.com/s/1GXqtpCCZZXexL07vZfZt4A?pwd=MOCO> 提取码: MOCO </p>
## 下载flowers数据集
链接: <https://pan.baidu.com/s/1W4INCmJs9JGhj9ggblBSXQ?pwd=MOCO>提取码: MOCO </p>
下载之后解压到根目录即可
--来自百度网盘超级会员v4的分享
## 仓库简介
</p>1、名称为moco-main的文件夹存放的是facebook官方提供的MOCO源码，需要在8张V100的GPU上运行5个小时，不建议实操，可以学习原理。</p>
</p>2、名称为moco_cifar10_demo.ipynb的notebook可以在colab上运行，使用其提供的T4 GPU,训练后会产生模型权重文件(.pth)、超参数文件(.json）、以及记录训练过程的日志（.csv)文件，这些都放在cache-2025-03-28-03-24-48-moco文件夹下。(该文件夹的名称是根据当天运行日期决定）</p>
</p>3、名称为moco_Flowers.ipynb的notebook同样可以在calab上运行，利用flowers数据集来对不同品种的花朵进行分类。</p>
