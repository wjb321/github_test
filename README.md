basic pull and push:
pull: 
git status
git pull

push:
#### git add *
#### git commit -m "update info"
#### git push origin -u main

basic for checking username and user email

#### git config user.name 
#### git config user.email

#### git config --global user.name
#### git config --global user.email
(sometime user has two git account, when push some files remotely, the commits is not the using account, so change with up command)

basic address:
#### cd file
#### cd ..
...
when do this:
'''
#### git add .
'''
and then find some file is not needed to be updated to cash do this:
'''
#### git rm --cached c/test/folder/ -r
'''
then all the files will be removed from cash, or you can remove some files respectively.

when doing branch:
1. create branch
#### git branch branch_Name
2. switch branch
#### git checkout branch_Name
3. merge the git
#### git merge
4. quit the branch and go to main branch
#### git checkout main
