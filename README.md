# CelebHair

## CelebHair Framework

A visual layout of our data collection framework: 

![image-20211123101213358](https://tva1.sinaimg.cn/large/008i3skNly1gwov2x86b5j30r10g1wfg.jpg)

## Faceshape Classification

Five classes of face shapes and their classification results: 

![image-20211123100423516](https://tva1.sinaimg.cn/large/008i3skNly1gwouus2wu6j30l109h75r.jpg)

## Hairstyle Classification

Ten classes of hairstyles available in the Hairstyle30k dataset:

![image-20211123100852698](https://tva1.sinaimg.cn/large/008i3skNly1gwouzfolmuj30kn0b1myv.jpg)

## Hairstyle Try-on

The hairstyle try-on process through face-swapping:

![image-20211123100930480](https://tva1.sinaimg.cn/large/008i3skNly1gwov0379c3j30ee06k74i.jpg)

## Data Description

The distribution of different face shapes and hairstyles in *CelebHair*: 

![image-20211123101339818](https://tva1.sinaimg.cn/large/008i3skNly1gwov4ezt78j315j0g73zr.jpg)

## How to train

```shell
./darknet detector train data/face.data cfg/face.cfg yolov4.conv.137 -map 
```



