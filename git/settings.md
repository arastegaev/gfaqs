#### Global
git config --list

git config user.name "username"
git config user.email "email"

git init


#### …or create a new repository on the command line
echo "# gfaqs" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:arastegaev/gfaqs.git or https://github.com/arastegaev/gfaqs.git
git push -u origin main

#### …or push an existing repository from the command line
git remote add origin git@github.com:arastegaev/gfaqs.git or https://github.com/arastegaev/gfaqs.git
git branch -M main
git push -u origin main