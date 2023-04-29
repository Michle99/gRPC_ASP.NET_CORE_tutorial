# Create a gRPC client and server in ASP.NET Core

# Description
Create a .NET Core gRPC client and an ASP.NET Core gRPC Server.

# Pre-requisites
- [Visual Studio Code](https://code.visualstudio.com/download)
- [C# for Visual Studio Code (latest version)](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
- [.NET 6.0 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)

# Create a gRPC service
- Open the integrated terminal.
- Change to the directory ```(cd)``` that will contain the project.
- Run the follwing commands:
```
dotnet new grpc -o GrpcGreeter
code -r GrpcGreeter
```
- The ```dotnet new``` command creates a new gRPC service in the GrpcGreeter folder.
- The ```code``` command opens the GrpcGreeter folder in a new instance of Visual Studio Code.

# Resources
[Continue learning how to create a gRPC service](https://learn.microsoft.com/en-us/aspnet/core/tutorials/grpc/grpc-start?view=aspnetcore-7.0&tabs=visual-studio-code)