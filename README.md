[![Test](https://github.com/toshimaru/delete-action-cache/actions/workflows/test.yml/badge.svg)](https://github.com/toshimaru/delete-action-cache/actions/workflows/test.yml)

# Delete Action Cache

## Motivation

TODO

## Usage

```yml
name: Delete Action Cache
on:
  pull_request_target:
    types: [closed]
jobs:
  delete-cache:
    runs-on: ubuntu-latest
    steps:
      - uses: toshimaru/delete-action-cache@main
```

## Inputs

See [action.yml](action.yml)

| Name | Description | Default | Required |
| - | - | - | - |
| `who-to-greet` | Who to greet | `World` | yes |

### Supported Events

- `pull_request`
- `pull_request_target`
