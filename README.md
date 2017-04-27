# goenv
Yet another goenv for Go

## Installation

Place `goenv` anywhere in your `$PATH` for convenience.

## Usage

Example:

```sh
./goenv $HOME/new_workspace

cd $HOME/new_workspace
source activate
go get github.com/whatever/...

# Your changes will be confined to this environment

exit;   # or ^D to deactivate
```

When you're back in the next day and wish to continue your work just do:

```sh
source $HOME/new_workspace/activate
```
