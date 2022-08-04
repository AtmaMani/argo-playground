# Argo workflow playground
Workflows and templates for [Argo](https://argoproj.github.io) workflow engine. 

## How to use this repo
The `simple-wf-templates` folder contains a number of workflow templates which are a good starting point for creating workflows in argo. For any given workflow, use `kubectl` or `argo` CLI to submit as shown below:

```yaml
(base) ➜  ~ k create -n argo-local -f wf-hello-world.yaml 
workflow.argoproj.io/hello-world-p4wlj created
```

For more resources on this, go to [Argo workflows for Kubernetes](https://atmamani.github.io/projects/cloud/argo/)

### Challenges and solutions
 - `ex1-simple-flow` folder has a simple folow chart that is solved a DAG workflow.