# node-reference

## NODE
Node provides a server-side environment that can handle logic written in JavaScript.

## Node Package Manager (npm)
NPM is a package manager that is used to install or uninstall Node packages from the working directory. 

## Node Packages
Node packages are javaScript files that can be installed in our working directories to add functionality to our current files. Commonly, Node packages are added to increase efficiency in build time and help get a project up and running without having to rewrite several commonly used functions. 

###

## Setting up a Node Package
1. Once we have a directory that we want to inititialize the npm, we run the following command in our terminals:

`npm init -y`

(the -y flag says yes to the default settings)

2. This will create a .json file that the contains the values of the npm. Now we must create the default file that npm is looking for:

`touch index.js`

3. You can now install node packages by running:

`npm i <package name>` 

4. **IMPORTANT!** If the directory we are working in is a github repo, we must tell git to ignore the files installed in the node_module directory. We can do this by running:

`echo "node_modules" >> .gitignore`

6. Now that our packages are installed, we import the module into our index.js file by using:

`const <variable name> = require('<package name>)`