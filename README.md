# First time setup

If you have just installed [Git](https://git-scm.com/) on your system then you need to do some additional work😒 .

* Open your Git and paste then below mentioned command there replace `FIRST_NAME LAST_NAME` with your fullname and replace `MY_NAME@example.com` with your email-id that you have used to sign up on **Github**.

* Use this command to set your username `git config --global user.name "FIRST_NAME LAST_NAME"` .

* Then use `git config --global user.email "MY_NAME@example.com"` to Set your email address.

## Push an Existing Repo

* Open your terminal.

* `cd` to your project's folder.

* In your teminal type `git init -b main`.

* Then type `git add .` .

* Now it's time to commit those changes `git commit -m "First commit"` .

* Now add the url of your newly created repo on Github in this command `git remote add origin  <REMOTE_URL>` .

* `git remote -v` this command will verify the new remote url.

* `git push origin main` and finally with this command you can push your existing repo on Github.

## For those who are Just Getting Started With their Project

* Make a new repo on Github.

* Clone that repo on your system.

* Open up your Git terminal.

* `cd` to that cloned repo.

* For a sanity check use `git pull` .

* Now use `git branch branch_name` to make a new branch.

* Use `git switch branch_name` to switch to the branch that you have just created.

* Now open your code editor from that cloned repo and start your work.

* When you're done Open your Git terminal again and use `git add .` to stage your changes.

* Now use `git commit -m "Your commit message"` to commit your changes.

* Now you are ready to push your changes to Github use
`git push` .

* You might get an error saying there's no upstream branch, don't fret cause with that error you also get an command you just have to copy and paste that command in your Git terminal and hit enter that's it.
