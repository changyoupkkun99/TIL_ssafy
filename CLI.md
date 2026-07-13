# 마크다운

> 문서를 체계적으로 관리할 수 있도록 하는 문법

- 순서가 없는 리스트
  1. 순서가 있는 리스트

[링크](https://naver.com)

```python
# 백틱(`)으로 감싸진 영역은 code block이 되어서
print('hello') # 이렇게 그 언어의 문법에 맞춰 하이라이팅
```

![스크린샷]('image.png')

# CLI
> CLI(Command Line Interface): 명령어를 통해 사용자와 컴퓨터가 상호 작용하는 방식
- 왜 CLI를 사용해야 할까?
  - 효율성
  - 정밀한 제어
  - 강력한 자동화
  - 표준 환경

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
> 작업 -> add -> commit