# Contributing to Satus

First off, thank you for considering contributing to Satus! It's people like you
that make Satus such a great community.

## Where do I go from here?

If you've noticed a bug or have a feature request,
[make one](https://github.com/satusdev/issues/new)! It's generally best if you
get confirmation of your bug or approval for your feature request this way
before starting to code.

### Fork & create a branch

If this is something you think you can fix, then fork Satus and create a branch
with a descriptive name.

A good branch name would be (where issue #33 is the ticket you're working on):

```bash
git checkout -b 33-add-new-feature
```

### Get the style right

Your patch should follow the same conventions & pass the same code quality
checks as the rest of the project.

### Make a Pull Request

At this point, you should switch back to your master branch and make sure it's
up to date with Satus's master branch:

```bash
git remote add upstream git@github.com:satusdev/satus.git
git checkout master
git pull upstream master
```

Then update your feature branch from your local copy of master, and push it!

```bash
git checkout 33-add-new-feature
git rebase master
git push --force origin 33-add-new-feature
```

Finally, go to GitHub and make a Pull Request.

### Keeping your Pull Request updated

If a maintainer asks you to "rebase" your PR, they're saying that a lot of code
has changed, and that you need to update your branch so it's easier to merge.

To learn more about rebasing and merging, check out this guide on
[merging vs. rebasing](https://www.atlassian.com/git/tutorials/merging-vs-rebasing).
