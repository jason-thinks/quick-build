# Quick Build scripts

Useful for quickly compiling and running a single file or small project
when you don't want to deal with bloated build tools.

- qc for C
- qj for Java

Works well with [STB single-file header libraries] (https://github.com/nothings/stb)

# Usage Options
- Copy the script into a project directory and create a main.c file.  Running
  'qc' within that directory will compile main.c and generate an executable
  with the same name as the directory.
- Run 'qc <sourcefile>'.  This builds the executable into a temp file and runs
  it much like a script.  Nothing is left afterwards.


# TODO
- build-build command for building a simple in-repo project management/build tool.
- Implement 'qj <sourcefile>'
- Rework qj dir structure
- Gen jar file for deploy

