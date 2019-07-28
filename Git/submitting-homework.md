# Basic workflow for using git to submit homework

## Forking and cloning 

1. Go to the current week's repository on our HackYourFutureCanada [page](https://github.com/HackYourFutureCanada).

2. In the upper right corner, press the **Fork** button.

3. On the subsequent dialog box, select your GitHub account as the place to fork this repository.

4. Once forking is complete, you'll be redirected to your forked version of the repository. Verify that it's your username before the repository name.

5. Click on the **Clone or download** button and you will see a link for the project. Copy this link. Make sure you use the clone with HTTPS URL.

6. Open up your terminal or Git Bash and navigate to a directory where you'd like to clone the project. Type the following command, replacing https://github.com/YOUR-USERNAME/YOUR-REPOSITORY with the clone url that you just copied. 

```
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

## Committing and pushing changes

1. Make changes to your files. When you are ready to add your changes to git, use `git add` (see below) to prepare the files that you want to include in your commit (i.e., add them to the staging area).

To add all new and modified files:
```
git add .
```

To add a specific file (replace [filename] with the actual name of your file):
```
git add [filename]
```

2. Commit the files that you've added, making sure to add a descriptive commit message:
```
git commit -m "your commit message"
```

3. Push the changes from your local repository to GitHub. Change `master` to whatever branch you want to push your changes to:
```
git push origin master 
```

You can run `git status` to see the files that have been added to the staging area and that haven't, and the files aren't being tracked by git.
You can run `git log` to see a history of the project's commits.

You can (and should) add and commit often! You don't have to push after every commit, but it's a good idea to push once you've completed all your work for the day so your changes will be readily available on GitHub.

## Creating a pull request and submitting your homework

When you are ready, you should submit your homework using a pull request.

1. Make sure you've pushed your latest work to GitHub. You should be able to see your latest changes on GitHub.

2. Go to the GitHub repository containing your homework on GitHub.

3. Click the button [**New pull request**].

4. Select the HackYourFuture repository branch on the left side **with your name** and your repository and homework branch on the right side.

5. Press the green [**Create pull request**] button to continue.

6. Add a title for your pull request, and any comments.

7. Finally, press the green [**Create pull request**] button to finish sending off the pull request.