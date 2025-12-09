# composite-action-template

A GitHub repository template for creating a new Composite Action.

> Composite actions allow you to collect a series of workflow job steps into a single action which you can then run as a single job step in multiple workflows.

## Usage

See [action.yml](action.yml) for the various `inputs` this action supports.

### Inputs

| Input            | Required? | Default                    | Description                                        |
| ---------------- | --------- | -------------------------- | -------------------------------------------------- |
| `my-input`       | `false`   | `The default description.` | This is my input, there is no other input like it. |

### Outputs

| Output      | Description                                |
| ----------- | ------------------------------------------ |
| `my-output` | The output this composite action produces. |
