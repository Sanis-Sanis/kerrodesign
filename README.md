# CREATE NEW REPO 
echo "# kerrodesign" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:Sanis-Sanis/kerrodesign.git
git push -u origin main

# PUSH TO AN EXISTING REPO 
git remote add origin git@github.com:Sanis-Sanis/kerrodesign.git
git branch -M main
git push -u origin main 


