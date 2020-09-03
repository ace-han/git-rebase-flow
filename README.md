# git-rebase-flow

rebase branching practice

* mm - should be master (checkout b1, b2)
* b1 - should be b1
* mm - should be b2 and then merge into master
* b1 - should be b1 rebase here master and then merge into master
* mm - should be master

using vscode

* mm - should be master (checkout b3, b4)
* b3 - should be b3
* b4 - should be b4 and then merge into master
* b3 - should be b3 rebase here master and then merge into master
* mm - should be master

using source tree

* mm - should be master (checkout b5, b6)
* mm - should be b5
* b6 - should be b6 and then merge into master
* mm - should be b5 merge here master and then merge back into master
* mm - should be master