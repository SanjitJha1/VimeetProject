connecting remote repo using git hub
echo "# VimeetProject" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/SanjitJha1/VimeetProject.git
git push -u origin main
