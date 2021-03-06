## Types of Loops

Loops can be written as `while` loops, `do-while` loops, and `for` loops.

## while Loops

`while` loops iterate until a condition is met.

```c
while (a < 10) {
  a++;
}
```

## do-while Loops

`do-while` loops are `while` loops that initially execute the body once before checking the condition.

```c
do {
  printf("not true!");
} (while 2 == 3);
```

## for Loops

`for` loops complete a set number of iterations before meeting a condition.

```c
for (int i = 0; i <= 10; i++) {
  printf("Hello!");
}
```

## Loop Keywords

All loops can utilize keywords like `continue` and `break`. `continue` restarts the loop and `break` breaks out of (or ends) the loop.

## Rewriting Loops

A `for` loop can always be re-written as a `while` loop; most `while` loops can be re-written as a `for` loop.
