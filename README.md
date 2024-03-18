# Project Title: Customized Compiler

This project is a customized compiler developed using Java. It is designed to compile specific source code into assembly language.

## Structure

The project is organized into several directories:

- `ASM_Emulator/`: Contains assembly code examples and an emulator for running them.
- `input/`: Contains test files for the compiler.
- `output/`: Contains the output of the compiler after processing the input files.
- `runConfigurations/`: Contains configuration files for running the compiler.
- `src/`: Contains the source code of the compiler.

## Key Files

- `src/asmCodeGenerator/ASMCodeGenerator.java`: This is the main code generator. It transforms the parsed syntax tree into assembly code.
- `src/asmCodeGenerator/runtime/RunTime.java`: This class manages the runtime environment for the generated assembly code.
- `src/asmCodeGenerator/runtime/MemoryManager.java`: This class manages memory allocation and deallocation during the execution of the assembly code.

## How to Run

To run the compiler, use the configuration specified in `runConfigurations/TanCompiler_currentTest (tan-S).launch`. This configuration runs the `TanCompiler` application with `input/currentTest.tan` as the input file.

## Note

Do not call the code generator if any errors have occurred during analysis. The `ASMCodeGenerator` class is designed to handle this.

## Contributing

Contributions are welcome. Please submit a pull request with your changes.

## License

This project is licensed under the terms of the MIT license.
