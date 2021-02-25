# Java_Study

## Java_Study 플레이그라운드 by 호눅스님
  - 만들어가면서 지식이 필요할때, 그때서야 지식을 채워넣는 방식이 빠름.
  - 초중고 12년 대학교 4년동안 우리는 만들고싶은게 없는상태에서 지식만을 배움
  - 이런방식의 교육이 효과가 있나요?? 없음.
  - 어떤 방식으로 공부할때, 덜 스트레스 받는 방법으로 공부해야한다.

## 자바 학습관런 조언
  - 구현해보고 싶은 작은 프로그램을 만들거나/따라하기식 강의
  - 문제부터 해결하고 이해가 안되는 부분은 책을 참고
  - A라는 개념/단원이 이해가 안되면 걸려서 넘어지지말고 일단 빠르게 Pass하고 다음에 필요할때 돌아오기
    - 모르는 개념을 내버려두다 보면 다른개념을 학습하다가 자연스럽게 이해되는 경우가 많다!
  - 검색을 습관화!
  
## 프로그래밍 개념 맛보기 
  - 원문 : https://www.slideshare.net/baejjae93/nhn-next-preschool
  - 인간의 본능은 절차지향적으로 생각하려고 함
  - 컴퓨터에게 일을 시키기 위한게 : 프로그래밍 랭귀지
    - 콤퓨타의 관점에서, 콤퓨타가 이해할 수 있는 언어로 표현하는 방법을 학습
  - Flow chart : 작업의 순서를 그림으로 표현
    - 생각의 결과를 표현하고 다른사람에게 설명하기 위해서
    - 내가 스스로 정리하고 처음에 헀던 생각을 그대로 구현하기위해 (금방 까먹거든)
  - 모든일(작업)을 논리적인 순서에 따라 요리책처럼 정리하는 사고능력이 중요함

# 자바 이론/개념 정리
   ###  - 5차시(2020-12-19) : [링크 /하드 : Java_Study/Mobidic/자바 5차시.md](./Mobidic/java5t.md)
   ###  - 6차시(2020-12-19) : [링크](./Mobidic/java6t.md)
   ###  - 7차시(2021-01-02) : [링크](./Mobidic/java7t.md)
   ###  - 8차시(2020-12-19) : [링크](./Mobidic/java8t.md)
   ###  - 9차시(2020-12-19) : [링크](./Mobidic/java9t.md)
   
   
# 토이프로젝트 - 구구단
  - 학습목표
    - 구구단 프로그램을 구현하고 실행하는 방법
    - 프로그래밍 구현시 단축키를 사용하는 방법
    - 사용자 값을 입력하는 방법과 콘솔에 값을 출력하는 방법
    - 변수, 데이터 타입, 반복문, 조건문을 사용하는 방법
    - 배열, 메소드, 클래스를 활용해 프로그래밍하는 방법

  ```
  ```

# 토이프로젝트 - 캘린터
 
## 1) 월별 최대 일수 구하기
## 2) 프롬프트를 추가해서 년월을 입력하면 몇일로 되어있는지 출력하기
## 3) 윤년을 고려해서 기능추가하기
## 4) 프롬프트에 종료조건 출력하기
  - 입력하는 곳 앞에 프롬프트를 출력한다.
  - 1일 입력받을 경우 프로그램을 종료한다
## 5) 달력 찍기 : 1.기본달력
  - 월을 입력하면 해당월의 달력을 출력한다.
  - 1일이 무조건 일요일로 출력되도 무방하다
  - -1 입력시 종료, 프롬프트 출력
  - 윤년고려 테스트(2400년 2월..)
## 6) 달력 찍기 : 2.정교해짐
  - 년/월 + 요일을 입력받는다.
  - 입력받은 요일을 시작으로 출력한다.
  - 입출력 예시
  ```
	년도를 입력하세요.
	YEAR> 2017
	달을 입력하세요.
	MONTH> 3
	첫번째 요일을 입력하세요. (SU, MO, WE, TH, FR, SA)
	WEEKDAY> WE

		<<2017년  3월>>
	 SU MO TU WE TH FR SA
	---------------------
           1  2  3  4
	5  6  7  8  9 10 11
  ```
## 7) 달력 찍기 : 3.요일 시작 자동화
  - 3단계와 같지만 년도와 월만 입력받는다.
  - 진짜 캘린더에서 나오는 달력과 똑같은 모양의 달력을 출력한다.
  - 추가적으로 입력받아야 하는 내용이 있는지 생각해 보자.
  - 입력 및 출력 예시
	```
	년도를 입력하세요.
	> 2017
	월을 입력하세요.
	> 6

	2017년 6월
	일 월 화 수 목 금 토
	1  2  3
	4  5  6  7  8  9 10
	11 12 13 14 15 16 17
	18 19 20 21 22 23 24
	25 26 27 28 29 30

	년도를 입력하세요.
	> -1
	Bye  
	```
  - 힌트 및 검색 키워드
    - 어떤 방식으로 구현해야 할 지 생각이 필요하다.
    - 날짜 계산 알고리즘을 공부해서 이해하고 구현한다.
    - 최대한 검색을 하지 말고 직접 구현해 보도록 하자.
    - 검색 힌트: 그레고리력, 달력 알고리즘
  - 완성링크 : https://github.com/honux77/codesquad-java-calendar/tree/0.1

## 8) 일정 등록/ 검색 기능구현
## 9) 클래스로 구현
## 10) 저장 기능 추가하기
  


# 학습하다 걸려넘어진부분

## static public 키워드
- 