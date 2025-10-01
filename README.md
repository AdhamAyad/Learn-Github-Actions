# Learn GitHub Actions

This repository contains **practice workflows** for learning GitHub Actions.  
Each workflow file demonstrates different features, triggers, and use cases.

## Workflows Overview

| Workflow File                 | Description |
|--------------------------------|-------------|
| `actions.yaml`                 | Basic actions and usage examples. |
| `command_variables.yaml`       | Using commands and variables in workflows. |
| `docker.yaml`                  | Docker build & push examples. |
| `dotnet_CI.yaml`               | CI workflow for .NET projects. |
| `expressions.yaml`             | Examples of expressions and conditional steps. |
| `jobs.yaml`                    | Examples of jobs, dependencies, and strategies. |
| `main.yml`                     | Main workflow example. |
| `reuse_workflow.yaml`          | Demonstrates **reusable workflows**. |
| `self_hosted.yaml`             | Self-hosted runner setup & usage. |
| `star.yaml`                    | Example workflow using `on: star` trigger. |
| `Triggers.yaml`                | All types of workflow triggers explained. |

## Key Concepts Covered

- Workflow triggers: `push`, `pull_request`, `workflow_dispatch`, `repository_dispatch`, `schedule`, and `workflow_call`.
- Jobs and steps, including **matrix strategies**.
- Self-hosted runners setup and labels.
- Artifacts for passing files between jobs.
- Code scanning with **CodeQL**.
- Docker integration in workflows.
- Expressions, variables, and reusable workflows.

## How to Use

1. Clone this repository:  
   ```bash
   git clone https://github.com/AdhamAyad/Learn-Github-Actions.git
   cd Learn-Github-Actions
2. Browse `.github/workflows/` to explore each workflow file.  
3. Copy or adapt any workflow to your own repositories to test or practice.

## Notes

- Each workflow file demonstrates a **specific feature**; names reflect their purpose.  
- Many workflows include examples of **inputs, matrix jobs, and reusable workflows**.  
- Use self-hosted workflows with proper **labels and runner setup** if required.

---

Happy learning GitHub Actions! 🚀
  
   
