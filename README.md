# pauser

`pauser` is a simple program that sleeps in a while loop. It is useful for containers running int he background: instead of executing a shell and then erroring because there is no tty, run `pauser`.

## Installation

go install github.com/msquatch/pauser/cmd/pauser@latest
