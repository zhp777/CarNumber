# CarNumber
1.运行train-license-province.py train,首先进行省份简称训练。在运行代码之前，需要先把数据集解压到训练脚本所在目录;
2.运行train-license-province.py predict,省份简称识别;
3.运行train-license-letters.py train,城市代号训练,如车简称后的字母;
4.运行train-license-letters.py predict,识别城市代号;
5.运行train-license-digits.py train,执行车牌编号训练
6.运行train-license-digits.py predict,识别车牌编号;
这样分布得到图片中的车牌号.
