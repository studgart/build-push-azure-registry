# Build and Push to Azure Registry

- [Build and Test TS/JS Application](#tag-semver-action)
  - [Input Parameters](#build-and-test-tsjs-applications)
  - [Workflow Examples](#workflow-examples)
  - [Reference](#reference)
  - [Contributing](#contributing)

**Universal Actions** are GitHub Composite Actions that are highly reusable, maintainable and can adapt to work with multiple types of project. They are born to abstract the underlying commands and logics to achieve a specific task, enabling DevOps Engineers to focus on the most crucial parts of their implementation and reduce an amount of time to repeatedly write these actions.

**Build and Push to Azure Registry** is an Universal Action created to log into Azure, build and push Docker Image to Azure Container Registry (ACR).

## Input Parameters

| Parameter Name    | Required? | Type    | Default Value | Description                                    |
| ----------------- | --------- | ------- | ------------- | ---------------------------------------------- |
| working-directory | false     | string  | .             | Path to the project directory                  |
| package-manager   | false     | string  | npm           | Package manager (npm \| yarn \| pnpm)          |
| node-version      | false     | string  | 20            | Node.js version                                |
| run-sonar-test    | false     | boolean | false         | Whether to run Sonar test or not               |
| sonar-token       | false     | string  | ""            | Token to authenticate connection to SonarCloud |

## Workflow Examples

## Reference

## Contributing
