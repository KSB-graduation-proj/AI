# AI

## Dataset

서울 열린데이터 광장 - `상품 표지 이미지 AI 학습 데이터셋` - `dataset_snack` 이용

[데이터셋 바로가기](https://data.seoul.go.kr/etc/aiEduData.do) 

images: 1300

bBox per images: 5~6


## Object Detection Model

Ultralytics에서 설계한 [yolov5모델](https://github.com/ultralytics/yolov5) 이용

16 batch, 50 epoch로 우선 학습

89% 

## Fine-tuning

W&B 이용하여 진행 중

