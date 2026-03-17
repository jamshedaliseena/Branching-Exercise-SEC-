# Branching Exercise (SEC)
Branching Exercise (SEC)

1 = What is the difference between a fast-forward and recursive merge?

Fast-forward merge:

Happens when there are no new commits on the target branch.

Git simply moves the pointer forward—no new merge commit is created.

Clean and linear history.

Recursive merge:

Happens when both branches have new commits.

Git combines changes and creates a new merge commit.

Used when histories have diverged.





2 = How do merge conflicts happen?

Merge conflicts happen when:

Two branches change the same file, and

The same part (lines) of that file is edited differently.
