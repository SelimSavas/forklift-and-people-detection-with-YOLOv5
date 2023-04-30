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



### Tagged Dataset


I tagged the image data from ImageNet, Roboflow and Kaggle platform with MakeSense. You can use my  [Google Drive](https://drive.google.com/file/d/1b5-plGXRc4u5CjxOvDp3xEuAdsyA1eRs/view?usp=sharing) to download.

**Data Distribution**

 ![image](https://user-images.githubusercontent.com/48186387/235375937-7ae9f4dc-501c-4037-8678-60f9116e64c4.png)



### Flow Chart Diagram
![AkisDiyagrami](https://user-images.githubusercontent.com/48186387/235375838-95dd3210-bbdc-4d07-9a80-fe2892fe9b93.jpg)



