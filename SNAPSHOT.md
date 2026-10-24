# mceval_x86_linux

**Source:** HuggingFace dataset [`adpretko/mceval_x86_linux`](https://huggingface.co/datasets/adpretko/mceval_x86_linux) (community dataset)
**Downloaded:** 2026-10-23

The same 50 McEval C tasks (`C_1`…`C_50`) compiled for **x86-64 Linux**. Splits `O0` / `O2`, 50 each = **100 rows**.

Fields: `source_code` plus `compiler_asm`, `object_asm`, `shared_asm`, `program_asm`.
Note: **no PIC / `_v2` columns** here, unlike the arm / riscv `reloc_v2` sets.

Companions: [`mceval_arm_linux_reloc_v2`](https://github.com/chihyu-wang-tsmc/mceval_arm_linux_reloc_v2), [`mceval_riscv_linux_reloc_v2`](https://github.com/chihyu-wang-tsmc/mceval_riscv_linux_reloc_v2).

---

Snapshot kept for benchmark work; see [chihyu-wang-tsmc/code-benchmarks](https://github.com/chihyu-wang-tsmc/code-benchmarks) for the full benchmark index. Licensing follows the upstream source.
