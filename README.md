# Sample Graph QL Server

A very basic graph server for testing the api

## Bulding
Building will create a dynamic code directory called `graph`. This directory is not checked in, but if something is needed it can be commited.

    `go get github.com/99designs/gqlgen`
    `go build server.go`

## Running

    `./server`

then send in:

    query ExampleQuery {
        names
    }

## License

I apply an open license to this project such that I specificly mark this project as free and open in all ways of use for NASA, Raytheon, KBR, and a smattering of other contractors which I, Thomas.Cherry@gmail.com, work with. Contact me to be explicitly added to this list if you feel the need.

