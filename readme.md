![glm](/doc/manual/logo-mini.png)

[OpenGL Mathematics](http://glm.g-truc.net/) (*GLM*) is a header only C++ mathematics library for graphics software based on the [OpenGL Shading Language (GLSL) specifications](https://www.opengl.org/registry/doc/GLSLangSpec.4.50.diff.pdf).

*GLM* provides classes and functions designed and implemented with the same naming conventions and functionality than *GLSL* so that anyone who knows *GLSL*, can use *GLM* as well in C++.

This project isn't limited to *GLSL* features. An extension system, based on the *GLSL* extension conventions, provides extended capabilities: matrix transformations, quaternions, data packing, random numbers, noise, etc...

This library works perfectly with *[OpenGL](https://www.opengl.org)* but it also ensures interoperability with other third party libraries and SDK. It is a good candidate for software rendering (raytracing / rasterisation), image processing, physics simulations and any development context that requires a simple and convenient mathematics library.

*GLM* is written in C++98 but can take advantage of C++11 when supported by the compiler. It is a platform independent library with no dependence and it officially supports the following compilers:
- [*GCC*](http://gcc.gnu.org/) 4.7 and higher
- [*Intel C++ Compose*](https://software.intel.com/en-us/intel-compilers) XE 2013 and higher
- [*Clang*](http://llvm.org/) 3.4 and higher
- [*Apple Clang 6.0*](https://developer.apple.com/library/mac/documentation/CompilerTools/Conceptual/LLVMCompilerOverview/index.html) and higher
- [*Visual C++*](http://www.visualstudio.com/) 2013 and higher
- [*CUDA*](https://developer.nvidia.com/about-cuda) 9.0 and higher (experimental)
- [*SYCL*](https://www.khronos.org/sycl/) (experimental: only [ComputeCpp](https://codeplay.com/products/computesuite/computecpp) implementation has been tested).
- Any C++11 compiler