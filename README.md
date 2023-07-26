# Getting started with Testcontainers for .NET

This is sample code for the [Getting started with Testcontainers for .NET](https://testcontainers.com/guides/getting-started-with-testcontainers-for-dotnet) guide.

## 1. Setup Environment

Make sure you have .NET 7 and a [compatible Docker environment](https://www.testcontainers.org/supported_docker_environment/) installed.

For example:

```shell
$ dotnet --list-sdks
7.0.104 [C:\Program Files\dotnet\sdk]
$ docker version
...
Server: Docker Desktop 4.12.0 (85629)
 Engine:
  Version:          20.10.17
  API version:      1.41 (minimum version 1.12)
  Go version:       go1.17.11
...
```

## 2. Setup Project

* Clone the repository

```shell
git clone https://github.com/testcontainers/tc-guide-getting-started-with-testcontainers-for-dotnet.git
cd tc-guide-getting-started-with-testcontainers-for-dotnet/TestcontainersDemo
```

* Open the **tc-guide-getting-started-with-testcontainers-for-dotnet/TestcontainersDemo** project in your favorite IDE.

## 3. Run Tests

Run the command to run the tests.

```shell
$ dotnet test
```

The tests should pass.
