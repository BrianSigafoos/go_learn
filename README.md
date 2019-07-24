# Go learn

## Resources

### Watch

- [The Why of Go](https://www.youtube.com/watch?v=bmZNaUcwBt4)
- [Simplicity Is Complicated, Rob Pike](https://www.youtube.com/watch?v=rFejpH_tAHM)
- [Concurrency Is Not Parallelism, Rob Pike](https://vimeo.com/49718712)
- [A Tour of Go, Russ Cox](https://research.swtch.com/gotour)
- [Go: building on the shoulders of giants and stepping on a few toes](https://www.youtube.com/watch?v=sX8r6zATHGU)

### Read / Do

- [The Go Programming Language](https://www.amazon.com/dp/B0184N7WWS/)
- [A Tour of Go](https://tour.golang.org/welcome/1)
- [Effective Go](https://golang.org/doc/effective_go.html)
- [Package Docs](https://golang.org/pkg/)
- [Language Specification](https://golang.org/ref/spec)
- [Many links on golang.org Documentation](https://golang.org/doc/)
  - Especially see: **codewalks**

### Cheatsheets

- [Learn Go in Y Minutes](https://learnxinyminutes.com/docs/go/)
- [a8m/go-lang-cheat-sheet](https://github.com/a8m/go-lang-cheat-sheet)
- [devhints.io/go](https://devhints.io/go)

### Practice

- [Gophercieses](https://gophercises.com)

### Podcasts / Video series

- [Go Time](https://changelog.com/gotime)
- [Just for Func](https://www.youtube.com/c/justforfunc)

## Tooling

### Linting

- [golangci-lint](https://github.com/golangci/golangci-lint)
  - Configurable meta linter

### Development

- Versions of Go
  - Use gimme for easy version switching: brew install gimme; eval "$(gimme 1.12.7)"
  - Add this to your shell init script (~/.bash_profile, ~/.profile, etc)

```bash
export GOPATH=~/go
export PATH="$GOPATH/bin:$PATH"
eval "$(gimme 1.12.7)"
```

- Use Go modules ([read this wiki](https://github.com/golang/go/wiki/Modules))
  - You can either:
    - A: git clone the code outside your GOPATH (ie, next to your other code) to use go modules automatically (recommended)
    - B: set `GO111MODULE=on` and keep your Go code in your GOPATH

### IDE Tools

- VS Code
  - [Go modules in VS Code](https://github.com/Microsoft/vscode-go/wiki/Go-modules-support-in-Visual-Studio-Code)
