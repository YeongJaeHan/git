<local->git>
1. 연결할 local폴더 만든다
2. 열결할 git repository만든다(처음 연결 할 때 비어있어야 한다)
3. local폴더에서 마우스 오른쪽 눌려서 Git Bash Here
   code . 명령어 친다
3-1. vs코드에서 폴더 연다
4. terminal에서 git init 명령어 입력
   local폴더에서 .git 폴더 생긴거 확인
4. vs코드에서 공유버튼 같이 생긴거 눌림
5. +버튼 눌려서 연결할 local폴더 눌려서 chages에 올릴 파일들 보이게 한다
5-1. git remote origin [ git address ]
6. changes상태인것들 stages에 올린다.(chages옆에 +버튼)
6-1. git add .
7. 맨위에 체크버튼 눌려서 commit한다.
7-1. git commit -m [ commit message ]
8. 맨밑에 순환버튼 같이 생긴거 눌려서 push
8-1. git push origin master
