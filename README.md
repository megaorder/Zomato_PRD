# go to the folder containing Zomato_PRD
cd "C:\path\to\your\workspace"

# enter the Zomato_PRD folder
cd Zomato_PRD

# configure git identity (only if not set)
git config user.name "megaorder"
git config user.email "megaorderhomelandmegahertz@gmail.com"

# init, commit, set remote and push
git init
git checkout -b main
git add .
git commit -m "Add PRD and README for Zomato_PRD"
git remote add origin https://github.com/megaorder/Zomato_PRD.git
git push -u origin main
