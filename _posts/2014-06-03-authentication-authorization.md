---
layout: post
published: true
---

## 사용자 인증 및 권한 설정

2014년 6월 3일 프로그래밍 모임에서 발표함

* devise + rolify + cancancan (박성완 발표)

모든 권한 로직을 Ability라 클래스 한 군데에서 구현하기 때문에 권한설정을 관리하기가 손쉽다.

* devise + rolify + authority (최효성 발표)

권한 로직을 모델별로 분산하여 구현할 수 있다. 3가지 정도의 구현 전략으로 분류해 볼 수 있다. 

![](http://i1373.photobucket.com/albums/ag392/rorlab/Photobucket%20Desktop%20-%20RORLAB/exploring_devise/authority_strategy_zpsa6415ee4.png)

## Authority 젬을 이용한 실전 코딩

시나리오의 작성

1. Foundation 젬을 설치하여 뷰 템브릿을 디자인한다.
2. Simple_form 젬을 설치하여 셋업한다. 
3. Devise 젬을 설치하여 회원인증 시스템을 구현한다. 
4. Rolify 젬을 설치한다.
5. Authority 젬을 설치한다. 



