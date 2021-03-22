# UiPath를 이용한 RPA 기능별 로직 Portfolio
## 목적
<p> 1. RPA 개발자의 기본 소양 배양.</p>
<p> 2. 기본적인 UiPath의 기능을 실습하고 해당 기능에 대한 이해도를 높인다.</p>
<p> 3. 기능 학습을 통해 문제 해결의 로직 설계 능력을 배양한다.</p>
<hr contenteditable="false" data-ke-type="horizontalRule" data-ke-style="style5" />

## 개발 환경
<p>Uipath Community Cloud Edition</p>
<p>Windows 10</p>
<hr contenteditable="false" data-ke-type="horizontalRule" data-ke-style="style5" /
<hr contenteditable="false" data-ke-type="horizontalRule" data-ke-style="style5" />

## 로직 별 사용한 주요 기능
<p> 1. 레코딩 데이터 스크래핑 중심 로직: Recoding, GetText, Excel Application Scope, DataScraping</p>
<p> 2. 엑셀 데이터 추출 및 가공 작업: for each row, if문, build data table 등을 이용한 엑셀 데이터를 추출 후 가공 및 엑셀 파일에 쓰는 작업</p>
<p> 3. 셀렉터: 셀렉터를 이용한 UI 변경시 오류 Tracking</p>
<p> 4. 데이터 가공: Text(Replace, Split, StartWith, trim), Date, Array, List, Dictionary등을 이용한 추출한 데이터 가공</p>
<p> 5. try catch문과 retry scope를 이용한 예외처리</p>
<p> 6. InvokeWorkflow를 이용한 확장성 개념 실습</p>
<hr contenteditable="false" data-ke-type="horizontalRule" data-ke-style="style5" />

## 로직 내역(자세 내역은 파일 참조)

# <p>1. 레코딩 데이터 스크래핑 중심 로직: Recoding, GetText, Excel Application Scope, DataScraping</p>
![image](https://user-images.githubusercontent.com/73808497/111138737-a3e8ec00-85c3-11eb-867a-2a7e96fccd1f.png)

# <p> 2. 엑셀 데이터 추출 및 가공 작업: for each row, if문, build data table 등을 이용한 엑셀 데이터를 추출 후 가공 및 엑셀 파일에 쓰는 작업</p>
![image](https://user-images.githubusercontent.com/73808497/111139401-6c2e7400-85c4-11eb-913d-3b59885bfd04.png)

# <p> 3. 셀렉터: 셀렉터를 이용한 UI 변경시 오류 Tracking</p>
![image](https://user-images.githubusercontent.com/73808497/111139887-055d8a80-85c5-11eb-9021-4cb381e9d53a.png)

# <p> 4. 데이터 가공: Text(Replace, Split, StartWith, trim), Date, Array, List, Dictionary등을 이용한 추출한 데이터 가공</p>
![image](https://user-images.githubusercontent.com/73808497/111140313-8c126780-85c5-11eb-84a5-519b033bab04.png)

# <p> 5. try catch문과 retry scope를 이용한 예외처리</p>
![image](https://user-images.githubusercontent.com/73808497/111140648-f1665880-85c5-11eb-8623-0c5ed76102ba.png)

# <p> 6. InvokeWorkflow를 이용한 확장성 개념 실습</p>
![image](https://user-images.githubusercontent.com/73808497/111141113-7cdfe980-85c6-11eb-91b2-838f45475563.png)
![image](https://user-images.githubusercontent.com/73808497/111141145-86695180-85c6-11eb-9361-1345cad81d73.png)

## RPA(UiPath) 이론 정리

학습 블로그 개설하여 TIL(Today I Learned)형식으로 정리
(https://laundarywarrior.tistory.com/category/RPA?page=1) 참조 요망

![image](https://user-images.githubusercontent.com/73808497/111141314-bdd7fe00-85c6-11eb-939b-39b97ea4b2e2.png)

## RPA(UiPath) 향후 학습 목표
1. Orchestrator를 이용한 배포 및 robot 배치
2. VB뿐만이 아닌 C#을 이용한 프로세스 로직 설계
3. uiArd 자격증 취득을 통해 RPA 전문가로의 성장

