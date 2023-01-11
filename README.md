# Dependabot Demo Repository

Setting to enable in the repo

1. Enable Auto Merge -> Go to "https://github.com/[organization]/[repo]/settings" at Pull Requests and check "Allow auto-merge"
2. Enable or check "Allow GitHub Action to create and approve pull request" in https://github.com/[organization]/[repo]/settings/actions
3. Add Branch projection rules -> Go to "https://github.com/Uchehens/copy-directory/settings/branches" in "Protect matching branches" enable "Require a pull request before merging" and then enable "Require approval" and select 1 approver.
4. Add Branch projection rules -> Go to _https://github.com/Uchehens/copy-directory/settings/branches_ in "Protect matching branches" enable "Require status checks to pass before merging" and then enable "Require branches to be up to date before merging" and select all the pipeline that must pass before the pull request will be merged with the main branch
5. Remember to enter the branch name before saving.
6. To identify the projects use labels in the dependabot and verify the label in the CI pipeline and provide the appropriate folder path.

Read More: https://nicolasiensen.github.io/2022-07-23-automating-dependency-updates-with-dependabot-github-auto-merge-and-github-actions/#:~:text=To%20enable%20this%20feature%2C%20we,a%20new%20branch%20protection%20rule
