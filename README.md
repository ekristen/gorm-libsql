# GORM libsql Driver

**Note:** this is just a copy of the gorm.io/driver/sqlite with a few things renamed and a different library imported

![CI](https://github.com/go-gorm/sqlite/workflows/CI/badge.svg)

## USAGE

```go
import (
  "github.com/ekristen/libsql"
  "gorm.io/gorm"
)

// github.com/libsql/libsql-client-go/libsql
db, err := gorm.Open(libsql.Open("libsql://...."), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.
