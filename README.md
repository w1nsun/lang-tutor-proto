## Generate files

Generate code from proto files

```
protoc -I proto proto/*.proto --go_out=./gen/go/ --go_opt=paths=source_relative --go-grpc_out=./gen/go/ --go-grpc_opt=paths=source_relative
```

How to push it to repo

```
git tag v0.0.1
git push origin v0.0.1
```
