my-new-project
  

Q1:how to remove them locally and remotely?

To delete a local branch:
    git branch -d branch_name
If the branch has unmerged changes and you want to force delete
    git branch -D branch_name
To delete a remote branch:
    git push origin --delete branch_name

Q2:CheckOut Another Branch Without Committing Changes?

    git stash
    git checkout branch_name

    Q3:how to list tags ?

    GIT TAG

    Q4: how to delete tag locally and remotely ?

    localy 
    git tag -d "tag name"
    remotly
    git push origin --delete "tag name"




![CR7](images.jpeg)


