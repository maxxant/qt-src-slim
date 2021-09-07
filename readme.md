# slim tarballs

Choose needs version from branch and download source tarball

branches:

- qt/5.7.1
- qt/5.9.9
- qt/5.11.3
- qt/5.12.11
- qt/5.15.2

## for developers notes:

https://stackoverflow.com/a/13969482

You can create an empty branch as an orphan:

git checkout --orphan branchname

This will create a new branch with no parents. Then, you can clear the working directory with:

git rm --cached -r .
