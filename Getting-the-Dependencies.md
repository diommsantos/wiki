# Getting the Dependencies #

x64_dbg has various dependencies. Here is a list of them and how you can obtain them yourself. The easiest method is simply downloading the latest release from [Github](http://releases.x64dbg.com) and extract the binaries in the `bin` directory, but here is a guide **in case you want to do it manually** (which you don't because this guide is outdated as fuck).

### BeaEngine ###
Clone and compile the repository [here](https://bitbucket.org/mrexodia/beaengine).

### Capstone ###
Clone and compile the repository [here](https://github.com/aquynh/capstone).

### dbghelp & symserv ###
Get [Debugging Tools For Windows](http://go.microsoft.com/fwlink/p/?linkid=84137) and extract dbghelp.dll and symserv.dll from the installation directory.

### DeviceNameResolver ###
Clone and compile the repository [here](https://bitbucket.org/mrexodia/devicenameresolver).

### jansson ###
Clone the repository [here](https://bitbucket.org/mrexodia/jansson), checkout the branch 'jansson_x64dbg' and compile using Visual Studio 2010.

### lz4 ###
Clone and compile the repository [here](https://bitbucket.org/mrexodia/lz4).

### OGDF ###
Clone and compile the repository [here](https://bitbucket.org/mrexodia/ogdf).

### Scylla ###
Download the binaries from [here](https://tuts4you.com/download.php?view.3503), or manage to compile the repository [here](https://github.com/NtQuery/Scylla). Don't forget to rename to Scylla.dll.

### TitanEngine ###
Clone and compile the repository [here](https://bitbucket.org/mrexodia/titanengine-update).

### Qt ###
Usually QtCore4, QtGui4 and QtNetwork4 are inside the /bin directory of your Qt installation.

### XEDParse ###
Clone and compile the repository [here](https://bitbucket.org/mrexodia/xedparse).

### snowman ###
Clone and compile the repository [here](https://github.com/x64dbg/snowman). You need to have Boost and Qt 4 (same version you use to compile x64dbg).