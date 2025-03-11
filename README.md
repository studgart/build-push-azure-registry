# Build and Push to Azure Registry

- [Build and Push to Azure Registry](#build-and-push-to-azure-registry)
  - [Input Parameters](#input-parameters)
  - [Workflow Examples](#workflow-examples)
  - [Reference](#reference)
  - [Contributing](#contributing)

**Universal Actions** are GitHub Composite Actions that are highly reusable, maintainable and can adapt to work with multiple types of project. They are born to abstract the underlying commands and logics to achieve a specific task, enabling DevOps Engineers to focus on the most crucial parts of their implementation and reduce an amount of time to repeatedly write these actions.

**Build and Push to Azure Registry** is an Universal Action created to log into Azure, build and push Docker Image to Azure Container Registry (ACR).

## Input Parameters

| Parameter Name  | Required? | Type    | Default Value | Description                               |
| --------------- | --------- | ------- | ------------- | ----------------------------------------- |
| azure-registry  | true      | string  |               | Azure Container Registry DNS              |
| build-args      | false     | list    |               | A list of arguments to pass to the build  |
| client-id       | false     | UUID    | ""            | Azure Service Principal Client ID         |
| client-secret   | false     | UUID    | ""            | Azure Service Principal Client Secret     |
| creds           | false     | string  | ""            | Azure JSON Service Principal Credentials  |
| context         | false     | string  | "."           | The build context to use                  |
| dockerfile      | false     | string  | "Dockerfile"  | The location of Dockerfile                |
| image-name      | false     | string  | "app"         | The name of the image to build            |
| platform        | false     | string  | "linux/amd64" | The platform to build the image for       |
| push            | false     | boolean | "false"       | Whether to push the image to the registry |
| subscription-id | false     | UUID    | ""            | Azure Subscription ID                     |
| tag             | false     | string  | "latest"      | A tag for the Docker image                |
| tenant-id       | false     | UUID    | ""            | Azure Service Principal Tenant ID         |

## Workflow Examples

## Reference

## Contributing
