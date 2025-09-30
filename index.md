# 🔢 Magic Cube of Prime Factors

*A mathematical curiosity: numbers that equal the sum of powers of their prime factors (distinct or all)*

## Definition
A number \( n \) is called a **first type of "magic cube of prime factors"(or MCPF1)** of order \( k \) if:

n is not a prime power and

\[
n = \sum_{p \mid n} p^k
\]

where the sum is over **distinct** prime factors of \( n \).

n is not a prime power and

A number \( n \) is called a **second type of "magic cube of prime factors"(or MCPF2)** of order \( k \) if:

\[
n = \sum_{p^\alpha \parallel n} \alpha\codt p^k
\]

where the sum is over **all** prime factors of \( n \).

## Quick Navigation
- [**Results of MCPF**](results/k3-core.md) - 最全列表
- [**Mathematical Definitions**](definitions.md) - 详细定义
- [**Search Code**](code/) - 搜索算法

## Known Results Table

| Order k | MCPF1 | Count |
|---------|-------------------|-------|
| 3 | [378, 2548, 2836295, 4473671462,23040925705,13579716377989,21467102506955,119429556097859](results/k3-core.md) | 8 |
| 4 | (searching) | - |
| 5 | (searching) | - |

| Order k | MCPF2 | Count |
|---------|-------------------|-------|
| 3 | [1096744,2836295, 4473671462,23040925705,13579716377989,119429556097859](results/k3-core.md) | 6 |
| 4 | (searching) | - |
| 5 | (searching) | - |

## Recent Updates
- 2025: Discovered 0 new MCPF
- Code optimized for faster searching

---

*This project is maintained by [Yuchen Li]. Found something interesting? [Open an issue!](https://github.com/YuchenLi378/magic-cube-of-prime-factors/issues)*
