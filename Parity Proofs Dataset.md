# Parity Proofs Dataset

---

# Prove that the sum of two even numbers is even.

## Version 1: 
Let $a$ = $2m$ and $b$ = 2$n$ be even integers, where $m$, $n$ are integers. 
Then \[a + b = 2m + 2n = 2(m+n)\]. 
Since $m$, $n$ are integers, $m+n$ is also an integer. Thus, $2(m+n)$ is even. 

---

## Version 2: 
Even numbers come in pairs, e.g. ...,-4, -2, 0, 2, 4,...
Adding one collection of pairs to another still gives a pair, never leaving a single leftover object. Therefore the sum is even.

---

## Version 3: 
If $a$ and $b$ are even, then \[a \equiv 0\pmod{2}\]  and \[b \equiv 0 \pmod{2}\]. 
Thus \[a + b \equiv 0 + 0 \equiv 0\pmod{2}\].  Hence $a+b$ is even.

---

# Prove that the sum of two odd numbers is even.

## Version 1: 
Let $a$ = $2m + 1$ and $b$ = $2n + 1$ be odd integers, where $m, n$ are integers.
Then $a + b$ = $(2m + 1) + (2n + 1) = 2m + 2n + 2 = 2(m + n + 1)$.
Since $m, n$ are integers, $(m + n + 1)$ is an integer. Thus, $(2m + 1) + (2n + 1)$ is even.

---

## Version 2: 
An odd number is one more than a pair structure. Combining two odd numbers gives all the original pairs plus two leftover singles. 
Those two singles form another pair, so the total is even.

---

## Version 3: 
Every odd number can be written as odd = even + 1. So $(2m + 1) + (2n + 1) = (2m + 2n) + 2$. The first part is even and adding 2 preserves evenness, so the sum is even.

---

# Prove that the sum of an even number and an odd number is odd.

## Version 1: 
Let $a$ = $2m$ and $b$ = $2n + 1$. Then $a + b = 2m + 2n + 1 = 2(m+n) + 1$. Therefore $a + b$ is odd.

---

## Version 2: 
Adding an even number changes a number by jumps of size 2, which preserves parity, so starting with an odd number and moving by an even amount keeps the result odd.

---

## Version 3: 
Suppose \[a \equiv 0 \pmod{2}\] and \[ b \equiv 1 \pmod{2}\]. Then \[a + b \equiv 0 + 1 \equiv 1 \pmod{2}\]. Thus the sum is odd.

---

# Prove that the product of two odd numbers is odd

## Version 1: 
Let \[a=2m+1,\qquad b=2n+1.\] Then \[ab=(2m+1)(2n+1)=4mn+2m+2n+1.\]
Factoring, we get: \[ab=2(2mn+m+n)+1.\] Hence \(ab\) is odd.

---

## Version 2: 
Assume the product of two odd numbers were even. An even product must be divisible by \(2\), meaning one factor must be even. But both factors are odd. Contradiction.

---

## Version 3: 
Since \[a\equiv 1\pmod 2,\qquad b\equiv 1\pmod 2,\] we have \[ab\equiv 1\cdot1\equiv 1\pmod 2.\] Therefore \(ab\) is odd.

---

# Prove that the product of an even number and any integer is even.

## Version 1: 
Let \(a=2m\) and let \(b\) be any integer. Then \[ab=(2m)b=2(mb).\] Since \(mb\) is an integer, \(ab\) is even.

---

## Version 2:
Multiplying by \(b\) means adding the even number repeatedly: \[a+a+\cdots+a.\]
A sum of even numbers is even, so the product is even.

---

## Version 3: 
An even number is divisible by \(2\). If \(2\mid a\), then \[2\mid ab\] for every integer \(b\). Hence \(ab\) is even.

---

# Prove that if \(n^2\) is even, then \(n\) is even.

## Version 1: 
Prove the contrapositive: If \(n\) is odd, then \(n^2\) is odd.
Let \(n=2k+1\). Then \[n^2=(2k+1)^2=4k^2+4k+1=2(2k^2+2k)+1.\]
So \(n^2\) is odd. Therefore, if \(n^2\) is even, \(n\) must be even.

---

## Version 2: 
Assume \(n^2\) is even but \(n\) is odd. Then \[n=2k+1.\]
Squaring, we get: \[n^2=(2k+1)^2=4k^2+4k+1,\] which is odd. Contradiction. Hence \(n\) is even.

---

## Version 3: 
If \(n\) were odd, its prime factorization would contain no factor of \(2\). Squaring doubles every exponent but still introduces no factor of \(2\). Thus \(n^2\) would remain odd. Therefore an even square must come from an even integer.

---

# Prove that if \(n^2\) is odd, then \(n\) is odd.

## Version 1: 
Prove the contrapositive: If \(n\) is even, then \(n^2\) is even.
Let \(n=2k\). Then \[n^2=4k^2=2(2k^2),\] which is even. Therefore, if \(n^2\) is odd, \(n\) must be odd.

---

## Version 2: 
Assume \(n^2\) is odd but \(n\) is even. Then \(n=2k\), so \[n^2=(2k)^2=4k^2=2(2k^2),\] which is even. Contradiction.

---

## Version 3: 
Every integer is congruent to either \(0\) or \(1\pmod 2\). Squaring gives:
\[0^2\equiv0,\qquad 1^2\equiv1\pmod2.\] If \(n^2\equiv1\pmod2\), then \(n\equiv1\pmod2\). Hence \(n\) is odd.

---

# Prove that the square of any integer has the same parity as the integer.

## Version 1: 
If \(n\) is even, then \(n=2k\), so \[n^2=4k^2,\] which is even. If \(n\) is odd, then \(n=2k+1\), so \[n^2=(2k+1)^2=4k^2+4k+1,\] which is odd. Thus \(n\) and \(n^2\) have the same parity.

---

## Version 2: 
Every integer satisfies \[n\equiv0\text{ or }1\pmod2.\] Squaring preserves these values: \[0^2\equiv0,\qquad1^2\equiv1\pmod2.\] Therefore \[n^2\equiv n\pmod2.\]

---

## Version 3: 
From:
\begin{itemize}
    \item if \(n\) is even, then \(n^2\) is even;
    \item if \(n^2\) is even, then \(n\) is even;
\end{itemize}
and similarly for odd parity, we conclude \(n\) and \(n^2\) always share parity.

---

# Prove that if \(a+b\) is odd, then \(a\) and \(b\) have opposite parity.

## Version 1: 
Assume \(a+b\) is odd. If both were even, their sum would be even. If both were odd, their sum would also be even. Both possibilities contradict the assumption that \(a+b\) is odd. Therefore one is even and the other is odd.

---

## Version 2: 
Suppose \[a+b\equiv1\pmod2.\] The only possible parity combinations are:
\[0+0\equiv0,\qquad 1+1\equiv0,\qquad 0+1\equiv1.\] Hence exactly one of \(a,b\) is odd.

---

## Version 3: 
Suppose \(a+b\) is odd. If \(a\) is even, then subtracting an even number from an odd number leaves an odd number: \[b=(a+b)-a.\] Thus \(b\) is odd. Similarly, if \(a\) is odd, then \(b\) must be even. So they have opposite parity.

---

# Prove that if \(a+b\) is even, then \(a\) and \(b\) have the same parity.

## Version 1: 
Assume \(a+b\) is even. If one were even and the other odd, their sum would be odd. Contradiction. Therefore both must have the same parity.

---

## Version 2: 
Suppose \[a+b\equiv0\pmod2.\] 
Possible parity sums:\[0+0\equiv0,\qquad 1+1\equiv0,\qquad 0+1\equiv1.\]
Therefore \(a,b\) are either both even or both odd.

---

## Version 3: 
If \(a+b\) is even, then \[a=(a+b)-b.\] Subtracting two numbers of the same parity gives an even result, while subtracting opposite parities gives an odd result. Since \(a+b\) and \(b\) determine \(a\), the only way for the total to remain even is for \(a\) and \(b\) to share parity.

---
