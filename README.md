I created a public GitHub repository named GIT-HOL_assignment-1.

I generated an SSH key with a passphrase for secure authentication using the following commands:

ssh-keygen -t ed25519
ls ~/.ssh
cat ~/.ssh/id_ed25519.pub

Then, I added the generated public key to my GitHub account via:
https://github.com/settings/keys


I configured git with my name and email using the command

git config --global user.name “Htet Yee Mon Oo”
git config --global user.email “htetyeemonoo98@gmail.com”


I created a new branch named feature/new-feature from the main branch. 

- git branch
- git checkout -b feature/new-feature
- git branch
- code .

Then I check my git status with the command "git status"

To create a new text file named feature.txt in the repository and add some text (e.g., "This is a new feature"). I used this commands below
- touch feature.txt
- added “This is a new feature” text inside feature.txt

I commit the changes with a descriptive commit message using command "git commit -m “text file added” ".

I pushed the feature/new-feature branch to the remote repository using "git push origin feature/new-feature". 

Then I created a pull request to merge the feature/new-feature branch into the main branch using below commands,

- git checkout main
- git branch
- git merge feature/new-feature
- git push origin main 

I initiated a pull request to merge the feature/new-feature branch into the main branch via GitHub:

Pull requests → New pull request

After reviewing the pull request, I merged it into the main branch on GitHub

As part of the assignment, I collaborated with my classmate and sister. I invited them as collaborators by email through the "Settings → Collaborators" section of the repository.

This is my README.md file I wrote.
