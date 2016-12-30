create a new repository on the command line

echo "# 136class" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/gzdx136/136class.git
git push -u origin master

push an existing repository from the command line

git remote add origin https://github.com/gzdx136/136class.git
git push -u origin master
