# greetings-action

A composite action that greets someone with the Vulcan phrase “Live long and
prosper.”

## Inputs

| Input | Required | Description |
| --- | --- | --- |
| `who-to-greet` | Yes | The person to greet |

## Usage

```yaml
steps:
  - uses: robstrdev/greetings-action@v1
    with:
      who-to-greet: Spock
```

This prints `Live long and prosper, Spock!`.