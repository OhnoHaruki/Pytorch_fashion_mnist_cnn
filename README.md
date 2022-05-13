# データセットであるFashion_MNISTをPyTorchを用いて機械学習モデルを作成してみた

衣類の画像から作成されたデータセットで[Fashion_MNIST](https://github.com/zalandoresearch/fashion-mnist)の分類にコンピュータビジョンや自然言語処理で利用されているTorchを元に作られた、Pythonのオープンソースの機械学習ライブラリである、PyTorchを用いてモデルの作成を行いました。

## Pytorchとは
PyTorchはPythonのオープンソースの機械学習ライブラリです。詳しくは[こちら](https://pytorch.org/)をご覧ください。

## 使用したライブラリとインポート
import torch  
from torch.utils.data import DataLoader  
import torch.nn as nn  
import torch.nn.functional as F  
from torch import optim  

import torchvision  
import torchvision.transforms as transforms  
from torchvision.transforms.functional import normalize  

import matplotlib.pyplot as plt  

from google.colab import drive  
drive.mount('/content/drive')  

## 実行環境
MacBook air(2018)  
macOS Monterey  
Google colaboratory  

## 使用したデータ
今回は衣類の画像から作成されたデータセットである、[Fashion_MNIST](https://github.com/zalandoresearch/fashion-mnist)を使用しました。  

## 作者  
* はるき  
* 大学生
* Twitter: @haruki_data

## 最後に
ご覧いただきありがとうございます。PyTorchの基礎を学んだのでFashion_MNISTを用いて実装しました。今回実装してみて、当たり前ですが、データの前処理をもっと工夫することであったり、モデルの内容をもっと工夫することでより良い結果が得られると思うのでもっと勉強して改善を試みようと思います。  
アドバイスなどがありましたらTwitterのDMでお願いします。