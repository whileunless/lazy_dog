
lazy_dog
====

[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](https://choosealicense.com/licenses/isc/)
[![GoDoc](https://img.shields.io/badge/godoc-reference-blue.svg)](http://godoc.org/github.com/kaspanet/lazy_dog)

## What is lazy dog

Lazy dog is an attempt at a proof-of-work cryptocurrency with instant confirmations and sub-second block times. 
It is based on [the PHANTOM protocol](https://eprint.iacr.org/2018/104.pdf). 
We want to ossify now and surpass Bitcoins market cap by 100 times.

## Requirements

Go 1.18 or later.

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
