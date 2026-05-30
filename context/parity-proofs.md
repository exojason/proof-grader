# Parity Proofs Dataset

---

# Prove that the sum of two even numbers is even.

## Version 1: 
Let $a = 2m$ and $b = 2n$ be even integers, where $m, n$ are integers. 
Then \[a + b = 2m + 2n = 2(m + n)\]. 
Since $m, n$ are integers, $m + n$ is also an integer. Thus, $2(m+n)$ is even. 

---

## Version 2: 
An even number is one whose objects can be arranged into pairs with nothing left over. Take two even numbers, each already split into pairs. Combining them while leaving every pair intact leaves no object unpartnered, so the result is even.

---

## Version 3: 
If $a$ and $b$ are even, then \[a \equiv 0\pmod{2}\]  and \[b \equiv 0 \pmod{2}\]. 
Thus \[a + b \equiv 0 + 0 \equiv 0\pmod{2}\].  Hence $a + b$ is even.

---

# Prove that the sum of two odd numbers is even.

## Version 1: 
Let $a = 2m + 1$ and $b = 2n + 1$ be odd integers, where $m, n$ are integers.
Then \[
    a + b = (2m + 1) +(2n + 1)
    = 2m + 2n + 2
    = 2(m + n + 1)
    \]
Since $m, n$ are integers, $m + n + 1$ is an integer. Thus, $(2m + 1) + (2n + 1)$ is even.

---

## Version 2: 
An odd number is one more than a pair structure. Combining two odd numbers gives all the original pairs plus two leftover singles. 
Those two singles form another pair, so the total is even.

---

## Version 3: 
Every odd number can be written as odd = even + 1. So \[(2m + 1) + (2n + 1) = 2m + 2n + 2 = 2(m + n + 1).\] Since $m + n + 1$ is an integer, the sum is divisible by $2$. Hence the sum is even.

---

# Prove that the sum of an even number and an odd number is odd.

## Version 1: 
Let $a = 2m$ and $b = 2n + 1$. Then \[a + b = 2m + 2n + 1 = 2(m+n) + 1\]. Therefore $a + b$ is odd.

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
Factoring, we get: \[ab=2(2mn+m+n)+1.\] Hence $ab$ is odd.

---

## Version 2: 
Assume the product of two odd numbers were even. Then \[ 2 \mid ab.\] Since $2$ is prime, the only way for $2$ to divide $ab$ is for $2$ to divide at least one of the factors. So \[2 \mid a \quad \text{or} \quad 2 \mid b.\] So, at least one of $a$ or $b$ is even, which contradicts our initial assumption that both $a$ and $b$ were odd. So the product of two odd numbers is odd.

---

## Version 3: 
Since \[a\equiv 1\pmod 2,\qquad b\equiv 1\pmod 2,\] we have \[ab\equiv 1\cdot1\equiv 1\pmod 2.\] Therefore $ab$ is odd.

---

# Prove that the product of an even number and any integer is even.

## Version 1: 
Let $a=2m$ and let $b$ be any integer. Then \[ab=(2m)b=2(mb).\] Since $mb$ is an integer, $ab$ is even.

---

## Version 2

Let $a$ be an even number and let $b$ be a positive integer. Since $a$ is even, $a=2m$ for some integer $m$. 
Multiplying $a$ by $b$ means adding $a$ to itself $b$ times, we get: \[ab = a+a+\cdots+a.\] Substituting $a=2m$, we get \[ab = 2m+2m+\cdots+2m = 2(m+m+\cdots+m).\]
Since $m+m+\cdots+m$ is an integer, $ab$ is of the form $2k$ for some integer $k$. Therefore $ab$ is even.

---

## Version 3: 
An even number is divisible by $2$. If $2\mid a$, then $2\mid ab$ for every integer $b$. Hence $ab$ is even.

---

# Prove that if $n^2$ is even, then $n$ is even.

## Version 1: 
Prove the contrapositive: If $n$ is odd, then $n^2$ is odd.
Let $n=2k+1$. Then \[n^2=(2k+1)^2=4k^2+4k+1=2(2k^2+2k)+1.\]
So $n^2$ is odd. Therefore, if $n^2$ is even, $n$ must be even.

---

## Version 2: 
Assume $n^2$ is even but $n$ is odd. Then \[n=2k+1.\]
Squaring, we get: \[n^2=(2k+1)^2=4k^2+4k+1,\] which is odd. Contradiction. Hence $n$ is even.

---

## Version 3: 
If $n$ were odd, its prime factorization would contain no factor of $2$. Squaring doubles every exponent but still introduces no factor of $2$. Thus $n^2$ would remain odd. Therefore an even square must come from an even integer.

---

# Prove that if $n^2$ is odd, then $n$ is odd.

## Version 1: 
Prove the contrapositive: If $n$ is even, then $n^2$ is even.
Let $n=2k$. Then \[n^2=4k^2=2(2k^2),\] which is even. Therefore, if $n^2$ is odd, $n$ must be odd.

---

## Version 2: 
Assume $n^2$ is odd but $n$ is even. Then $n=2k$, so \[n^2=(2k)^2=4k^2=2(2k^2),\] which is even. Contradiction.

---

## Version 3: 
Every integer is congruent to either $0$ or $1\pmod 2$. Squaring gives:
\[0^2\equiv0,\qquad 1^2\equiv1\pmod2.\] If $n^2\equiv1\pmod2$, then $n\equiv1\pmod2$. Hence $n$ is odd.

---

# Prove that the square of any integer has the same parity as the integer.

## Version 1: 
If $n$ is even, then $n=2k$, so \[n^2=4k^2,\] which is even. If $n$ is odd, then $n=2k+1$, so \[n^2=(2k+1)^2=4k^2+4k+1,\] which is odd. Thus $n$ and $n^2$ have the same parity.

---

## Version 2: 
Every integer satisfies \[n\equiv0\text{ or }1\pmod2.\] Squaring preserves these values: \[0^2\equiv0,\qquad1^2\equiv1\pmod2.\] Therefore \[n^2\equiv n\pmod2.\]

---

## Version 3
Suppose for contradiction that $n$ and $n^2$ have different parity.
If $n$ is even and $n^2$ is odd, then $n=2k$ for some integer $k$. Therefore
\[n^2=(2k)^2=4k^2=2(2k^2),\] which is even, a contradiction.
If $n$ is odd and $n^2$ is even, then $n=2k+1$ for some integer $k$. Therefore
\[n^2=(2k+1)^2=4k^2+4k+1
=2(2k^2+2k)+1,\] which is odd, a contradiction.
Both possibilities lead to contradictions. Therefore $n$ and $n^2$ must have the same parity.

---

# Prove that if $a+b$ is odd, then $a$ and $b$ have opposite parity.

## Version 1: 
Assume $a+b$ is odd. If both were even, their sum would be even. If both were odd, their sum would also be even. Both possibilities contradict the assumption that $a+b$ is odd. Therefore one is even and the other is odd.

---

## Version 2: 
Suppose \[a+b \equiv 1 \pmod 2.\] The possible parity combinations are
\[0+0\equiv0,\qquad 1+1\equiv0,\qquad 0+1\equiv1,\qquad 1+0\equiv1 \pmod 2.\]
Since $a+b\equiv1\pmod2$, the cases $0+0$ and $1+1$ are impossible. Therefore exactly one of $a$ and $b$ is odd and the other is even. Hence $a$ and $b$ have opposite parity.

---

## Version 3
Suppose $a+b$ is odd. If $a$ is even, then $a=2m$ for some integer $m$. Since $a+b$ is odd, there exists an integer $k$ such that
\[a+b=2k+1.\] Then \[b=(a+b)-a=(2k+1)-2m=2(k-m)+1.\]
Since $k-m$ is an integer, $b$ is odd. Similarly, if $a$ is odd, then $a=2m+1$ and \[b=(a+b)-a=(2k+1)-(2m+1)=2(k-m),\] which is even.
Therefore one of $a$ and $b$ is even and the other is odd. Hence they have opposite parity.

---

# Prove that if $a+b$ is even, then $a$ and $b$ have the same parity.

## Version 1: 
Assume $a+b$ is even. If one were even and the other odd, their sum would be odd. Contradiction. Therefore both must have the same parity.

---

## Version 2: 
Suppose \[a+b\equiv0\pmod2.\]
The possible parity combinations are \[0+0\equiv0,\qquad
1+1\equiv0,\qquad
0+1\equiv1,\qquad
1+0\equiv1
\pmod2.\]
Since $a+b\equiv0\pmod2$, the cases $0+1$ and $1+0$ are impossible. Therefore $a$ and $b$ are either both even or both odd. Hence $a$ and $b$ have the same parity.


---

## Version 3
Since $a+b$ is even, there exists an integer $k$ such that \[a+b=2k.\]
Every integer is either even or odd. If $a$ is even, then $a=2m$ for some integer $m$. Substituting into the equation gives \[2m+b=2k,\] so
\[b=2(k-m).\] Since $k-m$ is an integer, $b$ is even.
If $a$ is odd, then $a=2m+1$ for some integer $m$. Substituting into the equation gives \[2m+1+b=2k,\] so \[b=2(k-m-1)+1.\]
Since $k-m-1$ is an integer, $b$ is odd.
Therefore, whenever $a+b$ is even, $a$ and $b$ have the same parity.

---
