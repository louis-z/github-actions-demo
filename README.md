# Project to test GitHub actions

## Workflows

A workflow is an automated procedure, made up of one or more jobs, that can be scheduled or triggered by an event.

## Events

An event is a specific activity that triggers a workflow. Such an activity can, for instance, originate from GitHub when someone pushes a commit to a repository. You can also use the repository dispatch webhook to trigger a workflow when an external event occurs.

## Jobs

A job is a set of steps that execute on the same runner. By default, a workflow with multiple jobs will run those jobs in parallel, but you can configure it to run jobs sequentially.

## Steps

A step is an individual task that can run commands. A step can be either an action or a shell command. Each step in a job executes on the same runner, allowing the actions in that job to share data with each other.

## Actions

Actions are standalone commands that are combined into steps to create a job. Actions are the smallest portable building block of a workflow. You can create your own actions, or use actions created by the GitHub community.

## Runners

A runner is a server that has the GitHub Actions runner application installed. A runner listens for available jobs, runs one job at a time, and reports the progress, logs, and results back to GitHub. GitHub-hosted runners are based on Ubuntu Linux, Microsoft Windows, and macOS, and each job in a workflow runs in a fresh virtual environment.