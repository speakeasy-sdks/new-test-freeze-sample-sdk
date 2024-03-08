<!-- Start SDK Example Usage [usage] -->
```go
package main

import (
	"context"
	newtestfreezesamplesdk "github.com/speakeasy-sdks/new-test-freeze-sample-sdk"
	"log"
)

func main() {
	s := newtestfreezesamplesdk.New()

	ctx := context.Background()
	res, err := s.Pets.CreatePets(ctx)
	if err != nil {
		log.Fatal(err)
	}
	if res != nil {
		// handle response
	}
}

```
<!-- End SDK Example Usage [usage] -->