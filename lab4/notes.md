\# Lab 4: Git \& GitHub — Notes



\## Question 1: What does `--global` mean?

The `--global` option saves my name and email in Git's user-wide configuration, so they apply to all my repositories by default. Without it, Git normally applies the setting to the current repository if I am inside one.



\## Question 2: What appeared in `ls -a` but not in `ls`?

The `.git` directory appeared because `ls -a` shows hidden files and directories as well. It contains Git's configuration, commit history data, references, and other information needed to manage the repository.



\## Question 3: Roughly how many files and folders is Git offering to track?

My initial Git status showed approximately \[enter your observed count] untracked files and folders. I checked the output to see which files Git was offering to track.



\## Question 4: What disappeared after creating `.gitignore`?

Files matching the patterns in `.gitignore`, such as `.venv/`, `\_\_pycache\_\_/`, `\*.pyc`, and `.DS\_Store`, should no longer appear as untracked files. These rules prevent generated files and local environment folders from cluttering the repository.



\## Question 5: Should `.gitignore` itself be committed?

Yes, `.gitignore` should be committed because it tells Git which files and directories to ignore. Tracking it allows other contributors to follow the same rules.



\## Question 6: Which two headings did `README.md` move between?

Before staging, `README.md` appeared under Untracked files. After running `git add README.md`, it appeared under Changes to be committed, meaning it had moved into Git's staging area.



\## Question 7: What did Git print after the commit?

Git displayed a summary showing the commit identifier, the number of files changed, and the insertions or deletions. My first commit reported 2 files changed and 31 insertions.



\## Question 8: What are the first seven characters of a commit called?

The first seven characters are an abbreviated commit hash, a shortened form of the commit's unique identifier. They help identify a specific commit in the repository history.



\## Question 9: What are the four steps of the Git loop?

The four steps are edit, inspect, stage, and commit. I modify files, inspect the changes, stage them using `git add`, and save them in the repository using `git commit`.



\## Question 10: Why does `README.md` have a special name and place?

`README.md` is a standard introduction to a project that explains its purpose and contents. GitHub automatically displays it on the repository's front page and renders its Markdown formatting.



\## Question 11: What did `gh auth login` do?

The `gh auth login` command authenticates GitHub CLI with my GitHub account. It allows authorized GitHub operations through the command line after authentication.



\## Question 12: What is showing on the GitHub front page, and why?

The `README.md` file is displayed on the repository's front page because GitHub automatically recognizes and renders README files. It provides visitors with a formatted overview of the project.



\## Question 13: Did pushing change local history?

No, `git push` did not change my local commit history. It uploaded my existing commits to GitHub so that the remote repository could contain the same history.



\## Question 14: What is the difference between a private repository and no repository on GitHub?

A private repository exists on GitHub but is accessible only to its owner and people who have been granted permission. If no repository exists on GitHub, there is no remote repository there to access or collaborate on, even if a local copy exists.

