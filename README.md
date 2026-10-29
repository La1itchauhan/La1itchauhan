# Hi, I'm Lalit Chauhan 👋

**Systems & AI Infrastructure Engineer** | Electronics & Telecommunication Engineering (B.E.), Army Institute of Technology (AIT) Pune  
Active upstream open-source contributor to **ARM Bare-Metal Architecture Compliance**, **NVIDIA AI Cloud Runtimes**, **Google S2 Geometry**, and **llama.cpp**. Deep foundations in C/C++, Linux kernel/OS synchronization, compilers, and hardware-software co-design.

---

### 🚀 High-Impact Upstream Contributions

#### 🟢 Merged Pull Requests
- **[ARM-software/sysarch-acs #653](https://github.com/ARM-software/sysarch-acs/pull/653)** — Fixed bare-metal Generic Interrupt Controller (GIC) distributor register addressing for Extended Shared Peripheral Interrupts (ESPI) enable and routing.
- **[ARM-software/sysarch-acs #664](https://github.com/ARM-software/sysarch-acs/pull/664)** — Resolved PCIe Architecture compliance test suites ensuring Base Address Register (BAR) memory restoration after PCI configuration probing.
- **[NVIDIA/aicr #3313](https://github.com/NVIDIA/aicr/pull/3313)** — Resolved enterprise release engineering defect for GPU-accelerated Kubernetes runtime by enforcing boundary tagging across multi-package changelogs.
- **[NVIDIA/aicr #3293](https://github.com/NVIDIA/aicr/pull/3293)** — Scoped Helm-controller v1.5.0 migrations for NVIDIA Network Operator deployment pipelines.
- **[AcademySoftwareFoundation/OpenTimelineIO #2055](https://github.com/AcademySoftwareFoundation/OpenTimelineIO/pull/2055)** — Fixed null pointer dereference in `Composable::available_image_bounds` eliminating undefined behavior crash.
- **[AcademySoftwareFoundation/MaterialX #3087](https://github.com/AcademySoftwareFoundation/MaterialX/pull/3087)** — Resolved double UI scaling issue on macOS Retina high-DPI displays in OpenGL viewport.
- **[AcademySoftwareFoundation/rawtoaces #309](https://github.com/AcademySoftwareFoundation/rawtoaces/pull/309)** — Refactored C++ input validation in image converter into modular, testable components with zero regression.
- **[goharbor/harbor #23646](https://github.com/goharbor/harbor/pull/23646)** — Added dynamic column resizing for Software Bill of Materials (SBOM) table.

#### 🟡 Active Upstream Pull Requests
- **[google/s2geometry #701](https://github.com/google/s2geometry/pull/701)** — Implemented sequence construction and tuple unpacking bindings in pybind11 for spherical computational geometry primitives (`S2Point`).
- **[facebook/pyrefly #5287](https://github.com/facebook/pyrefly/pull/5287)** — Meta's next-gen Python static type checker & language server (Rust) inlay hint suppression.
- **[ggml-org/llama.cpp #30722](https://github.com/ggml-org/llama.cpp/pull/30722)** — Implemented schema grammar controls gating deep-reasoning thinking tokens for Gemma-4 architecture models in low-latency C++ inference runtime.

---

### 💻 Key Systems Projects

- **[High-Throughput Sharded Concurrent Cache (C++17)](https://github.com/La1itchauhan/lru-cache)**
  - Thread-safe LRU and FIFO caches with O(1) ops, zero-allocation hit promotion via `std::list` node splicing, and cache-line-aligned SplitMix64 lock sharding.
  - Scaled concurrent throughput from 7.3 Mops/s to **20.3 Mops/s** under heavy multi-core contention.
  - Verified with 400,000-operation randomized differential test suite; clean under **ThreadSanitizer (TSan)**, **AddressSanitizer (ASan)**, and **UBSan**.

- **[WebAssembly Wide Arithmetic Primitives (C++17 & Assembly)](https://github.com/La1itchauhan/wide-arith-primitives)**
  - Implemented WASM 128-bit instructions (`i64.add128`, `i64.sub128`, `i64.mul_wide`) in portable C++ with carry-chain lowering (`adc`/`sbb`, `_addcarry_u64`) and `__int128` multiplication.
  - Validated against 200,000 randomized cross-checks and a 2,316-case Python arbitrary-precision differential suite on `wasmtime`.

- **WasmEdge LFX Mentorship Pre-tests & JIT Lowering**
  - Instrumented WasmEdge bytecode interpreter dispatch loop to trace and log fixed-width SIMD instructions with operand-level detail.
  - Engineered LLVM ORC JIT demonstrations for 128-bit integer arithmetic with `llc` lowering proofs across SysV and Windows x64 ABIs.

---

### 🛠️ Tech Stack & Systems Rigor

- **Languages:** C, C++ (C++17/20), Rust, Python, Bash, Assembly (x86-64 / ARM / WASM WAT)
- **Systems & Kernel:** ARM Bare-Metal, GICv3/v4 Interrupts, PCIe Memory BARs, POSIX / Multithreading (`std::thread`, atomics, mutexes, lock sharding)
- **Compilers & Runtimes:** LLVM IR, ORC JIT, WebAssembly (`wasmtime`, `WasmEdge`), `llama.cpp` inference & constrained grammars
- **Spatial & Geocomputation:** Google S2 Geometry (`pybind11`), ISRO-IIRS GIS Spatial Analysis & Uncertainty Modeling
- **Verification & Profiling:** AddressSanitizer (`ASan`), ThreadSanitizer (`TSan`), Valgrind, GDB, CMake, Ninja

---

### 📫 Connect With Me

- **Email:** [chauhanlalitofficial@gmail.com](mailto:chauhanlalitofficial@gmail.com)
- **LinkedIn:** [linkedin.com/in/la1it-chauhan5](https://www.linkedin.com/in/la1it-chauhan5/)
- **Location:** Pune, India
