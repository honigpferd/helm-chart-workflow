# helm-chart-workflow
a workflow to lint test and release helm charts

## usage
reuse this github workflow with `.github/workflows/<my_workflow>.yaml`
```YAML
name: <myWorkflow>

on: <myTriggers>

jobs:
  <my-helm-chart-workflow>:
    uses: honigpferd/helm-chart-workflow/.github/workflows/helm-chart.yml@v1
