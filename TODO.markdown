# TODO

* Support for on-the-fly-signing
* (Re)sign zonefiles
* TLSA support
    * create record from PEM(?) files
    * sign
    * verify
* Use BIND10 memory efficient zone structure?
* make more use of io.Reader/io.Writer

## Nice to have

* Speed, we can always go faster. A simple reflect server now hits 45/50K qps
* go test; only works correct on my machine
* privatekey.Precompute() when signing? 
