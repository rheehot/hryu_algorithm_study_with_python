# hryu_algorithm_study_with_python


#### hryu_algorithm_study c++로 문제 해결 -> 이제 파이썬으로 해결
- 계획대로 해보자

<details>
<summary>hryu_algorithm_study_with_python로 문제 해결</summary>
<div markdown="1">

#### 노션주소 https://www.notion.so/how-to-algorithm_study-hryu-dc135bded1b44b098c7302cd63a3295e

##### 이코테 2회차 마무리하면 두개 먼저 해결
0. [코드업](https://www.codeup.kr/)

1. [삼성 A형 기출 문제](https://www.acmicpc.net/workbook/view/2771)

2. [프로그래머스](https://programmers.co.kr/learn/challenges)

1번 마무리 하면 아래 두개 + 프로그래머스

3. [solved.ac](https://solved.ac/problems/level/11)

4. [삼성 sw 역량 테스트 기출 문제](https://www.acmicpc.net/workbook/view/1152)

5. [프로그래머스](https://programmers.co.kr/learn/challenges)

<details>
<summary>daily solution commit</summary>
<div markdown="1">



## 0310

- 정렬

  - part2
    - 예제
    - 위에서아래로
    - 성적이낮은순서대로
    - 두배열의원소교체

  - part3
    - 국영수
    - 카드정렬하기


## 0311

- 정렬
  - part3
    - 안테나
    - 실패율  
- 이진탐색
  - part2
    -  예제
    - 부품찾기
    - 떡볶이만들기
- dp
  - part2
    - 예제
    - 1로만들기
    
## 0315

- dp
  - part3
    - 정수삼각형
    - 퇴사

## 0316

- dp
  - part3
    - 금광
    - 병사배치하기

## 0317

- 그리디
  - part2
    - 1로만들기

## 0318

- 그리디
  - part3
    - 곱하기혹은더하기
    - 만들수없는금액
    - 모험가길드
    - 문자열뒤집기
    - 볼링공고르기

## 0319

- 그리디
  - part3
    - 무지먹방라이브(나중에 다시 => 넘어려움)

- 구현
  - part2
    - 예제
    - 게임개발(잘 못함 turn left )
    - 왕실의나이트
  - part3
    - 문자열압축
    - 럭키스트레이트
  
- dfs_bfs

  - part2

    - 예제_종료조건있는재귀
    - 예제_팩토리얼
    - 예제_인접리스트
    - 예제_dfs (로직을 외우자)
    - 예제_bfs (로직을 외우자)
    - 음료수얼려먹기
    - 미로탈출
  
## 0322
- dfs_bfs
    - part3
        - 연구소
    
## 0323
- dfs_bfs   => bfsdfs 구현 부분 적응 잘 안됨 => 문제 마니 풀어보기 + 연습 필요
    - part3
        - 연산자끼워넣기
        - 특정거리의도시찾기
- 코드업
    - 파이썬기초100
      - 6000 ~ 6008 입출력 해결
- 프로그래머스
    - 해시
      - 완주하지못한선수(L1)

## 0324

- 코드업
    - 파이썬기초100
      - 6009 ~ 6016 
- dfs_bfs
    - part3
      - 감시피하기(푸는중)
- 프로그래머스
    - 해시
        - 완주하지못한선수
        - 전화번호목록
        - 위장
        - 베스트앨범(푸는중)



## 0325

- 코드업
    - 파이썬기초100
        - 6017 ~ 6024
- 프로그래머스
    - 해시
        - 베스트앨범

## 0326

- 프로그래머스
    - 힙
        - 더맵게
        - 디스크컨트롤러 (푸는중)
        - 이중우선순위큐
    - 스택큐
        - 기능개발
        - 주식가격
        - 다리지나는트럭
    
## 0327

- 프로그래머스
    - 스택큐
        - 프린터
    - 정렬
        - k번째수
        - 가장큰수
        - H-INDEX (푸는중)
    - 완전탐색
        - 모의고사

## 0327

- 프로그래머스
    - 완전탐색
        - 소수찾기 (다시, itertools 순열 조합 익히자)

        - 카펫

## 0330

- 코드업
    - 파이썬기초100
        - 6025 ~ 6031

## 0331

- 프로그래머스
    - 그리디
        - 체육복
        - 조이스틱(미해결)
        - 큰수만들기
        - 구명보트
        - 단속카메라(거의해결 풀이2개마무리)

## 0401

- 프로그래머스

  - 그리디
    - 단속카메라 

  - dp
    - 정수삼각형 

</div>
</details>    


## 이코테  part 2&3

| part 2&3 이코테    | 그리디                                                       | 구현                                           | DFS/BFS                                               | 정렬                                        |
| ----------- | ------------------------------------------------------------ | ---------------------------------------------- | ----------------------------------------------------- | ------------------------------------------- |
| 리뷰필      | 모험가길드(논리정립&그대로구현)                              | 왕실의나이트, 예제(문자열재정렬,시각,상하좌우) | 예제(dfs,bfs,종료조건재귀)음료수얼려먹기,미로탈출, 특정거리의 도시찾기 | 두배열의원소교체,국영수,카드정렬하기,안테나 |
| 어려운 문제 | 무지먹방라이브(그냥어려움), 만들수없는금액(아이디어어려움),볼링공고르기(조건확인및 논리&단순화) | 게임개발(잘 못함), 문자열압축(어려움)          | 미로탈출,연구소(함수여러개), 연산자끼워넣기(백트래킹),감시피하기(연구소랑 비슷,구현능력딸림) | 실패율                                      |
|             | 이진탐색                                                     | DP                                             | 최단경로                                              | DP기타 그래프 이론                          |
| 리뷰필      | 부품찾기,떡볶이만들기                                        | 1로만들기, 정수삼각형, 금광                    |                                                       |                                             |
| 어려운 문제 |                                                              | 퇴사, 병사배치하기                             |                                                       |                                             |

## 코드업

|        | 파이썬100기초  |
| ------ | -------------- |
| 리뷰필 | 6019 6024 6030 6031     |
| 어려운 | 6020 6021 6022 6027 6028 6029 |

## 프로그래머스
못푼 : 디스크컨트롤러, 조이스틱, 섬연결하기(크루스칼 공부하고 풀기), N으로표현(나중에) 네이놈!!

|        | 해시                                                         | 힙                                              | 스택큐                                                       |
| ------ | ------------------------------------------------------------ | ----------------------------------------------- | ------------------------------------------------------------ |
| 풀어본 | [L1]완주하지못한선수(ZIP,SET)<br>[L2]전화번호목록<br>[L2]위장(dic or 여러방법)<br> | [L2]더맵게<br>                                  | [L2]다리를지나는트럭<br>[L2]주식가격<br>[L2]기능개발(문자열처리!)<br> |
| 어려운 | [L3]베스트앨범                                               | [L3]이중우선순위큐<br>[L3el디크스컨트롤러(못품) | [L2]프린터                                                   |

  

|        | 정렬                                              | 완전탐색 | 탐욕법 |
| ------ | ------------------------------------------------- | -------- | ------ |
| 풀어본 | [L1]k번째수<br>[L2]가장큰수<br>[L2]H-인데스(두잇) | [L1]모의고사<br>[L2]카펫 | [L1]체육복<br>[L2]구명보트(커서이용) |
| 어려운 |                                                   | [L2]소수찾기(itertools익히기) | [L2]조이스틱(논리, 구현력)<br>[L2]큰수만들기(스택활용)<BR>[L3] 단속카메라 |

  



|        | DP                    | DFS/BFS | 이분탐색 | 그래프 |
| ------ | --------------------- | ------- | -------- | ------ |
| 풀어본 | [L3]정수삼각형(갸꿀~) |         |          |        |
| 어려운 |                       |         |          |        |

  

