## What is a pointer?

A pointer is a variable that stores the hexadecimal address of the variable it is pointing to.

## Declaring Pointers

A pointer variable is declared like so:

```c
type* pntr;
type *pntr;
```

## Accessing Memory Address

A memory address of a variable is obtained using the reference operator (`&`). Example:`&var`.

## Dereferencing Pointers

A pointer is dereferenced using the dereference operator (`*`). Example: `*pntr`.

## Incrementing and Decrementing Pointers

Pointers can be incremented and decremented using the `+` and `-` arithmetic operators.

## Accessing Arrays

Arrays can be accessed by using a pointer to the first element and incrementing and decrementing as necessary.
