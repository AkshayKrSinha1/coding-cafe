Q1) --global means that git stores your name and email in all the repositories.
If it was left out git would only store your name and email in the working repository.

Q2) ls -a reveals hidden files/folders (dotfiles), showing .git, which contains internal database configuration (config), pointers (HEAD, refs/), and history (objects/).

Q3) Git is offering to track 4 untracked items (README.md, week01/, week02/, and lab4/ / notes.md). Everything listed corresponds to my own lab folders and files.

Q4) it's the same as my setup didn't contain any .venv/ directory or compiled files to ignore.The only thing that changed was that .
 .gitignore was added to the list of untracked files.

Q5) .gitignore should be committed. It needs to be tracked by Git so that everyone working on the repository shares the same ignore rules, ensuring consistent behavior across all machines and preventing unwanted files like .venv/ or compiled code from being tracked by collaborators.

Q6) README.md moved from "Untracked files" to "Changes to be committed". In the three-places model, running git add README.md moved the file from the Working Directory into the Staging Area (Index), preparing it to be included in the next commit.

Q7) Git printed [master 3d033a2]  Lab work so far. It reported that 1 file changed, 1 insertion(+), 1 deletion(-).

Q8) The first seven characters (3d033a2) are called a short commit hash (or short SHA-1 checksum). They serve as a unique ID to identify that specific commit snapshot in the repository's history.

Q9) The 4 steps of Git cycle are Edit (modify files) , Check (git status) , Stage (git add) , Commit (git commit).

Q10) README.md is given a standard name and placed in the root directory because Git hosting platforms (like GitHub and GitLab) automatically detect and render it on the project's main homepage. It serves as the front page or shop window for the repository, providing visitors and collaborators with an immediate overview of the project, setup instructions, and repository contents. 

Q11) gh auth login authenticates your terminal using OAuth/web authentication and stores a secure access token locally on your machine. Git automatically uses this stored credential token to authenticate your identity with GitHub, eliminating the need to type your account password or a personal access token every time you push.

Q12) 12. Refreshing the repository page shows the contents of README.md formatted on the front page. GitHub automatically renders README.md because it is designated as the repository's default landing document to introduce visitors to the project.

Q13) Running git log --oneline shows that pushing did not alter the local commit history or hashes at all. It simply updated the tracking pointers so that origin/master now points to the same commit as your local master HEAD.

Q14) A private repository exists on GitHub's servers but limits access exclusively to the repository owner and invited collaborators keeping the code hidden from the general public, if a repository does not exist on GitHub at all, no remote copy or history exists on the cloud platform, meaning no one—including TAs—can view, access, or grade it onlie.
 

