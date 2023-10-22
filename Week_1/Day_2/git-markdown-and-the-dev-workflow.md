# Day 2
## Git Markdown and the Dev Flow notes

Today we worked on creating directory and files with the git repository being the main one for the [Lighthouse Lab notes](https://github.com/sdoull/lighthouse-lab-notes)

Key notes after some major trial and errors
* **mkdir** will create a directory
* **touch** will create a file as long as the is no / at the end

Key Steps to remeber when creating/ attaching links/ repositries
1. Make sure you are first in the right spot in the terminal/WSL2
2. Create your directory
3. switch to the new directory ```cd "new directory"```
4. Initalize a new git repo ```git init```
5. Create the file wanted (.md for readable notes/ .js or whatever coding language being used)  ```touch "filename.md/js```

Next Steps you will repeat for any changes made within the files 

1. to add the new files to github ```git add / git add "filename"```
2. Commit the changes with a comment to know hat you have done ```git commit -m "add comment```
3. If its a new repository you will ned to add it to git hub and complete the following steps, if already added move past these steps 
* Create new repository on git hub
* If added your own readme, do not select that option
* Copy the *SSH* key
* Add it to the ternimal ```git remote add origin <SSH>```
* out of repsect Change the name from Master to Main ```$ git branch -m master main```

4. Push the entire thing to the  repositry ```git push -u origin main```