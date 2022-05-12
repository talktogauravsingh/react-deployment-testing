# Steps to Deploy React Websites on github pages

### STEP 1 : Install GitHub Pages dependency package
```
npm install gh-pages — save-dev
```

### STEP 2 : Add homepage url to package.json file
```
"homepage": "https://{username}.github.io"
```

### STEP 3 : Add deploy scripts to package.json file
```
"predeploy": "npm run build",
"deploy": "gh-pages -d build"
```
### STEP 4 : Create a remote GitHub repository
```
git init
```
```
git remote add origin your-github-repository-url.git
```
### STEP 5 : Deploy the Application to GitHub Pages
```
npm run deploy
```

### STEP 5 :To get the published URL
1] Go to your GitHub Repo.
2] Click Settings menu.
3] Go to the "Pages" Section.
4] Select branch to "gh-pages" and click on the "Save" button.

Now, you can access the deployed site using the published URL!
