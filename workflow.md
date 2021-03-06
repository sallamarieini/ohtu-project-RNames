# Way of working 

Description of the workflow in this project.

## Before starting new work

Check Slack, product backlog and sprint backlog. See what has happened before starting any new work to stay up to date.

## Start a new task

* Check out the task you want to start working on from the sprint backlog and change the status to *in progress*.
* Remember to keep your fork up to date with the original repo! See [this](https://docs.github.com/en/github/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) for instructions.
* Code the task. Create a new branch for the feature/task: `git checkout -b your-branch-name`.

### When starting your first task

1. Fork the [repository](https://github.com/karilint/rnames) and clone the fork (not the original repository). [More info](https://docs.github.com/en/get-started/quickstart/fork-a-repo#cloning-your-forked-repository)
2. Configure git to sync the fork with the original repository. More detailed instructions can be found [here](https://docs.github.com/en/github/collaborating-with-pull-requests/working-with-forks/syncing-a-fork).
3. Create a new branch for the feature you're developing with `git checkout -b your-branch-name`

### Several people doing the same task?

Add co-author(s)! Check out [these instructions](https://docs.github.com/en/github/committing-changes-to-your-project/creating-and-editing-commits/creating-a-commit-with-multiple-authors).

## Task is done

When the coding for the task is done, follow these steps.
1. Once you've finished implementing a feature, push the changes to your fork with `git push -u origin your-remote-branch-name`
2. Go to https://github.com/karilint/rnames/pulls and click New pull request. Click "compare across forks", select your repository and branch on the right, and create new pull request. Add an appropriate title and description as required.
3. Request a review from another project member. Wait for the review. If changes are requested, commit them to the same branch and re-request a review.
4. Once approved, merge the PR. On the pull request page, make sure the merge commit option is selected in the merge button dropdown before merging.

## When you are asked to review a pull request
* Reviews are done through the `Files changed` tab of the PR.
* Go through the changes.
* Write comments to the PR and request changes if needed. Inform the opener of the PR that the PR has been reviewed.
  * When the requested changes have been made, review the PR again and make comments if necessary.
* Mark the PR approved if/when the PR is ready to be merged and inform the opener about the approval.

## Miscellanious notes
* Remember to keep your fork's branches up to date with the upstream repository. This can be done in many ways, e.g.
* Syncing with the click of a button on your fork's github page
* Setting up a second [remote](https://docs.github.com/en/github/collaborating-with-pull-requests/working-with-forks/configuring-a-remote-for-a-fork) and [pulling changes from it](https://docs.github.com/en/github/collaborating-with-pull-requests/working-with-forks/syncing-a-fork)
* Pulling changes into your current branch without setting up a remote with `git pull REPOSITORY BRANCH`, for example, `git pull git@github.com:karilint/rnames.git master`
