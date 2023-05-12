## To remove all old commits in Github, you can delete the .git directory in your project root (note that it’s hidden). Then initialize a new repository in the same folder and link it to the GitHub repository. 
Here are the steps:

- Delete the .git directory in your project root (note that it’s hidden).
- Initialize a new repository in the same folder by running git init.
- Add all files to the new repository by running git add ..
- Commit all files by running git commit -m "Initial commit".
- Link the new repository to your GitHub repository by running git remote add origin git@github.com:user/repo.
- Push the changes to your GitHub repository by running git push -u --force origin master.

### *Please note that this will remove all commit history from your repository and replace it with a single initial commit.*