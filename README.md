Bool
====

x86 implementation of `true` and `false` in AT&T syntax assembly.

```
gcc x86_false.s -o false
gcc x86_true.s -o true
./true && echo $?
0
./false || echo $?
1
```

Why? Why not?
