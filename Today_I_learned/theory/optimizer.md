# optimizer란?
-  머신러닝과 딥러닝의 성능을 높이기 위해 사용하는 것
- 신경망의 모델이 실제 결과와 예측결과의 차이를 최소화 시키기 위해서 사용
- EX) 네비게이션이 도착지까지 빠른길을 알려주거나 큰길을 알려주거나, 무료로된 길을 알려주고 사용자가 자신이 그 상황에 가장 적합한 길을 선택하는 것처럼, 다양한 최적화 방법들 가운데 사용자가 가장 적합한 알고리즘을 선택하고 대응하는 것과 같음
- 머신러닝 학습 프로세스에서 실제로 파라미터를 갱신시키는 부분
  - 각 파라미터 기울기를 그라디언트로 구하여 재료를 구해왔으면, 이를 이용하여 실제 가중치의 변화를 주는 부분
- 종류
  1. GD(Gradient Descent:경사하강
  2. SGD(Stochastic Gradient Descent:확률적 경사 하강법)
  3. Momentum
  4. NAG(Nesterov Accelerated Gradient)
  5. Adam
  6. AdaGrad
  7. RMSProp
  8. AdaMax
  9. Nadam

 -![image](https://user-images.githubusercontent.com/88295944/131448438-4e7652fc-bb7a-49b3-8668-39edabc86666.png)
