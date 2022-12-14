## GUI 기반의 할리갈리 게임 구현
## 할리갈리 룰 및 프로그램 동작 방식
 - #### 처음 시작 할리갈리 게임을 실행시키면 게임 난이도를 사용자에게 선택하라는 입력창이 뜬다. 
 - #### 상은 타이머의 시간을 1초로 설정, 중은 타이머의 시간을 2초로 설정, 하는 타이머의 시간을 3초로 설정. 
 - #### 이후 플레이어와 컴퓨터가 전체 56장의 카드를 랜덤하게 28장씩 나눠가진 뒤 게임을 진행할 frame이 화면에 출력된다. 
 - #### Draw 버튼을 누르면 처음에 플레이어가 먼저 카드를 내고 그 다음 Draw 버튼을 누르면 컴퓨터가 카드를 한 장 낸다. 
 - #### 이때 서로 제출한 카드의 과일의 종류가 같으면서 총합이 5개가 되는 순간 컴퓨터가 버튼을 누르는 동작을 대신하는 타이머가 나오고 그 타이머가 time out 상태에 이르기 전에 플레이어가 벨 버튼을 누르면 플레이가 지금까지 냈던 카드들을 모두 자신의 카드덱으로 가져간다. 
 - #### 만약 플레이어가 타이머가 time out 상태에 이르기 전에 벨 버튼을 누르지 못한다면 컴퓨터가 이긴 것으로 간주하고 컴퓨터의 카드덱에 지금까지 냈던 카드들을 모두 추가해준다.
 - #### 이런 방식으로 컴퓨터와 플레이어가 한 장씩 카드를 내다가 한 플레이어의 남은 카드 수가 0장이 되면 다른 플레이어가 계속 카드를 제출한다(같은 과일의 총합이 5개가 될 때까지). 
 - #### 최종적으로 둘 중 한 플레이어가 가진 카드 수가 0장이 되면  게임이 종료되고 56장의 카드를 가진 플레이어가 할리갈리 게임에 승리한다.
 
 ## 프로그램 클래스 다이어그램
 <img src="./Untitled_Workspace.png" width="100" height="100"/>
