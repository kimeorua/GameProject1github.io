# 게임제목 : ProjectD
## 목차
[1.게임 장르](#게임-장르)

[2. 게임 제작 환경](#게임-제작-툴)

[3.주차별 개발 현환](#주차별-개발-현황)

## 게임 장르
### 디펜스
디펜스란??

끊임없이 몰려오는 적들의 공격이나 진입으로부터 기지나 중요 시설, 인물등을 일정 시간동안 보호하는 게임/맵을 칭하는 용어다.

## 게임 제작 툴
### 언리얼 엔진 4
선정이유: 3D게임을 만들 예정으로 3D에 최적화된 언리얼 엔진을 사용 하며, 평소에 언리얼 엔진에 관심이 있고 이를 이용하여 게임을 만드는 것은 좋은 경험이 될 것으로 생각 하기 때문이다.

### 에셋 선정 장소
Mixamo: 무료 캐릭터 및 애니메이선 사이트로 플레이어 캐릭터의 그래픽 및 애니메이션을 가져올 예정이다
언리얼 마켓플레이스: 게임이 판타지 배경이므로 판타지 배경에 맞는 적과 무기 배경등 여러 에셋을 가져올 예정이다.

## 주차별 개발 현황
### 1주차
  개발 목표: 제작할 게임의 장르 선정 및 게임에 사용할 에셋 선정
  
   -> 제작할 게임 장르: 디펜스로 장르 선정
   
   ---> 이유: 처음에는 RPG게임을 만들려 볼려고 하였으나, 시간 및 언리얼 엔진의 이해도 부족으로 인해 구현하기 힘들다고 판단,  비교적 에셋이 적고 구현이 편한 디펜스 게임을 만들기로 결정
                 
  -> 사용할 에셋: 언리얼의 무려 에셋 Infinity Blade 와 파라곤의 에셋 및 Mixamoo, freesound.org의 무료 음향을 사용
  
  ---> 이유: 접근하기 쉽고 무료에셋으로 부담이 적음
      
### 2주차
  개발 목표: 캐릭터의 에셋 선정 및 이동 구현
  
  --->캐릭터 및 적 에셋 선정 및 이동 구현
  
  캐릭터 에셋
  
  <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/%ED%94%8C%EB%A0%88%EC%9D%B4%EC%96%B4%20%EC%BA%90%EB%A6%AD%ED%84%B0.PNG?raw=true">
 
 ----------------------------------------------------------------------------------------------------------------------------------------------------------------------
  
  거미형 적 캐릭터(화속성 약함)
  
  거미형 적은 화속성에 약하며 가장 기초적인 적이다.
  
 <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/%EC%A0%81%20%EC%BA%90%EB%A6%AD%ED%84%B0.PNG?raw=true">
 
 ---------------------------------------------------------------------------------------------------------------------------------------------------------------------
 
 기계형 적 캐릭터
 
 1.(전기 속성 약함)
 거미와 다르게 인간형으로 2족 보행을 하고 전기 속성에 약하다
 
 <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/%EA%B8%B0%EA%B3%84%ED%98%95%20%EC%A0%81%20%EC%BA%90%EB%A6%AD%ED%84%B0.PNG?raw=true">
 
 2.(전기 속성 약함)
 1번의 기계형 적의 강화형태로 공격력과 생명력이 높다. 똑같이 전기 속성에 취약
 
 <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/%EA%B8%B0%EA%B3%84%ED%98%95%20%EC%A0%81%20%EC%BA%90%EB%A6%AD2.PNG?raw=true">
 
 3.(물리 속성 약함)
 1,2번 기계형과 다르게 갑옷을 더 입었다. 전기 속성에 대한 내성을 높힌 대신 물리속성에 약하다.
 
 <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/%EA%B8%B0%EA%B3%84%ED%98%95%20%EC%A0%81%20%EC%BA%90%EB%A6%AD%ED%84%B03.PNG?raw=true">
 
 
### 3주차
  개발 목표: 적 및 캐릭터의 애니메이션 구현
  
  Mixamo사이트 및 Infinity Blade 와 파라곤의 애니메이션을 이용하여 구현
  
  1.캐릭터 
