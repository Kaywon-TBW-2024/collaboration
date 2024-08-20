#Quick Start

relay.md 를 열어 공동 집필하세요.

#공동 글쓰기

1. `git branch`로 현재 내가 있는 branch가 main 인걸 확인하기 (아니면 checkout 해서 main으로)
2. 리모트를 fetch 하고 merge 할것 (`git fetch` / `git merge origin/main`)
3. 자기 branch 만들기 `git branch branchName`
4. 자기 branch 로 이동checkout `git checkout branchName`
5. relay.md를 열어 내용 추가하기
6. `git add .` / `git commit -m “commit message”`
7. 다시한번 리모트를 fetch & merge (혹시 바뀐 내용이 있을까봐) (`git fetch` / `git merge origin/main`)
8. 내 branch를 push (`git push origin 내브랜치이름`)
- 다음에 작업할때는 자기 브랜치가 만들어진 상태일것이다.
- 그때는 자기브랜치로 checkout 에서 (`git fetch` / `git merge origin/main`) 하고 시작하고 push 하기전에 또 한다.

#머징 하기

머징은 앞 사람부터 차례로 진행한다. 또는 하루가 끝날때 한명이 하게된다. 

1. branch를 main으로 바꾼다. `git branch main`
2. 이상적으로는 가장 마지막으로 바뀐 branch 의 commit을 보고 그것만 merge 한다.
    1. `git merge branchName`
3. 어떻게 하면 잘 merge할지 찾아본다.

#다시 글쓰기

1. branch main에서 `git pull origin` 하여 main에 최종 업데이트된 코드를 가져온다.
2. 작업하는 branch로 이동한다. git checkout branchName
3. main에 업데이트된 코드를 내 브랜치와 머지한다. git merge main (branchName)
4. 내 브랜치에서 다시 이어 글쓰기를 시작한다. 
