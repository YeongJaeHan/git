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
//git hub하면서 로그인 에러 같은게 계속 나면 안에서 꼬인거
   git config --system --unset credential.helper
   위에 일종의 초기화 하는 거
   push할라하면 로그인하라고 하는데 로그인 하면 된다. 

// 모두의 딥러닝
https://github.com/gilbutTbook/080228
www.gilbut.co.kr

// 딥러닝 부트캠프 with 케라스
https://github.com/gilbutITbook/006959
