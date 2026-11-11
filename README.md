# C++ Fundamentals

My first C++ programs from 2021, written while learning the language. They used to live in five separate repos and are collected here.

| Folder | Program | Concepts |
| --- | --- | --- |
| [hello-world](hello-world) | `hello_world.cpp` | Output with `cout` |
| [functions](functions) | `prime_numbers.cpp` | Functions returning `bool`, loops |
| | `default_arguments.cpp` | Default parameter values, reading input with `cin` |
| | `function_template.cpp` | Function templates (a generic `Swap<T>`) |
| [recursion](recursion) | `recursive_sum.cpp` | Recursion: sums the integers from m to n |
| [oop](oop) | `youtube_channel.cpp` | Classes, constructors, member functions, `std::list` |
| [atm](atm) | `atm.cpp` | A menu-driven ATM (balance, deposit, withdraw) using `switch` and `do-while` |

## Building

Each file is a standalone program:

```bash
g++ -std=c++17 functions/prime_numbers.cpp -o prime_numbers
./prime_numbers
```

The programs call `system("pause")` and `system("cls")`, so they're meant to run in a Windows console.
