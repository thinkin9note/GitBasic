---

Title : My Summary Git Note

---

[Git Manual](https://heecheolman.tistory.com/55)
[Git Manual](https://sukvvon.tistory.com/43)


```

git init

git config credential.username <github email>
// Each Folder has GitUser
// Windows , Occur Error 제어판/사용자계정/자격증명관리자/  git관련 자격사항 삭제


echo "secret file name.txt" >> .gitignore 
git status



git add .

git add <file Name>

git status

git log 

git log --oneline

git commit -m "Message"

git push <name> <branch>

git clone <URL>

git pull <name> <branch>

git remote add origin <URL>

git remote -v

git push -u origin master


git remote set-url <url>


git config --global user.email "you@example.com"
git config --global user.name "your name"


git branch "branch Name"

git switch "branch Name : master/main"

git checkout // old switch version


git reset --hard <hash id>

git revert <hash.id>


git merge

git rebase  // branch dispear




```
---

## Directory → git init → Repository
* Directory : 폴더, 아무 기능 없음
  * git init : directory를 repository로 만들어줌

    * 실행 시, 현재 경로 뒤에 (master) 표시가 생기고, 해당 폴더에는 .git 이라는 폴더가 생성됨
    * ! 주의 ! repo안에 또 repo를 만들지 말자 (이미 git init한 폴더 안에서 또 git init하지 말자)

---

---
## git commit
$ vi editor

$  입력 : i

$  입력종료 : esc

$  저장없이 종료 : ♒

$  저장없이 강제종료 : :q! 

$  저장하고 종료 :  :wq 

$  아래로 스크로 : j

$   위로스크롤 : k

---









===


	
$ git remote add origin "https://github.com/leechoong/git_test.git"
이 명령어는 원격 저장소의 주소를 로컬 저장소에게 알려주는 것이다.

$ git remote -v
1
$ git remote -v
이 명령어로 현재 로컬저장소가 알고있는 원격 origin 저장소가 무엇인지 확인한다.

현재 원격 저장소는 텅 비어있는 상태이고, 로컬 저장소는 README.md파일이 있다. README.md 파일을 커밋해보자

$ git add .
1
$ git add .
.은 모두 를 뜻한다. 로컬 저장소의 모든 파일을 추가한다.

$ git commit -m "initial commit"
1
$ git commit -m "initial commit"
위에서 추가한 파일들 모두에 “커밋 메세지”와 함께 커밋한다.
명령어를 입력하면

1 file changed, 0 insertions(+), 0 deletions(-)
create mode 100644 README.md
1
2
1 file changed, 0 insertions(+), 0 deletions(-)
create mode 100644 README.md
위와 같은 메세지로 변경될 파일을 확인할 수 있다.

$ git push origin master
1
$ git push origin master
원격 저장소로 push 한다.










