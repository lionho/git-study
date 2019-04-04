# Git 내용 정리

## Git이란?

- 버전(형상)관리도구, DVCS(분산관리시스템)
- git과 github는 다름, github는 hosting 사이트를 의미


## Git 사용하는 이유는?

- 협업할 때 사용
- 이전버전으로 되돌아 갈 수 있음
- 이력관리

commit을 관리해주는 시스템으로 언제든지 commit한 지점으로 되돌아 갈 수 있다. 한번 commit을 하면 로컬 저장소에 안전하게 저장이 된다.

내 컴퓨터의 .git 폴더 생성

## Git 명령어

- git init : 현재 디렉토리에 git 저장소를 생성
- git clone : 원격 저장소 로컬에 복제
- git add : 스테이지 영역에 파일 올림
- git commit : 스테이지 영역에 올라가 있는 파일 커밋.
- git push : 원격 저장소로 보냄
- git pull : fetch + merge
- git status : 현재 깃 상태를 확인
- git branch 브랜치명 : 브랜치 생성
- git branch -d 브랜치명 : 브랜치 삭제
- git checkout 브랜치명 : 해당 브랜치로 HEAD를 이동하고, HEAD의 내용을 워킹디렉토리(워킹트리)에 반영
- (dev) git rebase master : 브랜치의 내용을 떼어내어 master 브랜치에 붙이는 것
- (master) git merge dev : master 브랜치에서 dev 브랜치 커밋을 머지. 최종 결과는 master 브랜치가 되고, dev는 의미가 없어짐

