
# Build

## Xcode

command line:

```
make osx-release64
cd examples/runtime
../../.build/osx64_clang/bin/examples.app/Contents/MacOS/examplesRelease
```

IDE:

```
../bx/tools/bin/darwin/genie --with-combined-examples --xcode=osx xcode9
open .build/projects/xcode9-osx/bgfx.xcworkspace
```

