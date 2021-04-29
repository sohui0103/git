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
- 사용자의 데이터베이스가 많이 포함된 파일은 staging area에 올리지 않음

git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/sohui0103/git.git
git push -u origin main