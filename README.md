# xmlCompiler

Uses Flex (GNU Lex) for Lexical Analysis. Flex gathers a series of tokens (simple or
complex) based off of a series of regular expressions. These regular expressions are
broken into Finite State Machines and futher into State Transition Tables.

The tokens are fed into Bison (GNU Yacc), a parser. Bison is designed to work with Flex.
Bison will parse the file based off of a series of Grammar in BNF of Postal Addresses.

Flex and Bison together work like a compiler. A file of Postal Addresses that are in the
correct format are compiled to an XML file form. This idea is similar of how a GNU C++
Compiler converts a C++ file (.cc file) into an object file (.o file).
