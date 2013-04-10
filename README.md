Build and run single C# files from Sublime Text 2 on OSX.

USAGE
------
With any *.cs file open.
- `Cmd + b` Build FILENAME.exe in same folder and output errors
- `Shift + Cmd + b` Run FILENAME.exe in the folder of the current file

DEPENDENCIES
------------
Assumes you have `gmcs` and `mono` commands available in your PATH.

If you have previously installed Xamarin Studio or Mono Develop you should have these available in your path. If you don't please read more at [here](http://www.mono-project.com/) or [here](http://monodevelop.com/)

CODE-COMPLETION
---------------
If you want Visual Studio-style code completion, be sure to also install the awesome plugin [CompleteSharp](https://github.com/quarnster/CompleteSharp) (available via package manager) 

INSTALLATION
------------

### Using Package Manager
Sorry, not yet...

### The old-school way
1. `cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
2. `git clone git@github.com:ChrOkh/chsharp-build-singlefile-sublime-text-2.git CSharpSinglefile`