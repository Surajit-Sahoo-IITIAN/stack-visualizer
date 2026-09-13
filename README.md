# Stack — Array Implementation

An interactive visualization of Stack operations using an array.

## Interactive Visualization

👉 [Open the Interactive Stack Visualization](https://surajit-sahoo-iitian.github.io/stack-visualizer/)

## Features

- Enter values dynamically
- PUSH operation
- POP operation
- PEEK operation
- DISPLAY operation
- Stack Overflow
- Stack Underflow
- Visual representation of the array
- Dynamic `top` pointer
- Step-by-step execution
- Previous / Next / First / Last
- Automatic Play / Pause
- Reset
- Corresponding C logic for each operation

## Stack Representation

```c
#define MAX 5

int stack[MAX];
int top = -1;
```

Initially:

```text
top = -1
```

The `top` variable stores the index of the current top element.

## Operations

### PUSH

```c
if (top == MAX - 1)
{
    printf("Stack Overflow");
}
else
{
    top++;
    stack[top] = value;
}
```

### POP

```c
if (top == -1)
{
    printf("Stack Underflow");
}
else
{
    value = stack[top];
    top--;
}
```

### PEEK

PEEK displays the element currently at `top` without removing it.

### DISPLAY

DISPLAY prints the stack elements starting from `top` and moving towards index `0`.

## GitHub Pages

This repository is configured to deploy the interactive visualization using GitHub Pages.

After enabling GitHub Pages, the site will be available at:

```text
https://YOUR-USERNAME.github.io/stack-visualizer/
```
