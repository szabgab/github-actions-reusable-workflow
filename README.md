# Reusable workflow

The `reusable.yaml` is a workflow that can be reused by other workflows.
This is accomplished by having `workflow_call` as a trigger.

[reusing_other_workflow.yaml](.github/workflows/reusing_other_workflow.yaml)

The `.github/workflows/reusing_other_workflow.yaml` file has a regular job
and then it also runs the jobs in the other file.

See another example where we reuse this workflow in [another repo](https://github.com/szabgab/github-actions-reuse-public-workflow).

See the full list of [GitHub Actions examples](https://code-maven.com/github-actions)

See also [reusing workflows](https://docs.github.com/en/actions/using-workflows/reusing-workflows)
