# Git Learning Journal

## What I Learned
I learned how to effectively use Git branches, pull requests, and issue tracking for structured project management. The importance of atomic commits with clear, descriptive messages became evident throughout the workflow. Creating and resolving merge conflicts taught me valuable lessons about collaborative development practices and how Git handles concurrent changes to the same files.

## Mistakes Fixed
1. **Forgot issue references**: Initially forgot to include "Closes #X" in commit messages to automatically link and close issues upon PR merge. Fixed by being more mindful of commit message conventions.

2. **Non-atomic commits**: Made some commits too large initially, bundling multiple unrelated changes together. Learned to break work into smaller, focused commits that each serve a single purpose.

## Command That Saved the Day
The `git log --oneline --graph --all` command was invaluable for visualizing the entire branch structure, commit history, and merge relationships. It helped me understand where I was in the workflow and verify that branches were properly merged. Additionally, `git status` kept me constantly oriented about which branch I was on and what changes were staged, preventing confusion during the multi-branch workflow.
