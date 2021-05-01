# Find-unique-in-array
there could be many methods like, keep comparing each elenent to each other and if not found then its unique.
or sort the whole array, then compare consequetive index, and more
but a simple approach could be
using XOR logic.
XOR of 0(zero) with n(any number) gives output  = n.
and XOR of n with n gives iutout = 0.
using this
initialize ans = 0;
now xor it with each no. in array,
0 XOR ary[i] will give ary[i];
now ary[i] XOR zry[i+1] can have only 2 outputs, either 0 or the same number.
at last, ans will contain only that number which is not there in the array twice. and here is our answer.
