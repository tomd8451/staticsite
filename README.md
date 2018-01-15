# Static Site
This repository is a static site consisting of a template from [W3Schools](https://www.w3schools.com/w3css/w3css_templates.asp).

## Getting the code
1) Fork the repo (for the sake of this, assume your github username is jdoe)
2) `git clone https://github.com/jdoe/staticsite.git`
3) `cd staticsite`

## Setting up heroku
1) Create an account https://heroku.com
2) Click the new button in the top right corner, and select "Create new app"
3) Give your app a name (this has to be unique) and click create app
4) Under deployment method, click the "Connect to Github" link
5) Search for staticsite, then click connect for "jdoe/staticsite"
6) Click on the "Settings" link
7) Click "Add buildpack" button
8) Add the buildpack url `https://github.com/heroku/heroku-buildpack-static.git` 
9) Click the "Deploy" link
10) Click the "Deploy Branch" at the bottom of the page
11) Open a new tab and navigate to https://{appname}.herokuapp.com

### Making changes
When you edit files locally, to see your changes, run the following commands on the command line:
1) `git add *`
2) `git commit -m "message about what I changed"`
3) `git push`
4) On your heroku dashboard https://dashboard.heroku.com/apps/{appname}/deploy/github, click the "Deploy" button again.

### Cheat Sheets
#### HTML
If you're wanting a cheat sheet (not searchable, sorry), you can find it [here](https://hostingfacts.com/wp-content/uploads/2016/06/HTML_CHEAT_SHEET_PNG.png)

#### Javascript
A vanilla javascript cheat sheet can be found [here](https://github.com/mbeaudru/modern-js-cheatsheet)
