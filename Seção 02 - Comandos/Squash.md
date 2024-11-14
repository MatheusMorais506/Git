# Squash (Comprimir vários commits em apenas 1)

`git rebase --interactive HEAD~3` (Ex:Ultimos três commits) 

* Vai abrir o editor, nesse caso os commit 2 e 3 estão sendo fundidos no 1:

`pick hashCommit1` 
`squash hashCommit2`
`squash hashCommit3`