# GIt_Practice


1. git rm -r --cached .idea
2. git checkout -b dev
3. git add .
4. git commit -m "dev branch 생성"
5. git push origin dev


[개인]
1. git pull origin dev
2. git checkout -b 이름
3. 해당 브랜치에 본인 디렉토리 생성
4. 본인 디렉토리에서 코드 작성
5. git add, commit, push
   4-1. git add .
   4-2. git commit -m "커밋 내용"
   4-3. git push origin 본인 브랜치 이름
6. github에서 Compare & Pull Request 수행
   5.1 본인 PR이 리포지토리 메인화면에서 안보여요 ㅠㅠ
      1. 상단 바에서 Pull requests 클릭
      2. New pull request 클릭
      3. base:dev, compare:본인 브랜치 로 설정 후 Create pull request
      4. 내용 비교 및 title, description 알맞게 작성후 Create pull request 클릭
7. 1 -> 4 -> 5 -> 6번 반복

[주의사항]
만약 Merge branch 'dev' of ~~~ 발생시, Ctrl + C 입력
