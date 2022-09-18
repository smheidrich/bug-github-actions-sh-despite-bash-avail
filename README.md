**NEVERMIND,** they do explain it
[here](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#jobsjob_idcontainer):

>Note: The default shell for run steps inside a container is sh instead of
bash. This can be overridden with jobs.<job_id>.defaults.run or
jobs.<job_id>.steps[*].shell.

# bug-github-actions-sh-despite-bash-avail
Minimal example for GitHub Actions bug: Commands run in sh despite bash being available
