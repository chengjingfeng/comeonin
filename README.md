# Comeonin [![Build Status](https://travis-ci.org/riverrun/comeonin.svg?branch=master)](https://travis-ci.org/riverrun/comeonin) [![Hex.pm Version](http://img.shields.io/hexpm/v/comeonin.svg)](https://hex.pm/packages/comeonin) [![Join the chat at https://gitter.im/comeonin/Lobby](https://badges.gitter.im/comeonin/Lobby.svg)](https://gitter.im/comeonin/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Password hashing library for Elixir.

This library is intended to make it very straightforward for developers to check users' passwords in as secure a manner as possible.

Comeonin supports Argon2, Bcrypt and Pbkdf2 (sha512 and sha256).

## Features

* Comeonin supports the most secure, well-tested, and up-to-date password hashing schemes.
    * Argon2 is the winner of the 2015 Password Hashing Competition.
    * Bcrypt and Pbkdf2 have no known vulnerabilities and have been widely tested for over 15 years.
* It is easy to use.
    * Salts are generated by default.
    * Each function has sensible, secure defaults.
* It provides excellent documentation.
    * Clear instructions are given on how to use Comeonin.
    * Several recommendations are also given to help developers keep their apps secure.

## Installation and Use

See the [Comeonin wiki](https://github.com/riverrun/comeonin/wiki) for details.

### Documentation

http://hexdocs.pm/comeonin

### License

BSD. For full details, please read the LICENSE file.
