## Working with => (Git- GitHub-Bash-Netlify- Cloud server -Database-Node)

## git pull -> add->commit-> push

## fatal: remote cloudbees already exists.

link [here]('https://www.cloudbees.com/blog/remote-origin-already-exists-error')
Create a new repository online using GitHub or GitLab.

Go to your local repository and remove the existing origin remote.

Add the new online repository as the correct origin remote.

## Push your code to the new origin.

1. Remove the Existing Remote

## git remote remove origin

## git remote set-url origin https://github.com/git/git.git

## git rebase when you pull it and cros orgin problem with local and remote

hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint:
hint: git config pull.rebase false # merge
hint: git config pull.rebase true # rebase
hint: git config pull.ff only # fast-forward only
hint:
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.

## git branching when

## For checking git remote conncetions

-git remote -v

# View existing remotes

# origin https://github.com/user/repo.git (fetch)

# origin https://github.com/user/repo.git (push)

git remote set-url origin https://github.com/user/repo2.git

# Change the 'origin' remote's URL

git remote -v

# Verify new remote URL

# origin https://github.com/user/repo2.git (fetch)

# origin https://github.com/user/repo2.git (push)

-atal: 'orgin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

## Git branch

-git branch -git branch (branch name) -git switch -c brancName -git branch -d branchName
