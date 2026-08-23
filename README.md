# CI/CD Pipeline Concepts

A reference of the stages and terminology involved in building a modern
**Continuous Integration / Continuous Delivery** pipeline, including GitOps-style
environment promotion.

## What's inside

- `The-CI-Stages.txt` — the stages of a CI pipeline (checkout, setup, build, test).
- `The-CD-Stages.txt` — the stages of a CD pipeline (staging, promotion, deploy).
- `The-Release-Stages.txt` — how releases are packaged and promoted.
- `CI-CD-Playbook.txt` — an end-to-end playbook tying the stages together.
- `GitOps-CI-CD-Pipeline-steps.txt` — a GitOps-flavoured CI/CD flow.
- `ReleaseFlow.txt` / `ReleaseFlow2.txt` — alternative release flow diagrams.
- `gitops_env_promotion.txt` — promoting environments through GitOps.
- `gitops_post_deployment_guide.md` — post-deployment verification and rollback.
- `Tools.txt` — the tooling typically used at each stage.
- `Youtube-CI-CD.txt` — linked video walkthroughs.

## What you'll learn

- The distinct responsibilities of CI vs CD.
- How to structure build, test, and deploy stages for feature branches and trunk.
- How GitOps shifts deployment to a pull model from a Git repo.
- How environments are promoted (dev → staging → prod) safely.

## Tools covered

- Jenkins (declarative pipelines), GitOps controllers (Argo CD), CI/CD tooling.

## How to use

Read `The-CI-Stages.txt` and `The-CD-Stages.txt` for the conceptual model, then
`CI-CD-Playbook.txt` for how they fit together in a real pipeline.

## Related

- The Twelve-Factor App: https://12factor.net/
