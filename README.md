# SAP-Edunet
fahad@ACER-LAPTOP MINGW64 ~/OneDrive/Desktop/SAP (main)
$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Git Commands

no changes added to commit (use "git add" and/or "git commit -a")

fahad@ACER-LAPTOP MINGW64 ~/OneDrive/Desktop/SAP (main)
$ git add Git Commands
fatal: pathspec 'Git' did not match any files

fahad@ACER-LAPTOP MINGW64 ~/OneDrive/Desktop/SAP (main)
$ git add .
warning: in the working copy of 'Git Commands', LF will be replaced by CRLF the next time Git touches it

fahad@ACER-LAPTOP MINGW64 ~/OneDrive/Desktop/SAP (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


fahad@ACER-LAPTOP MINGW64 ~/OneDrive/Desktop/SAP (main)
$ git push origin main


fahad@ACER-LAPTOP MINGW64 ~/OneDrive/Desktop/SAP (main)
$ git push origin main
fatal: unable to access 'https://github.com/iamfahadshaikh/SAP-Edunet.git/': Failed to connect to github.com port 443 after 21088 ms: Couldn't connect to server

fahad@ACER-LAPTOP MINGW64 ~/OneDrive/Desktop/SAP (main)
$ git commit -m "added file"
[main e18521f] added file
 1 file changed, 23 insertions(+)

fahad@ACER-LAPTOP MINGW64 ~/OneDrive/Desktop/SAP (main)
$ git status
On branch main
nothing to commit, working tree clean

fahad@ACER-LAPTOP MINGW64 ~/OneDrive/Desktop/SAP (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 554 bytes | 554.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/iamfahadshaikh/SAP-Edunet.git
   e8b5cbf..e18521f  main -> main

fahad@ACER-LAPTOP MINGW64 ~/OneDrive/Desktop/SAP (main)
$
