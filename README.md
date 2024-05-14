# gitbot

This is a Github action that performs various git-based tasks automatically.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: joerisner/gitbot@0.1.0
with:
  who-to-greet: 'Mona the Octocat'
```
