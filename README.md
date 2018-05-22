# Appveyor Test Logger
Appveyor logger extensions for [Visual Studio Test Platform](https://gtihub.com/microsoft/vstest).

[![Build Status](https://travis-ci.com/Nipunam/xunit.testlogger.svg?branch=master)](https://travis-ci.com/Nipunam/xunit.testlogger)
[![Build status](https://ci.appveyor.com/api/projects/status/rac9mgpdslmffoqd?svg=true)](https://ci.appveyor.com/project/Nipunam/xunit-testlogger)

## Packages
| Logger | Nuget Package |
| ------ | ------------- |
| AppVeyor | [![NuGet](https://img.shields.io/nuget/v/Appveyor.TestLogger.svg)](https://www.nuget.org/packages/Appveyor.TestLogger/) |

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
