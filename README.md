# source-consistency
check if one source is consistent with another.

## Case 1 - git commit comparison
`git vs git`

In some case, one person will mirror a git repo A to A~.
We need to check if A equals to A~.

## Case 2 - sha comparision
`tar vs tar`

In some case, one person will mirror a tar A to A~.
We need to check if A euqals to A~.

## Case 3 - folder sha comparision
### Case 3.1 
`folder vs folder`

In some case, one person will get a folder A~ from A.
We need to check if A euqals to A~.

### Case 3.2
`git vs tar`

For example, we need to sure a `git commit` euqals to `git release`.


### Case 3.3 
`tar vs folder`

In some case, we need to untar a tar file and use the source directly.

