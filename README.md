# C-env-installation
Easy C++ environment install for 64bits windows

Visit and download: https://www.msys2.org/

After installation, a terminal appear, enter this command and follow up with 'Y'
```
pacman -S mingw-w64-x86_64-gcc
```

After the installing go to Windows settings -> System Properties -> Advanced -> Environment Variables -> System Variable -> Add a new path

```
C:\msys64\mingw64\bin
```

- Go to your visual studio code
- Install "Code Runner"
- Go to vscode Settings -> Extension -> Run Code configuration
- Checked on "Run In Terminal" box
- 
