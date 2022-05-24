# DACON_Motion_Keypoint
![20220524_131106](https://user-images.githubusercontent.com/84311270/169982753-e3d93427-5a32-4630-a79f-adba602c6fbe.png)
Motion keypoint detection 알고리즘 개발
스마트 헬스케어 산업에 적용 가능한 데이터 분석 방법

## Dataset
HumanFit human keypoint set :신체 24개 부위에서 측정한 포인트  

1.open.zip (1.9GB)  
train_imgs : train 이미지 4195장   
test_imgs : test 이미지 1600장  
train_df (4195 *49) : train이미지의 이름과 keypoint 24 지점의 x,y 좌표  
sample_submission(1600 *49) : 정답지  


## Model 
ResNet101과 Keypoint R-CNN을 사용하여 학습을 진행.


