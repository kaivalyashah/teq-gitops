This repo is the source of truth for Kubernetes deployments (GitOps).
Argo CD watches specific paths under ./environments/<env>/<service>.

Structure:
- environments/
  - dev/
    - product/
      - deployment.yaml
      - service.yaml
  - prod/
    - product/
      - deployment.yaml
      - service.yaml
