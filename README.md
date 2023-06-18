# Reusable workflow

The `reusable.yaml` is a workflow that can be reused by other workflows.
This is accomplished by having `workflow_call` as a trigger.

The `.github/workflows/reusing_other_workflow.yaml` file has a regular job
and then it alsoruns the jobs in the other file.

