# Benchmarks

## Table of Contents

-   [`Benchmark Results`](#benchmark-results)
    -   [`typescript.js`](#typescript.js)

## Benchmark Results

### typescript.js

|                     | `oxc`                     | `swc`                           | `biome`                         |
| :------------------ | :------------------------ | :------------------------------ | :------------------------------ |
| **`single-thread`** | `58.31 ms` (✅ **1.00x**) | `210.81 ms` (❌ _3.62x slower_) | `324.68 ms` (❌ _5.57x slower_) |
| **`no-drop`**       | `58.43 ms` (✅ **1.00x**) | `193.08 ms` (❌ _3.30x slower_) | `283.26 ms` (❌ _4.85x slower_) |
| **`parallel`**      | `72.39 ms` (✅ **1.00x**) | `257.81 ms` (❌ _3.56x slower_) | `434.60 ms` (❌ _6.00x slower_) |

---

Made with [`criterion-table`](https://github.com/nu11ptr/criterion-table)
