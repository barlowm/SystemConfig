# SystemConfig

*The workstation used to build/run many of my applications requires a basic node.js development environment. Below are instructions on how to establish this. If you already have a functional environment, please disregard.*

From Cmd Prompt with Admin access run the following:

1. [Chocolatey](chocolatey.org) - This is a package manager for windows application for installing software on Windows. It is installed as part of the Node.JS environment installation but I install it by itself and use it to install most of my workstation applications. The instructions for [installation](https://chocolatey.org/install) can be found on the Chocolatey website.

2. [Node Version Manager](https://github.com/coreybutler/nvm-windows) - Install different versions of node.

   ```
   > choco install nvm
   > nvm -v
   ```

3. [Git](https://git-scm.com/) Distributed Version Control System
   Install git then check to ensure the `git/user/bin` folder is in your path
   ```
   > choco install git
   > git -v
   > echo %PATH%
   ```
   
4. [Gulp](https://gulpjs.com/) - A toolkit to automate & enhance your workflow

   ```
   > choco install gulp-cli
   > npm install gulp
   ```

5. Run NVM to install version 11.x.x of NodeJS and check it. 
   *Some of the old projects I have repos for won't work with the latest version of Node w/o some changes*

   ```
   > nvm install 11
   > nvm use 11.0.0
   > node -v
   ```

---
