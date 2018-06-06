# Appveyor Test Logger
Appveyor logger extensions for [Visual Studio Test Platform](https://gtihub.com/microsoft/vstest).

[![Build Status](https://travis-ci.com/spekt/appveyor.testlogger.svg?branch=master)](https://travis-ci.com/spekt/appveyor.testlogger)
[![Build status](https://ci.appveyor.com/api/projects/status/l2htcwb0v8tyg9uh?svg=true)](https://ci.appveyor.com/project/spekt/appveyor-testlogger)

## Packages
| Logger | Stable Package | Pre-release Package |
| ------ | -------------- | ------------------- |
| AppVeyor | [![NuGet](https://img.shields.io/nuget/v/Appveyor.TestLogger.svg)](https://www.nuget.org/packages/Appveyor.TestLogger/) | [![MyGet Pre Release](https://img.shields.io/myget/spekt/vpre/appveyor.testlogger.svg)](https://www.myget.org/feed/spekt/package/nuget/Appveyor.TestLogger) |

## Usage
Appveyor logger can report test results automatically to the CI build. See an example: https://ci.appveyor.com/project/Faizan2304/loggerextensions/build/1.0.24/tests.

1. Add a reference to the [AppVeyor Logger](https://www.nuget.org/packages/Appveyor.TestLogger) nuget package in test project
2. Use the following command line in tests
```
> dotnet test --test-adapter-path:. --logger:Appveyor
```
3. Test results are automatically reported to the AppVeyor CI results

## LICENSE
MIT
