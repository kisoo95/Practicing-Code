# Coding U-net
Dataset: https://github.com/alexklibisz/isbi-2012

Data Preprocessing & U-net code: https://github.com/HyunLee103/Pytorch_practice/blob/master/UNet_segmentation/UNet_train.ipynb

# U-net을 배운 이유
이미지의 모든 픽셀이 어떤 카테고리에 속하는지 분류하는 작업을 Image Segmentation이라고 한다. Image classification과는 달리 픽셀 단위로 학습이 진행되므로 더 어려운 문제이다. 이러한 Image Segmentation에서 성과가 좋은 모델 중 하나가 U-net이다. U-net은 2015년 U-Net: Convolutional Networks for Biomedical Image Segmentation이라는 논문에서 제안하였다. U-net의 기본구조는 Autoenocder과 비슷하게 econder-decoder 기반 모델이지만, 저차원 정보와 고차원 정보 두 가지 모두 이용하기 위해 concatenation 방법을 사용한다. 이러한 구조로 인해 U자 모형처럼 생겨서 U-net이라고 통용하였다.
