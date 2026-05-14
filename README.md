# Jayve Saint Louis — Smart Contract Security Researcher

Independent security researcher focused on EVM smart contracts and Move-based protocols (Aptos, Sui). I hunt HIGH and CRITICAL severity vulnerabilities on HackenProof, Code4rena, and Immunefi.

## Selected Work

**[vaultx-refund-bypass](https://github.com/jayvealex-cpu/vaultx-refund-bypass)** — Asymmetric validation bypass (Pattern 2). `depositCurve()` missing the refund-flag check that `depositStandard()` enforces. Foundry PoC with 3 passing tests, quantified fee-avoidance impact.

## What I Hunt

- Asymmetric validation: two code paths for the same operation, one missing a guard
- State machine bypasses: reaching an action in a state the protocol never intended
- Fee bypass via dust, rounding manipulation, division-before-multiplication
- Reentrancy (CEI violations), approval mismatches, oracle staleness
- Move/Aptos: TreasuryCap leakage, shared object auth gaps, capability abuse

## Tools

Foundry · Slither · Python · Solidity · Move · Git

## Contact

jayvealex@gmail.com
