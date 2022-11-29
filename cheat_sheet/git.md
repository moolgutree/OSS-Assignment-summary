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
    @@ 라는 브랜치로 이동
$ git checkout @@
    @@ 라는 브랜치로 이동
$ git merge @@
    지금 브랜치와 @@브랜치를 head에 병합
$ git log
    현재 사용 중인 저장소의 모든 변경 이력을 출력
```
## 검사
```
$ git log
    현재 사용 중인 저장소의 모든 변경 이력을 출력
$ git show
    지정한 커밋의 정보 확인
$ diff branch @@@ ###
    @@@브랜치와 ###브랜치 비교
```
## 삭제
```
$ git rm @@@
    @@@파일 삭제
$ git mv @@@ ###
    @@@파일을 ### 디렉터리로 이동
```
## 업데이트
```
$ git remote add
    리모트 저장소 삭제
$ git fetch @@@
    원격 저장소@@@ 로부터 소스를 가져옴
$ git merge @@@
    지금 브랜치와 @@@브랜치를 head에 병합
$ git push @@@
    commit된 파일을 원격 저장소에 저장
$ git pull
    원격 저장소에 저장된 파일중 새로운 것들을 복사함
```
## 기록 변경
```
$ git rebase @@@
    @@@브랜치 이전 브랜치의 모든 커밋을 @@@브랜치 이후에 추가함 
$ git reset --hard
    reset 이후에 커밋 내용을 WD, SA 모두 같게 함
```
## 임시 저장
```
$ git stash
    지금 작업중인 내용 임시 저장
$ git stash list
    여러번 할 수 있는 스태시 내역 확인
$ git stash pop
    스태시 복원 및 삭제
$ git stash drop 
    가장 최근 스태시 
```
