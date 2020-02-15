# go-branch-only

Simple Golang program, tested by go get(modules), check whether go get use git branch as version

This repository has semver branch only, without any tags.

# usage

```sh
# create empty dir outside GOPATH
mkdir ~/test-go-branch

cd ~/test-go-branch

# init empty go module
go mod init example.com/a/b

cat go.mod

# go get this module
go get -v github.com/vikyd/go-branch-only

# check version
cat go.mod
```
