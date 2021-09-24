# golang-study-note

## day 1 Download and install and run test code
- 	https://golang.org/doc/install
	step by step(well I use windows10 OS)
	done in minutes
	check code `go version`

-	https://golang.org/doc/tutorial/getting-started
	step by step
	run hello code
	```go
	go run .
	```
	Call code in an external package
	https://pkg.go.dev/
	-	network issue happen
	```shell
	rsc.io/quote: module rsc.io/quote: Get "https://proxy.golang.org/rsc.io/quote/@v/list": dial tcp 172.217.27.145:443: connectex: A connection attempt failed because the connected party did not properly respond after a period of time, or established connection failed because connected host has failed to respond.
	```
	Well I try to import it from other web server.
	```go
	go env -w GOPROXY=https://goproxy.cn
	```
	Bingo!Done!Go sleep.

## day 2

