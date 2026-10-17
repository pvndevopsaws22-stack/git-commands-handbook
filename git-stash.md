# Save Changes Temporarily
git stash

# Save Changes with a Message
git stash push -m "my temporary changes"

# Stash Tracked and Untracked Files
git stash -u

# List All Stashes
git stash list

# Restore and Remove the Latest Stash
git stash pop

# Restore a Stash Without Removing It
git stash apply

# Show Stash Details
git stash show

# To see the full diff:
git stash show -p

# Delete a Specific Stash
git stash drop 'stash@{0}'

# Delete All Stashes
git stash clear
