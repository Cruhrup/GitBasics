# Practice making repository for learning Git

## Commands users

- git init: Create a new git repository
- git status: Compare working directory, staging area, and current branch
- git add: Add changes from working directory to staging area
- git commit: Commit changes from working directory to staging area
- git config: Set or get configuration
- git log: Show a history (aka "log") of project commits
- git checkout: Check out branch (update HEAD and apply changes to working directory)
- git branch -c: Create a branch
- git merge: Merge changes from different branches

## Commit Messages

Default editor is vim (MobaXTerm is what I use though)
  ctrl+s to save commit message after adding it
  exit text editor after saving

Easier way is to use 'git commit -m "<message>"'
  This will append your message to the commit without opening a text editor
  Commit message should be clear, accurate, and concise
  Don't end with a '.'

## Merging

Merging means to bring the changes from one branch into another.

- A fast-forward merge happens when the target branch was branched from the current one, and there are no new changes to the current branch since then.
- An Automatic merge happens when the two histories have diverged, but git is able to reconcile them into one set of changes. This creates a new commit on the current branch.
