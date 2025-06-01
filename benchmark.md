# Baseline results — 2025-05-31

| Variant | Batch | TVM INT8 (ms) | PyTorch FP32 (ms) | Speed-up |
|---------|-------|---------------|-------------------|----------|
| Conv-only | 1 | 0.158 | 0.533 | 3.36× |

Notes:

* NumPy 1.26.4, TVM 0.14.dev273 CPU wheel, AVX2 laptop.
* Global-scale PTQ, no AutoTVM tuning.
