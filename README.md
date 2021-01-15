The main personal content is in the folder content/authors/drinkingcoder/\_index.md
After editing, we need to run `hugo server` to check the effects and `hugo` to update the modification.
The content of the website is in the public folder, we need to `cd public`, `git add . -A`, `git commit -m`, `git push -u origin master` to update the website.
Therefore, the working pipeline is as follow:
```
do something
cd DrinkingCoder-GitPage
hugo server
check effects
git add . -A
git commit
git push -u origin master
hugo
cd public
git add . -A
git commit
git push -u origin master
```
The website on drinkingcoder.github.io will be refreshed after seconds.
