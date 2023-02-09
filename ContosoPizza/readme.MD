# Build .NET Applications with C

## Last step "Create a web API with ASP.NET Core Controllers"

- Create new project with:
    > dotnet new webapi -f net7.0
- Build and run project with:
    > dotnet build

    > dotnet run
- Install httprepl for testing the REST APIs
   > dotnet tool install -g  Microsoft.dotnet-httprepl

   > [!WARNING] Had to install .NET Framework compatible runtime to fix mismatch with version 7.0 and 6.0.
- httprepl commands:
  - Connect to localhost:
    > httprepl <http://localhost:{port>}
  - Get list of APIs:
    > httprepl ls
  - Enter API directory:
    > httprepl cd
- Add the Models, Services, and Controllers Respectively according to the files.
