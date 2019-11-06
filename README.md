# fibonacci-c

[![Build Status](https://travis-ci.org/xaoc-303/fibonacci-c.svg?branch=master)](https://travis-ci.org/xaoc-303/fibonacci-c)

## recursive if-else

| v | # | 30 | 35 | 40 | 45 |
| --- | --- | --- | --- | --- | --- |
| clang 10.0.1 | [C](./fibo.c) (compiled) | 0,011 | 0,068 | 0,615 | 0:06,656 |
| | [Total](https://github.com/xaoc-303/fibonacci) | | | | |

## optimization

| v | # | 30 | 35 | 40 | 45 |
| --- | --- | --- | --- | --- | --- |
| clang 10.0.1 | [C](./fibo.c) (compiled) | 0,004 | 0,004 | 0,004 | 0,003 |
| | [Total](https://github.com/xaoc-303/fibonacci) | | | | |

## run

```
gcc -x c fibo.c -o fibo
time ./fibo f1 30
time ./fibo f2 30
```
