# rediscover_csharp
just a repo to see if csharp on vscode &amp; linux is a nice thing now


## Installing dotnet
https://learn.microsoft.com/en-us/dotnet/core/install/linux-ubuntu

```
Warning
It's recommended that you avoid using both the Microsoft and Ubuntu package repositories for .NET, as this leads to problems when apps try to resolve a specific version of .NET.
```

https://learn.microsoft.com/en-us/dotnet/core/install/linux-scripted-manual
```sh
wget https://dot.net/v1/dotnet-install.sh -O dotnet-install.sh
sudo chmod +x ./dotnet-install.sh
# ./dotnet-install.sh --version latest
./dotnet-install.sh --channel 7.0
```

## New project

```sh
dotnet new hello
```

## Tooling


