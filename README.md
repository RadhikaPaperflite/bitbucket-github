# Migrating repository from BitBucket to GitHub
Select BitBucket repository and make sure committed all the changes.

1. Clone the BitBucket repository in your local.
 
   `git clone --mirror <Bitbucket_repo_address>`

2. Create a repository in GitHub
    
    In the upper-right corner of GitHub page, use the ` + ` drop-down menu, and select New repository.
    
3. Change remote origin address	

   `git remote add origin <GitHub_repo_address>`

4. List and confirm all the branches

   `git branch -a`
      
5. Finally push changes into GitHub repository

   `git push --mirror`
