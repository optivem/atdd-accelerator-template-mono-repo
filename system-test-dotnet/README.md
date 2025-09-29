# System Test (.NET)

## Instructions

Docker Compose Up

```shell
docker compose up -d
```

Run Tests

```shell
dotnet test --filter "FullyQualifiedName~Optivem.AtddAccelerator.Template.SystemTest.SmokeTests"
```