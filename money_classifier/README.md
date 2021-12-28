![](https://vaytienaz.com/wp-content/uploads/2020/10/me%CC%A3%CC%82nh-gia%CC%81-tie%CC%82%CC%80n-vie%CC%A3%CC%82t-nam.jpg)
# VietNamese Money Classifier

## Install 
#### Requirement
[python>=3.8](https://www.python.org/) is required with [torch](https://pytorch.org/)
#### Setup
```bash
$ git clone https://github.com/GiangNguyenMinh/giang.git
$ cd giang/money_classifier
```

## Create data
```bash
$ python MakeData.py --value 0000
                             10000
                             50000
                             200000
                             500000
```
## Training
```bash
$ python train.py --lr 0.0001 --batch-size 32 --n-epochs 100
```

## Inference
```bash
$ predict.py
```

## Train colab
Colab code [click here](https://colab.research.google.com/drive/15aTHA5HJFVxIv1HLv3zdQu1sqbvCsa3b)