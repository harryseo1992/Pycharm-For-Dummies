---
layout: default
title: Working with Version Control
nav_order: 6
---

# Working with Version Control
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

--- 

## Pull from Existing Repository       
                                        
As you learn how to code, you soon realize that there will be a lot of group coding involved. As such, it is important to be aware of certain practices when it comes to version control. One of them happens to be **_"Pull first, make changes and commit later"_**. Therefore, we will go over how to pull first before we get to committing and pushing changes.

### Steps

1. Press the _update project button_.
    
    ![pulling](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/update_project.png?raw=true "Update project button")


2. Check off _Merge incoming changes into the current branch_ then press _ok_.
    
    ![merging](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/merge_project.png?raw=true "Merge project")

    **Recommended**
    {: .label .label-blue } 
            "Rebase the current branch on top of incoming changes" will 
            also integrate changes from one branch to another. However, rebasing
            can be dangerous because it can "rewrite history" of shared branches.
            Therefore, it is better to _Merge incoming changes_ instead.


Congratulations! You should see a pop-up that indicates successful project update.

![success](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/update_success_real.png?raw=true "Updated project")

---

## Committing and Pushing Changes       


We have all experienced losing our saved work whether by forgetting where we have put them or messing up so bad the file got corrupted. It is also important to save your work when coding as well. To do that, you need to *commit* the changes you have made and *push* the changes to the repository you have cloned.

### Steps


If you see your files change colour as highlighted below, it means there are changes made that is not saved.       

![committing_changes](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/commit_highlighted.png?raw=true "committing changes")


As highlighted below, you will see 3 shapes on the top right of your PyCharm.

1. Press the *Check-mark shape* to commit.

    ![committing_changes](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/commit_button_highlighted.png?raw=true "committing changes")


2. Check the files you want to save.

    ![committing_changes](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/commit_message_highlighted.png?raw=true "committing changes")


3. Fill out the changes you have made to those files.

    ![committing_changes](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/commit_message_filledout.png?raw=true "committing changes")

    Simple descriptions that others can understand what changes you have made are best.

    **CAUTION**
    {: .label .label-yellow }
            You may choose to press "commit" here to simply commit the changes you have made. 
            However, in order to SAVE the changes you have made to a repository that you cloned from,    
            you must also "push" the changes you made as well. The next step will entail "pushing" changes.
   
4. Press the downward arrow next to *commit button*.

    ![committing_changes](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/commit_and_push.png?raw=true "committing changes")

    You will be led to a new window detailing what will be pushed.

5. Press *commit and push* and then _push_.

    ![committing_changes](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/commit_and_push_finally_pushing.png?raw=true "committing changes")


Congratulations! You committed and pushed the changes you made to the files! 

---

**Recommended**
{: .label .label-blue } 
    It is a good practice to commit and push often;   
    Committing and pushing after coding a function is ideal.

## Side-note
{: .d-inline-block }
**CAUTION**
{: .label .label-yellow }
If you have run into this error above, it means the repository has changes that your local files have not received yet. You can press _Merge_ here to push and update your current files. However, it is good practice to **pull first** before committing and pushing.

![merge_conflict](https://github.com/harryseo1992/Pycharm-For-Dummies/blob/gh-pages/assets/images/merge_conflict.png?raw=true "conflict")

---


