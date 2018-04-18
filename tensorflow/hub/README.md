# tensflow hub 学习

示例：https://tensorflow.google.cn/hub/


## 一、获取 花卉 图片集

```
cd ~

curl -LO http://download.tensorflow.org/example_images/flower_photos.tgz

tar xzf flower_photos.tgz
```

## 二、下载示例代码

```
mkdir ~/example_code

cd ~/example_code

curl -LO https://github.com/tensorflow/hub/raw/r0.1/examples/image_retraining/retrain.py

```

## 训练数据

```
python retrain.py --image_dir ~/flower_photos
```

获取选项列表

```
python retrain.py -h
```