# slim tarballs

Choose needs version from branch and download source tarball

branches:

- qt/5.15.2

## 4developes notes:


You can create an empty branch as an orphan:

git checkout --orphan <branchname>

This will create a new branch with no parents. Then, you can clear the working directory with:

git rm --cached -r .
