# GitHub Steps

Describe in your own words how to establish a connection between a local repository and a remote repository on GitHub.
> So first you need to create the repository on github with what ever name you want, then navigate through terminal to where you want to store your repository locally, the run the following commands:


`$ git remote add origin git@github.com:USERNAME/REPO_NAME.git`
> Tells your local repo to set the *remote* repo to this address; also called origin.


`$ git branch -M main`
> Names the default branch as main if not already configured.


`git push -u origin main`
> Sends current *local* version of repo to *remote* version of repo and sets main branch as default branch to send work up to.