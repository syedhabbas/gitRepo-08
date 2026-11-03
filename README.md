# gitRepo-08
Practice Git

# staging file

# vim one.txt 
# git add .
# git status


# Unstaging file
 
# git status
# git restore --staged one.txt
# git status

# Commit

# git commit -m 'File is updated successfully.'
# git log, it will show commit history.

# git tag, we can tag an older commit with its hash value

# git log --oneline | this will show hash value.
# git tag v1.1.0 79fb40c

# How to display tag details

# git tag
# git show v1.0

# Create branch locally and then propogate it on GitHub

# git branch lalpir
# git push --set-upstream origin lalpir | this will propogate new branch on GitHub.
# git checkout lalpir
# Update files under this branch independently, then merge it with main branch.
# git checkout main
# git merge lalpir
# git branch -d lalpir | this will delete branch locally.
# git push origin --delete lalpir | this will delete branch on GitHub.



