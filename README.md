Instructions on how to use GitHub

Create an issue in the Github repository. The issue should be 'Add {your name', e.g., 'Add Xinjian'. Note the issue number.

Clone the repository: git clone https://github.com/xinjianguosccs/hello-world.git

Create a new branch. Name it after yourself to avoid conflicts: cd hello-world; git checkout -b xinjian

Edit the README.md file and add an entry under Team Members, Add Xinjian

Tell Git that you want to include the file in the next commit: git add README.md

Commit the file to your local repository. Supply the number of the issue that you created above: git commit -m "Adding Xinjian, Closes #1"

Push the change to the remote repository: git push origin xinjian

Log in to the Github interface and you should be able to create a pull request.

Issue #4: Add Xinjian
