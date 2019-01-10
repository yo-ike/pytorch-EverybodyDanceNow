# pytorch-EverybodyDanceNow
This repository tries to implement [Everybody Dance Now](https://arxiv.org/abs/1808.07371) by pytorch.

![Result](output.gif)

forkしたnyoki-mtl氏のものをGoogle Colaboratoryで動かすようにした  
及びGlobal Pose Normalizationの実装のチャレンジ（途中)  

## 実行方法
Googleドライブにここの構成をそのまま流す  
そうしたら1から順番に実行してゆく(ディレクトリなどは適応調整)  
I/O入力がColaboratoryでは出来なそうなので新たに1.5としてtargetも動画から行えるように（その場合、2は省略して3を実行する）  
4は省略可(実装が中途半端)


## Environments
Google Colaboratory(2019-01-10 Python3 GPUmode)  
pytorch: 0.4.1  
opencv: 3.4.1  
