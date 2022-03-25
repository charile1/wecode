`$ git clone (remote repository url)`
터미널 내에서 git clone (내 repository 주소)을 통해 remote repository안에 있는 파일을 내 local repository로 가져오는 것.

`$ git status`
git status를 입력하면 현재 작업중인 프로젝트의 staging area, untracked file의 목록을 주고 add, restore할 수 있는 명령어를 보여준다.

`$ git restore (파일명)`
commit 되지 않은 local repository내에 있는 파일의 변경사항을 취소할 수 있다.

`$git add (파일명)`
staging area에 변경사항이 있는 파일을 staged 되도록 추가하는 명령

`$ git commit (파일명)`
staging area에 있는 파일을 내 local repository로 옮기는 명령어

`$ git reset (파일명)`
commit된 파일의 commit을 취소하는 명령어

`$ git log`
해당 repository의 commit history를 보여주는 명령어

`$ git (short name) (branch name)`
페어의 작업 내용을 내 local repository로 가져오는 명령어
*변경사항은 자동 병합

`$ git push (파일명)`
내 local repository에 commit된 파일을 내 remote repository로 옮겨주는 명령어

`*$ git init`
해당 디렉토리를 local repository로 만들고 .git 이라는 하위 디렉토리를 만든다.

*새로운 remote repository의 기준이 될 디렉토리
remote repository는 github에서 만들 수 있다.

`$ git remote add (remote name) (remote url)`
새로운 remote repository를 추가하는 명령어

init 명령어를 통해 local repository를 설정하고 remote 명령어를 통해 remote repository와 연결해줄 수 있다.

협업하는 사람의 remote repository에서 pull해오거나
push할 때도 사용
remote name은 재량에 따라 변경

`$ git remote -v`
현재 적용된 remote repository의 단축이름과 url을 보여주는 명령어ㅎ