Git pull -  pulls from the repo we are connected to
Git push – push our local changes out to be used by others who have access to the repo
Git add . – stages any changes we have made ready to be committed
Git commit -m “ my message” – prepares our work ready to be uploaded to github
Git status 0 shows status of whether files have been added or pushed or committed
Git clone <address of repo> - makes a copy of the repo from github to your local environment
Git init – used to initialise a repo so we can start tracking it 
Git log – gives us a history of commits so far
Git remote add origin <address of repo> - creates the link between our pc and github
Git branch -M main
Git push -u origin main – for our first push 

Add -> commit -> push

CI / CD – continuous integration and continuous development 

Git branch
Git checkout -b dev – adds a new branch called dev and switches to it
Git checkout “main” – switches to main “branch”
Git push –set-upstream origin dev – this allows us to push our new branch

Git diff <filename> - shows any differences in the file you specify









…or create a new repository on the command line
echo "# WarmupDay1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/NecipYildizcan/WarmupDay1.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/NecipYildizcan/WarmupDay1.git
git branch -M main
git push -u origin main
