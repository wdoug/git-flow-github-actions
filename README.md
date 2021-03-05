> NOTE: This repo was originally forked from https://github.com/thomaseizinger/github-action-gitflow-release-workflow. Due to the way github actions work on forks, however, I decided to switch this to be just a copy instead of a fork.

At this point, however, it has completely diverged from the original.

# GitFlow release workflow using GitHub actions

This repo is a demo of one way to set up github actions to automate some of the steps of [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow).

For preparing releases of the `dev` branch, run the `Prepare new release` workflow. This will create a new release branch and open a pull request against the `production` branch.

For any pull requests merged into the `production` branch the version will be incremented and a GitHub release and tag will be created.
