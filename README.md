# Hiwi-notes
This is note of hiwi job
</br>
Case: I have created a branch: lin/dev, I do the operation in this branch, and want to push the new version to the dev branch.
</br>
**git pull**
</br>
**git add .**
</br>
**git checkout dev**
</br>
**git merge lin/dev**
</br>
**git push origin dev**
</br>
<https://stackoverflow.com/questions/70460220/how-to-merge-a-branch-to-main-branch-in-github>
05.04.2023
</br>
There is a new commit in the dev branch, I want to keep my lin/dev branch with the newest version:
</br>
**git add .**
</br>
**git commit -m "<some message>"**
</br>
Go to your dev branch, fetch the remote changes and merge to your local lin/dev branch
</br>
**git checkout dev**
</br>
**git pull origin dev**
</br>
Now go back to your local lin/dev branch and merge those changes with the dev branch
</br>
**git checkout lin/dev**
</br>
**git merge dev**
</br>
<https://stackoverflow.com/questions/69374455/fetch-the-latest-changes-from-main-branch>
