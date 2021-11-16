# 2021 BASIC SQL - 코사다마 스터디 가이드

작성자: 이정윤, 정 찬

참고자료: SQL/SB(MySQL)기본부터 파이썬/데이터분석 활용까지! (잔재미코딩), 부스트코드 1-1 SQL 및 관계형 데이터베이스(모원서), SQLite3로 가볍게 배우는 데이터베이스: SQL 기초 실습(최용), [백문이 불여일타] 데이터 분석을 위한 기초/중급/고급 SQL(데이터리안), DATABASE 1&2 - MySQL(Egoing Lee)



## 0. 스터디 지향점

**[Intro-to-Data-Science](https://github.com/Team-COSADAMA/2021-Curriculum/tree/main/Intro-to-Data-Science)** 까지 우리는 주어진 csv, xlsx, json 정도의 파일을 이용했습니다. 하지만

**[Advanced-WebCrawling](https://github.com/Team-COSADAMA/2021-Curriculum/tree/main/Advanced-WebCrawling)** 을 거쳐오면서 데이터의 크기가 무한정 커질 수 있는 상황도 확인했습니다. 이런 대용량의 데이터를 수집, 조작하는 과정을 모든 개별 컴퓨터에서 담당해야할까요? 분명 사람들은 더 좋은 방법을 찾아냈을 겁니다. 그리고 그 방법이 바로 SQL이죠. 

이제 우리는 대용량의, 공유된 데이터를 다루는 방법을 배울 예정입니다. 그것도 오픈 소스로 배포된 MySQL을 활용해서 말이죠!



## 1. 스터디 목표

1. MySQL을 이용해 데이터베이스를 설계할 수 있다.
2. 쿼리를 이용해 데이터를 조작 및 조회할 수 있다.
3. jupyter notebook을 이용해 python 라이브러리를 사용해 조작할 수 있다.



## 2. 스터디 진행 방식

- 매주 토요일 **슬랙** **announcement 채널**에 교안이 업로드 됩니다.
- 교안이 업로드 되면 그 교안으로 일주일 동안 스스로 공부합니다.
- 모르는 질문은 언제든 **슬랙 sql 채널**에 질문해 주시면 됩니다.
- 다음주 토요일 오후 2시까지 해당 주차의 과제를 업로드 해주시면 됩니다.



## 3. 과제 제출 방식

- 과제 제출 시 슬랙 assignment 채널에 아래와 같은 제목으로 .sql, .csv, .zip 파일을 제출해 주세요.
- 과제를 하나라도 제출하지 못한다면 해당 주차는 0점 처리 됩니다..! 대신 난이도가 어렵지 않으니 걱정하지 마세요!

>  [SQL]고다람_1주차 과제.sql





## 4. 스터디 유의사항

- 커리큘럼의 뼈대는 네이버 부스트코스 '**기초 데이터분석을 위한 핵심 SQL**'을 따릅니다. 이외에도 inflearn의 잔재미코딩의 ''**SQL/DB(MySQL) 기본부터 파이썬/데이터분석 활용까지!**', 데이터리안의 '**[백문이불여일타]데이터 분석을 위한 초급/중급/고급  SQL**', 생활코딩의 Egoing Lee가 집필한 '**DataBase 1&2 MySQL**'을 참고했습니다.
- 커리큘럼 환경: Workbench와 Anaconda 가상환경의 jupyter notebook을 이용합니다. colab을 사용할 경우 `(2003, "Can't connect to MySQL server on 'localhost' ([Errno 99] Cannot assign requested address)")` 에러가 발생합니다.



## 5. 커리큘럼 목차

| week | title                                      |
| ---- | ------------------------------------------ |
| 1    | MySQL 다운로드 및 데이터 조작 기초         |
| 2    | 테이블 조작법 - SQl 문법 및 활용           |
| 3    | 실전 데이터 분석 및 문제 풀이 - HackerRank |
| 4    | PyMySQL 익히기                             |

