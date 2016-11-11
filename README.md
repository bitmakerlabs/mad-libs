# Mad Libbing

## Getting started
* Get into groups
* One person forks the Mad Libs repo
  * https://github.com/bitmakerlabs/mad-libs
* Owner adds teammates as collaborators with write access
* Everyone in the group clones the repo

## Exercise
* Everyone makes a feature branch
* Follow the usual edit-stage-commit process
* When finished,
  * Switch back to master and pull to get the latest code
  * Merge your feature branch into master
  * If there are conflicts, resolve them first




CONSOLE NOTES - BRANCHES

- Connor-Offutts-MacBook-Pro:mad-libs  - ConnorOffutt$ cd mad-libs/
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ ls
-README.md	mad-libbing.txt
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git branch
-* master
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git branch test
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git branch
-* master
-  test
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git remote rm origin
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git remote -v
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git remote add origin -git@github.com:connoroffutt/mad-libs.git
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git remote -v
-origin	git@github.com:connoroffutt/mad-libs.git -(fetch)
-origin	git@github.com:connoroffutt/mad-libs.git -(push)
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git checkout test
-Switched to branch 'test'
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git branch
-  master
-* test
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git checkout master
-Switched to branch 'master'
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git branch
-* master
-  test
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git checkout -b cool-name
-Switched to a new branch 'cool-name'
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git branch test
-fatal: A branch named 'test' already exists.
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git checkout test
-Switched to branch 'test'
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git branch
-  cool-name
-  master
-* test
- ConnorOffutt$ git branch -D test
-error: Cannot delete branch 'test' checked out -at -'/Users/ConnorOffutt/desktop/bitmaker/mad-libs/mad-libs'
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git checkout master
-Switched to branch 'master'
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git branch -d test
-Deleted branch test (was 7faf2d1).
-Connor-Offutts-MacBook-Pro:mad-libs -ConnorOffutt$ git branch -D cool-name
-Deleted branch cool-name (was 7faf2d1).
-Connor-Offutts-MacBook-Pro:mad-libs
