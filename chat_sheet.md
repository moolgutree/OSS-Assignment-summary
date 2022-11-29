## 설정
```
$ git config --global user.name "@@@"   
    커밋 유저네임 설정
$ git config --global user.email "@@@.@@"   
    커밋 이메일 설정
```
## 준비
```
$ git init @@@   
    .git이 있는 폴더 생성
$ git clone [url]   
    원격저장소(url)에 있는 것을 복사함
```
## 스테이지
```
$ git status    
    현재 작업 상태를 출력
$ git add    
    WD에 있는 내용을 SA로 이동
$ git reset    
    commit 되돌리기
$ git diff   
    SA와 WD 상태 차이를 알려줌
$ git diff --staged   
    commit된 파일과 SA 상태 차이를 알려줌
$ git commit -m "@@"   
    WD에 있는 파일을 commit하고 메시지를 @@라고 함
```
## 브랜치
```
$ git branch   
    branch 목록 확인
$ git branch @@   
    @@ 라는 브랜치
$ git checkout @@
$ git merge @@
$ git log
```
## 검사
## 삭제
## 업데이트
## 기록 변경
## 임시 저장
