[![Test](https://github.com/snow-actions/composite-action-template/actions/workflows/test.yml/badge.svg)](https://github.com/snow-actions/composite-action-template/actions/workflows/test.yml)

# Create a Composite Action

Click the `Use this template` to bootstrap the creation of a [composite action](https://docs.github.com/en/actions/creating-actions/creating-a-composite-action).:rocket:

This template includes tests, a validation workflow and versioning guidance.

Learn how to use this template at [Wiki](https://github.com/snow-actions/composite-action-template/wiki).

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

## Environment variables

| Name | Description | Default | Required |
| - | - | - | - |
| `WHO_TO_GREET` | Who to greet | `World` | no |

## Inputs

See [action.yml](action.yml)

| Name | Description | Default | Required |
| - | - | - | - |
| `who-to-greet` | Who to greet | `World` | yes |

## Outputs

See [action.yml](action.yml)

| Name | Description |
| - | - |
| `greet` | The word we greeted you |

## Supported

### Runners

- `ubuntu-*`
- `windows-*`
- `macos-*`
- `self-hosted`

### Events

- Any
<!--
- `push`
- `pull_request`
-->

## Dependencies

- Bash
- [actions/cache](https://github.com/actions/cache) >= 3.0.0
- [GitHub CLI](https://cli.github.com/) >= 2.6.0

## Contributing

Welcome.
