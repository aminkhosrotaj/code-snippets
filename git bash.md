
DELL khosrotaj@DellKhosrotaj MINGW64 /
$ ls
LICENSE.txt        cmd/  git-bash.exe*  proc/         unins000.exe*
ReleaseNotes.html  dev/  git-cmd.exe*   tmp/          unins000.msg
bin/               etc/  mingw64/       unins000.dat  usr/

DELL khosrotaj@DellKhosrotaj MINGW64 /
$ cd e:/

DELL khosrotaj@DellKhosrotaj MINGW64 /e
$ ls
'$RECYCLE.BIN'/   RAPT/                         code-snippets/
 MetriLand/      'System Volume Information'/

DELL khosrotaj@DellKhosrotaj MINGW64 /e
$ cd code-snippets/

DELL khosrotaj@DellKhosrotaj MINGW64 /e/code-snippets (main)
$ s
bash: s: command not found

DELL khosrotaj@DellKhosrotaj MINGW64 /e/code-snippets (main)
$ ls
README.md  test.md

DELL khosrotaj@DellKhosrotaj MINGW64 /e/code-snippets (main)
$ git status s
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

DELL khosrotaj@DellKhosrotaj MINGW64 /e/code-snippets (main)
$ git statuss
git: 'statuss' is not a git command. See 'git --help'.

The most similar command is
        status

DELL khosrotaj@DellKhosrotaj MINGW64 /e/code-snippets (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        test.md

nothing added to commit but untracked files present (use "git add" to track)

DELL khosrotaj@DellKhosrotaj MINGW64 /e/code-snippets (main)
$ git add .

DELL khosrotaj@DellKhosrotaj MINGW64 /e/code-snippets (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   test.md


DELL khosrotaj@DellKhosrotaj MINGW64 /e/code-snippets (main)
$ git commit -m "test push"
[main 8fabe44] test push
 1 file changed, 1 insertion(+)
 create mode 100644 test.md

DELL khosrotaj@DellKhosrotaj MINGW64 /e/code-snippets (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

DELL khosrotaj@DellKhosrotaj MINGW64 /e/code-snippets (main)
$ git push -uf origin main
Enter passphrase for key '/c/Users/DELL khosrotaj/.ssh/id_rsa':
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 361 bytes | 120.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:aminkhosrotaj/code-snippets.git
   41c5db0..8fabe44  main -> main

DELL khosrotaj@DellKhosrotaj MINGW64 /e/code-snippets (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

