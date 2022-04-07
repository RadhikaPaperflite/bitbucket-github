# bitbucket-github
migrate repo from bitbucket to github


      First of all, choose one repository which want to migrate bitbucket to github,

      And then make sure all necessary data is in the repository.

      Next, we want to clone the choosen repository in local,using the --mirror parameter.
      follow the below comment to clone repository from bitbucket.

          //git clone --mirror <Bitbucket_repo_address>//

      Now we got a repository in local.
      
      Now we have the bitbucket repository,next we need to replace the remote origin address	
      so follow the below mentioned comment to replace the remote address

      In github, copy the URL and paste it in below comment.

          //git remote add origin <GitHub_repo_address>//
      
      Neccessary to know we have all the branches in local mechine.so, run the below comment

          //git branch//

      So we have one last thing to do, which is syncing the local copy with the new target repository address in GitHub.

          //git push --mirror//

      After completing all the steps, now check the result in GitHub.
      
