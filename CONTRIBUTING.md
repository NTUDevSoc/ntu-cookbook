If you're reading this document, then it's (somewhat!) safe to assume that you're familiar(ish) with git, and working with github repositories. In that case:

1. If you haven't already, fork the `ntu-cookbook` repository by clicking on the fork button, as shown below:
   ![Fork]()
2. Install git. Create a new folder called `ntu-cookbook` on your computer and write `git clone https://github.com/<your username here>/ntu-cookbook.git` while in that directory you've just created.
3. Make sure you're on the `main` repository (`git checkout main`) and pull the repository to a directory using `git pull`.
4. Create a new branch named after your recipe (`git checkout -b [branch-name]`) and make sure to follow these guidelines:
     - Create a new folder within the `recipes` directory with the name of your recipe (e.g. `recipes/omelette`).
     - Within this folder, create the `assets` folder (to store multimedia), and copy `TEMPLATE.html` into this directory. 
5. Begin working on your new recipe by editing the template.    
   - Remember to place any images or other media into the assets folder and refer to them within your HTML page's code.
6. Push the changes to the remote branch (`git push -u https://github.com/<your username here>/ntu-cookbook [branch-name]`)
7. Create a pull request on github requesting for your fork to be merged with the upstream repository, where the request will be reviewed and integrated into the main website.