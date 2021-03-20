## Reason for .gitkeep
-- literally does nothing but we use it to be able to push to github because if there is nothing there it wouldn't push to github, so its basically a placeholder.


sudo kill -9 $(sudo lsof -t -i:3000)
-- //Is to kill any port that is in use//


# BOILERPLATE DIRECTIONS
- clone with command `npx degit githubusername/githubreponame#branchname projectName`
- cd into new project folder
- run `npm install` to install dependencies
- rename template.env to .env
- make sure to replace MONGODB_URI with a working Mongo URL
- enjoy!