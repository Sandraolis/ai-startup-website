# Part 3 Merging Changes

## Steps:

1. ### Switch to Tom's branch, Update-navigation: 
![branches](./images/banches.png)

2. ### Create new pull request:
![pull-request](./images/pull-request.png)

![pull-request-2](./images/pull-request-2.png)

# Updating Jerry's Branch with latest changes

## Steps:

1. ### Switch to Jerry's branch:

``` bash
git checkout add-contact-info
```
![checkout-branch](./images/checkout-branch.png)

2. ### Pull the changes from the main branch
``` bash
git pull origin main
```
![git-pull](./images/git-pull.png)

## Finalizing Jerry's Contribution

## Steps:
1. ### Push the updated version to github by following the github workflow

``` bash
git add .
```
![git-add](./images/git-add.png)

2. ### After staging it, then you commit it by running this command.

``` bash
git commit -m "pushing the updated version to github"
```
![git-commit](./images/git-commit.png)

3. ### Finally, you push the change to github with this command.
``` bash
git push origin add-contact-info
```
![git-push](./images/git-push.png)