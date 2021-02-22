# PUSIL

### 1. 게임 소개

- 게임 시작 화면
![image](https://user-images.githubusercontent.com/57399274/108728742-32da8980-756d-11eb-8e22-cd14f0448d88.png)

- 스테이지 선택 화면
![image](https://user-images.githubusercontent.com/57399274/108729042-79c87f00-756d-11eb-8b66-94e7ef465b32.png)

- 게임 화면
![image](https://user-images.githubusercontent.com/57399274/108729336-c1e7a180-756d-11eb-92e4-4e6cdf9b557f.png)

  횡스크롤 리듬게임으로 나타나는 노트에 맞춰 해당되는 키를 눌러 판정받아 점수를 얻는 게임이다.   
  노트는 점프 노트와 몬스터 노트가 있는데, 점프 노트는 space 키로, 몬스터 노트는 e, f, j, o 키로 입력받는다.   
  miss 판정이 뜨면 플레이어의 체력이 깎이고 체력바의 체력이 0이 되면 게임이 끝난다. (추후 개발 예정)   
  각 스테이지마다 플레이어가 진행한 게임의 진행률(%)가 기록되고 게임오버가 된 경우 이전의 진행률을 갱신하면 스테이지 선택화면에서의 진행률도 갱신된다. (추후 개발 예정)   
  플레이어는 게임 중 코인을 모아 상점을 이용할 수 있다. (추후 개발 예정)   
  
---

### 2. 게임 조작법 (사용법)
  
  ##### 1) 몬스터 공격 키 : e f j o
   ![몬스터 공격 키](https://user-images.githubusercontent.com/57399274/108726886-4553c380-756b-11eb-8829-b02e8ded8ffb.jpg)
    
   왼쪽부터 e, f, j, o
    
  ##### 2) 점프 키 : space
  
  ##### 3) 스페셜 공격 키 : enter (추후 추가될 예정)
  
  ---
  
  
### 3. 스토리라인

  푸실 종족은 어느 날 갑작스럽게 멸망하고 주민들이 모두 사라져버렸다.
  그 안에서 살아남은 주인공(플레이어)은 주민들을 찾아내서 종족을 다시 부흥시키고자 한다.
  플레이어는 푸실을 조종함으로써 몬스터를 처치하고 주민들을 하나둘씩 찾아내야 한다.
  
---

### 4. 추후 게임 개발 방향

   1) 몬스터와 노트 오브젝트를 오브젝트 풀링으로 관리
   2) 장애물 배치
   3) 노트 배치
   4) 스테이지 업데이트
   5) 상점 및 기타 컨텐츠 추가
   6) 몬스터 공격 키별로 푸실 공격 애니메이션 추가 및 몬스터 세부 애니메이션 추가
   7) 몬스터 체력바 추가
   8) 스토리 진행 가시화 컨텐츠
