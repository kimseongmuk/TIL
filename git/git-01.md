git 01

$ git init
$ touch README.md
$ git add README.md
$ git config --global user.name '내이름'
$ git config --global user.email 'github에서@쓸메일주소'
$ cat ~/.gitconfig  # => 입력한 대로 잘 나오는지 확인!
$ git commit -m 'first commit'

NEVER

    ~ 에서 $ git init 진행
    리포 안에 리포 만들기
    $ git init 입력 전 확인할 점
        ~ 인지
        (master) 떠 있는지

초기화 시점에 1회 입력

$ git init 

작업하며 계속 입력

$ git add <filename>
$ git commit -m 'MESSAGE'

모니터링 명령어

$ git status  # 현재 상황
$ git log     # commit 로그 

원격 저장소(remote repo) 등록하기

$ git remote add origin <URL>

원격 저장소에 PUSH 하기

$ git push origin master


sdwoeiwoiepqweiowelwk;qkeqw;
wqpowpeoldklsw[ep]


9607be9 (HEAD -> master) cli .md 생성 및 git 내용 추가
e6d53c2 (origin/master) first commit
( origin 까지만 원격저장소에 올라갔다는 알림)