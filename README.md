# PlusBuild
This project contains CMake scripts for building Plus library, applications, and all required dependencies.

# Documentation

- [Windows build instructions](Docs/BuildInstructionsWindows.md)
- [Linux/Mac build instructions](Docs/BuildInstructionsLinux.md)
- [New release checklist](Docs/NewReleaseChecklist.md)

## Issues
Submit issues [here](https://github.com/PlusToolkit/PlusLib/issues).

git clone https://github.com/bharatm11/PlusBuild.git
mkdir PlusBuild-bin
cd PlusBuild-bin
cmake ../PlusBuild -DCMAKE_BUILD_TYPE=Release -DPLUS_USE_V4L2=ON -DPLUS_USE_POLHEMUS=ON

make