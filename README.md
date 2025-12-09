# lint-yaml

A composite action for linting YAML files.

## Usage

```yaml
name: Lint

on: pull_request

permissions:
  contents: read

jobs:
  yamllint:
    name: YAML
    runs-on: ubuntu-24.04
    steps:
      - name: Checkout
        uses: actions/checkout@v6

      - name: Lint YAML Files
        uses: craigsloggett/lint-yaml@v1
```

### Inputs

| Input            | Required? | Default                    | Description                                        |
| ---------------- | --------- | -------------------------- | -------------------------------------------------- |
| `my-input`       | `false`   | `The default description.` | This is my input, there is no other input like it. |

### Outputs

| Output      | Description                                |
| ----------- | ------------------------------------------ |
| `my-output` | The output this composite action produces. |
