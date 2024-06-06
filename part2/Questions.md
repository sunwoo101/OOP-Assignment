# Questions
1.	List three major version control software for software engineering.<br>
GitLab, GitHub, Bitbucket

2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.<br>
Git lets you keep track of what was changed and who changed it. It also has version control which means if there is something wrong in the current version of the repository you can change to an older version of the repository.

3.	Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge<br>
Branch: Different versions or copies of the repository that can be used for development or testing before comitting to the main branch.
Pull: Download the updated files from the repository.
Push: Update the files on the repository.
Repository: It is what includes all the project files.
Working copy: A working copy is a local git repository directory.
Merge: Merge lets you put together a different version or different changes to a file.

4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.<br>
Policies:<br>
- Code management<br>
- Version control<br>
- Security<br>

Procedures:<br>
- Repository setup and managing access<br>
- Branching and merging<br>
- Backup<br>

5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.<br>
Meld (meldmerge.org), DiffMerge, Visual Studio Code.

6.	In a merged source code file, how does Git let you know there is a conflict?<br>
On Github Desktop it notifies you that there is a merge conflict and offers you to open the merge conflict in Visual Studio Code. When opening the file in Visual Studio Code it will highlight where the merge conflict is and the differences so you can choose which change to keep.

7.	What are the steps you can take to resolve Git conflicts?<br>
Use a merge tool to find out where the merge conflict is then talk to your team members to find out which change/s to keep.

8.	What does git revert do, and how can you use it?<br>
Git revert allows you to undo a change. You can use git revert using the "git-revert" command.

9.	What does git reset do, and how can you use it?<br>
Git reset allows you to reset the repository back to a specific commit. You can use git reset using the "git-reset" command.

10.	What is the difference between git revert and git reset?<br>
Git revert undoes a change and removes it. Git reset goes back to the commit so you can edit the mistakes.

11.	True or False: It is okay to commit broken code to the main branch.<br>
False

12.	True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.<br>
True

13.	Describe what is DevOps, how is it useful for game developers?<br>
DevOps is a development cycle. It can be useful for game developers so they can smoothly develop and test their games.

14.	List what tools can be used with DevOps. Give a brief description of each one. (at least 3)<br>
Slack: Can be used to plan.
Git: Can be used for version control and to collab with other developers.
Jira: Can be used to track bugs.

15.	What is CI/CD and how can it be used to automate the game development process?<br>
CI/CD is a development cycle that can be used to accelerate software development. Updates to the Git repository, building the game and testing the game can be automated using scripts containing commands.
