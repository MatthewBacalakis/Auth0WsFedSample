# Quickstart Sample

This example demonstrates WS-FED login.


## Requirements

- [.NET SDK](https://dotnet.microsoft.com/download) (.NET Core 3.1 or .NET 5.0+)

## To run this project

1. Create an application in Auth0 and configure the ws-fed plugin.

2. Configure the `wsfed:realm` and `wsfed:metadata` in `appsettings.json` file with the values for your Auth0 account and application.

3. Run the application from the command line:

```bash
dotnet restore (first time only)
dotnet run
```

4. Go to `http://localhost:PORT` in your web browser to view the website.

## Run this project with Docker

In order to run the example with Docker you need to have [Docker](https://docker.com/products/docker-desktop) installed.

To build the Docker image and run the project inside a container, run the following command in a terminal, depending on your operating system:

```
# Mac
sh exec.sh

# Windows (using Powershell)
.\exec.ps1
```
