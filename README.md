# game project


<p>
	프로젝트 주제: 베스킨라빈스31 아이스크림을 모티브하여 계산기 앱을 통해 누적된 매출액을 정산하는 파이게임</br>
 프로젝트 진행기간: 2022년 4월 11일 ~ 2022년 6월 17일 예상</br>
	팀명: TWO준캐리조(3조)</br>
 - 팀장: 전혜나(202004449)</br>
 - 팀원: 김미영(202100573), 박정민(202004233), 이성준(202102467), 정준혁(202103172)</br>
 프로젝트 주제: 베스킨라빈스31 아이스크림을 모티브하여 계산기 앱을 통해 누적된 매출액을 정산하는 파이게임</br>
 포지션: 
</p>
<p>
<h4>주차별 일정</h4>
9 주차(4월 27일 ~ 5월 3일)  - 공통) 주제 선정 후, 코드 설계, pygame 모듈에 대한 공부</br>
10주차(5월 4일 ~ 5월 10일)  - 공통) pygame 모듈에 대한 공부
                             프론트엔드)코드 작성 전 기본틀 깃허브에 주석으로 작성 </br>
11주차(5월 11일 ~ 5월 17일) - 공통) pygame 모듈에 대한 공부</br>
                             백엔드) 프로그램 시작단계 작성</br>
                             프론트엔드) 시작단계에 필요한 그림 제작, 이미지 찾기, png파일로 업로드</br>
12주차(5월 18일 ~ 5월 24일) - 게임화면 ~ 고객 주문 구현</br>
13주차(5월 25일 ~ 5월 31일) - 아이스크림 제조 ~ 종료 구현</br>
14주차(6월  1일 ~ 6월  7일) - 전체적인 보수, 앱사이트 만들기, 앱사이트에 업로드하기
</p>

개발 순서
게임 시작화면 -- 배경이미지, 게임 타이틀 아이콘, 도움말 아이콘 필요
게임 실행 -- 맛 8개 나열, 각 맛 별 값 배정, 랜덤으로 숫자 발생 후 키보드 이벤트로 받은 값과 비교하여 정답 오답처리. 왼쪽 위에 타이머, 오른쪽 위에 목숨 수.
---- Gamestart 클래스
---- 함수
 	init()
	quest() -- random 약 25개 정도
	check() -- quest와 비교하여 count
	endmenu()
	timer()
	sale()
	Hp()
	cup&con()
	
	//consumer() -- 말풍선//
	//saleman() -- 말풍선//
	
	
게임 종료 화면 -- 맞춘 스코어, 다시하기, 종료
