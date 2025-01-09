### 1.16
Name at least three things speciﬁed by an ISA.
> [!solution]-
Operations ([[Opcode]]s), [[Data Type]]s, and [[Addressing Mode]]s

### 1.17
Brieﬂy describe the diﬀerence between an ISA and a
microarchitecture.
> [!solution]-
An [[ISA]] describes the way a computer can be interfaced with, what operations it can perform, and way syntax those operations require; A [[Microarchitecture]] describes the physical implementation of all those operations in hardware.
### 1.18
How many ISAs are normally implemented by a single
microarchitecture? Conversely, how many microarchitectures could exist for a single ISA?
> [!solution]-
Often, many [[Microarchitecture]]s will all use the same [[ISA]]
### 1.23
Why is an ISA unlikely to change between successive generations
of microarchitectures that implement it? For example, why would Intel
want to make certain that the ISA implemented by the Pentium III is
the same as the one implemented by the Pentium II? Hint: When you
upgrade your computer (or buy one with a newer CPU), do you need to
throw out all your old software?
> [!solution]-
An ISA is unlikely to change between successive generations of microarchitectures that implement it, as that would defeat the whole purpose of having an ISA; an ISA serves as an level abstraction over the microarchitecture. The whole point of the ISA is for it to be the same regardless of hardware. Furthermore, if the ISA changed for each piece of hardware, it is true that the software would have to change with it, which would be awful.