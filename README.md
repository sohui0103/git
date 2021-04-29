# git
echo "# git" >> README.md
- readme.md 파일을 생성해줘

git init
-.git을 만들어주는 명령어

git add README.md
- git add 파일명
- staging area에 파일명을 저장함
- readme.md를 staging area에 저장한 것임

git add .
- git 폴더에 있는 모든 파일이 staging area에 올라감

git satus
-staging area에 올라간 파일을 확인할 수 있음

git ignore
- https://www.toptal.com/developers/gitignore
- 사용자의 개인정보 / 데이터베이스가 포함된 파일은 staging area에 올리지 않음

git commit -m "주석처럼 달리는 메세지"
- staging area의 파일을 저장하는 명령어

git log
- git의 log 내용들을 볼 수 있는 명령어

git branch "branch 이름"
- 분기점을 만드는 명령어

git branch -M main
- 마스터 branch 이름을 main으로 변경하겠다는 명령어

git checkout
- 이동할 branch 명령어

git remote add
- git 레퍼지토리의 주소를 origin이라는 이름으로 연결하겠다
- origin이 아니라 다른 이름으로 해도됨

git push origin master
- git push 파일이름 브랜치이름
- git에 origin이라는 이름의 레포지터리를 올리겠다
- master라는 이름의 브랜치를 올리겠다

git push -u origin main

