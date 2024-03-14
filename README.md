# AzureActionDeploy
Walkthrough Steps
Step 1>On Azure Portal > Create a resource group > Create a service principal > Assign Role > Get the secret
By running 
Create a service principal
az ad sp create-for-rbac --name "hhgithubactionazure" --role contributor --scopes /subscriptions/xxxxxxx232324cxxxxxxx/resourceGroups/honeyhlinegithubdeploy --sdk-auth

Step 2> Copy and Paste the secrets in the secret area.
Step 3> On VS Code git clone<your github repo link
Step 4> Edit in VS Code, Commit > Sync back to GitHub Repo
Step 5> Check the deploy status!
