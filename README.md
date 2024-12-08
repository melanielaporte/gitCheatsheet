<h1 align="center">Git Cheat Sheet for Beginners</h1>

### What is Git? 
Git is a version control system that helps developers track and manage changes to their code. It allows multiple developers to collaborate on a project without the risk of overwriting each other's work. Git enables you to "commit" changes, share code on platforms like GitHub, and easily revert to previous versions if needed.

It is essential for collaboration in software development, offering tools to track every change and merge contributions from different team members smoothly. Learning Git is a must for any beginner coder looking to work on real-world projects and collaborate effectively with others.

For more detailed information, check out [Git Handbook](https://guides.github.com/introduction/git-handbook/) and [Why Learn Git](https://www.codecademy.com/articles/why-learn-git).

### Why learn Git/bash/terminal? 
Understanding Git allows you to manage versions, collaborate with teams effectively, and track project history. Bash and terminal usage is also critical because they enable faster, more efficient workflows. You can automate tasks, access system files directly, and manipulate directories with simple commands.

Git helps streamline collaboration, providing tools to handle merge conflicts and version control. As you dive deeper into coding, you'll find that these skills save you time and allow you to work more productively, especially on larger projects or when collaborating with others. Embracing these tools from the beginning of your journey sets a strong foundation for future growth in coding.

---

## Essential Git Commands
| **Action**        | **Git Command**                | **Example**                  |
|-------------------|---------------------------|------------------------------|
| <span style="background-color:lightgray">Check Git version</span> | `git --version` | `git --version` |
| Check software version | `software name --version` | `pip3 -version` |
| Add or stage changes (Files/Folders) | `git add <file> or git add` | `git add index.html` |
| Commit Changes | `git commit -m "<message>"`	 | `git commit -m "Added new feature"` |
| Push to Remote Repository | `git push origin main`	 | `git push origin main` |
| Check Status of Staged Changes | `git status`	 | `git status`	 |
| Pull Updates from Remote | `git pull` | `git pull origin main` |
| Unstage Staged Changes	 | `git restore --staged <file>`	 | `git restore --staged app.js` |
| Delete Local (on your computer) Repository	 | `rm -rf <repository>`	 | `rm -rf my-repo` |
| Create a Repository Locally	 | `git init`	 | `git init my-repo` |
| Resolve Merge Conflict	 | `git reset --hard origin`	 | `git reset --hard origin` |
| --- | --- | --- |

## Terminal Basics
| **Action**        | **Git Command**                | **Example**                  |
|---------------------------------------|---------------------------|------------------------------|
| <span style="background-color:lightgray">Create a File</span> | `touch <filename>`         | `touch example.txt`|
| Create a Folder                       | `mkdir <folder>`          | `mkdir projects`            |
| Move a File                           | `mv <filename> <folder>`  | `mv file.txt ~/Documents/`  |
| Rename File/Folder	  | `mv <old-name> <new-name>`	 | `mv oldname.txt newname.txt` |
| Write into a File frome bash/terminal | `echo "content" >> <filename>` | `echo "Hello World" >> greetings.txt` |
| --- | --- | --- |



























