# leetcode I guess

https://leetcode.com/u/actual_ant/

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

**[1480. Running Sum of 1D Array](https://leetcode.com/problems/running-sum-of-1d-array/description/)*
list comprehension, walrus operator

**[1672. Richest Customer Wealth](https://leetcode.com/problems/richest-customer-wealth/description/)**
started describing time & space complexity
space complexity saving of lazy processing via yielding iterables

**[412. Fizz Buzz](https://leetcode.com/problems/fizz-buzz/description/)**
string concat? no: https://docs.python.org/3/faq/programming.html#id41
unnecessary and counterproductive optimization: global string fields for fizz, buzz, and fizzbuzz

**[1342. Number of Steps to Reduce a Number to Zero](https://leetcode.com/problems/number-of-steps-to-reduce-a-number-to-zero/description/)**
/= provokes float type result
//= provokes int type result

### data structures
isn't the answer always hashmap?


