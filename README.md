# non-linear-code-editing

Simple tool to manage merging partial branches into main feature branch.

Proposed workflow:

1.  Define steps (partial branches) and target branch.
2.  Work on sub-features in their dedicated branches.
3.  Committing to any step triggers regeneration of the main feature branch and update of branch that tracks diffs to latest pushed main feature branch.
5.  Push the diffed main feature branch to remote.
