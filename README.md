# 中原大學人工智慧11/17，11/18，12/01課程
(fork from https://github.com/hunkim/PyTorchZeroToAll)

下載本課程的程式碼
```shell=
mkdir ~/workspace
cd ~/workspace
git clone https://github.com/joshhu/chtpytorch.git
```


## 00
### 安裝必要的東西



先更新Linux!

```shell=
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install git
```

檢查Nvidia驅動程式
```shell=
nvidia-smi
/usr/local/cuda/bin/nvcc -V

```
![](https://i.imgur.com/sWRBvDV.jpg)

## 下載[anaconda](https://repo.anaconda.com/archive/Anaconda3-5.2.0-Linux-x86_64.sh)

或是
```
cd ~
wget https://repo.anaconda.com/archive/Anaconda3-5.2.0-Linux-x86_64.sh
chmod +x Anaconda3-5.2.0-Linux-x86_64.sh
./Anaconda3-5.2.0-Linux-x86_64.sh

```


建立兩個python virtual envs
```shell=
conda create -n pytorch anaconda nb_conda
conda create -n py27 python=2.7 anaconda nb_conda
```
先切換到Pytorch的環境，並安裝pytorch
```shell=
source activate pytorch
pip install torch --upgrade
```

建立一個工作目錄
```
mkdir ~/workspace
```

檢查pytorch是否安裝成功
```python=
import torch
print(torch.__version__)
```
## Graident Descent
## [線上解方程式](https://www.derivative-calculator.net/)
## [線上繪圖](https://www.geogebra.org/3d)

## Data Augmentation

### [Data Aug](https://github.com/aleju/imgaug)

## Learning Rate Decay
### [Learning Rate Decay](https://zhuanlan.zhihu.com/p/32923584)
