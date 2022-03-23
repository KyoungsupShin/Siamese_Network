# Siamese Network for one shot learning

Siamese Network는 CNN의 합성곱에 3차원 이하의 Vector로 Output을 내며 기존 Classification과 다른 별도의 Loss function을 사용하여 
학습하는 모델링 개념이다. 

1. 사용목적
2. 장점
3. 단점

### Classification 아키텍처
![image](https://user-images.githubusercontent.com/66240947/159627529-5164b26b-06af-4259-b6f1-31d23d71ffc5.png)


![image](https://user-images.githubusercontent.com/66240947/159627583-bb78e7ec-5bf9-487a-873b-5750db2ce205.png)


![image](https://user-images.githubusercontent.com/66240947/159627593-7458d387-b9fe-4f96-ad19-dd6eb13c08c3.png)


### 실험 데이터
1.MINST
2.CIFAR10

### CNN 아키텍처
1. SimpleCNN
2. ResNet18
3. ResNet52
4. EfficientNet
