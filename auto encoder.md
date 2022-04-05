# auto encoder

https://deepinsight.tistory.com/126

input

![img](https://blog.kakaocdn.net/dn/8JonH/btqFBec9cAF/mhxdDF930R0CrHs9NdUKv1/img.png)



- 입력과 출력이 같은 구조
- Bottleneck Hiddenlayer
  - latent variable
  - feature
  - hidden representation



- Input data를 encoder network 에 통과시켜 압축된 z값 얻음
- 압축된 z vector로부터 input data 와 같은 크기 출력 값 생성
- Loss 값은 입력값 x와 decoder를 통과한 y값의 차이



-- 선택한 키워드를 입력값에

예측된 결과물을 y decoder 값에

ex) alopecia --> Z (latent variable) --> minoxidil



언제 Autoencoder 사용?

- 실제로 **input data의 feature를 추출할 때** 많이 사용
- 주로 dimension reduction 에 사용
  - network parameter 초기화, pre-training 에 많이 사용
  - 이 때는 batch-norm, xavier initialization같은 기법 없었음





비지도 학습

