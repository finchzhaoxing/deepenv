# deepenv
可以使用gpu的深度学习环境Dockfile
cuda：10.1
CUDNN：7
Anaconda：2019.07-Linux-x86_64
openssh-server
tensorflow-gpu：1.14
tensorboardX：1.9
pytorch:1.3
keras
autopep8
torchsnooper
pysnooper
NNI：1.1
jupyter_contrib_nbextensions
部分包用清华镜像下载比较大，最好先下载到本地，COPY到容器里去，再安装
基础的nvidia/docker镜像有时可能会因为网络问题，下载很慢，需要多尝试几次
最终镜像大约11G
