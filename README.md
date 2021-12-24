# theForger's Win32 API Tutorial

## Introduction

This repository is an unofficial repo for [theForger's Win32 API Tutorial](http://www.winprog.org/tutorial/) [source code](http://bit.ly/2ntziDq). No representation is made that this is my code, it's reproduced here simply so I don't forget about it and can easily reference it. All copyrights remain with theForger.

## Building

You'll need Visual Studio 2022 with the _Desktop development with C++_ workload installed. You should then be able to open any of the VS solution files and immediately build them. It may be possible to open the VS solution files using older (but still modern) versions of Visual Studio, but I've not tested this.

## Changes

The solution and projects have been upgraded to VS 2022 Community Edition.

## Considerations

The projects successfully compile, but the source code and compiler/linker settings are dated, and so may generate compiler and security warnings during the build. These warnings don't stop the builds, but I strongly recommend you heed them before using any code in production. When using any Win32 code from this repo in production, always consult the [Windows API Index](https://docs.microsoft.com/en-us/windows/win32/apiindex/windows-api-list) for relevant and updated API usage notes, as some APIs may have since been deprecated or had their behaviour modified in newer versions of Windows.

## Additional resources

* [Build desktop Windows apps using the Win32 API](https://docs.microsoft.com/en-us/windows/win32/)
* [Get Started with Win32 and C++](https://docs.microsoft.com/en-us/windows/win32/learnwin32/learn-to-program-for-windows)
* [Windows API Index](https://docs.microsoft.com/en-us/windows/win32/apiindex/windows-api-list)
* [COM and ATL](https://docs.microsoft.com/en-us/cpp/atl/introduction-to-com-and-atl?view=msvc-160)
* [C++/WinRT](https://docs.microsoft.com/en-us/windows/uwp/cpp-and-winrt-apis/)
* [Source code for Charles Petzold's Programming Windows 5th edition](https://github.com/yottaawesome/programming-windows-5th-edition)