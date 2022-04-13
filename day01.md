# 오늘 공부한 내용들!

- git 기초
    - git : 분산 버전 관리 프로그램
    
    - 창 띄우기
    vscode -> ctrl + `


    - 기본 명령어
    mkdir test: test 디렉토리(폴더) 생성
    touch a.txt: a.txt 파일 생성
    ls : 있는 모든 파일 보여줘
    ls -a : 숨긴 파일까지 다 보여줘
    pwd : 내가 있는 경로 위치 알려줌

    cd (change directory)
    cd . : 현재 디렉토리
    cd .. : 상위 디렉토리로 이동

    cd test -> ~/test
    git init -> ~/test(master)


    - 초기 설정
    git config --global user.name "유저명"
    git config --global user.email "깃허브 메일"

    - 설정 확인하기
    git congig --global --list


    - 3가지 공간 
    Working Directory : 기록할 준비 완료 및 수정
    Staging  Area : Commit 날림
    Commits : Commit 실행된 결과 기록

    Working Directory -> Staging Area -> Commits

    git add 
    : working directory -> staging area
    무대 위로 올리기
    ex) git add day01.md : day01.md 올리기!

    git commit
    : staging area -> commits
    변경사항을 기록해줘~
    ex) git commit -m "메시지"

    
    - Local에서!!
    1. 폴더를 저장소로 만든다 (최초 1회)
        git init

    2. 무대 위로 올림 (Staging Area)
        git add a.md

    3. 파일 상태를 확인한다. (제일 중요)
        git status

    4. 변경사항을 기록해 (Commits)
        git commit -m "메시지"

    5. 변경사항 내역 보기
        git log --oneline




- Github
: Git으로 작성된 파일들을 Github(서비스)를 통해 다른 사람들과 함께 코딩 할 수 있음 (협업 가능)

    1. New Repository 만들기
    2. url 복사

    create repository -> https://git~~~


    <Git과 Github 연결하기>
    위의 https://git~~~을 복사 한 후 
    git remote add origin https://git~~ 입력

    - 연결 확인 : git remote -v

    - 오타난 경우 : git remote rm origin

    - Github에 변경사항 백업하기 
    : git push origin master












    
     

    
        
    
    
