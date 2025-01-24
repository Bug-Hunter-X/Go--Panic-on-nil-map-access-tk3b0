# Go: Panic on nil map access

This repository demonstrates a common error in Go: accessing a map element without checking if the map is nil.  This can lead to a runtime panic, which can be difficult to debug.

The `bug.go` file contains code that will panic.  The `bugSolution.go` file shows how to avoid this panic using safe map access.

## Running the code

1. Clone this repository.
2. Navigate to the directory.
3. Run `go run bug.go` to see the panic.
4. Run `go run bugSolution.go` to see the corrected code.
