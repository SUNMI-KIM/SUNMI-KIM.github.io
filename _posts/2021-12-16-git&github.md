---
layout: post
title:  "git&github"
date:   2021-12-26 01:30:36 +9000
categories: git github
---
# Git
버전 관리의 알파이자 오메가

여러 사람이 한 번에 코드를 관리하려면? -> 분산버전관리 시스템을 이용!

`$ git init`
현재 작업중인 디렉토리를 git 저장소로 지정
`git <명령어>를 통해 git을 관리 

# git commit

`$ git status`
위 명령어를 통해 현재 깃 상태 확인

`$ git add example.py`
example.py를 생성 혹은 수정하고, 이를 Commit에 반영하고 싶은 경우

`$ git commit -m "commit message"`
변경사항이 반영된 new commit 생성

# git Branch

`$ git branch <branch_name>`
위 명령어를 통해 branch 생성

`$ git checkout <branch_name>`
위 명령어를 통해 현재 작업중인 branch를 전환

`$ git merge <branch_name>`
현재 작업중인 branch를 원하는 branch에 병합

`$ git branch -d <branch_name>`
위 명령어를 통해 branch 삭제

# Github
#### 전 세계 사람들과 버전관리?

### git의 로컬 저장소에서 할 수 있는 일들을 알아보았다.

## 다른 사람과 협업하게 해주는 것 "Github"

local 저장소를 넘어 remote 저장소로!
원격 저장소 중 대표적인 Github