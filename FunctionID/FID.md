# Function Identification

These are datasets for Ghidra's Function Identification analyzer.
To add them to an installation, copy them to `Ghidra/Features/FunctionID/data`.
These are in their 'packed' form.
Ghidra should unpack them on first use.

To add them to a source tree, copy them into `ghidra.bin/Ghidra/Features/FunctionID/src/main/fidb`.
Note that `ghidra.bin` is a sibling directory of your clone of `ghidra`.
The Gradle task `prepDev` will unpack these into a directory for Ghidra (as run from Eclipse) to use.
The Gradle task `buildGhidra` will unpack these and include them in the build output.
