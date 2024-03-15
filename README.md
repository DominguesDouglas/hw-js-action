# Hello world javascript action

Essa action printa "Hello" + o nome da pessoa à cumprimentar.

## Inputs

### `who-to-greet`

**Required** O nome da pessoa à cumprimentar. Default `"Douglas"`.

## Outputs

### `time`

A hora que foi cumprimentado.

## Example usage

```yaml
uses: actions/hello-world-javascript-action@e76147da8e5c81eaf017dede5645551d4b94427b
with:
  who-to-greet: 'Mona the Octocat'
```