# amundson-constant

> The Amundson Constant — A_G = Σ G(n)/n! where G(n) = n/(1+1/n)^n. Defined by Alexa Louise Amundson. Computed to millions of digits from pure integer arithmetic.

Part of the [BlackRoad OS](https://blackroad.io) ecosystem — [BlackRoad-OS-Inc](https://github.com/BlackRoad-OS-Inc)

---

# The Amundson Constant & Framework

**A_G = 1.244331783986725374135061629258...**

Defined by Alexa Louise Amundson. Computed to 10,000,000 verified digits.

## Definition

```
G(n) = n^(n+1) / (n+1)^n = n / (1 + 1/n)^n

A_G = Σ G(n)/n!  for n = 0, 1, 2, ...
```

Six symbols: `n`, `1`, `+`, `/`, `^`, `()`

## Key Results

| Result | Value |
|--------|-------|
| G(1) = 1/2 | Critical line, spin-1/2, uncertainty minimum |
| ζ(0) = -G(1) | Riemann zeta at zero |
| ρ(n) = G(n)/(n!·A_G) | Valid density matrix (trace = 1) |
| Von Neumann entropy | S = 1.272 (1.835 bits) |
| L/H → e | Lagrangian/Hamiltonian ratio |
| G superadditive | G(a)+G(b) > G(a+b) always (= entanglement) |
| ∇²G < 0 | Concave, stable, no chaos |
| 0 + 0^0 = 1 | Euler's identity reversed |
| 1/(2e) gap | Irreducible correction term |
| DNA has 4 bases | Π G(k) crosses 1 between n=4 and n=5 |

## Files

| File | Description |
|------|-------------|
| `AMUNDSON_CONSTANT.txt` | 1,000,001 verified digits |
| `AMUNDSON_CONSTANT_10M.txt` | 10,000,000 verified digits |
| `FRAMEWORK.md` | Complete paper — G(n) connections to quantum mechanics, chemistry, biology, number theory |
| `compute.py` | mpmath computation script |

## 50+ Verified Identities

See [FRAMEWORK.md](FRAMEWORK.md) for the full list, including connections to:

- **Riemann**: G(1) = 1/2 = critical line
- **Euler**: 0 + 0^0 = 1
- **Gauss**: ρ(n) is a bell-curve density
- **Boltzmann**: W = n^(n+1) + (n+1)^n
- **Dirac**: 0 - 0^0 = -1 (antimatter)
- **Ramanujan**: ζ(0) = -G(1) = -1/2
- **Hamilton**: H = G(n), L/H → e
- **Laplace**: ∇²G < 0 always
- **Hilbert**: basis |n⟩, norm √(G/n!)
- **Gödel**: G is below arithmetic
- **Turing**: G always halts
- **Pascal**: G encodes C(2n,n)

## The Pigeonhole Reading

```
G(n) = n^(n+1) / (n+1)^n
     = (ways to crowd n+1 items into n boxes)
       / (ways to spread n items across n+1 boxes)
```

Crowding over spacing. Everything else follows.

## Author

**Alexa Louise Amundson**
Founder & CEO, BlackRoad OS, Inc.

## License

Proprietary — BlackRoad OS, Inc. All rights reserved.
