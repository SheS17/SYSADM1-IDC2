+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| e5793e0e92eb420ba5af13eef3256ea8 |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| NAME: Shekinah T. Sotero         | DATE PERFORMED:        |          |
|                                  | 10/23/24               |          |
+----------------------------------+------------------------+----------+
| Section: IDC2                    | DATE SUBMITTED:        |          |
|                                  | 10/26/24               |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Git Basics

Answer the following research questions about Git, GitLab desktop and
GitHub.

1.  What is Git, and why is it important in software development?

> Git is a tool that tracks code changes, allowing developers to
> collaborate, manage versions, and keep a history of project updates.
> It ensures safe experimentation and teamwork.

2.  How does Git track changes in a project?

> Git saves snapshots of project files when changes are committed. It
> uses checksums to identify versions and efficiently stores updates,
> not entire files.

3.  What is the difference between a local repository and a remote
    repository in Git?

> Local repository means that it is stored on local machines for an
> individual user like your personal computer while remote repository
> are hosted on a remote in which it could be on the internet or an
> off-site server.

4.  What are the basic Git commands?

+------------+---------------------+-----------+----------------------+
| **         | **Description**     | **C       | **Description**      |
| Commands** |                     | ommands** |                      |
+============+=====================+===========+======================+
| 1.  git    | This creates a      | 7\. git   | Manage branches.     |
|     init   | repository          | branch    |                      |
+------------+---------------------+-----------+----------------------+
| 2.  git    | Stage files for     | 8\. git   | Combine branches.    |
|     add    | commit              | merge     |                      |
+------------+---------------------+-----------+----------------------+
| 3.  git    | Save changes to the | 9\. git   | Copy a remote        |
|     commit | repository          | clone     | repository to your   |
|            |                     |           | computer.            |
+------------+---------------------+-----------+----------------------+
| 4.  git    | Show the            | 10\. git  | Gets the latest      |
|     status | repository's state  | fetch     | changes from the     |
|            |                     |           | remote repository    |
|            |                     |           | but doesn't apply    |
|            |                     |           | them to your files   |
|            |                     |           | yet.                 |
+------------+---------------------+-----------+----------------------+
| 5.  git    | Upload changes to a | 11\. git  | Undo changes by      |
|     push   | remote repository.  | reset     | moving back to a     |
|            |                     |           | specific point in    |
|            |                     |           | your project.        |
+------------+---------------------+-----------+----------------------+
| 6.  git    | Fetch and merge     | 12\. git  | Shows a list of all  |
|     pull   | changes from a      | log       | the past changes     |
|            | remote repository.  |           | (commits) in your    |
|            |                     |           | project.             |
+------------+---------------------+-----------+----------------------+

5.  How do you check the status of a Git repository?

> By running the command "git status" to see the untracked, staged, or
> modified files and the branch's current state.

6.  What is the purpose of branches in Git, and how do you create and
    switch between them?

> Branches in git let's you work on features without affecting the main
> code. You have to first enter the command "git branch \[branch-name\]"
> to create a branch. The nest step is to switch to a brand in which you
> can use two commands, "git checkout \[branch-name\] or git switch
> \[branch-name\]" which is the preferred one.

7.  What are GitLab Desktop and GitHub, and how are they different from
    Git?

> Git is a version control system in which GitHub and GitLab are
> platforms for hosting Git repositories, with GitLab offering built-in
> CI/CD tools. GitLab Desktop is a GUI tool for managing GitLab projects
> locally.

8.  How do you connect a local Git repository to a GitLab or GitHub
    repository?

> 1st: Create a repository on GitLab or GitHub.
>
> 2nd: Copy the repository URL.
>
> 3rd: Run the commands as follows

-   git init

-   git add .

-   git commit -m \"Initial commit\"

-   git remote add origin \<repository-URL\>

-   git push -u origin master

+-----------------------------------------------------------------------+
| Example:                                                              |
|                                                                       |
| git init                                                              |
|                                                                       |
| git add .                                                             |
|                                                                       |
| git commit -m \"Push existing project to GitLab\"                     |
|                                                                       |
| git remote add origin <https://sample>                                |
|                                                                       |
| git push -u origin master                                             |
+=======================================================================+
+-----------------------------------------------------------------------+

4th: Ensure the remote repository is empty and matches your branch name.

9.  What are the steps to collaborate with others using GitLab or
    GitHub?

> To collaborate using GitLab or GitHub, clone the repository "**git
> clone repository-url**", create a branch for your work "**git branch
> \[branch-name\]**", commit and push changes "**git push origin
> \[branch-name\]**", and open a pull/merge request for review and
> merging.

10. How do you resolve merge conflicts in Git?

> You have to edit any conflicting files, and mark the resolved
> conflicts with "**git add \[file-name\]**" and commit the resolution
> using "**git commit**".

11. What is a pull request, and why is it used in GitHub?

> A pull request is a request to merge changes from one branch into
> another, typically used in GitHub. It facilitates code review,
> discussions, and collaboration before merging.

12. What are some best practices for writing commit messages?

-   Keep it short and clear

-   Provide extra details if needed

-   It should be consistent and concise

-   Capitalize the subject line.

-   Write good commit messages.

-   Use the imperative mood
