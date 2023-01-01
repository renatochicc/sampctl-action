# sampctl-action
This action sets up sampctl in the environment for use in actions.

# Usage
Basic example:

```yml
steps:
  - uses: actions/checkout@v2
  - uses: renatochic69/sampctl-action
      with:
      version: '1.11.0'
  - run: sampctl p build
```
