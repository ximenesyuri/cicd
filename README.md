# About

This repository contains some helper composite actions to be used as steps in a Github workflow. Certain reusable docker compose files are also included.

# Usage

Each composite action requires certain `inputs`, whose values should be defined while calling it.

```yaml
...

steps:
  - name: some step
    uses: ximenesyuri/cicd/actions/<kind>/<name>@main
    with:
      some_input: <some_value>
      other_input: <other_value>
      ...
```
