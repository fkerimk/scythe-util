# SCYTHE <img width="24" height="24" alt="icon" src="https://fkerimk.com/scythe/icon.png" /> util

A simple CLI toolkit for the Scythe.

## 🛠 License

scythe-util is licensed under the [LGPL-2.1 license](./LICENSE).

## Building

Make sure you have the .NET 10 SDK packages installed.

Place scythe-lib at `./lib/bin/scythe-lib.dll`, or assign a custom location in `scythe-util.csproj` after cloning.

```bash
git clone https://github.com/fkerimk/scythe-util.git
cd ./scythe-util/
dotnet publish -v q -c Release -r "linux-x64" # for linux
dotnet publish -v q -c Release -r "win-x64" # for windows
cd ..
```

The build will be at the `./scythe-util/bin/Release/net10.0/linux-x64/publish/scythe-util` for linux, and at the `./scythe-util/bin/Release/net10.0/win-x64/publish/scythe-util.exe` for windows.


You can take an automatic build using the [scythe-build](https://github.com/fkerimk/scythe-build) module.

