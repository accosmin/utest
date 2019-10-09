# utest
Header-only library for writing unit tests in C++.

## Features

* Tiny footprint in code size.
* Very fast compilation (compared to Boost.Test).
* Supports checking similarity between Eigen3 matrices and vectors (if UTEST_WITH_EIGEN macro is defined).

## Limitations

* No support for fixtures or mocks.
* Needs an external runner (like ctest) to execute the tests.
