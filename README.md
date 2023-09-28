# Recursion
**Recursion from frontend freak**         
*SOLUTION FROM PRAKASH SHUKLA*
>  time complextiy:- o(n)  bcz iterate linearly
> sc :- O(1)     no extra space conssume

SOLVE:-   abba  means both side equal hona chahiye
          '  ' 
          '--' 
```             
function isPalindrome(S) {
    var n = S.length;
    for (var i = 0; i < Math.floor(n / 2); i++) {                          // half distance tk jaa rhe hai
        if (S.charAt(i) !== S.charAt(n - 1 - i)) return 0;                 // if first character and last character eqaul nhi hua to return zero  kr do.
    }
    return 1;             // agaar uper sahi false nhi hua to bta do palindrime hai
}

```
**Create a function which returns the sum of digits of a number (e.g., sumOfDigits(453) is 12)**
> SumOfDigits(n) = sumOfDigits(n/10) + (n%10)

```


