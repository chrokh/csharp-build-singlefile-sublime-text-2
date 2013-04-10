Build and run single C# files from Sublime Text 2 on OSX.

Usage
------
With any *.cs file open.
- `Cmd + b` Compile filename.cs into filename.exe in current folder and output errors
- `Shift + Cmd + b` Run filename.exe in current folder

About
-----
The aim of this plugin is to provide easy and fast and overhead-free access to the C# language. Without having to load heavy applications such as Visual Studio or Xamarin. This plugin provides a C# sandbox (usable for schools or other learning environments) and is not intended to be used to build production applications.

Dependencies
------------
Assumes you have `gmcs` and `mono` commands available in your PATH.

If you have previously installed Xamarin Studio or Mono Develop you should have these available in your path. If you don't please read more at [here](http://www.mono-project.com/) or [here](http://monodevelop.com/)

Installation
------------

#### Using Package Manager
Sorry, not yet...

#### The old-school way
1. `cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
2. `git clone git@github.com:ChrOkh/chsharp-build-singlefile-sublime-text-2.git CSharpSinglefile`

Code-completion
---------------
If you want Visual Studio-style code completion, be sure to also install the awesome plugin [CompleteSharp](https://github.com/quarnster/CompleteSharp) (available via package manager) 

Example
-------
Now we can write minimalistic C# console applications:
```C#
using System;
class MainClass{
  public static void Main(){
    Console.WriteLine("Hello world");
  }
}
```