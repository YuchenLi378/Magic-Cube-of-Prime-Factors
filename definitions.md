# Mathematical Definitions

## MCPF1
For a positive integer \( n \) and exponent \( k \geq 1 \), define:

\[
\S_k(n) := \sum_{p \mid n} p^k
\]

where \( p \) runs over the **distinct** prime factors of \( n \).

A MCPF1 of order \( k \) satisfies:

n is not a prime power and

\[
\S_k(n) = n
\]

## MCPF2
For a positive integer \( n \) and exponent \( k \geq 1 \), define:

\[
\T_k(n) := \sum_{p^\alpha \parallel n} \alpha\codt p^k
\]

where \( p \) runs over the **all** prime factors of \( n \).

A MCPF2 of order \( k \) satisfies:

n is not a prime power and

\[
\T_k(n) = n
\]

## Examples

### k=3 MCPF1
- \( 378 = 2 \cdot 3^3 \cdot 7 =  2^3 + 3^3 + 7^3 \)

### k=3 MCPF2
- \( 1096744 = 2^3\cdot 11^3\cdot 103 =2^3 + 2^3 + 2^3 + 11^3 + 11^3 + 11^3 + 103^3 \)


[Back to Home](index.md)
