# MadHat-OS
An open source operating system based on the SEL4 microkernel. The Rust langauge will be the primary language used to implement user level stacks on top of SEL4

## Goals 
  - *Goals of the program are subject to change and project matures* 




# Main Technologies 

## SEL4
![alt text](https://sel4.systems/images/logo-text-white.svg)

SEL4 is a state-of-the-art microkernel that is used to assure secure code base that is used to interface with the hardware 

### Target Architecture 
  - ARM *Subject to change*

## The Rust Language

![alt text](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftutsnode.com%2Fwp-content%2Fuploads%2F2020%2F12%2FRust-lang-The-complete-beginners-guide.jpg&f=1&nofb=1)

### Why Rust? 
- Security is a first class citizan in Rust. The Rust compiler will not compile unsecure code
- Rust's design is good for systems programing as well as user level application programming 
- The compiler messages are extermly helpfull in descerning why your program won't compile 
- Rust is a fast compiled lanague with many of the benefits of modern lanaguages 
- Compiled Rust code is small. Provided a smaller attack surface
