# emacs-travis

[![License GPL 3][badge-license]][LICENSE]
[![travis][badge-travis]][travis]
[![Melpa Status](http://melpa.milkbox.net/packages/travis-badge.svg)](http://melpa.milkbox.net/#/travis)
[![MELPA Stable](http://stable.melpa.org/packages/travis-badge.svg)](http://stable.melpa.org/#/travis)

`emacs-travis` provides :
* a REST client to the [Travis][] API
* a [Helm][] interface

## Installation

The recommended way to install ``emacs-travis`` is via [MELPA][]:

    M-x package-install emacs-travis

or [Cask][]:

	(depends-on "emacs-travis")


## Usage

* Setup your Travis configurations :

        $ (setq travis-token "xxxxxxxx")


## Development

### Cask

``emacs-travis`` use [Cask][] for dependencies
management. Install it and retrieve dependencies :

    $ curl -fsSkL https://raw.github.com/cask/cask/master/go | python
    $ export PATH="$HOME/.cask/bin:$PATH"
    $ cask


### Tests

* Launch unit tests :

        $ export TRAVIS_TOKEN xxxxxx
        $ make clean test


## Support / Contribute

See [here](CONTRIBUTING.md)



## Changelog

A changelog is available [here](ChangeLog.md).


## License

See [LICENSE](LICENSE).


## Contact

Nicolas Lamirault <nicolas.lamirault@gmail.com>

[emacs-travis]: https://github.com/nlamirault/emacs-travis
[badge-license]: https://img.shields.io/badge/license-GPL_2-green.svg?style=flat
[LICENSE]: https://github.com/nlamirault/emacs-travis/blob/master/LICENSE
[travis]: https://travis-ci.org/nlamirault/emacs-travis
[badge-travis]: http://img.shields.io/travis/nlamirault/emacs-travis.svg?style=flat
[GNU Emacs]: https://www.gnu.org/software/emacs/
[MELPA]: http://melpa.milkbox.net/
[Cask]: http://cask.github.io/
[Issue tracker]: https://github.com/nlamirault/emacs-travis/issues

[Travis]: https://www.travis.com/
[Helm]: https://github.com/emacs-helm/helm