# flashy

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Not any.

## Installation

```bash
pip install flashy
```

## Usage

```
>>> from flashy import dict_substract
>>> dict_substract({}, {'a': 11})
{}
>>> dict_substract({'a': 12}, {'a': 11})
{'a': 12}
>>> dict_substract({'a': 11, 'b': 0}, {'a': 11})
{'b': 0}
```

## Support

python3.6+

## Changelog

[Here](docs/CHANGELOG.md)

## License

[MIT](docs/LICENSE)

## Credits

This package was created with [cookiecutter](https://github.com/audreyr/cookiecutter) and [iamgodot/gen-pyckage](https://github.com/iamgodot/gen-pyckage) project template.
