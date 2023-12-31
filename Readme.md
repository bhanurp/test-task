# Jfrog-Pipelines-Task

This Pipelines Task is implementation mvn publish native step.
 
this task performs below actions

- Does some awesome work
- Installation of a popular package
- Performs some repetitive tasks
- Sends notification

### What's New

[Add whats latest in the release]
- Added to support caching

### Prerequisites

[Add pre requisites for running this task]
This task requires jfrog-cli, JFrog Xray

## Usage

Give some sample configuration for running 
**Basic:**

```yaml
- task: jfrog/pipelines-task@v0.0.1
  id: my-awesome-task
  input:
    inputA:
    inputB:
```

### Input Variables

| Name                        | Required | Default                               | Description                     |
|-----------------------------|----------|---------------------------------------|---------------------------------|
| inputA                      | true     |                                       | Simple description about inputA |
| inputB                      | false    | false                                 | Simple description about inputB |

```

### Exported Environment Variables

Mention all the environment variables which the task exports

### How does it work?

Give a simple description how Task functions

## License

Mention the License for the Task

## Release Notes

The release notes are available [here](RELEASE.md).

## Troubleshooting

Add any known errors and what might be the reason for the error.

## Related Tasks

Mention all the relatable tasks which might help.