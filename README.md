# Golang test TeamCity converter

Convert go test output to TeamCity format

Support Run, Skip, Pass, Fail

### How use
```bash
go test -v ./... | docker run -i xjewer/go-test-teamcity
```

### Links
- https://confluence.jetbrains.com/display/TCD9/Build+Script+Interaction+with+TeamCity
