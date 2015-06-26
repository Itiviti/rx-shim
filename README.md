[![Build status](https://img.shields.io/appveyor/ci/Ullink/rx-shim.svg?label=build windows)](https://ci.appveyor.com/project/Ullink/rx-shim) [![NuGet](https://img.shields.io/nuget/dt/RxShim.svg)](https://www.nuget.org/packages/RxShim/) [![NuGet](https://img.shields.io/nuget/v/RxShim.svg)](https://www.nuget.org/packages/RxShim/) [![GitHub license](https://img.shields.io/github/license/Ullink/rx-shim.svg)](http://www.apache.org/licenses/LICENSE-2.0)   

Introduction
============

Rx-Shim is a very small library that targets only .Net 4.0 and provides async/await glue between Microsoft.Bcl and Rx.
(glue which is otherwise available in Rx for .Net 4.5)

Code was copied from reactiveui-core (v4), only namespace was changed so that the extension methods are available in same namespace as in Rx for .Net 4.5.

Downloads
------

You can grab it using [NuGet](http://nuget.org/packages/RxShim/).

How to build
------

Builds directly from within VS, or using gradle:

```
git clone --recursive https://github.com/Ullink/rx-shim.git
cd rx-shim
gradlew.bat msbuild
```
