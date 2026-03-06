# C Lists and Stacks Lab

## Project Overview
A C programming lab covering linked list (ArrayList) and stack (Stack) data structures. Students implement functions in `exercises.c` and run tests with `bash test.sh`.

## Project Structure
- `exercises.c` — Student implementation file (the only file students should modify)
- `test.c` — Test suite (do not modify)
- `arraylist.h` / `arraylist.c` — ArrayList TDA implementation
- `stack.h` — Stack TDA interface
- `test.sh` — Build and test runner script
- `log` — Test run log file

## Build System
- Language: C (GCC 14)
- Compiler: `gcc -g test.c -Wall -Werror -o a.out`
- Tests: `bash test.sh`

## Workflow
- **Run Tests** (console) — runs `bash test.sh`, not auto-started (students run it manually from the shell)

## Important Notes
- README explicitly says not to modify the project structure or configuration
- No frontend or backend server — this is a pure command-line C project
- Students should only modify `exercises.c`
