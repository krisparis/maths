* Theorem : **A number is divisible by 3 if sum of its digits is divisible by 3.**

* Let x be a positive integer with n+1 digits:  x = a0 + a1*10 + a2*10^2 + a3*10^3... + an*10^n
* Let s be the sum of its digits: s = a0 + a1 + a2 + a3 + ... + an
* Now,
** x - s = (a0 - a0) + (a1*10 - a1) + (a2*10^2 - a2) + ... + (an*10^n - an)
** x - s = a1*(10 - 1) + a2*(10^2 - 1) + ... + an*(10^n - 1)

* If we write b^k = 10^k - 1, we will have
** x - s = a1*b1 + a2*b2 + ... + an*bn

* Notice that bk = 9...9 (9 occurs k times).

* Hence all the numbers bk are divisible by 3.
* Hence all the numbers ak*bk are divisible by 3.
* Hence their sum (which is x-s) is divisible by 3.

* Since x-s is divisible by 3, if s is divisible by 3 then so is x and vice versa.
