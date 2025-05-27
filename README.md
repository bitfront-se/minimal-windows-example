# Minimal Windows Example

The executable is a minimal Windows application that uses OpenSSL to generate a random string.

It is only useful for testing build pipelines etc.

## Build

The solution should build out of the box with Visual Studio 2022.

```powershell
msbuild minimal-windows-example.sln /p:Configuration=Debug /p:Platform=x64
```

Run the executable `.\x64\Debug\minimal-windows-example.exe` directory.