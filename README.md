# gitHowTo

>command line

##set up

` git config --global user.name "myUser Name" ` <br />
` git config --global user.email "myname@domain.com" ` <br />
` git config user.name // check username ` <br />
` git config user.email // check user email ` <br />

---

##clone repo

` cd to dir root` <br />
` git clone + repo url + dir name` <br />

---

##commit and push 

` cd to dir ` <br />
` git status // origin=remote repo master=current/default branch ` <br />
` mkdir newProject // add dir ` <br />
` cd newProject touch app.js // add file to dir `<br />
` git status // untracked file - not yet 'staged' ` <br />

  > ` git add app.js // add file ` <br />
  > ` git add myProject // add dir ` <br />
  > ` git add * // add all files and folders ` <br />

` git status // tracked file ready to be committed` <br />
` git commit -m "this is the commit message" // commit with message` <br />
  
  > ` git log // list commits in full ` <br />
  > ` git log --pretty=oneline // list all commits in a compact view` <br />
  > ` git log --pretty=online -2 // shows last two commits` <br />
  
` git push origin master // push to remote repo ` <br />

---

##pull requests 

` git pull ` <br />
> ` see 'collaborating' section below for community forking and pulling ` <br />

---

##branching 
> edit code without affecting the original

` git branch hello-newBranch // add custom name to your branch` <br />

> ` add -b to the above to automatically switch to that branch ` <br />

###switching 

` git checkout hello-newBranch // manually switch to branch ` <br />
` git status // check switch has been made `<br />
` git push origin hello-newBranch // push new branch to repo ` <br />

##merging

` git checkout master // switch to master branch ` <br />

> ` git status ` <br />
> ` git branch ` <br />

` git merge hello-newBranch ` <br />

> ` git branch -d hello-newBranch // delete branch locally now it is merged` <br />

` git push origin master ` <br />
` git push origin --delete hello-newBranch // deletes from repo ` <br />

##collaborating

` on github : search for repo ` <br />
` click 'fork' button ` <br />
` git clone + repo url + newDirName ` <br />
` create edit add commit push as usual` <br />
` on github : (your project fork) click on pull request tab ` <br />
` click new pull request button ` <br />
` select branch (using 'edit' button in branch panel) ` <br />
` click 'create pull request' button ` <br />
` add title, description and notes ` <br />
` click 'create pull request' button ` <br />
> ` repo owner accepts your pull request using 'merge pull request' and 'confirm merge' buttons ` <br />

---

` rm -rf // remove file ` <br />
` rmdir // remove dir ` <br />

> ` git help gitignore ` <br />

---

#git add 
#git commit -m "" 
#git push

