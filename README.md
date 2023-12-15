# Komplex Kanban Team14
This project creates a library of complex numbers which include functions that take parameters of complex numbers. The project was completed by the LASA computer science department under Mr. Shockey: 1st Period Class, Team 4, Fall Semester of 2023.
## Getting Started
Clone this repo to your IDE or local machine. Once you have cloned this project, you will be one step closer to accessing the library that was created.
### Prerequisites
- A GitHub account to clone this repository
- CMake (v 3.15 or later)
- Make (v 3.0 or later)
- GCC (GNU Compiler Collection) - C++ compiler
- Catch2
### Installing
1. Clone the repo from your IDE/local machine (git clone URL)
2. Create "build" directory
3. Enter the build directory created using "cd build"
4. Run CMake
5. Run Make
6. You have now made your Makefile file and can run the tests using the instructions below.'
  - Enter ./MyProgram into the shell to get sample output
## Running the tests
To run the automated tests, follow the detailed steps below:
1. Ensure all login credentials are accurate on your local machine before starting
2. Enter the "komplexkanbanv3-team14" directory - cd komplexkanbanv3-team14
3. Enter the "build" directory - cd build
4. type - cmake ..
5. type - make (let the compiler generate, may not generate immediately)
6. type - ./MyProgram
7. The compiler will write "Hello World", then prompt the user to type in any character
8. Once the user types in any character, the default test case output will appear
### Break down into end to end tests
- The first half of the file tests the basic functions created.
  - Tests Complex Number
    - a = 5+6i
  - Tests for equality, addition, multiplication, and division of complex numbers
    - b = 5
    - a + b = 10+6i
    - a * b = 25+30i
    - a / b = 1+1.28
  - Tests other basic functions like sqrt, log, sin, and more.
- Second-half tests more complex functions
  - Log base 10
    - log (base 10) is: 0.892665+0.380467i
  - arc trigonometric functions
  - hyperbolic trigonometric functions
  - etc
### And coding style tests
- Use camel case for variable names
- Instead of having one large header file, create a header for each function to keep consistency and functionality (for if a new function must be added)
- Comments aren't used frequently but recommended if the function is complicated to understand on first look or has an outside source that would be helpful to look at
## Deployment
It is not necessary to deploy the library on a live system.
## Built With
- Replit
- GNU Tools (GCC-the GNU Compiler Collection-C++ Compiler)
- CMake
- Make
## Structure
```
komplexkanbanv3-team14
├── build
│   ├── cmake_install.cmake
│   ├── CMakeCache.txt
│   └── MyProgram
├── lib
│   ├── abs.cpp
│   ├── abs.h
│   ├── acos.cpp
│   ├── acos.h
│   ├── acot.cpp
│   ├── acot.h
│   ├── acoth.cpp
│   ├── acoth.h
│   ├── acsc.cpp
│   ├── acsc.h
│   ├── acsch.cpp
│   ├── acsch.h
│   ├── addition.cpp
│   ├── addition.h
│   ├── arg.cpp
│   ├── arg.h
│   ├── asec.cpp
│   ├── asec.h
│   ├── asech.cpp
│   ├── asech.h
│   ├── asin.cpp
│   ├── asin.h
│   ├── asinh.cpp
│   ├── asinh.h
│   ├── atan.cpp
│   ├── atan.h
│   ├── atanh.cpp
│   ├── atanh.h
│   ├── Complex.cpp
│   ├── Complex.h
│   ├── conj.cpp
│   ├── conj.h
│   ├── cos.cpp
│   ├── cos.h
│   ├── cosh.cpp
│   ├── cosh.h
│   ├── coth.cpp
│   ├── coth.h
│   ├── csch.cpp
│   ├── csch.h
│   ├── divequals.cpp
│   ├── divequals.h
│   ├── division.cpp
│   ├── division.cpp
│   ├── equality.cpp
│   ├── equality.h
│   ├── exp.cpp
│   ├── exp.h
│   ├── imag.cpp
│   ├── imag.h
│   ├── instream.cpp
│   ├── instream.h
│   ├── log.cpp
│   ├── log.h
│   ├── log10.cpp
│   ├── log10.h
│   ├── minusequals.cpp
│   ├── minusequals.h
│   ├── multequals.cpp
│   ├── multequals.cpp
│   ├── multiplication.cpp
│   ├── multiplication.h
│   ├── norm.cpp
│   ├── norm.h
│   ├── notequals.cpp
│   ├── notequals.h
│   ├── outstream.cpp
│   ├── outstream.h
│   ├── plusequals.cpp
│   ├── plusequals.h
│   ├── polar.cpp
│   ├── polar.h
│   ├── pow.cpp
│   ├── pow.h
│   ├── real.cpp
│   ├── real.h
│   ├── root.cpp
│   ├── root.h
│   ├── rotate.cpp
│   ├── rotate.h
│   ├── sech.cpp
│   ├── sech.h
│   ├── sin.cpp
│   ├── sin.h
│   ├── sinh.cpp
│   ├── sinh.h
│   ├── sqrt.cpp
│   ├── sqrt.h
│   ├── subtraction.cpp
│   ├── subtraction.h
│   ├── tan.cpp
│   ├── tan.h
│   ├── tanh.cpp
│   └── tanh.h
├── src
│   ├── main_test.cpp
│   └── main.cpp
└── tests
│   ├── catch_amalgamated.cpp
│   └── catch_amalgamated.hpp
├── cmake_install.cmake
├── CMakeLists.txt
├── main-debug
└── result
```
## Building
1. Create a "build" directory
2. Run CMake
3. Run Make
## .gitignore
Can be added to the CMakeFiles directory
## Contributing
N/A - future students of Advanced Computer Science at LASA will post their libraries. You can check if anything changes in a year by checking their READ.ME file
## Versioning
SemVer
## Authors
- Yang Fan Chau
- William Gu
- Jacob Mathew
- Lalsin Nilian
- Liam Teltow
## License
Currently, this project is not licensed. However, soon this project will be licensed under the GNU General Public License v3 license. For more information please visit: https://www.gnu.org/licenses/gpl-3.0.en.html
## Acknowledgments
- LASA CS Department
- Mr. Shockey
- LASA
- Austin Independent School District
