# C++ Vector Out-of-Bounds Access

This repository demonstrates a common error in C++: accessing elements in a `std::vector` outside of its valid bounds.  Accessing elements beyond the `size()` of the vector results in undefined behavior, leading to crashes, unexpected results, or other unpredictable errors.

The `bug.cpp` file contains the erroneous code, while `bugSolution.cpp` offers a corrected version that avoids the out-of-bounds access.  Understanding and preventing this type of error is crucial for writing robust and reliable C++ programs.  Always double-check your vector indices before accessing elements.