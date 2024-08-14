[![Test](https://github.com/toshimaru/delete-action-cache/actions/workflows/test.yml/badge.svg)](https://github.com/toshimaru/delete-action-cache/actions/workflows/test.yml)

# Delete Action Cache

## Usage

### Basic

```yml
steps:
  - uses: snow-actions/composite-action-template@v1.0.0
```

### Optional

```yml
steps:
  - uses: snow-actions/composite-action-template@v1.0.0
    with:
      who-to-greet: Your name
```

## Inputs

See [action.yml](action.yml)

| Name | Description | Default | Required |
| - | - | - | - |
| `who-to-greet` | Who to greet | `World` | yes |

### Events

- Any
<!--
- `push`
- `pull_request`
-->

