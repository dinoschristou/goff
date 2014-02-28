# goff [![GoDoc](https://godoc.org/github.com/Forestmb/goff?status.png)](https://godoc.org/github.com/Forestmb/goff) #

goff is a library for communicating with the [Yahoo Fantasy Sports APIs](
http://developer.yahoo.com/fantasysports/guide/).

This application is written using the Go programming language and is licensed
under the [New BSD license](
https://github.com/Forestmb/goff/blob/master/LICENSE).

## Building ##

    $ go get https://github.com/Forestmb/goff
    $ cd $GOPATH/src/github.com/Forestmb/goff
    $ ./build.sh

To make sure this build runs before every commit, use:

    $ ln -s "$(pwd)/build.sh" .git/hooks/pre-commit