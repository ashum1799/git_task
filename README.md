## Task 1
1. git config: It is used to set the name of the author and the email address which you want your commitment to addressing.

```
git config --global user.email "[emails]"
``` 

2. git init: It is used to start a new git repository. This is generally used at the beginning.

```
git init
```

3. git add: It is used to add a file to the staging area. Instead of choosing a single file name, you can also choose to give all filenames with an '.'

```
git add .
```

4. git commit –m: It is used to snapshot or record a file in its version history permanently.

```
git commit -m "[message]"
```

5. git push origin [branch-name]: It used to puch the changes to the branch in the repository

```
git push origin [branch-name]
```

6. git remote lets you view all remote repositories. The following command will list all connections along with their URLs:

```
git remote add origin <URL>
```
7. git status: This is one of the most frequently used as this is used to list down all the files which are ready to be committed.

```
git status
```

8. git branch: Git branch command is used to list down all the branches that are locally present in the repository.

```
git branch
```

9. git branch [branch-name]: This is used to create a new branch.

```
git branch [branch-name]
```

10. git checkout: It is helpful in switching from one branch to another.

```
git checkout [branch-name]
```

11. git diff: As the name suggests, this command is used to display all the differences between the files until the changes have not yet been staged.

```
git diff
```

12. git pull: It merges all the changes present in the remote repository to the local working directory.

```
git pull
```

13. git merge: It is used to merge a branch into the active one.

```
git merge [branch-name]
```

14. git clone: It is used to copy a repository. If the repository lies on a remote server.

```
git clone username@host:/path/to/repository
```
15. git reset: It will reset the index and the working directory to the last git commit’s state.

```
git reset
```

