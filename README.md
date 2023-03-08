# commitlint-action

## How to use

```
jobs:
  commitlint:
    if: github.event_name == 'pull_request'
    runs-on: ubuntu-latest

    steps:
      - name: Check-out
        uses: actions/checkout@v3
        with:
          fetch-depth: 0

      - name: Commitlint
        uses: wintero92/commitlint-action@v1
```

## Inputs

See `action.yaml` for possible inputs.