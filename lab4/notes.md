
Lab 4 : Git and Github
Q1. Meaning of --global in git config and omitting it
Answer: --global makes the Git configuration apply across all repositories on the computer. Without it, the setting applies only to the current repository.
Q2. Contents of .git revealed by ls -a
Answer: A hidden .git directory appeared. It contains Git's internal repository information, including the data needed to track commits, branches  and other Git information.
Q3. Approximate untracked file count and identifying untracked code
Answer: 7 untracked files or folders
Q4. Difference in git status after creating .gitignore
Answer: After adding .gitignore, .DS_Store disappeared from the list of untracked files.The other files and folders were still shown because they were not listed in .gitignore
Q5. Why .gitignore itself should be committed rather than ignored?
Answer:.gitignore should be committed as it contains the rules for which files Git should ignore so the same rules are available to anyone working on the repository.
Q6. Movement of README.md across sections in git status (three-places model)
Answer: git add README.md moved README.md from the working directory to the staging area. The staging area lets me choose which changes I want to include in the next commit.
Q7. Output produced by git commit and count of changed files
Answer: Git created the first commit with the message "Lab work so far." It recorded 8 files changed, with 1746 insertions.
Q8.Name and purpose of the first seven characters of a commit hash
Answer: e2ee193 is the short form of the commit's unique hash (commit ID). It identifies that particular commit and can be used to refer to it when working with Git. 
Q9. The 4 steps of the repetitive Git loop
Answer: The 4 steps are create or edit a file, stage the changes using git add, commit them using git commit and then repeat the process for new changes.
Q10.Special purpose and placement of README.md
Answer:README.md is special because GitHub automatically displays it on the main page of the repository. It gives people an overview of what the repository contains.
Q11. How gh auth login eliminates future password prompts?
Answer: gh auth login authenticates the GitHub CLI with my GitHub account. It also allows Git to use my GitHub credentials for HTTPS operations
Q12. File rendered on GitHub's front page and the reason why
Answer.GitHub  renders the README.md file in the repository's main page. Markdown formatting such as headings and bullet points is displayed as formatted text.
Q13.Effect of git push on local history
Answer: pushing sends my local commits to the GitHub repository and updates the remote branch. It does not change  local commit history.
Q14.Distinction between a private repository vs. no repository on GitHub
Answer: A private repository exists on GitHub but only the owner, collaborators and people with permission can access it. If there is no repository on GitHub, there is nothing available online for others to acces
