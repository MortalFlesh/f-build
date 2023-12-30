Build
=====

> Meta package for building F# projects

## List of projects (specifications)
- Library
- Executable
- ConsoleApplication
- SAFEStackApplication

All specs have their own default.

## Usage

1. Simply copy `build` dir into a root of your project
2. Copy `build.sh` as well
3. Copy/Require the `Build` group from `paket.dependencies`
4. Copy dependencies from `.config`
5. Change/Configure `build/Build.fs` by your needs
6. Run `./build.sh build` or other commands
