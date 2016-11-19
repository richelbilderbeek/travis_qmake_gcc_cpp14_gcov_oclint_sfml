# travis_qmake_gcc_cpp14_gcov_oclint_sfml

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)
![Whitespace](Whitespace.png)
[![Codecov logo](Codecov.png)](https://www.codecov.io)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_gcov_oclint_sfml.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_gcov_oclint_sfml)
[![codecov.io](https://codecov.io/github/richelbilderbeek/travis_qmake_gcc_cpp14_gcov_oclint_sfml/coverage.svg?branch=master)](https://codecov.io/github/richelbilderbeek/travis_qmake_gcc_cpp14_gcov_oclint_sfml?branch=master)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++14`
 * Libraries: `STL` and `SFML`
 * Code coverage: `gcov`
 * Static type checking: `OCLint`
 * Source: one single file, `main.cpp`

Less complex builds:
 * No `gcov`: [travis_qmake_gcc_cpp14_oclint_sfml](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_oclint_sfml)
 * No `OCLint`: [travis_qmake_gcc_cpp14_gcov_sfml](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_gcov_sfml)
