# learnable-git-task


## Explain version control.

Version control is a mechanism designed to document alterations made to a file or group of files over time, facilitating the retrieval of specific versions at a later point. Although widely employed in software development to monitor modifications in source code, its application extends to any file type. The primary objective of version control is to foster collaboration among numerous contributors while meticulously recording the progression and history of a project.

## Explain difference between git and github

Git functions as the standalone version control system, overseeing the monitoring of changes directly on a developer's local machine. In contrast, GitHub is a platform constructed on the foundation of Git, furnishing web-based hosting services and supplementary collaboration tools to streamline remote cooperation, code sharing, and project management. While Git remains capable of independent use, platforms such as GitHub (or alternatives like GitLab and Bitbucket) offer an online environment for hosting and collaboration, augmenting Git's capabilities.

## List 3 other github alternatives

1. Gitlab
2. Bitbucket
3. SourceForge

## Explain the difference between git fetch and git pull,

The primary distinction lies in their approach to updating the local repository. While git fetch retrieves changes, providing the flexibility to decide when and how to merge them, git pull fetches changes and promptly incorporates them into your current working branch. The decision between the two depends on whether you prefer more control over the timing of merging changes or if you favor an automatic and immediate update.

## Explain in simple terms git rebase and the command for it

git rebase is a Git command that allows you to change the way your commits are organized or applied on top of another branch. It's like rewriting history.

`git rebase <target-branch>`

## Explain in simple terms git cherry-pick and the command for it 

`git cherry-pick` is a Git command that allows you to copy a specific commit from one branch and apply it onto another branch.

`git cherry-pick <commit-hash>`
