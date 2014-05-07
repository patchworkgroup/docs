# Unfuddle git workflow
As our projects are almost always very simple, this is the workflow that we will follow 99% of the time.

Rules of thumb:
- Always pull before you push
- Always pull in the beginnig of the day
- Always push before you go home
- Don't push broken code (at least not without notifying other collaborators that your feature is not yet working)

Workflow:
- Pull
- Add files
- Commit
- Push

In code:
```bash
# Fetch all updates
git pull unfuddle master

# What files have been modified or added? (this is optional and only 
# to give an overview of what you are about to add/commit)
git status

# Add all modified files (if you have new files, add them with "git add -A")
git add -u

# Commit files
git commit -m "Added styling to landingpage"

# Push (You don't have to push immediately after a commit. You can do many commits and push them all at once)
git push unfuddle master
```





