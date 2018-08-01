# sm - SEV Manager

[![Build Status](https://travis-ci.org/prologic/sm.svg)](https://travis-ci.org/prologic/sm)
[![CodeCov](https://codecov.io/gh/prologic/sm/branch/master/graph/badge.svg)](https://codecov.io/gh/prologic/sm)
[![Go Report Card](https://goreportcard.com/badge/prologic/sm)](https://goreportcard.com/report/prologic/sm)
[![GoDoc](https://godoc.org/github.com/prologic/sm?status.svg)](https://godoc.org/github.com/prologic/sm) 
[![](https://images.microbadger.com/badges/image/prologic/sm.svg)](https://microbadger.com/images/prologic/sm "Get your own image badge on microbadger.com")

A simple SEV Manager (*Site Event Management*) that lets you create and
communicate real-time information for critical infrastructure events brining
all communication, tracking and resolution in once place.

**Status:** Early alpha stages, in heavy development.

## Features

* Simple HTTP API
* Simple command-line client
* UNIX friendly

## Install

```#!bash
$ go install github.com/prologic/sm/...
```

## Usage

Run the sm daemon/server:

```#!bash
$ sm -d
INFO[0000] sm 0.0.1-dev (HEAD) listening on 0.0.0.0:8000
```

...

## License

sm is licensed under the [MIT License](https://github.com/prologic/sm/blob/master/LICENSE)
