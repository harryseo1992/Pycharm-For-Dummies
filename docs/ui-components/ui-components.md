---
layout: default
title: Linking to Github
nav_order: 3
has_children: false
permalink: /docs/ui-components
---

# Linking to Github
{: .no_toc}
PyCharm allows you to connect your GitHub account and manage your GitHub projects directly from PyCharm. This GitHub integration saves you time when managing and contributing to different GitHub repositories.
{: .fs-6 .fw-300 }

---
## TABLE OF CONTENTS
{: .no_toc .text-delta}
1. TOC
{:toc}
---

   **Recommended**
    {: .label .label-blue }
      Make sure you have an existing GitHub account before proceeding.

## Connect your GitHub account
1. From the project workspace, go to **File** -> **Settings** to access the main settings for PyCharm

    ![Connect-GitHub-Account-Step1](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccountLogIn-1.png?raw=true "File -> Settings")

2.  Go to **Version Control** -> **GitHub**. Click on the **+** button to add a GitHub account.

    ![Connect-GitHub-Account-Step2](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccountLogIn-2.png?raw=true "Version Control -> GitHub")

3.  Choose and click on either Option A or Option B to log-in to your GitHub account.

    ![Connect-GitHub-Account-Step3](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccountLogIn-3.png?raw=true "Log-in Options A and B")

    **STOP**
        {: .label .label-red } 
          PyCharm provides two options to add a GitHub account.
          A) Log-in with your GitHub credentials
          B) Log-in with a personal access token
    
    **RECOMMENDED**
        {: .label .label-blue }
            This guide recommends **Option A** as this option is the quickest method. Option B serves as an alternative method should you fail to log-in with Option A.
    
### Option A - Log-in with GitHub Credentials ###
1. Click **Log in via GitHub...**.

2. PyCharm will redirect you to another page. 

3. Enter your GitHub account credentials. If successful, PyCharm will automatically add your GitHub account. 

4. [Verify GitHub Account](#verify-your-github-account-log-in)

### Option B - Log-in with Personal Access Token ###
1. Go to [GitHub](https://github.com/) and log-in to your GitHub account.

2. Click on your profile picture located at the top right corner and click on **Settings** to access your account settings.

    ![GitHub-Account-Settings](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccessTokens-1.png?raw=true "GitHub Account Settings")

3. Click on **Developer Settings** located at the bottom of **Account Settings**.

    ![Developer-Settings](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccessTokens-2.png?raw=true "Developer Settings")

4. Click on **Personal access tokens** -> **Generate new token**.

    ![Generate-New-Token](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccessTokens-3.png?raw=true "Generate New Token")

5. Create a suitable name for this access token (eg. pyCharmToken). Check the box for the following scope options: **repo**, **workflow**, **read:org**, and **gist**

    ![Access-Token-Settings](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccessTokens-4.png?raw=true "Access Token Settings")

    **STOP**
        {: .label .label-red }
            Make sure that **repo**, **workflow**, **read:org**, and **gist** are checked off.
            The access token may not work correctly if these four scope options are not selected.   

6. Press **Generate Token** to confirm your access token settings.

7. Copy the access token by clicking on the <span style="color:blue">blue clipboard icon</span>.

    ![Copy-Access-Token](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccessTokens-5.png?raw=true "Copy Access Token")
    
    **CAUTION**
        {: .label .label-yellow }
            Keep your access tokens confidential as the tokens provide access to your GitHub account!
            For security reasons, this newly generated token is **ONE TIME ACCESS** only. 
            Ensure you have copied the key or you will have to generate another access token.

8. In PyCharm, click **Log in with Token...**.

9. Paste your access token in the box and presss **Add Account**. 

    ![Paste-Access-Token](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccountLogIn-4.png?raw=true "Paste Access Token")

10. [Verify GitHub Account in the next step.](#verify-your-github-account-log-in)

### Verify your GitHub Account Log-in
1. Confirm your GitHub account details displayed next to the light blue arrow. Press **Apply** and press **OK** to save your changes. 

    ![Connect-GitHub-Account-Step4](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-AccountLogIn-5.png?raw=true "Confirm Settings")

## Control multiple GitHub accounts
1. Add multiple GitHub accounts by pressing the **+** button and follow the same steps as described in [the previous section](#connect-your-github-account).

  ![Control-GitHub-Accounts](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-MultipleAccounts.png?raw=true "Control GitHub Accounts")

2. Delete a GitHub account by selecting the intended account and press the **-** button.

3. Set a default GitHub account be selecting the intended account and press the **check** button.

## Share your project on GitHub

**STOP**
    {: .label .label-red }
        You must have linked an active GitHub account before proceeeding.
  
1. Select and open the intended project that you want to share.

2. From the project workspace, go to **VCS** -> **Share Project on GitHub**.

    ![VCS-Settings](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-ShareProject-1.png?raw=true "VCS -> Share Project on GitHub")

3. In the new window, provide the following project information to create a repositiory on GitHub.

    ![Project-Information](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-ShareProject-2.png?raw=true "Project Information")
    
    1. Give a name for the repository where your project will be located on GitHub.
    
    **STOP**
        {: .label .label-red }
            You have the option to set the your repositoriy visibilty to private by checking **Private** on the right hand side.
   
    2. Provide a project description.
    
    3. Press **Share** to confirm your changes.

4. Provide a commit message and press **Add** to add the project files to the repositiory.

    ![Commit-Message](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-ShareProject-3.png?raw=true "Commit Message")

5. Wait for PyCharm to upload your project files to the GitHub repository. A window will pop-up in the lower right hand corner to indicate your project has been succesfully shared on GitHub.

    ![Shared-Project-Confirmation](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-ShareProject-4.png?raw=true "Shared Project Confirmation")

6. To verify your project, click on the project name in the above screenshot. You will be directed to the GitHub project repository.

    ![Project Repositiory](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-ShareProject-5.png?raw=true "Project Repositiory")

## Clone an existing project to Pycharm
1. Go to the GitHub repository page of an existing project.

2. Click on the <span style="color:green">**CODE**</span> button to access the git url. Click on the clipboard icon to copy the url.

    ![Copy-Git-URL](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-CloneRepo-1.png?raw=true "Copy Git URL")

3. From the PyCharm welcome page, click on **Get from VCS** to access the Version Control settings.

    ![VCS](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-CloneRepo-2.png?raw=true "VCS")

4. Click on **Repository URL**. Select the **Git** option for Version control.

    ![Paste-Git-URL](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/Link-GitHub-CloneRepo-3.png?raw=true "Paste Git URL")

5. Paste the copied git url from Step 2 into the **URL box**.

6. Select where the cloned project will be stored in your directory.

7. Press **Clone** to copy the GitHub project to your computer.

8. Success! You have now cloned an existing GitHub project to your local computer.
