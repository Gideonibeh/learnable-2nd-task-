# learnable-2nd-task-

1. ## ***Version Control*** 

> Version control is a systems that takes notice and registers changes made to different files, so you can go back to a desired stage later.  
it also enables multiple individual to work on the same project regardless  
of time and space, and also track changes made to files individually.

2. ## ***Difference between git and gitHub***

> git on itself its the version control system whereas gitHub is the platform for hosting git repositories and working with other people  in different places.

3. ### ***3 alternatives for gitHub***

> .Bitbucket
>
> .Sourceforge  
>
> .Gitlab  

4. #### ***Diffrence between git fetch and git pull***

> git fetch downloads the current changes from the remote repositories, while git pull combines the changes into the current branch by merging.  

5. ##### ***Git rebase and its command***

> git rebase is a command used in reapplying series of commits onto another base commit, used in the combination of changes from one branch to another at the maintaining a linear project history.
>
> .*command for git rebase*: git rebase (--continue, --skip, --abort, --interactive, --show-current-patch) 
> --continue
Restart the rebasing process after having resolved a merge conflict.

> --skip
Restart the rebasing process by skipping the current patch.

> --abort
Abort the rebase operation and reset HEAD to the original branch. If < branch > was provided when the rebase operation was started, then HEAD will be reset to < branch >. Otherwise HEAD will be reset to where it was when the rebase operation was started.

> --quit
Abort the rebase operation but HEAD is not reset back to the original branch. The index and working tree are also left unchanged as a result. If a temporary stash entry was created using --autostash, it will be saved to the stash list.

6. ###### ***Git cherry-pick and its command***

> git cherry-pick is a command that enables you to choose and pick individual commit and apply them to a different branch, it is used for selectively combining changes from one branch to another.  
>
> .*command for git cherry-pick*: git cherry-pick (--edit, --cleanup=< mode >, -x, -r, -m < parent number >, --signoff)
>
> --edit
With this option, git cherry-pick will let you edit the commit message prior to committing.

> --cleanup=< mode >
This option determines how the commit message will be cleaned up before being passed on to the commit machinery. 

> -x
When recording the commit, append a line that says "(cherry picked from commit …​)" to the original commit message in order to indicate which commit this change was cherry-picked from.

> -r
It used to be that the command defaulted to do -x described above, and -r was to disable it. Now the default is not to do -x so this option is a no-op.

> -m < parent-number >
--mainline < parent-number >
Usually you cannot cherry-pick a merge because you do not know which side of the merge should be considered the mainline. This option specifies the parent number (starting from 1) of the mainline and allows cherry-pick to replay the change relative to the specified parent.

> -n
--no-commit
Usually the command automatically creates a sequence of commits. This flag applies the changes necessary to cherry-pick each named commit to your working tree and the index, without making any commit. In addition, when this option is used, your index does not have to match the HEAD commit. The cherry-pick is done against the beginning state of your index.
>
> This is useful when cherry-picking more than one commits' effect to your index in a row.

> -s
--signoff
Add a Signed-off-by trailer at the end of the commit message. 



