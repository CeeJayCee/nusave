### Generate executable
macOS:
```shell
cd ./nusave
dotnet publish -c Release -r win-x64 -p:PublishSingleFile=true -p:PublishReadyToRun=true -p:PublishTrimmed=true --self-contained true
dotnet publish -c Release -r osx-x64 -p:PublishSingleFile=true -p:PublishReadyToRun=true -p:PublishTrimmed=true --self-contained true
dotnet publish -c Release -r linux-x64 -p:PublishSingleFile=true -p:PublishReadyToRun=true -p:PublishTrimmed=true --self-contained true
```