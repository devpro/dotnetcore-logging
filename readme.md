# DevPro experiments - Logging in .NET Core

The goal of this repository is to provide concrete examples of Logging in .NET Core applications.

## Serilog

### WebAppWithSerilog

_Goal_: demonstrate ASP.NET Core Web App logging in a Redis cache with **Serilog** framework.

To run the project you will need a running Redis cache. It can be easily done with Docker.

#### Running Redis in standalone on default port 6379

```dos
docker run -p 6379:6379 redis
REM should display at the end: "* Ready to accept connections"
```

#### References

- "Step by step: Serilog with ASP.NET Core" [carlos.mendible.com](https://carlos.mendible.com/2016/09/19/step-step-serilog-asp-net-core/)
