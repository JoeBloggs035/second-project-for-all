# Практическая работа №1. «Делимся проектом с миром»  

---

*JoeBloggs035@Win MINGW64 ~/dev $* __mkdir second-project__  

---

*JoeBloggs035@Win MINGW64 ~/dev $* __cd second-project__  

---

*JoeBloggs035@Win MINGW64 ~/dev/second-project $* __git init__  
Initialized empty Git repository in C:/Users/Бусинка/dev/second-project/.git/  

---

*JoeBloggs035@Win MINGW64 ~/dev/second-project (master) $* __touch readme.md__  

---

*JoeBloggs035@Win MINGW64 ~/dev/second-project (master) $* __git status__  
On branch master  
  
No commits yet  
  
Untracked files:  
  (use "git add <file>..." to include in what will be committed)  
        readme.md  
  
nothing added to commit but untracked files present (use "git add" to track)  

---
  
*JoeBloggs035@Win MINGW64 ~/dev/second-project (master) $* __git add --all__  

---
  
*JoeBloggs035@Win MINGW64 ~/dev/second-project (master) $* __git status__  
  
On branch master  
  
No commits yet  
  
Changes to be committed:  
  (use "git rm --cached <file>..." to unstage)  
        new file:   readme.md  

---  

*JoeBloggs035@Win MINGW64 ~/dev/second-project (master) $* __git branch -m main__  

---
  
*JoeBloggs035@Win MINGW64 ~/dev/second-project (main) $* __git commit -m 'создал файл readme.md'__  
[main (root-commit) 2b0d35c] создал файл readme.md  
 1 file changed, 0 insertions(+), 0 deletions(-)  
 create mode 100644 readme.md  

---
  
*JoeBloggs035@Win MINGW64 ~/dev/second-project (main) $* __git log__  
commit 2b0d35ccf02bc4181d536f0f705c910df18a8b64 (HEAD -> main)  
Author: JoeBloggs <JosephBloggs035@gmail.com>  
Date:   Wed Mar 6 11:07:51 2024 +0300  
  
    создал файл readme.md  

---
  
*JoeBloggs035@Win MINGW64 ~/dev/second-project (main) $* __git remote add origin2 git@github.com:JoeBloggs035/second-project-for-all.git__  

---
  
*JoeBloggs035@Win MINGW64 ~/dev/second-project (main) $* __git remote -v__  
origin2 git@github.com:JoeBloggs035/second-project-for-all.git (fetch)  
origin2 git@github.com:JoeBloggs035/second-project-for-all.git (push)  

---
  
*JoeBloggs035@Win MINGW64 ~/dev/second-project (main) $* __git status__  
On branch main  
nothing to commit, working tree clean  

---
  
*JoeBloggs035@Win MINGW64 ~/dev/second-project (main) $* __git push -u origin2 main__  
Enumerating objects: 3, done.  
Counting objects: 100% (3/3), done.  
Writing objects: 100% (3/3), 243 bytes | 243.00 KiB/s, done.  
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)  
To github.com:JoeBloggs035/second-project-for-all.git  
 * [new branch]      main -> main  
branch 'main' set up to track 'origin2/main'.  

---
  
*JoeBloggs035@Win MINGW64 ~/dev/second-project (main) $*