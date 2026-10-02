Q1) --global means that git stores your name and email in all the repositories.
If it was left out git would only store your name and email in the working repository.

Q2) it revealed git's internal files and directories used to manage the repository.

Q3) There were 2 untracked files. I could identify the untracked code by running git status --untracked-files=all.

Q4) it's the same as my setup didn't contain any .venv/ directory or compiled files to ignore.The only thing that changed was that .
 .gitignore was added to the list of untracked files.

Q5) .gitignore should be committed. It needs to be tracked by Git so that everyone working on the repository shares the same ignore rules, ensuring consistent behavior across all machines and preventing unwanted files like .venv/ or compiled code from being tracked by collaborators.

Q6) README.md moved from "Untracked files" to "Changes to be committed". In the three-places model, running git add README.md moved the file from the Working Directory into the Staging Area (Index), preparing it to be included in the next commit.

Q7) 
