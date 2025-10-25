# Notes - PR Strategy & Merge

- Feature branch: feature/auth
- Conflict: README.md edited on both branches (main: Project: A, feature/auth: Project: B)
- Resolution: Resolved locally using vi; final content combined into "Project: A & B".
- Merge strategy: Merge commit chosen to preserve full branch history.
- Rationale: Keeps visibility of conflict resolution for review and learning.

I learned how to manage branches, create pull requests, and resolve merge conflicts.
While merging feature/auth with main, I had to manually fix the README.md file conflict.
I also learned how to use git rebase to rewrite history and keep commits clean.
Creating tags and using reflog helped me understand how to recover lost commits.
One gotcha I learned: never rebase shared branches; always do it on local feature branches.
Overall, this lab taught me proper Git hygiene and version control discipline.


