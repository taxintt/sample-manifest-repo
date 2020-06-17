[![CircleCI](https://circleci.com/gh/TaxiN/sample-manifest-repo.svg?style=svg)](https://circleci.com/gh/TaxiN/sample-manifest-repo)
# Demo: CI/CD pipeline

## Abstract
This is the sample of CI/CD pipeline with Circle CI and Kustomize.<br>
Please refer to [Application code repository](https://github.com/TaxiN/sample-app-ci).<br>


```
├── .circleci
|   └── config.yml
├── base
│   ├── deployment.yaml
│   └── kustomization.yaml
└── overlays
    ├── staging
    │   ├── deployement-patch.yaml
    │   └── kustomization.yaml
    └── production
        ├── deployement-patch.yaml
        └── kustomization.yaml
```