# Technichal test for Devops position at Connecting Food
## Tasks
Create a Github Actions worfklow that will:
* Build and push a Docker image running the Django app in app directory
* Deploy it the Kubernetes cluster (kubeconfig provided in email) using a simple helm chart, with deployment and service objects
## Submission
Helm chart and workflow should be saved on a private `candidate/connecting-food-devops-test` repository on your github account.
Access should be granted to 2 members of the `connecting-food` group:
* <https://github.com/nicolasramy>
* <https://github.com/nmilon-cf>
## Expected repo structure
```bash
$ tree .
.
├── .github
│   └── workflows
│       └── workflow.yml
├── app
└── helm
    └── Chart.yaml
    └── values.yaml
    └── templates
```