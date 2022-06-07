# C Programming Lanuguage: Issues and Developments

I use the C language for most of my projects due to its performance,
fast compiler times, wide support, low-level control, long-term
stability and simplicity ([advantages](./good.mkd))

Despite these advantages, the language also still has many issues
affecting both the specification as well as specific implementations. 
Here I track some of these issues and (my and others) efforts in
addressing them.

## Language Features ##

* [Arrays](./arrays.mkd) *C23 Improvements*
* [Pointers](./pointers.mkd)
* [Atomics](./atomics.mkd)
* [Labels](./labels.mkd) *C23 Improvements*
* [Unions](./unions.mkd)
* [Structs](./structs.mkd)
* [Macros](./macros.mkd)

## Existing Extensions ##

* [Typeof](./typeof.mkd) *C23*
* [Auto](./auto.mkd)
* [Checked Integer Arithmetic](./checked.mkd) *C23*
* [Statement Expressions](./stexp.mkd)
* [Nested Functions](./nested.mkd)
* [Unreachable](./unreachable.mkd) *C23*

## Missing Features ##

* [Safe String Type](./strings.mkd)
* [Containers](./containers.mkd)
* [Stack Bounds](./stack.mkd)
* [Wide Functions Pointers](./wide.mkd)

## General Issues ##

* [Indeterminate Values](./indet.mkd) *C23 Improvements*
* [Effective Types](./tbaa.mkd)
* [Uninitialized Values](./uninit.mkd)
* [Signed Overflow](./signed.mkd)
* [Bounds Checking](./bounds.mkd) *C23 Improvements*
* [Undefined Behavior](./undef.mkd)
* [Weird Representations](./repr.mkd)
