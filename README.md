# Test Composite action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `random-number`

Random Number Generated

## Example usage

uses: actions/test-composite-action@v1.0
with:
  who-to-greet: 'Mona the Octocat'