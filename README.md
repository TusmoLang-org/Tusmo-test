# Tusmo Examples

Test suite and language examples for Tusmo.

This repository contains `.tus` programs used to test Tusmo's syntax, compiler, runtime behavior, language features, and standard library.

## What is tested?

* Variables and built-in types
* Arithmetic, comparison, and logical operators
* Arrays and dictionaries
* Functions and return values
* Default and named arguments
* Conditional statements and loops
* `break` and `continue`
* Classes and object-oriented programming
* Lambdas
* Modules and imports
* Memory and lifetime behavior
* Built-in functions
* C interoperability
* Standard library features
* Raylib and native library functionality

## Test Files

The repository uses focused `.tus` files so individual language features can be tested independently.

Examples include:

* `01_variables.tus` — variables and types
* `02_operators.tus` — operators
* `03_arrays.tus` — arrays
* `04_dictionaries.tus` — dictionaries
* `05_functions.tus` — functions
* `06_classes.tus` — classes and objects
* `07_controlflow.tus` — conditions and loops
* `08_builtin.tus` — built-in functions
* `09_ascii.tus` — ASCII-related functionality
* `test_lambda.tus` — lambda functions
* `test_memory.tus` — memory and lifetime behavior
* `test_named_args.tus` — named arguments
* `test_imports_main.tus` — modules and imports
* `test_isticmaal_class_main.tus` — selective module usage

## Example

Tusmo programs use Somali keywords and a typed syntax. For example:

```tusmo
keyd:tiro a = 10;
keyd:eray magac = "Mubra";

qor("Name:", magac);
qor("Number:", a);
```

A function can be written as:

```tusmo
hawl add(a:tiro, b:tiro): tiro {
    keyd:tiro result = a + b;
    soo_celi result;
}
```

## Purpose

This repository is primarily for development and verification of the Tusmo language.

When a new language feature is introduced, its behavior should be covered by an appropriate test program here whenever practical.

The main Tusmo repository contains the compiler and language implementation. This repository contains test programs and examples used to validate that implementation.

## Related Repository

**Tusmo** — the main compiler and language implementation:

https://github.com/TusmoLang-org/Tusmo

## Status

Tusmo is under active development. The syntax and language features may change as the compiler evolves.

---

## Creator

Tusmo is created and maintained by **Mubarak Abdikadir Jamac (Mubra)**.

For development updates, new Tusmo features, and other projects, follow the creator:

* GitHub: [@Mubarak-mubra](https://github.com/Mubarak-mubra)
* LinkedIn: [@mubarak-mubra](https://www.linkedin.com/in/mubarak-mubra)

More social links and updates will be shared as the Tusmo project continues to grow.


Built for testing **Tusmo**, a Somali programming language.

**TusmoLang** — *Ku qor. Ku dhis. Af-Soomaali.*
