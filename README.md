# How to upload a repository that's created locally

Create the file, and create a new empty repository on Github


Use "git init" to turn your folder into a repository


Use "git add ." to add all files in the repository to be tracked


Use "git commit -m """ where after -m it's quotation marks containing your commit message


Go on your online repository and copy the HTTP link


Use "git remote add origin " where after origin you paste the HTTP link


For the first push, use "git push -u origin main" to set the upstream


Afterwards, for all pushes you can just use "git push"

# How to check and change your origin repository

Use "git remote -v" to see where you're fetching and pushing to


Use "git remote set-url origin " followed by the HTTP link of your new repository