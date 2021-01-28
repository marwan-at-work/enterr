# enterr

To reproduce this error, simply `cd ent && go generate` 

To fix the error, you can run `go install github.com/facebook/ent/cmd/ent@master` and manually run `ent generate ./schema` and things will work.
