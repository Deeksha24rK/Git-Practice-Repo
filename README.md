## Getting started with Git and Github

### Steps to clone repository from Github (Remote) and upload the changes to your own repository.

1. Create a Repository in GitHub: https://github.com/Deeksha24rK

_Click on profile icon (top right) and select `Your repositories`\
 Click on the `New` button , and create a repository. Give it a name, add description if you want._

2. Clone the repository to your local machine using command prompt or terminal:

```
git clone https://github.com/username/repository_name.git
```

3. Create files and add them to the staging area using git add command:

```
git add .
```

    or

```
git add <filename>
```

4. Commit the changes (add a comment) using the commit command:

```
git commit -m "Add the commit message here"
```

5. Push the changes to your remote repository using the push command:

```
git push origin main
```

Additionally, `git status` shows the state of the working directory, staging area, and the history information.

## Git Branch Commands

    Default Branch - **Main**

### BRANCH & MERGE

    Isolating work in branches, changing context, and integrating changes.

1. List your branches. A `*` will appear next to the currently active branch.

   ```
   git branch
   ```

2. Create a new branch at the current commit:

   ```
   git branch [branch-name]
   ```

3. Switch to another branch and check it out into your working directory:

   ```
   git checkout [branch-name]
   ```

4. Merge the specified branch’s history into the current one.

   ```
   git merge [branch-name]
   ```

5. Show all commits in the current branch’s history.
   ```
   git log
   ```
6. Create and checkout to newly created branch.

   ```
   git checkout -b [new_branch]
   ```

7. Rename a Branch

   ```
   git branch -m old-branch new-branch
   ```

8. Delete a Branch
   ```
   git  branch -d [branch-name]
   ```

## Terms

```
Repo - Repository

Directory - Folder

Terminal or Command Line - Interface for Text Commands

CLI - Command line interface

cd - change directory

Repository - Project , or the folder / place where your project is kept

Github - Website to host your repositories online

Working Tree -

Branch -
```

## Git Terms

`clone` : Bring a repo down from the internet (remote repository like Github) to your local machine.

`add` : Track your files and changes with Git.

`commit` : Save your changes into Git.

`push` : Push your changes to your remote repo on Github (or another website).

`pull` : Pull changes down from the remote repo to your local machine.

`status` : Check to see which files are being tracked or need to be commited.

`init` : Use this command inside of your project to turn it into a Git repository and start using Git with that codebase.
