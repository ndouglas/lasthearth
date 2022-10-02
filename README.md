# Lasthearth

Lasthearth is an experimental programming language, VM, and domain-specific library.

As part of my work on [Hornvale](https://github.com/ndouglas/hornvale/), I want to write a scripting language that is:

- powerful
- performant
- tailored to the subject at hand, which is creating highly extensible virtual worlds

I can afford to compromise the first and second points for the third, given the nature of Hornvale.

This work is based on Lox, from Robert Nystrom's amazing [Crafting Interpreters](https://craftinginterpreters.com), and specifically his bytecode-based CLox, but I'm customizing it heavily based on my personal preferences and intended use case, and adding bindings for functionality in other projects.

## Hornvale Project
- [Hornvale](https://github.com/ndouglas/hornvale/): Frontend and connective logic
  - [Goldengrove](https://github.com/ndouglas/goldengrove/): Narrative/mythopoetic procedural content generation and tools
  - [Lasthearth](https://github.com/ndouglas/lasthearth/): Embedded programming language and domain-specific library
  - [Breakwater](https://github.com/ndouglas/breakwater/): Environmental procedural content generation and tools
  - [Brownhollow](https://github.com/ndouglas/brownhollow/): Artificial life/social/factional/economic procedural content generation and tools
