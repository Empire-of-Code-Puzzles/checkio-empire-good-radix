You are given some number 'n' written as a string with a radix equal to `k` `(1 < k < 37)`.
We know that our number is divisible by `(k - 1)` without a remainder. 
You should find the smallest possible `k` if it exists, or return `0` in the case where it doesn't.

For example: where `n = 18`, `k` should be greater than 8.

If `k == 9`, then `n = 17` in the decimal system and `17 % 8 == 1`. This is the wrong radix.

If `k == 10`, then `n = 18` in the decimal system and `18 % 9 == 0`. We found the answer.
