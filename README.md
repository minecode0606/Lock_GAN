
# Lock GAN

##abstract  
본 연구는 생성적 적대 신경망(Generative Adversarial Network, GAN)의 경쟁적 학습 구조를 정보 보안 분야, 특히 비밀번호 인증 및 암호화 체계에 적용한 새로운 기법 LOCK GAN을 제안한다. LOCK GAN은 Generator를 공격자(블랙해커)로, Discriminator를 방어자(화이트해커)로 설정하여 상호 대립적 학습을 반복한다. Generator는 실제 비밀번호와 유사한 위조 입력을 생성함으로써 판별자를 교란시키고, Discriminator는 이를 판별하는 과정에서 점진적으로 정확도를 향상시킨다. 본 연구에서는 MNIST 데이터셋을 활용하여 LOCK GAN의 프로토타입을 구현하였으며, 학습 과정에서 공격자와 방어자의 성능이 주기적으로 우세와 열세를 교차하면서도 최종적으로는 판별자의 정확도가 기하급수적으로 향상되는 결과를 확인하였다. 이를 통해 LOCK GAN이 단순 정적 암호화 방식보다 적응적이고 지속적인 보안 강화를 제공할 수 있음을 입증하였다. 제안된 방법은 딥러닝 기반 보안 알고리즘의 새로운 가능성을 제시하며, 향후 복잡한 패스워드 데이터셋 및 실전 환경에서의 확장 연구가 요구된다.

##Lock GAN Structure
<p align="center">
  <img src="https://github.com/minecode0606/Lock_GAN/blob/master/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202025-08-24%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%2010.24.41.png?raw=true" 
       alt="Lock GAN 구조 이미지" 
       width="500"/>
</p>

#Project PPT
[![PPT 아이콘](https://img.icons8.com/color/100/microsoft-powerpoint-2019--v1.png)](https://github.com/minecode0606/Lock_GAN/blob/master/lock%20GAN.pptx)
