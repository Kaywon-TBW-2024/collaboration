# Quick Start

relay.md 를 열어 공동 집필하세요.

## 시작하기

1. 상단 초록색 `<> CODE` 버튼을 눌러 HTTPS 의 URL을 복사합니다.

2. 터미널 창에서 `pwd`를 사용해 본인 터미널이 현재 작동하고 있는 위치를 확인합니다.

3. `ls`를 눌러 파일리스트를 확인하고 

4. `cd Desktop` 명령어를 통해 Desktop 폴더로 이동합니다.

5. Desktop 폴더에서 `git clone https://github.com/Kaywon-TBW-2024/collaboration.git` 를 사용해 repository를 다운받습니다.

6. vscode 에서 open Folder를 사용해 해당 폴더를 엽니다. 

7. [relay.md](https://github.com/Kaywon-TBW-2024/collaboration/blob/main/relay.md) 를 열어 ※ 한 문장 이상을 추가합니다 ※ (중요)

8. `git add .` 수정된 모든사항을 staging area에 업데이트 합니다.

9. `git commit -m "학번, 이름"` 학번 이름을 적어 커밋메시지를 남기세요.

10. `git push` 로 repository에 업로드합니다. 

## 부록(브랜치 만들기)

1. 상단 초록색 `<> CODE` 버튼을 눌러 HTTPS 의 URL을 복사합니다.

2. 터미널 창에서 `pwd`를 사용해 본인 터미널이 현재 작동하고 있는 위치를 확인합니다.

3. `ls`를 눌러 파일리스트를 확인하고 

4. `cd Desktop` 명령어를 통해 Desktop 폴더로 이동합니다.

5. Desktop 폴더에서 `git clone https://github.com/Kaywon-TBW-2024/collaboration.git` 를 사용해 repository를 다운받습니다.

6. vscode 에서 open Folder를 사용해 해당 폴더를 엽니다. 

7. ※한 문장 이상을 추가합니다※

8. `git branch` : 현재 branch main 인지 확인

9. 브랜치 만들기

    a. `git branch branchName` : 자기 branch 만들기

    b. `git checkout branchName` : 자기 branch 로 이동

10. [relay.md](https://github.com/Kaywon-TBW-2024/collaboration/blob/main/relay.md) 를 열어 내용 추가하기 

11. 중간에 변경된 내용 있는지 체크

    a. (`git fetch` / `git merge origin/main`)
    or `git pull origin <branch-name>` 

12. github repo 에 올리기

    a. `git add .`
    
    b. `git commit -m “학번 이름”`

    c. `git push`