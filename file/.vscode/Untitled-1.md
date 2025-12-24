git remote set-url origin https://github.com/Hrushi7780/her-birth-day.git
git branch -M main
git push -u origin main
# then publish the `file` folder with:
git subtree push --prefix file origin gh-pages
# Site will be available at: https://Hrushi7780.github.io/her-birth-day/ (may take a minute)
