# go-idioms

Collection of idiomatic Go functions to deal with common boilerplate.

## env

Idiomatic functions to deal with Environment variables.

```go
import "github.com/caarlos/go-idioms/env"

env.Set("AWS_KEY", "***")
env.GetOr("AWS_REGION", "sa-east-1")
env.Unset("KEY")
env.Get("ANOTHER_KEY")
```
