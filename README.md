# AWS Shell Script Project

[root@ip-12-0-1-77 ~]# mkdir Newgit
[root@ip-12-0-1-77 ~]# ls
Newgit  devops-workshop
[root@ip-12-0-1-77 ~]# cs Newgit
-bash: cs: command not found
[root@ip-12-0-1-77 ~]# cd Newgit
[root@ip-12-0-1-77 Newgit]# echo "# Power-BI-Projects" >> README.md
[root@ip-12-0-1-77 Newgit]# ls
README.md
[root@ip-12-0-1-77 Newgit]# cd README.md
-bash: cd: README.md: Not a directory
[root@ip-12-0-1-77 Newgit]# cat README.md
# Power-BI-Projects
[root@ip-12-0-1-77 Newgit]# ls -a
.  ..  README.md
[root@ip-12-0-1-77 Newgit]# git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../.bash_history
        ../.bash_logout
        ../.bash_profile
        ../.bashrc
        ../.cshrc
        ../.gitconfig
        ../.lesshst
        ../.ssh/
        ../.tcshrc
        ./
        ../devops-workshop/

nothing added to commit but untracked files present (use "git add" to track)
[root@ip-12-0-1-77 Newgit]# git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint:   git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint:   git branch -m <name>
Initialized empty Git repository in /root/Newgit/.git/
[root@ip-12-0-1-77 Newgit]# git add README.md
[root@ip-12-0-1-77 Newgit]# git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

[root@ip-12-0-1-77 Newgit]# git commit -m "first commit"
[master (root-commit) fe9aa23] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
[root@ip-12-0-1-77 Newgit]# ls
README.md
[root@ip-12-0-1-77 Newgit]# ls -a
.  ..  .git  README.md
[root@ip-12-0-1-77 Newgit]# git status
On branch master
nothing to commit, working tree clean
[root@ip-12-0-1-77 Newgit]# git branch -M main
[root@ip-12-0-1-77 Newgit]# git remote -v
[root@ip-12-0-1-77 Newgit]# git remote add origin https://github.com/thilakts212/Power-BI-Projects.git
[root@ip-12-0-1-77 Newgit]# ls
README.md
[root@ip-12-0-1-77 Newgit]# git remote -v
origin  https://github.com/thilakts212/Power-BI-Projects.git (fetch)
origin  https://github.com/thilakts212/Power-BI-Projects.git (push)
[root@ip-12-0-1-77 Newgit]# git push -u origin main
Username for 'https://github.com': thilakts212
Password for 'https://thilakts212@github.com': 
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 234 bytes | 234.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/thilakts212/Power-BI-Projects.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
[root@ip-12-0-1-77 Newgit]#


