# check_golang_lint
A script that runs several checks on your golang project
## To install the different tools
```
go install github.com/fzipp/gocyclo/cmd/gocyclo@latest
go install golang.org/x/tools/cmd/goimports@latest
go install github.com/client9/misspell/cmd/misspell@latest
go install golang.org/x/tools/go/analysis/passes/shadow/cmd/shadow@latest
go install golang.org/x/lint/golint@latest
```
