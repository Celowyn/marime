# marime…or create a new repository on the command line

echo "# marime" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Celowyn/marime.git
git push -u origin master
