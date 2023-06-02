# AI

## Dataset

서울 열린데이터 광장 - `상품 표지 이미지 AI 학습 데이터셋` - `dataset_snack` 이용

[데이터셋 바로가기](https://data.seoul.go.kr/etc/aiEduData.do) 

매점 상품을 직접 촬영한 영상으로 annotation한 데이터셋

[roboflow 데이터셋 바로가기](https://universe.roboflow.com/team-ksb/coopgo-jt0i6/dataset/6https://universe.roboflow.com/team-ksb/coopgo-jt0i6/dataset/6)

### Augmentation
Outputs per training example: 3

Hue: Between -19° and +19°

Brightness: Between -30% and +30%

Bounding Box: Shear: ±15° Horizontal, ±15° Vertical

## Object Detection Model

Ultralytics에서 설계한 [yolov5모델](https://github.com/ultralytics/yolov5) 이용



## Result

```
YOLOv5l summary: 267 layers, 46318293 parameters, 0 gradients, 108.3 GFLOPs
                 Class     Images  Instances          P          R      mAP50   mAP50-95
                   all       4161       7415      0.962      0.966      0.983      0.792
                 Binch       4161        262      0.995      0.996      0.995      0.913
            Oreo_black       4161         14      0.857          1      0.995      0.662
              Oreo_red       4161        124      0.961      0.987      0.993      0.808
              CushCush       4161        180      0.989      0.982      0.993       0.76
                Gosomi       4161        226      0.996      0.992      0.995      0.831
          Yegam_Cheese       4161        243       0.99          1      0.995      0.811
    OreoThins_Tiramisu       4161        258      0.995      0.996      0.995      0.848
OreoThins_VanillaMooth       4161        270          1      0.995      0.995      0.868
  ChocChocHanChocoChip       4161        283          1          1      0.995      0.896
              ChicChoc       4161        530      0.994      0.997      0.995        0.9
  YuginongBlueberry_TT       4161        498      0.954      0.907      0.982      0.795
     YuginongAronia_TT       4161        194      0.927      0.933      0.957      0.718
  YuginongSiguemchi_TT       4161         89      0.989          1      0.995      0.891
     YuginongBanana_TT       4161         53      0.989          1      0.995      0.839
YuginongPlaneYogurt_Cube       4161         39      0.911          1      0.994      0.752
                simpop       4161         85      0.944      0.953      0.991      0.718
             cheetos_r       4161         92      0.864      0.913      0.917      0.623
             cheetos_b       4161         59      0.875          1       0.98      0.737
             cheetos_y       4161         74      0.884      0.931      0.979      0.694
             gamjasokB       4161         33      0.945          1      0.994      0.706
             gamjatokB       4161        210      0.894       0.96      0.978      0.637
             gamjatokG       4161         76      0.889      0.953      0.973      0.692
 AlmondBreeze_Original       4161        247      0.981      0.947      0.985      0.841
             Bodyfit_4       4161        242          1      0.964      0.988      0.822
   ChaltteokPie_single       4161        123      0.963      0.855      0.916      0.718
          CherryTomato       4161        892      0.994      0.935      0.983       0.79
          CocaCokeZero       4161        244          1      0.964      0.987      0.888
         CupNoodle_Hot       4161        394      0.991      0.995      0.995      0.926
        CupNoodle_Mild       4161        404      0.998          1      0.995      0.942
      EwhaBallPointPen       4161        118      0.991      0.988      0.994      0.799
       Margaret_single       4161        122      0.991      0.863      0.955      0.821
           Tofu_Kimbap       4161        296      0.993      0.933      0.988      0.716
         ToothBrushSet       4161        286      0.971      0.938      0.973      0.802
     UmmasonPie_single       4161        155      0.996      0.961      0.992      0.769
```



## 팀원
Coop-go AI 개발 팀원
|김정원|
|:---:|
|AI|
