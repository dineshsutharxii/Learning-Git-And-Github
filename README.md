**5Min Revision notes for git and Github:**

mkdir "Name of directory" -> to make folder or Directory
cd -> to go inside folder/location

git init -> to initiate git at that location
git status -> to get the status of files (if file is commited or not)

- STAGING CONCEPT: a stage between adding file and committing file. this where we hold the file before commiting to your repo.
	- working directory -> git add(command) -> staging area -> git commit(command) -> repository
   
git add <filename> -> adding modified/new files to staging area
git add .(dot) -> all modified files comes into staging area
git commit -m "commit message" -> to commit the modified files into repository

- if using Vim then press i or insert from keyboard to start inserting text/message
- if using Vim then to save and exit use "ESC then :wq and press ENTER"
- for every commit there are always new hashcode generated.
  
git log -> to get all the logs of changes made by people
git restore --staged <file>... -> to unstage file
git checkout <HashCode of branch/commit> -> to checkout/move to specific branch
git checkout master -> to move head to master
git branch <Name_of_Branch> -> to create branch in that branch or master
git checkout <Name_of_Branch> -> to move to specific branch
git checkout -b <Name_of_Branch> -> to create and checkout to branch with Name<Name_of_Branch>
git mere <branch_Name> -> to merge branch<branch_Name> with current branch
git branch --delete <branchname> -> to delete perticular branch

- two ways to create .gitignore -
1-> $null > <Name_of_file_with_extension>
2-> direct make file in location with name ".gitignore"

$null > <Name_of_file_with_extension> -> to create file in windows
