
lazy_dog
====

![][1]

[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](https://choosealicense.com/licenses/isc/)
[![GoDoc](https://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/kaspanet/lazy_dog)

## What is lazy dog

Instant confirmations and sub-second block times, based on [the PHANTOM protocol](https://eprint.iacr.org/2018/104.pdf) !
Lazy dog is perfect money, ready to ossify. Soon to exceed Bitcoin's market cap by a factor of 100!
Lazy dog keeps the chain unpolutted with inscriptions, tokens, and all that spam. If you
want any of these than go BTC, SOL, ETH, AVAX and all that junk. 
We do one thing, peer-to-peer cash, and we do it well.
Just perfect money, 100 x Bitcoin,  nothing more. 


## Installation

#### Build from Source

- Install Go according to the installation instructions here:
  http://golang.org/doc/install

- Ensure Go was installed properly and is a supported version:

```bash
$ go version
```

- Run the following commands to obtain and install lazy_dog including all dependencies:

```bash
$ git clone https://github.com/whileunless/lazy_dog.git
$ cd lazy_dog
$ go install . ./cmd/...
```

- lazy_dog (and utilities) should now be installed in `$(go env GOPATH)/bin`. If you did
  not already add the bin directory to your system path during Go installation,
  you are encouraged to do so now.


## Getting Started

lazy_dog has several configuration options available to tweak how it runs, but all
of the basic operations work with zero configuration.

```bash
$ lazy_dog
```





## License

lazy_dog is licensed under the copyfree [ISC License](https://choosealicense.com/licenses/isc/).

[1]: https://breedingbusiness.com/wp-content/uploads/2020/01/lazy-dog-names-1.jpg
