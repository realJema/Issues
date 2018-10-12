# Issues
A list of issues I come across and their proposed solutions 

## Github
#### Change "origin" of your GIT repository
>git remote rm origin  
>git remote add origin [url]  
>git config master.remote origin  
>git config master.merge refs/heads/master  
[Reference](https://gist.github.com/DianaEromosele/fa228f6f6099a8996d3cb891109ab975)

#### Learn Markdown 
Learn how to use the markdown language used on github  
**A double space to force newline**  
[Reference](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)  
[Reference 2](https://markdown-guide.readthedocs.io/en/latest/basics.html)

#### Uploading to github
>git init
>git add .  
>git commit -m "first commit"  
>git remote add origin https://github.com....
>git push -u origin master  

#### Git Push failed 
git pull origin master --allow-unrelated-histories

#### Stop tracking folder 
>git rm -r --cached --ignore-unmatch folder_name
or 
>git rm --cached -r <dir>

#### Force push to Github
git push -f origin master
#### Force merge from Github
[to do]
#### Git credential manager 


## Useful CMD
create directory 
`mkdir [name]`
delete files and directory
`del filename.txt`
`rmdir dirname`