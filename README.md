# SecureC
The secure version of the C/C++ programming language

# Goals
* To design and implement a programming language, which is compatible with C/C++ and at the same time doesn't have the concept of undefined behavior. 
* The machine code created by the compiler should b able to handle all types of overflows (numeric, buffer including stack, heap, global).
* The language must provide a mechanism for applications to handle all types of overflow
* There must be a possibility to replace a runtime part of the Secure C with custom implementations
* The compatibility with existing source must be retained as much as possible, the amount of beaking changes must be minimal.
 * Obvious exceptions: raw pointers, arithmethics, etc

# Non-goals
* Reinventing completely new language. If you need one use Rust or Go

# Extensibility

# Potential use cases
* Any security-sensitive native components, such as priviledged system services or kernel modules
