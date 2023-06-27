<!-- markdownlint-disable -->

## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| application | The application name | N/A | false |
| attributes | Comma separated attributes | N/A | false |
| environment | The environment name | N/A | true |
| implementation\_github\_pat | GitHub PAT that allows fetching environment action implementation | N/A | true |
| implementation\_path | Repository path with Environment action implementation | N/A | true |
| implementation\_ref | Ref of environment action implementation | N/A | true |
| implementation\_repository | Repository with Environment action implementation | N/A | true |
| namespace | The namespace | N/A | true |
| repository | The repository name | N/A | true |
| tenant | The tenant for the deployment | N/A | true |


## Outputs

| Name | Description |
|------|-------------|
| cluster | The cluster to deploy to |
| cluster-role | The IAM role to work with the cluster |
| platform-ssm-path | The path to the EKS cluster secrets in the SSM Parameter Store |
| name | The environment name |
| namespace | The namespace |
| region | The region |
| service-ssm-path | The path to the service secrets in the SSM Parameter Store |
| service-ssm-role | The IAM role to work with the secrets in the SSM Parameter Store |
<!-- markdownlint-restore -->
