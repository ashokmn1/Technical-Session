# Conditional Statements

Conditional statements are used to perform different actions based on different conditions.
 
## if Statement

Use **if** to specify a block of code to be executed, if a specified condition is true.

### Syntax:
```
if (condition) {
  //  block of code to be executed if the condition is true.
}
```

## else Statement

Use **else** to specify a block of code to be executed, if the same condition is false.

### Syntax:
```
if (condition) {
  //  block of code to be executed if the condition is true.
} else {
  //  block of code to be executed if the condition is false.
}
```

## else if Statement

Use **else if** to specify a new condition to test, if the first condition is false.

### Syntax:
```
if (condition1) {
  //  block of code to be executed if condition1 is true.
} else if (condition2) {
  //  block of code to be executed if the condition1 is false and condition2 is true.
} else {
  //  block of code to be executed if the condition1 is false and condition2 is false.
}
```

## switch Statement

Use **switch** to specify many alternative blocks of code to be executed.

### Syntax:
```
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
```

# Loops

Loops can execute a block of code a number of times.

## for loop

**for** - loops through a block of code a number of times.

### Syntax
```
for (statement 1; statement 2; statement 3) {
  // code block to be executed.
}
```

**Statement 1** is executed (one time) before the execution of the code block.

**Statement 2** defines the condition for executing the code block.

**Statement 3** is executed (every time) after the code block has been executed.

## for in loop

**for/in** - loops through the properties of an object.

### Syntax
```
for (key in object) {
  // code block to be executed.
}
```

## for of loop

**for/of** - loops through the values of an iterable object.

### Syntax
```
for (variable of iterable) {
  // code block to be executed.
}
```

## while loop

**while** - loops through a block of code while a specified condition is true.

### Syntax
```
while (condition) {
  // code block to be executed.
}
```

## do while loop

**do/while** - also loops through a block of code while a specified condition is true.

### Syntax
```
do {
  // code block to be executed.
}
while (condition);
```
