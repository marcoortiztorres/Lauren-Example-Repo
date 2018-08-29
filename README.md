# Lauren-Example-Repo
This is an example repo for Lauren. Here are the instructions for downloading a repository locally and and committing changes:

Author: Marco A. Ortiz Torres

Collaborator: [Replace this with your name]

1. Make sure that you have git set up on your terminal properly. I found this link that might help you out

https://stackoverflow.com/questions/26620312/installing-git-in-path-with-github-client-for-windows

if it doesn't, have Andrea help you set it up.

2. Cloning the github repository to your local machine. You can do this by running

`git clone https://github.com/marcoortiztorres/Lauren-Example-Repo.git`

when ever cloning you will run git clone <Clone URL>. You can find the url by going to the repo you want to clone on github.com and you will find a green button in the middle of the page to the right that says "Clone or Download" and you can just copy the link.

3. Once you run that command the repo will be downloaded as a folder inside of your user folder. So you want to go into that folder by running

`cd Lauren-Example-Repo`

  if the name is long you can click tab while typing the name and it should auto fill if there isn't anything else that has the same name as what you typed.

4. If you are going to be editing a repo you want to create a local branch, do to so you will run:

`git checkout branch -b feature/my_first_feature`

  the **-b** means that you are creating a new branch. if you just use `git checkout branch name_of_branch` you will enter that brach. To get back to the master branch you just use `git checkout master` you will do this to make sure you update your local repository when you create new branches. But once you run this command you are automatically in that new branch.

5. Now that you are in you're own branch, you can start making changes like adding files or editing files that are existing. **For now we will have you edit this document in Atom by adding your name to the collaborators list in the top of this document.** Once you have saved a change you want to commit, you want to add them to the list of items

`git add README.md`

  this is adding only the README.md file to the list, but you can add multiple items or do `git add .` to add everything that has any changes including deleted files, added files, or edited files.

6. When everything has been added you now want to commit your changes to the local repo, which just means you are making a record locally of all the changes that have been made. To do this, you run:

`git commit -m "some message"`

  what that line says is:

  **git commit** - make a commit

  **-m** - with the message

  **"some message"** - a short description of what is in the commit that should always be in quotes.

  You always need to add a message to the commit you are making, so the **-m "bla bla bla"** is always required. A commit is basically like saving, everything locally but you have a decription of what every save was about.

7. Now that we have a commit that is a working file we want to push that commit to github (aka the cloud). Do this by running the following:

`git push origin feature/my_first_feature`

  what this line says is

  **git push** - push to the repository

  **origin feature/my_first_feature** - in the specific branch "feature/my_first_feature"

  You always want to use **origin name_of_branch** because it creates a new branch on the cloud for github to keep track of. Now on github you will see that the branch you created is a part of the list of branches.

8. Now you want to create a pull request to merge your changes to the master branch. So you will go to the github website and navigate to the repo. You will now see a small pup up that says open a pull request. When you click it you will see a page that you can fill out and you will describe the changes you made with the most amount of detail as possible. Then you click "Create Pull Request" and you can either add someone to review your code or wait for someone to approve your pull request
