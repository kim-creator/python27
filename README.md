학습이란?
머신러닝 알고리즘에 데이터를 대입해서 머신러닝 모델이 데이터를 이해하게 하는 것

지도학습을 위해 필요한 것
feature : 학습해야 할 데이터
label : 정답
분류(Classification), 회귀(Regression)
분류
카테고리를 예측하는 과정

고양이, 강아지 둘 중 하나를 예측 하겠다.
비만인지 아닌지를 예측하겠다.
스팸메일인지 아닌지를 예측 하겠다.
이진 분류(Binary Classification)
Yes(1) No(0) 으로 분류하는 과정.
1(양성)이라고 무조건 좋은게 아니다.
0(음성)이라고 무조건 나쁜게 아니다.
비만이면 1, 비만이 아니면 0
1번 클래스를 양성 클래스
0번 클래스를 음성 클래스
다중 분류(Multiclass Classification)
3개 이상의 결과를 분류하는 것
이 숫자는 0,1,2,3,4,5,6,7,8,9중에 무엇입니까?
이 동물은 고양이, 강아지, 닭 중에 무엇입니까?
회귀
연속적인 숫자, 또는 부동 소수점 수(실수)를 예측 하는 것
올해 옥수수 수확량 예측
이 택시가 얼마나 걸릴 것인가?
올해 아파트 가격은 얼마정도 될 것인가?
주식의 변동량이 얼마일까요?
일반화(generalization)
학습된(훈련된) 모델이 처음 보는 새로운 데이터가 주어져도 정확하게 예측을 할 수 있는 것

너무 모델이 데이터를 복잡하게 해석하게 해서도 안되고, (과대적합 방지) 모델이 데이터를 너무 단순하게 해석하게 해서도 안된다.

복잡도 조절
데이터의 복잡도를 조절하는 방법
데이터의 특성(feature)가 많아지면 데이터가 복잡해 진다.
데이터의 양(volumn)이 많아지면 데이터가 복잡해 진다.
데이터의 스케일이 서로 많이 다르면 데이터가 복잡해 진다.
데이터가 복잡하게 섞여있으면 데이터가 복잡해 진다.
머신러닝 모델의 복잡도를 조절하는 방법
하이퍼 파라미터 조정
과대적합( Overfitting )
모델이 알고 있는(훈련된) 데이터만 너무 복잡하게 해석하는 것
이미 알고 있는 데이터는 잘 예측을 하지만, 보지 못한 새로운 데이터는 예측이 잘 안되는 현상
과소적합( Underfitting )
모델이 훈련 데이터를 너무 단순하게 해석해 버린 것
알고 있던 데이터도 잘 예측을 못하고, 처음보는 데이터도 예측이 잘 안됨
