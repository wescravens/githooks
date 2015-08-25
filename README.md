# githooks

Scripts to be stored in .git/hooks for various projects

####npm.post-install
After checkout, it runs a git diff on the current `package.json` and `HEAD@{1}`'s `package.json`.  If there are changes, it asks you if you want to remove changed `node_modules` dirs and run `npm install`.
