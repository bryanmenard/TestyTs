# TestyTs
[![Build Status](https://travis-ci.com/Aboisier/TestyTs.svg?token=vuBsBM3yD6PMvt3zwT9s&branch=master)](https://travis-ci.com/Aboisier/TestyTs)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FAboisier%2FTestyTs.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FAboisier%2FTestyTs?ref=badge_shield)


TestyTs is a modern TypeScript testing framework.

## Why?
Writing tests should be fun. The other testing framework solutions do not make use of the full power of TypeScript. This one uses decorators and OOP and stuff. Therefore, it makes writing tests fun.

## Installation

```
$ npm install --save-dev testyts
$ npm install -g testyts
```

## Setup

To generate a testy.json configuration file, use the following cmmand:

```
$ testy init
```

## Run the tests

To run the tests, use the following command

```
$ testy
$ testy --config custom/config/file.json // To specify a custom configuration file
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](./LICENSE)