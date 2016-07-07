# GitBasics
1. r.click proect folder open git bash here

2. git init  // will create .git hidden folder initialization setting with folders as hooks,info,
objects,relfs and other files.

3. git status // will show all the locally sync files and
folders to git  as untracked files. if untracked the files 
will not be considered by git.

4.  since we do not want to add all kind of files to git 
like .log file, then create .gitignore file and mention
the file pattersn it to exclude while adding.

	use touch .ignore command  to create it.
	*.class
	*.log
	*.jar
	/target			--this is folder
	/.settings                          --this is folder
	.project			--file

4.1 git add .  //will stage files ready for commit  
you can add files with patterns like *.doc,*.java etc.

4.2 to undo the adding
git reset

5. git commit  // its just like taking a snapshot or
creating savepoints so that in crisis we can revert back

eg: git commit -m "1st commit"


5.2.  git push // will push the commited files to default branch  pointed
        git push origin master //push the local files to repo site on branch as master
        or git push https://www.github.com/sandy.git  master


If every thing is ok then , we wil see this
$ git status
On branch branch_2
Your branch is up-to-date with 'origin/branch_2'.
nothing to commit, working directory clean


6.git branch newbranch  //  in default the main
folder that we work for the project is MASTER branch,
but to work safely or work in team we will create 
branches on the project and we can collaborate on them
with mergin of branches

6. git checkout newbranch //to switch from master to newbranch created, now here the others will make changes add, edits files and makes commit
6.1 git push  //to push the local branch to pointed git repo

7.git merge  newbrach // to merge the changes in newbranch
.............
Now we will put the files locally or pull the repository files from or to github.com

8. to clone any projects from git hub



git clone https://www.github.com/sandy.git  // will clone the project to your working directory


9.git pull origin //pulls any changes made to repo to local

10. git push origin master //push the local files to repo site on branch as master

or git push https://www.github.com/sandy.git  master

heree origin is the default 1st repo name, similarly you can add othere repo and push the codes to that site repo.



Git status
Git branch
Git diff  //to find which files are changed
Git diff –name-only

Git diff (file_name)
