# Mirai
###### the Multijudge Independently Rebuilt Asynchronous Interface

## Getting started
You will need to be familiar with [Repo](https://source.android.com/source/using-repo.html) and [Git](https://git-scm.com/).

If you're on Linux, you can use the [default `repo` script provided by the Android Open Source Project](https://source.android.com/setup/build/downloading#installing-repo). On Windows, [git-repo](https://github.com/esrlabs/git-repo) can be used (untested though).

To initialize your local repository with Mirai's trees, use something like this :
```
repo init -u https://github.com/vnma0/mirai-repo
```
Then to sync up everything :
```
repo sync
```
