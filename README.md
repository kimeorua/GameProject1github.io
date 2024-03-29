# 게임제목 : ProjectD
## 목차
[1.게임 장르](#게임-장르)

[2. 게임 제작 환경](#게임-제작-툴)

[3.주차별 개발 현황](#주차별-개발-현황)

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
  
  캐릭터: 앞,뒤,좌,우,점프 애니메이션 구현
  적: 대기, 이동, 공격. 죽음 모션 구현
  
### 4주차
  개발 목표: 적 및 캐릭터의 전투 기초 구현
  
  게임에 사용할 무기 아이템 구현 및 전투 역학 기초 구현
  
  여러 아이템의 장착 및 공격 모션 HP가 다떨어져 죽는 애니메이션등을 추가 하였다.
  
  무기를 이용 하는 공격은 물리 데미지를주며 어떤 속성의 무기를 사용하던 무기를 이용한 집적 공격은 물리공격으로 판정한다.
  
  무기를 이용한 직접 공격은 마우스 좌클릭을 눌러서 발동하며, 모션은 가로롤 베는 모션과 세로로 베는 모션 2가지가 있다.
  
  공격용 무기
  
  1.화염속성 마법검
  
  <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/%EB%A7%88%EB%B2%95%20%EA%B2%80.PNG?raw=true">
  
  2.번개속성 마법도끼
  
  <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/%EB%A7%88%EB%B2%95%20%EB%8F%84%EB%81%BC.PNG?raw=true">
  
### 5주차
  개발 목표: 주인공이 사용하는 마법 스킬 구현
    
   주인공이 사용하는 마법은 무기에 종속 되어 있으며, 마법 공격은 속성 데미지를 준다
    
   화염 속성 마법검 = 화염 속성의 마법만을 발사 할수 있다.
    
   번개 속성 마법도끼 = 번개 속성의 마법만을 발사 할수 있다
    
   마법은 마우스 우클릭을 눌러서 발사하며 조준은 마우스를 이용하여 조준 한다.
    
   화염 마법
  
   <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/%EB%B6%88%20%EB%A7%88%EB%B2%95.PNG?raw=true">
   
   전기 마법
   
   <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/%EC%A0%84%EA%B8%B0%20%EB%A7%88%EB%B2%95.PNG?raw=true">
   
### 6주차
  개발 목표: 마법 스킬의 이펙트 구현 및 데미지 수치 지정
  
   마볍 스킬의 이펙트및 효과음을 추가하여 보다 게임에 맞는 효과를 보이게 수정 하였고, 
    
   적 캐릭터의 약점 속성에 맞는 공격을 하면 원래 들어가는 데미지 보다 2배의 데미지가 들어가게 데미지 계산 역학을 수정 하였다.
    
   수정방법: Enum 클래스를 생성하여 각각 화염. 번개, 물리의 속성을 생성 하였고 각각의 클래스에 변수(에디터에서 변경 가능하게)로 지정하여, 에디터에서 속성을 선택.
    
   데미지를 주기전에 약점 속성과 현제 데미지 속성이 같으면 2배의 데미지를 주도록 코드를 작성 하였다.
    
### 7주차
  개발 목표: 맵이동을 위한 포탈 이펙트 수정 및 맵 구조 변경
  
  포탈 객체에 이펙트를 추가하여 눈에 잘 띄게 변경 하고 첫번째 맵의 몬스터 및 무기와 아이템의 배치를 변경 하엿다.
  
  포탈 
  
  <img src ="https://github.com/kimeorua/kimeorua.github.io/blob/main/%ED%8F%AC%ED%83%88.PNG?raw=true">
  
### 8주차
  개발 목표: 몬스터가 생성되는 스폰 볼륨 생성
  
  플레이어가 특정 위치에 도달하면 일정간격으로 몬스터를 스폰하는 객체를 생성
  -> 랜덤으로 몬스터의 위치 및 종류를 설정 하고 생성하며 플레이어가 범위 안에 들어올시 추적 및 공격을 시작함

### 9주차
  개발 목표: 몬스터로 부터 지켜야하는 석상 구현
  
  플레이어가 지켜야 하는 석상으로 몬스터가 접촉하면 폭발 하며 HP가 감소한다.
  
  석상
  
  <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/%EC%84%9D%EC%83%81.PNG?raw=true">
  

### 10주차
  개발 목표: 맵 디잔인 및 배치
  
  플레이어가 플레이할 맵의 불필요한 요소를 제거하고 게임의 목표에 맞게 디자인을 변경 및 석상과 몬스터가 나오는 지점을 배치

  시작지점
  
  <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/%EC%8B%9C%EC%9E%91%EC%A7%80%EC%A0%90.PNG?raw=true">
  
  1스테이지
  
  <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/1%EC%8A%A4%ED%85%8C%EC%9D%B4%EC%A7%80.PNG?raw=true">
       
  2스테이지
  
  <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/2%EC%8A%A4%ED%85%8C%EC%9D%B4%EC%A7%80.PNG?raw=true">
  
### 11주차
  개발 목표: 관문 구현 및 몬스터의 드랍 테이블 설정
  
  플레이어가 일정 수의 몬스터를 잡으면 열수 있는 관문을 구현 하고 몬스터의 드랍 테이블을 설정 한다
  
  관문
  
  <img src = "https://github.com/kimeorua/kimeorua.github.io/blob/main/%EA%B4%80%EB%AC%B8.PNG?raw=true">

### 12주차
  개발 목표: UI 구현
  
  게임에 필요한  UI 구현 및 게임의 스타트 버튼 구현

### 13주차
  개발 목표: 게임의 종료 및 엔딩 구현
  
  플레이어가 게임을 클리어 하거나 죽으면 엔딩 및 재시작하는 프로그렘을 구현

### 14주차
  개발목표: 자잘한 버그 및 몬스터 스폰 구역 재설정
  
  문제점: 석상과 몬스터의 스폰 구역이 겹쳐서 몬스터가 스폰되자 마자 석상에 닿아 사라지는 현상이 생김
  
  해결: 몬스터의 스폰 구역을 줄이고 석상의 위치를 재배치해여 
