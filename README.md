# helm-charts

Repository to manage helm charts for our applications deployed on K8s

Before creating a pull request, user the below command locally for linting
## helm lint charts/<chart_name>

And also do a dry run before you start using it
## helm install digitalplan --dry-run --debug -f <values.yaml> charts/<chart_name>
