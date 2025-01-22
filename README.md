# webpack_practice
Practicing webpacks
when working with packages that are installed with npm, we dont need to track the contents of nde_modules with git, nor push these files to github like i did here. Because the package.json file contains all the dependency iformation, so that anyone can clone the project and install them on their machine using npn install.
instead we can make .gitignore file in the root of the project, and by writing file or directory names in it, we can tell git what things we dont want to track. its custoary to add node_modules to .gitignore, since it can get really big.
Similarily, dist(distributuon file) is also often ignored as it can be generated when someone runs the command to bundle/build application.
When creating a new repo on github, there is an option to specify a .gitignore template.
