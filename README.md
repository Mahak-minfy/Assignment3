# Steps Taken:
Created a new Git repository and set up the master branch.
Created feature/update-styling branch from master.
Made changes in feature/update-styling branch.
Committed change in branch.
Created feature/add-content branch from master.
Made changes in feature/add-content branch.
Commited change in branch.
Opened pull requests for both branches.
Merged feature/update-styling into master.
Attempted to merge feature/add-content into master, resulting in a merge conflict.

### Screenshot of conflict:
![Conflict](conflicts.png)

### Screenshot of Merged:
![Pull request merged successfully](resolve.png)

### Resolving the Merge Conflict:
Upon attempting to merge feature/add-content into master, Git identified a conflict in the HTML file, as both branches modified the same lines.

Steps to Resolve:
Ran git status to list files with conflicts.
Opened the conflicted HTML file to examine the conflicting changes.
Manually edited the file to integrate both sets of changes, ensuring the content and styling were both preserved.
Used git add <file> to stage the resolved file.
Committed the merge with a message indicating the resolution.
Pushed the updated master branch to the remote repository.
