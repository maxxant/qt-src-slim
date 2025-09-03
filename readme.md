# slim tarballs

Choose the required version from a Git branch and download the source code tarball

branches:

- qt/5.7.1
- qt/5.9.9
- qt/5.11.3
- qt/5.12.11
- qt/5.15.2
- qt/5.15.12
- qt/5.15.17

## for developers notes:

https://stackoverflow.com/a/13969482

You can create an empty branch as an orphan:

git checkout --orphan branchname

This will create a new branch with no parents. Then, you can clear the working directory with:

git rm --cached -r .
