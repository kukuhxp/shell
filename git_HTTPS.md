> Checking The Git Version:
git -v

> Configuring The Git:
git config --global user.name "Nama Kamu"
git config --global user.email "email@example.com"

> Creating a New Git Repo:
git init

> Checking The Staging Files:
git status

> Adding Files to The Staging Environment:
git add [file's name].[file format]
git add --all
git add -A
git add *
git add .

> Commiting All Staged Files:
git commit -m ["your message"]
git commit -am ["your message"]

> Checking Branch You Owned:
git branch

> Creating a New Branch's Repo:
git branch -M [new branch's name]
git branch [branch name]

> Switching a Branch's Repo:
git switch -c [your branch's name]

> Changing a Branch's Repo Name:
git branch -m [new branch's name]

> Deleting a Branch's Repo:
git branch -d [branch's name]

> Deleting a Folder:
git rm -r [folder's name]

> Checking The Remote You Owned:
git remote -v

> Creating a GitHub's Remote:
git remote add [remote's name] [remote url]

> Changing a Remote's Name:
git remote rename [old remote's name] [new remote name]

> Deleting a Remote:
git remote remove [remote's name]

> Showing Remote's Information:
git remote show [remote's name]

> Changing Remote's URL:
git remote set-url [remote's name] [remote url]

> Uploading Your Repo to GitHub:
git push [remote's name] [branch's name]

> Uploading Your Repo to GitHub (FORCE MODE!):
git push -f [remote's name] [branch's name]

> Downloading Your Repository in GitHub:
git clone [your git url in github]

> Merging a Repo from Another Repo:
git merge [your another repo]

> Pulling a Repo from GitHub:
git pull [remote's name] [branch's name]

> Pulling a Repo from GitHub (Non-fast-forward Issue):
git pull [remote's name] [branch's name]  --rebase

> Adding a Directory to Configuration (Dubious Ownership Issue):
git config --global --add safe.directory [repo location]
git config --global --add safe.directory /storage/emulated/0/[folder name]

> Restoring a File:
git checkout -- [file name]

> Restoring a File to Beginning Commit:
git reset --hard [commit ID]

> Showing Commit Log:
git log

> Setting The User Global:
git config --global user.name "[github username]"
git config --global use email "[github email]"

> Checking Git Configuration:
git config --list

> Unsetting and Deleting The Credentials Helper:
git config --global --unset credential.helper
rm ~/.git-credentials

> Getting The Password of Repository:
    *  Go to: https://github.com/settings/tokens
    *  Select "Personal access tokens" > "Tokens classic" -> "Generate new token (classic)"
    *  In "Select scopes", checking the "repo" option
    *  Click "Generate token"

> Saving The Personal Access Tokens (PAT):
git config --global credential.helper store