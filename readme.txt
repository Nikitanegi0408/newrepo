cross@DELL MINGW64 ~/OneDrive/Desktop/GIT NIKITA 2 (feat)
$ git commit "fith commit"
error: pathspec 'fith commit' did not match any file(s) known to git

cross@DELL MINGW64 ~/OneDrive/Desktop/GIT NIKITA 2 (feat)
$ git commit -m "fith commit"
[feat defaae4] fith commit
 1 file changed, 2 insertions(+), 3 deletions(-)

cross@DELL MINGW64 ~/OneDrive/Desktop/GIT NIKITA 2 (feat)
$ git checkout main
Switched to branch 'main'

cross@DELL MINGW64 ~/OneDrive/Desktop/GIT NIKITA 2 (main)
$ git merge feat
Updating fde83d6..defaae4
Fast-forward
 readme.txt | 5 ++---
 1 file changed, 2 insertions(+), 3 deletions(-)

cross@DELL MINGW64 ~/OneDrive/Desktop/GIT NIKITA 2 (main)
$ git branch test

cross@DELL MINGW64 ~/OneDrive/Desktop/GIT NIKITA 2 (main)
$ git checkout test
Switched to branch 'test'

cross@DELL MINGW64 ~/OneDrive/Desktop/GIT NIKITA 2 (test)
$
