# Expansions

Expansions provide dynamic string generation capabilities. These work identical to the standard
POSIX way, but there are a few major differences: arrays are denoted with an **@** sigil, and have
their own variant of process expansions (**@()**) which splits outputs by whitespace; the
arithmetic logic is more feature-complete, supports floating-point math, and handles larger
numbers; and Ion supports methods in the same manner as the [Oil shell](http://www.oilshell.org/).

- [Variable Expansions](ch05-01-variable.html)
- [Process Expansions](ch05-02-process.html)
- [Brace Expansions](ch05-03-brace.html)
- [Arithmetic Expansions](ch05-04-arithmetic.html)
- [Method Expansions](ch05-05-method.html)
