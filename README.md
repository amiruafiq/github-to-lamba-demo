# github-to-lamba-demo
[Source Video/Tutorial](https://www.youtube.com/watch?v=AmHZxULclLQ&t=132s)

1) Create Function (at AWS site)
    - give name function
    - runtime (python/node.js)
    
2) Create repo in Github (github-to-lamba-demo)
3) Clone repo from github via terminal
```
git clone https://github.com/amiruafiq/github-to-lamba-demo
```
4) Open VS Code in folder
```
/Users/amirulafiq/TestFunctionLambda/github-to-lamba-demo
```
5) Create all related file 

- lambda_function.py. [source code](https://github.com/felixyu9/github-to-lambda-demo/blob/main/lambda_function.py)
[Source Video/Tutorial](https://www.youtube.com/watch?v=AmHZxULclLQ&t=132s)
- requirements.txt [source code](https://github.com/felixyu9/github-to-lambda-demo/blob/main/requirements.txt)
- iam-policy.json *to be put in AWS* [source code](https://github.com/felixyu9/github-to-lambda-demo/blob/main/iam-policy.json)



6) From VS Code - push to github
## Working with Git

### Quick Start
```
- git clone <url> 					# Clone directory
- git checkout -b <new-branch> 		# Create new local branch
- git push -u origin <new-branch> 	# Sync local branch with remote
- git checkout <branch> 				# Checkout branch
- git push origin <branch> 			# Push branch to remote

- git branch -d <branchname>   	# deletes local branch
- git push origin :<branchname>	# deletes remote branch

- git subtree push --prefix docs origin gh-pages  # push docs as subtree to gh-pages
```


### Clone Directory
```
- git clone <url>
```


### Create Project
```
- cd project/
- git init                    # initializes the repository
- git add .                   # add those 'unknown' files
- git commit                  # commit all changes, edit changelog entry
- git rm --cached <file>...   # ridiculously complicated command to undo, in case you forgot .gitignore
```


### Branching and Merging
```
- git branch                          # show list of all branches (* is active)
- git checkout -b linux-work          # create a new branch named "linux-work"
<make changes>
- git commit -a
- git checkout master                 # go back to master branch
- git merge linux-work                # merge changesets from linux-work (Git >= 1.5)
- git pull . linux-work               # merge changesets from linux-work (all Git versions)
- git branch -m <oldname> <newname>   # rename branch
- git branch -m <newname>             # rename current branch
```


### Delete Project
```
- git branch -d <branchname>   	# deletes local branch
- git push origin :<branchname>	# deletes remote branch
- git remote prune <branchname>	# update local/remote sync
```
