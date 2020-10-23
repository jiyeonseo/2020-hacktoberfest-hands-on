# 2020-hacktoberfest-hands-on
👾  2020 Hacktoberfest Seoul 핸즈온 세션을 위한 리파지토리 

## 이벤트 정보
https://event-us.kr/hacktoberfestkorea/event/23432

## 준비사항 
- Github 계정
- [Git 설치](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)  

## 오늘의 핸즈온

### 1단계 : 이슈 만들기
![Issues_·_jiyeonseo_2020-hacktoberfest-hands-on](https://user-images.githubusercontent.com/2231510/97009712-671e4900-157f-11eb-8c5f-aa269d161b43.png)

![New_Issue_·_jiyeonseo_2020-hacktoberfest-hands-on](https://user-images.githubusercontent.com/2231510/97023689-d3ee0f00-1590-11eb-9df1-2c8c54671a45.png)

- 핵토버페스트 핸즈온 이슈를 만들어봅니다.

### 2단계 : 포크뜨기 

![jiyeonseo_2020-hacktoberfest-hands-on__👾_2020_Hacktoberfest_Seoul_핸즈온_세션을_위한_리파지토리_https___event-us_kr_hacktoberfestkorea_event_23432](https://user-images.githubusercontent.com/2231510/96999622-6af69f00-1570-11eb-8f95-fb1ad4a7399f.png)
- 리파지토리 우상단에 Fork 버튼을 눌러 개인 repository로 포크를 떠봅시다! 
### 3단계 : 로컬에 clone 받기 
- Client 사용하기
  - [Github Desktop](https://desktop.github.com/)
  - [Sourcetree](https://www.sourcetreeapp.com/)
  - [Fork](https://git-fork.com/)
- 커맨드라인 이용하기 
  - Git command
  ```sh
  $ git clone {repo url || ssh }
  ```
  - Github CLI 
  ```sh
  $ gh repo clone {org/repo}
  ```


### 4단계 : 파일 수정 & commit & push 
- 파일 수정 후 파일 추가 
  - 커맨드 라인으로 추가하고 commit 하기 
  ```sh
  $ git add . # 혹은 파일 경로
  $ git commit -m '커밋 메세지' 
  ```

- push 하기 
```sh
$ git push -u origin main # remote와 branch 명에 따라서 
```  

### 5단계 : 깃헙으로 돌아와서 PR 날리기  
- 다시 [리파지토리](https://github.com/jiyeonseo/2020-hacktoberfest-hands-on) 로 돌아오면 상단에 바로 PR 날릴수 있는 버튼이 생성되어있습니다. 

![jiyeonseo_2020-hacktoberfest-hands-on__👾_2020_Hacktoberfest_Seoul_핸즈온_세션을_위한_리파지토리](https://user-images.githubusercontent.com/2231510/97012078-7226a880-1582-11eb-9967-64406a8bdf42.png)


![Comparing_main___feature_github_docs_·_jiyeonseo_2020-hacktoberfest-hands-on](https://user-images.githubusercontent.com/2231510/97012696-190b4480-1583-11eb-9f44-065f635e9676.png)

- base가 jiyeonseo/2020-hacktoberfest-hands-on 인지 확인합니다 
- reviewer를 @jiyeonseo 를 지정해줍니다! 
