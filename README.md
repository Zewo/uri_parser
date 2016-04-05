uri_parser
==========

[![Platforms Linux](https://img.shields.io/badge/Platforms-Linux-lightgray.svg?style=flat)](https://developer.apple.com/swift/)
[![License MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat)](https://tldrlegal.com/license/mit-license)
[![Slack Status](https://zewo-slackin.herokuapp.com/badge.svg)](https://zewo-slackin.herokuapp.com)

**uri_parser** is an URI parser. It is a modularized excerpt of [node.js's http-parser](https://github.com/nodejs/http-parser) source.

## Installation

### OS X

```bash
brew tap zewo/tap
brew install uri_parser
```

### Linux

```bash
echo "deb [trusted=yes] http://apt.zewo.io/deb ./" | sudo tee --append /etc/apt/sources.list
sudo apt-get update
sudo apt-get install uri-parser
```

### Source

```bash
git clone https://github.com/Zewo/uri_parser.git && cd uri_parser
make
sudo make install
```

## Community

[![Slack](http://s13.postimg.org/ybwy92ktf/Slack.png)](https://zewo-slackin.herokuapp.com)

Join us on [Slack](https://zewo-slackin.herokuapp.com).

License
-------

**uri_parser** is released under the MIT license. See LICENSE for details.
