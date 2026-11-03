# CFG to Chomsky Normal Form

A Java program that converts a context-free grammar (CFG) into Chomsky Normal Form (CNF).

## Input

The grammar is hard-coded in `Main.java` as two parallel arrays:

- `grammar_left`: the left-hand side (non-terminal) of each production
- `grammar_right`: the matching right-hand side

Entry `i` in one array matches entry `i` in the other (a 1:1 mapping).

## Running

```bash
javac Main.java
java Main
```
