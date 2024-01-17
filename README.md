# install-packwiz

[![Current Tag](https://img.shields.io/github/v/tag/actionhippie/install-packwiz?sort=semver)](https://github.com/actionhippie/install-packwiz) [![Testing Build](https://github.com/actionhippie/install-packwiz/workflows/testing/badge.svg)](https://github.com/actionhippie/install-packwiz/actions/workflows/testing.yml)

[GitHub Action](https://github.com/features/actions) to install the
[Packwiz][packwiz] binary.

## Usage

```yml
name: Example

on:
  - push
  - pull_request

jobs:
  test:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v2

      - uses: actionhippie/install-packwiz@v1

      - run: packwiz --help
```

## Inputs

None

## Outputs

None

## Security

If you find a security issue please contact thomas@webhippie.de first.

## Contributing

Fork -> Patch -> Push -> Pull Request

## Authors

* [Thomas Boerger](https://github.com/tboerger)

## License

Apache-2.0

## Copyright

```console
Copyright (c) 2024 Thomas Boerger <thomas@webhippie.de>
```

[packwiz]: https://packwiz.infra.link/
