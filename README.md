# A02
Glossary:
<b>Branch</b> - A version or iteration of a repository.<br>
<b>Clone</b> - Downloads a copy of the repository to your local machine.<br>
<b>Commit</b> - Prepares to upload your changes to a repository. This is where you include the comment on the changes.<br>
<b>Fetch</b> - Downloads files from other repositories.<br>
<b>GIT</b> - A program used to work on collaborative projects. It provides tools to upload, download, and modify projects.<br>
<b>Github</b> - A service that hosts git repositories. It allows people to use git and collaborate with each other with ease. <br>
<b>Merge</b> - Combines the elements of two different versions of the same file into one.<br>
<b>Merge Conflict</b> - The merge tool was unable to combine the files, usually due to the files being too different or different code on the same line.<br>
<b>Push</b> - Uploads your changes to the repository.<br>
<b>Pull</b> - Downloads any new changes from the repository and updates old files.<br>
<b>Remote</b> - Show all associations to the repositories in a git project.<br>
<b>Repository</b> - The place where all the files are stored. Can keep track of older versions of the codebase and jump between them easily.<br>

How to use Git and GitHub:
1. Go to https://github.com and create an account. (github.com will be called "GitHub")
2. On the home screen of GitHub, there is a box to start a new repository. Enter a name for the new repository and click create.
You have now created a repository. Take note of the URL of your repository, as it will be important later.

3. Now, git must be installed on your machine. Start by going to git-scm.com and download Git for your machine.
4. After installing git, create a folder on your machine to store the projects you download.
5. In this tutorial, we will be utilizing the command line version of git. Open git bash or git CMD on your machine, and navigate to the created folder using the "cd" command.
6. Type "git clone" followed by a space and the link to your GitHub site and put ".git" at the end.
Example: "git clone https://github.com/[username]/[repository-name].git"
Following this, the repository will be downloaded to your machine in the working directory in the git program.
7. Use the "cd" command to navigate to your newly downloaded repository.
From here, you can start working. Add or change whatever files you need. 
If you want to change branches, you can use "git checkout [branch-name]". To create a new branch, use "git checkout -b [branch-name]"
8. After finishing your changes, you need to prepare to upload them back to the working repository. In the git command line, type "git add ." to add all files in the directory to be uploaded. 
9. Type "git commit -m "[comment]" to commit the files to be uploaded. Be sure to give a short, meaningful name for your commit that others will be able to understand.
10. Type "git push origin [branch-name]" to upload the files to the repository. For GitHub, the default branch name is "main".
At the end of this process, you new files should be accessible on the GitHub site. 