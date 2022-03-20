# PactJS Example

Taken from - https://www.mariedrake.com/post/contract-testing-with-pact-js-and-jest

## Install dependencies

`npm i`

## Pactflow

I am using [Pactflow](https://pactflow.io/) as my broker.

- sign up and create your broker
- head to settings
- click 'copy env vars'
- export the values in the clipboard before running tests

Run the consumer tests:
`npm run test:consumer`

Publish the contract to your pact broker:
`npm run publish:pact`

Start the actual provider and run the provider tests
`npm run start:and:test:provider`
