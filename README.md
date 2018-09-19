# theanswer-boshrelease

0. [Install, Run, Usage](#install-run-usage)
1. [Features](#features)
2. [Dependencies](#dependencies)
3. [Tests](#tests)
4. [Architecture Structure and Decisions](#architecture-structure-and-decisions)
5. [API Endpoints](#api-endpoints)
6. [Debugging Hints](#debugging-hints)
7. [Manifest Examples](#manifest-examples)
8. [Links to external Documentation](#links-to-external-documentation)
9. [TODOs](#todos)
10. [Nice to Have](#nice-to-Have)
11. [Known Issues](#known-issues)

## Install, Run, Usage

1. Update the sources with `./update`. This will download the linux64 binary.
1. Create the BOSH release with `bosh create-release`
1. Upload to your BOSH director `bosh upload-release`
1. Deploy the example without consul `bosh deploy -d theanswer examples/manifest -n`

## Features
The theanswer-boshrelease contains the [theanswer](https://github.com/phartz/the-answer-is) theanswer as a BOSH release.

Set the `port`property to change the listener port.
```yaml
properties:
  theanswer:
    port: 8080
```

## Dependencies

## Tests

## Architecture Structure and Decisions

## API Endpoints
See the [theanswer](https://github.com/phartz/the-answer-is) documentation.

## Debugging Hints

## Manifest Examples
Examples can be found in the examples folder.

## Links to External Documentation

## TODOs

## Nice to Have

## Known Issues
