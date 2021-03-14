If you're reading this document, then it's (somewhat!) safe to assume that you're familiar(ish) with git, and working with github repositories. In that case:

1. If you haven't already, install git. Create a new folder called `ntu-cookbook` on your computer and write `git clone https://github.com/NTUDevSoc/ntu-cookbook.git` while in that directory you've just created.
2. Make sure you're on the `new-recipes` repository (`git checkout new-recipes`) and pull the repository to a directory using `git pull`.
3. Create a new branch named after your recipe (`git checkout -b [branch-name]`) and make sure to follow these guidelines:
     - Create a new folder within the `recipes` directory with the name of your recipe (e.g. `recipes/omelette`).
     - Within this folder, create the `assets` folder (to store multimedia), and copy `TEMPLATE.html` into this directory. 
4. Begin working on your new recipe by editing the template.    
   - Remember to place any images or other media into the assets folder and refer to them within your HTML page's code.
5. Push the changes to the remote branch (`git push -u https://github.com/NTUDevSoc/ntu-cookbook [branch-name]`)
6. Create a pull request on github requesting for your branch to be merged with the `new-recipes` repository, where it will be reviewed and integrated into the main website.