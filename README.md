![Banner (2)](https://github.com/user-attachments/assets/6c7cd956-5f11-4396-87b1-82db2f292f2f)
Getting Started:
===============

To get started with Project Flare, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/Project-Flare/android -b 15 --git-lfs
```

Then to sync up:

```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

---------------------------------------------------------------------------------------
Compilation of Project Flare:
==================

From root directory of Project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch flare_$device-ap4a-userdebug
$ make bacon
```
---------------------------------------------------------------------------------------

# Credits:

 * [**LineageOS**](https://github.com/LineageOS)
