## Project Setup 🛠️​

### Packages

<a href="https://yara.readthedocs.io/en/stable/capi.html">YARA</a> : The YARA C API

```
vcpkg install yara
```

<a href="https://github.com/open-source-parsers/jsoncpp">JsonCPP</a> : A C++ library for interacting with JSON.
 
```
vcpkg install jsoncpp
```

<a href="https://github.com/microsoft/Detours">Detours</a> : A software package for monitoring and instrumenting API calls on Windows.
 
```
vcpkg install detours
```

<a href="https://github.com/microsoft/vcpkg">vcpkg</a> package manager :
```
git clone https://github.com/microsoft/vcpkg
.\vcpkg\bootstrap-vcpkg.bat
```

### Libs & Headers
Make sure to have the following linked to your project if you're using another environment than VStudio : 

Includes :
```
C:\Program Files (x86)\Windows Kits\10\Include\10.0.22621.0\km
C:\Program Files (x86)\Windows Kits\10\Include\10.0.22621.0\um
C:\Program Files (x86)\Windows Kits\10\Include\10.0.22621.0\ucrt
C:\Program Files (x86)\Windows Kits\10\Include\10.0.22621.0\winrt
C:\Program Files (x86)\Windows Kits\10\Include\10.0.22621.0\shared
```

Libs :
```
C:\Program Files (x86)\Windows Kits\10\Lib\10.0.22621.0\um\x64
C:\Program Files (x86)\Windows Kits\10\Lib\10.0.22621.0\km\x64
C:\Program Files (x86)\Windows Kits\10\Lib\10.0.22621.0\ucrt\x64
```


