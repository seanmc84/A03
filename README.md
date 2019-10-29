# A03
Assignment 3

Git is a distributed version-control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. (1)

GitHub is a Git repository hosting service, but it adds many of its own features. While Git is a command line tool, GitHub provides a Web-based graphical interface. It also provides access control and several collaboration features, such as a wikis and basic task management tools for every project. (2)


To use GIT and GITHUB you must first created an account on GITHUB.com. Once the account is created, you must click the "new" button, which should be green in the top left of your screen. This will begin the process of creating a new repository. A Repository is a folder that tracks all the changes made to files while using git over time. (3) Go through the settings and personalize the settings for the project you are working on. Now once you click create, you can work inside this repository. To work on files in it, you must clone the repository to save it locally on your computer. Click the green "clone or download" button and copy the link that it shows. Once copied, go to your favorite terminal, mine is Git Bash, which you can download for free online. Now type "git clone (enter link here)" this will save a copy of the repository on your computer. (Cloning allows you to work on the files in the repository and commit them to create an organized framework of edits). Now locate where the file was created and navigate to it in the terminal using the cd command. For example type "cd documents" to get into the documents folder. Now once you get into the folder where your files are, use an editing command like "vi" to start editing. Type "vi README.md" to edit the README.md text file. Then hit the i key to start typing. Once you are done typing and making edits, hit the ESC key and type ":wq". This will save the work you have done and bring you back to the command line. Now if you are done editing your files, type "git add ." This will add all the files into a queue to be commited. Now type git commit -m "(enter what you edited in these quotations)". Commiting a file is like saving, it adds an orginizational factor by allowing you to label the edits you have made to the files everytime you commit. Now you can Push the files back to github.com by typing "git push origin master" which will send the files back with all the commits, or edits, to github.com. When you look at the repository on github.com it will show the commits that you made along with the finalized file. Now if there were other changes to this remote repository on github.com, you can use the pull command to update the local repository. Use git pull origin and it will automatically pull all the updates and commits that were made on the remote repository to your local save. A way that you can do this is by making a branch of the main repository that is an exact copy, but when you edit, it doesnt mess up the main repository. Branching is used to test certain files without losing progress on the main repository. If you decided to Branch a file, then later want to add it back to the main repository you can use merge. Merge will add the information that isnt present in the main repoistory, but exists in the branched repository. If there is some issue in a file when merging, you will run into a merge conflict. This means that it will ask you which commits to make finalized if they are conflicting the main repository. Fetch allows you to retrieve all the commits and files that were added on the remote repository back to your local repository.


(1) https://techcrunch.com/2012/07/14/what-exactly-is-github-anyway/
(2) https://en.wikipedia.org/wiki/Git
(3) https://blog.axosoft.com/learning-git-repository/

