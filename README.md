# CVE-2016-2107
Simple test for the May 2016 OpenSSL padding oracle (CVE-2016-2107)

## Installation

```
$ go version
go version go1.6.2 darwin/amd64
$ go get github.com/FiloSottile/CVE-2016-2107
```

This tool only builds with Go 1.6+, and only when downloaded to the right position in the $GOPATH.

## Usage

```
$ CVE-2016-2107 filippo.io
2016/05/03 17:50:49 Vulnerable: false
```
