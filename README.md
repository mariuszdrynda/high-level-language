# High Level Language

# Goals

Goal of this language is create 
+ Fast as C
+ Easy as Python
+ Safe as Haskell

# Requirements

+ Pure funcrional programming language
+ Compiled
+ No automatic memory management overhead (e.g. garbage collector)

# Current status

# Language description

## Syntax

> [!CAUTION]
> No cases in match expression.

## Name checker

## Type checker

## Desugaring

### While loop and do-while loop

Not in LLL. It can be expressed via gotos and if statements

## Dead code elimination

### Unused global variable

### Unused function

### Unused variable

### Code after return

### Code after '_' pattern in match

```
match x
  0 => ...
  _ => ...
  1 => unreachable
```

## Optimisation
