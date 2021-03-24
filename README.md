# Markdown Practice

## learning GIT

Git is version control

## learning github

```
eeshan.jindal@LAPTOP-M9MJ6904 MINGW64 ~/eeshan_pyth/markdown-pratice (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

eeshan.jindal@LAPTOP-M9MJ6904 MINGW64 ~/eeshan_pyth/markdown-pratice (master)
$ git add README.md

eeshan.jindal@LAPTOP-M9MJ6904 MINGW64 ~/eeshan_pyth/markdown-pratice (master)
$ git log
fatal: your current branch 'master' does not have any commits yet

eeshan.jindal@LAPTOP-M9MJ6904 MINGW64 ~/eeshan_pyth/markdown-pratice (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


eeshan.jindal@LAPTOP-M9MJ6904 MINGW64 ~/eeshan_pyth/markdown-pratice (master)
$ git comiit -m "First Commit"
git: 'comiit' is not a git command. See 'git --help'.

The most similar command is
        commit

eeshan.jindal@LAPTOP-M9MJ6904 MINGW64 ~/eeshan_pyth/markdown-pratice (master)
$ ^C

eeshan.jindal@LAPTOP-M9MJ6904 MINGW64 ~/eeshan_pyth/markdown-pratice (master)
$ git commit -m "First Commit"
[master (root-commit) 61df1f8] First Commit
 Committer: Eeshan Jindal <Eeshan.Jindal@>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 5 insertions(+)
 create mode 100644 README.md

eeshan.jindal@LAPTOP-M9MJ6904 MINGW64 ~/eeshan_pyth/markdown-pratice (master)
$ git log
commit 61df1f84d46375f9e2333f2b757fd2e9407e099e (HEAD -> master)
Author: Eeshan Jindal <Eeshan.Jindal@>
Date:   Wed Mar 24 23:12:43 2021 +0530

    First Commit

eeshan.jindal@LAPTOP-M9MJ6904 MINGW64 ~/eeshan_pyth/markdown-pratice (master)
$ ^C

eeshan.jindal@LAPTOP-M9MJ6904 MINGW64 ~/eeshan_pyth/markdown-pratice (master)
$ ^C

eeshan.jindal@LAPTOP-M9MJ6904 MINGW64 ~/eeshan_pyth/markdown-pratice (master)
$

```
