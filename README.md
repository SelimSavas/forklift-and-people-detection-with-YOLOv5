# Forklift and People Detection with YOLOv5

I tagged forklifts and people in 3000 images. I developed forklift and human detection application with YoloV5.

**Train Code**
```
!python train.py --img 416 --batch 128 --epochs 400 --data data.yaml --weights yolov5s.pt --cache
```
**Test Detection (Video)**
```
!python detect.py --weights /content/best.pt --img 416 --conf 0.40 --source "/content/testVideo4.mp4"
```
![image](https://user-images.githubusercontent.com/48186387/235376590-d4282565-1d1b-48fb-9345-64a4d969b3ff.png)

**Tagged Dataset**
I tagged the image data from ImageNet, Roboflow and Kaggle platform with MakeSense. You can use my  [Google Drive](https://drive.google.com/file/d/1b5-plGXRc4u5CjxOvDp3xEuAdsyA1eRs/view?usp=sharing) to download.


