# GIT
> 분산 버전 관리 시스템

- Git의 3가지 영역
  - Wokrjing Directory -> 작업 장소
  - Staging Area -> 중간 점검 장소
  - Repository -> 최종

  - CLI에서 기억해야할 명령어
  - CLI에서 '.' (마침표)의 역할
    - . 현재 디렉토리
    - .. 현재의 상위 디렉토리(부모 폴더)
  - 터미널로 넘어가는 키: Ctrl + `(~)

- 기초 문법
  - touch: 파일생성
  - mkdir: 새 디렉토리 생성 -> make directiry 약자
  - ls: 현재 작업중인 디렉토리 -> 현재 폴데에 뭐가 있는지 확인 가능
  - mv: mv git.md day01/ -> day01폴더로 git.md가 옮겨짐
  - cd: cd day01/ -> 내가 작업하려는 폴더로 이동, Change Directiry 약자
  - code: code day01/git.md -> 파일열기
  - git init: git으로 관리하기
  - git status: git 상태보기
  - git add( CLI.md image.png): git아 추가해줘 CLI.md와 image.png를
  - git commit: git에 commit
  - git log: 메모장 내용 확인
  - 이름설정
    - git config --global user.email "lcy3049@gmail.com"
    - git config --global user.name "changyoupkkk"
  - code ~/.gitconfig: git 메모장 열기
    - insert/a/i: 수정모드
    - esc: 수정모드 나가기
    - :wq -> git 메모장 나가기
  - git commit -m "메시지 내용": git의 commit할게 -m메시지로 "메시지 내용"과 함께
  - git log --oneline: log내용을 간략히 한줄로 확인 가능
  - git log --oneline --graph: 노드와 엣지로 이루어져 있음
  - 
> 작업 -> add -> commit