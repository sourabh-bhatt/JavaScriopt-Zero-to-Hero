# Everything in JavaScript happens inside executon context

- The execution context is like a big box in which we have 2 components in it.

1. Memory Component: The firt component inside javascript is memory component. The memory component is also known as variable environment.

1.1: In Memory environment the codes variables are stored as the key value pair. Even functions are stored as the key value pair.
For example:

```Javascript
a: 10
function: {...}
```

2. The second component inside execution context is code component. The code component is also known as thread of execution.

2.2: The thread of execution is responsible for the running of code one line at a time. In a sequence.

## Javascript can also be defined as a synchronus single-threaded language.

In which

1. Single Threaded means one command at a time.

2. Synchronous means in a specific order.
