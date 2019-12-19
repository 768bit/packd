<p align="center"><img src="https://github.com/gobuffalo/buffalo/blob/master/logo.svg" width="360"></p>

<p align="center">
<a href="https://godoc.org/github.com/768bit/packd"><img src="https://godoc.org/github.com/768bit/packd?status.svg" alt="GoDoc" /></a>
<a href="https://travis-ci.org/gobuffalo/packd"><img src="https://travis-ci.org/gobuffalo/packd.svg?branch=master" alt="Build Status" /></a>
<a href="https://goreportcard.com/report/github.com/768bit/packd"><img src="https://goreportcard.com/badge/github.com/768bit/packd" alt="Go Report Card" /></a>
</p>

# github.com/768bit/packd

This is a collection of interfaces designed to make using [github.com/768bit/packr](https://github.com/768bit/packr) easier, and to make the transition between v1 and v2 as seamless as possible.

They can, and should, be used for testing, alternate Box implementations, etc...


## Installation

```bash
$ go get -u -v github.com/768bit/packd
```

## Memory Box

The [`packd#MemoryBox`](https://godoc.org/github.com/768bit/packd#MemoryBox) is a complete, thread-safe, implementation of [`packd#Box`](https://godoc.org/github.com/768bit/packd#Box)
