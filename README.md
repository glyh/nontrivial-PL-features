[Rationale](https://github.com/glyh/nontrivial-PL-features/blob/main/rationale.md) [Convention](https://github.com/glyh/nontrivial-PL-features/blob/main/convention.md) [Contributing](https://github.com/glyh/nontrivial-PL-features/blob/main/contributing.md)

## List of features

#### 1. [Runtime](https://en.wikipedia.org/wiki/Runtime_(program_lifecycle_phase)) and [compile-time](https://en.wikipedia.org/wiki/Compile_time) [AST](https://en.wikipedia.org/wiki/Abstract_syntax_tree)-based code generation in a [homoiconic](https://en.wikipedia.org/wiki/Homoiconicity) and [dynamically-typed](https://en.wikipedia.org/wiki/Type_system#Dynamic_type_checking_and_runtime_type_information) language -- [Lisp](https://lisp-lang.org/) [macros](https://lispcookbook.github.io/cl-cookbook/macros.html)
  - Pros: DRY, Productibility
  - Cons: Debuggablility, Readablility, Performance Predictablity

#### 2. [Compile-time](https://en.wikipedia.org/wiki/Compile_time) lisp macros that follows [lexical scope](https://en.wikipedia.org/wiki/Scope_(computer_science)#Lexical_scope) -- [Scheme](https://www.scheme.com/) [Hygeneic macro](https://docs.scheme.org/guide/macros/)
  - Related: 1
  - Pros: Debuggablility 

#### 3. Evaluation of code at [compile time](https://en.wikipedia.org/wiki/Compile_time) and type types in compile time -- [Zig](https://ziglang.org/) [comptime](https://ziglang.org/documentation/master/#comptime)
  - Pros: 
    - Eliminate the need of generics: generics are just compile time evaluated function from types to types
  - Cons: Compilation speed

#### 4. A structural way for obtain data from complicated [data structures](https://en.wikipedia.org/wiki/Data_structure) -- [Haskell](https://www.haskell.org/) [pattern matching](https://www.haskell.org/tutorial/patterns.html)
  - Pros: Clarity, Optimizabililty
