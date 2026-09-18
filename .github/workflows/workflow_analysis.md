1. Thie workflow is run when either pushed to or pulled from the main branch
2. 
    1. Checkout code: Downloads code from repo
    2. Validate HTML files: Checks the syntax of index.html
    3. Check links: Ensures no links are broken
    4. Upload the built site for deployment: Saves the files between jobs
3. The checkout code grabs all the code from the repository, it's necessary to ensure that the latest version of your code is used when deploying.
4. Configuring enviornments is important to not only maintain security over certain aspects of your code (e.g. API keys), they also allow you to establish rules in which workflows will only proceed once followed.
5. Automated deployment both saves time and is more effective due to deployment checks being needed to be made everytime the main branch is updated. Having a person manually check everything both takes considerably longer and is susceptible to human error.
6. Nothing as the workflow is set to only trigger when the main branch is pushed/pulled