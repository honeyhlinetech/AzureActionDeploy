
![image](https://github.com/user-attachments/assets/05dd95b5-d69b-4270-a9b6-760d35c60073)


# AzureActionDeploy
Walkthrough Steps

Step 1>On Azure Portal > Create a resource group > Create a service principal > Assign Role > Get the secret
By running 

Create a service principal
```shell
az ad sp create-for-rbac --name "xxyourapp" --role contributor --scopes /subscriptions/xxxxxxx232324cxxxxxxx/resourceGroups/xx-rg --sdk-auth
```
Note: Option '--sdk-auth' has been deprecated and will be removed in a future release. In a future release, this command will NOT create a 'Contributor' role assignment by default. 

Step 2> Copy and Paste the secrets in the secret area.
![secret](https://github.com/user-attachments/assets/9bbf1a7a-27c8-4c43-a754-afa5d5b7b355)

Step 3> On VS Code git clone your github repo link.

Step 4> Edit in VS Code, Commit > Sync back to GitHub Repo.

Step 5> Check the deploy status!
