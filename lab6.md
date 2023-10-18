# Git command
1. Version Control
- 소프트웨어 개발이나 다른 문서 작업에는 *버전 컨트롤 시스템* 이 중요 
```sh
1. local
2. centralized
3. distributed > git의 방식 # 각각의 로컬 컴퓨터가 중앙 컴퓨터의 사본을 모두 갖고 있음
```

2. Git config
```sh
system level: --system option. 시스템의 모든 uses, repositories에 영향
global level: --global option. 현재 유저의 repositories에 영향
local level:--local option. 현재의 repositoriy에만 
```

```sh
$ git init #initializng repository in an existing directory
$ git status # checking repository status
$ git add # Adding a new file to be staged
$ git add [file_name] 
$ nano words.txt
$ git rm -cached [file_name] # Unstaging a file
$ nano .gitignore # Ignoring a file
$ git commit -m "commit message" # Commit
$ git branch # Change branch name
```


