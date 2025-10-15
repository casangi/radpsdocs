# How to build and update these docs


## Read-the-docs and github

Opening a new pull request (PRs) will trigger the docs to build on read-the-docs. The success of the build will be reported back in the PR with a link to the rtd build log.


## Local

Local builds require python >= 3.11 with the following packages installed (see the `requirements.txt` file in the repository):
- sphinx>=6.0
- myst-parser
- sphinx-rtd-theme

Then to build these docs:
1. Clone the repository (https://github.com/casangi/radpsdocs). Switch to the `radpsdocs` directory.
2. Run `make`. The local build and HTML files will be placed in `docs/_build/`.


## Contributing to the documentation

Contributions should follow the the [git feature branch workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow).

This includes:
1. Create a fork of the branch (if one does not exist).
2. Locally, clone the forked repository. Add the parent repository to the remote repositories (see [this guide](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/configuring-a-remote-repository-for-a-fork)).
3. Create a new feature branch. Update and commit to the feature branch.
4. Push the feature branch to your fork: `git push origin feature_branch`. Via github, open the PR to trigger the RTD build.
5. Further commits should be pushed to the same feature branch.
