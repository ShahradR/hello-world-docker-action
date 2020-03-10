# Hello world docker action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

This repo was modeled after the ["Creating a Docker container action" tutorial][1] provided by GitHub.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```
uses: ShahradR/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'
```

[1]: https://help.github.com/en/actions/building-actions/creating-a-docker-container-action
