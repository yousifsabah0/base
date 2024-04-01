# Idiomatic Go

How to write clean and idiomatic Go code.

## Variables and Constants

- Always declare constants or variables in the top of your file.
- Don't use `THIS_CASE` when declaring constants instead, use regular cases used in Go. e.g. `const isThisAPrivateConstant = "yes"` or `const IsThisAPrivateConstant = "no"`
- Always group declarations.

```go
const (
  constantOne = 1
  constantTwo = 2
)

var (
  one = 1
  two = 2
)

```

## Functions

- If your function will panic prefix it with keyword `Must`, e.g. `func MustDoSomeLogic() int`

## Struct's

- Use named assignments always when initializing structs.
