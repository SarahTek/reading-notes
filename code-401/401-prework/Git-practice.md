# Git Practice

- Head : HEAD always points to the most recent commit which is reflected in the working tree.
- Relative Refs ^:
  - git log to see hashes
  - git checkout Head^
  - ~ operator: Say you want to move a lot of levels up in the commit tree. It might be tedious to type ^ several times, so Git also has the tilde (~) operator.
   The tilde operator (optionally) takes in a trailing number that specifies the number of parents you would like to ascend.
  - -f give us a way to quickly move a branch to another location.
 -HEAD~ oprator
- git reset :git reset reverses changes by moving a branch reference backwards in time to an older commit.
- git revert:In order to reverse changes and share those reversed changes with others, we need to use git revert.
- git cherry-pick:is the act of picking a commit from a branch and applying it to another.
- Git Interactive Rebase: it's the best way to review a series of commits you're about to rebase.
- Locally stacked commits:
- git rebase -i
- git cherry-pick
- Juggling Commits
- git tags
- Git Describe
- git clone
- git fetch :download all the commits
- Simulating collaboration
