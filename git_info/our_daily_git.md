# Github from 0 to commit.
Each day you'll be working on a number of projects.  Every time you switch out the current driver, also remember to commit your work.  You can push at the end of the project, but you should commit frequently so that you can roll back to previously working versions if necessary.  

You've sat down and started your project.  In the terminal type the following:

		working_directory > git init
		working_directory > git touch README.md
		working_directory > git config --local user.name **********
		working_directory > git config --local user.email *********
		working_directory > git add -A
		working_directory > git commit -m "skeleton"

This will add a `.git` directory, a `README.md` markdown file (which will be useful when people visit your git repositories), and set the directory user.name and user.email to whatever you put there.  

If you set the user.email to the email address registered to your (or your partner's) github account, then you will get your green box when you push for the day.  To that end one of you should [create a repository](https://help.github.com/articles/create-a-repo) for the project.  Once you do that you'll type the following:

		working_directory > git remote add origin https://github.com/hfc-tech-academy/**********.git
		working_directory > git push -u origin master

This will set the local origin and then push the current master to it.  Congrats!  You've got your green box, and you have setup version control.  Every time you want to update the master to include your recent changes just type `git add -A` and `git commit -m "description"` and the local version will update.  A simple `git push` will update the remote repository.

<!-- ##### But what about the second author?
Everyone doing work for the day deserves a few commits, right?  There's a couple of steps to do here.

1. The second author needs to create a repository, as above, on github.
2. Then, you'll follow the `git remote add ...`, changing `origin` to another name.  Perhaps `origintwo`.  This is because you're only allowed to have one remote for each and every name.
3.

Here's the command that will work for the second author.  Remember to replace the relevant information in the command.

		git filter-branch -f --env-filter "GIT_AUTHOR_NAME='your_full_name'; GIT_AUTHOR_EMAIL='your_email'; GIT_COMMITTER_NAME='your_full_name'; GIT_COMMITTER_EMAIL='your_email';" HEAD -->