<!-- markdownlint-disable -->

## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| application | Application name | N/A | false |
| attributes | Comma separated attributes | N/A | false |
| environment | Environment name | N/A | true |
| implementation\_github\_pat | GitHub PAT allow fetch environment action implementation | N/A | true |
| implementation\_path | Repository path with Environment action implementation | N/A | true |
| implementation\_ref | Ref of environment action implementation | N/A | true |
| implementation\_repository | Repository with Environment action implementation | N/A | true |
| namespace | Namespace name | N/A | true |
| repository | Repository name | N/A | true |
| tenant | The tenant for the deployment | N/A | true |


## Outputs

| Name | Description |
|------|-------------|
| cluster | The cluster to deploy to |
| cluster-role | The IAM role to work with the cluster |
| cluster-ssm-path | Path to the cluster ssm secrets |
| name | Environment name |
| namespace | Namespace |
| region | The region |
| secrets-ssm-role | The IAM role to work with the secrets in the SSM Parameter Store |
<!-- markdownlint-restore -->
