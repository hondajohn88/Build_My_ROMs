# Build-Mi Mix 2
Manifest for Xiaomi MI Mix 2

To build: repo init -u https://github.com/hondajohn88/Build_Xiaomi_ROMs -b staging/lineage-15.1

LineageOS
Submitting Patches
Patches are always welcome! Please submit your patches via LineageOS Gerrit. You can do this by using these commands:

(From root android directory)
. build/envsetup.sh
(Go to repo you are patching, make your changes and commit)
lineagegerrit <for(new)/changes(patch set)> <branch/change-id>

repo start lineage-15.1 .
(Make your changes and commit)
repo upload .
Note: "." means the current directory For more help on using this tool, use this command: repo help upload

Make your changes and commit with a detailed message, starting with what you are working with (i.e. "vision: Update Kernel") Commit your patches in a single commit. Squash multiple commits using this command: git rebase -i HEAD~<# of commits>

To view the status of your and others' patches, visit LineageOS Code Review

Getting Started
To get started with Android/LineageOS, you'll need to get familiar with Git and Repo.

To initialize your local repository using the LineageOS trees, use a command like this:

repo init -u git://github.com/LineageOS/android.git -b staging/lineage-15.1
Then to sync up:

repo sync
Please see the LineageOS Wiki for building instructions.

Buildbot
All supported devices are built weekly and periodically as changes are committed to ensure the source trees remain buildable.

You can view the current build statuses at LineageOS Jenkins

Builds produced weekly by the buildbot can be downloaded from LineageOS downloads
