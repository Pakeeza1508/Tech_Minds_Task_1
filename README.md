# Tech_Minds_Task_1

*so here is me again today what  have learnt is how to add your remote repo to your local machine.so here is the procedure:
1. create your first repo at remote
2. it can be private or public 
3. when your repo is created go and copy https link and paste it to your local terminal to clone it there
4. now you have added your remote repo to your local machine

*now what is your next step??
you want to be in your folder which you have cloned not in the one which is main . in my case GIT-DEMO is my main folder and inside main i have added my folders for repo now i want to go inside my repo folder from main directory. so we use 
"cd folder-name(we want to go inside)"
so now i am inside my repo foldre

*now it is time to check how many files you have in your repo folder. write 'ls' command 
*next step is to check list of hidden files but the command is not currently working in my pc idon't know the issue so i will check it later let move forword
*how to get list of all including hidden files in your terminal the command is : Get-ChildItem -Force

*next step is to check git status using 'git status' command
now what we have ot do is to add and commit these changes. with this i am also going to add my task 1 files in this folder also to make it a part of my remote repo
--> untracked files  ----------added some new file
--> modified files  ------added some change
when we add these files now our files are staged
then we can comit them

*how to add changes in the repo
git add 'filename'    -----you can use this command to save each file individually
orsimply a 'git add .' command can be used to have all files staged
*how to commit chandes
now you are going to add these changes in your remote repo
use commands 'git commit -m "your message"
now all changes are made
*nowit is a time to save all these changes to github using push command
'git push origin main'