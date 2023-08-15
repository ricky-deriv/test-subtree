# test-subtree-workflows

## Description
- [Git Subtree](https://gist.github.com/SKempin/b7857a6ff6bddb05717cc17a44091202) is used to add a repo as a subdirectory to another repo. 
- test-subtree-workflows repo serves as a single source of truth for workflows through iac-repos.
- New changes in the repo can be pulled via the subtree in the other repos.

## Adding test-subtree-workflows repo as a subtree in another repo
- syntax
    ```
        git subtree add --prefix <dir name> <subtree repo ssh link> <branchname>
    ```
- to-run
    ```
        git subtree add --prefix .github git@github.com:ricky-deriv/test-subtree-workflows.git main
    ```
- [optional] Insert any changes to the subtree.
- Push the changes to the remote repo.

## Pulling latest changes of test-subtree-workflows repo from subtree
- to-run
    ```
        git subtree pull --prefix .github git@github.com:ricky-deriv/test-subtree-workflows.git main
    ```
- Resolve conflicts if there's any
- push the changes to the remote repo

