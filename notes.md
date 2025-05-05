# leetcode I guess

## notes
### day 1
using python, starting as a beginner

**add two numbers**
is there such a thing as integer overflow in python? answer: "[Integers have unlimited precision](https://docs.python.org/3/library/stdtypes.html#numeric-types-int-float-complex)"
For fun try running this in a python repl and see how long it takes to resolve (minute 5 now, still going)
```
>>> sys.getsizeof(bigInt)
92
>>> help(sys.getsizeof)

>>> sys.getsizeof(2 ** 1000)
160
>>> sys.getsizeof(2 ** 10000)
1360
>>> sys.getsizeof(2 ** 1000000000000)

```

There's a PEP for that too: https://peps.python.org/pep-0237/

### data structures
isn't the answer always hashmap?


