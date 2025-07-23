# Pyx: A Pythonic Language with C++-Level Speed ⚡🐍

Pyx is an experimental, LLVM-based, Just-In-Time (JIT) and Ahead-of-Time (AOT) compiled programming language designed to combine the **simplicity of Python** with the **performance of C++**.

Pyx is built for **quantitative finance**, **AI/ML applications**, **high-performance computing**, and **real-time systems**, offering the best of both worlds — Python-like syntax and system-level speed.

---

## 🚀 Vision

> “Make Python as fast as C++, without sacrificing readability or flexibility.”

Pyx aims to become the **world's fastest Python-syntax-compatible compiled language**. It will:
- Support **LLVM IR** generation.
- Offer **function-level JIT** with GPU/CPU hybrid acceleration.
- Integrate **NumPy C-level functions** for fast numerical operations.
- Enable **hardware-tuned memory models**, **cache-aware execution**, and **parallelism** via multithreading & multiprocessing.
- Support **AI-assisted optimization** and **containerized deployment** for scalable supercomputing environments.

---

## 🔧 Key Features (Planned)

| Feature                       | Status     | Notes                                                                 |
|------------------------------|------------|-----------------------------------------------------------------------|
| Pythonic syntax              | ✅ Basic   | Fully Pythonic code, parsed to LLVM IR                                |
| LLVM-based compilation       | ✅ Working | Compiles to LLVM IR and executes via llvmlite                         |
| JIT support                  | ✅ Basic   | Simple JIT execution with function registration                       |
| `print()`, `return`, `if/else`, `for/while` | ✅ Working | Basic control structures supported                                    |
| NumPy C backend integration  | 🔄 Ongoing | Speeds up loops with C-based NumPy functions                          |
| SIMD/MemCopy loop optimization | 🔄 Ongoing | For high-speed numerical processing                                   |
| GPU acceleration (CUDA/OpenCL) | 🔜 Planned | Future support for GPU-compute kernels                                |
| Containerization & cloud support | 🔜 Planned | Pyx-in-the-cloud for scaling workloads                                |
| AI-based optimization        | 🔜 Planned | Automate tuning based on usage & real-time stats                      |

---

## 📈 Benchmarks (Prototype v1.0)

| Task               | Pyx (LLVM JIT) | C++ | Python | NumPy |
|--------------------|----------------|-----|--------|--------|
| 10M `x*x` loop     | ~0.012s        | 0.005s | 2.3s   | 0.015s |
| Fibonacci(30)      | ~0.05s         | 0.04s | 0.6s   | —      |

> Benchmarks run on Intel i5, 8GB RAM. Pyx compiled to LLVM IR with `llvmlite`.

---

## 🧠 Why Pyx?

- ❤️ Python simplicity
- ⚡ C++ speed via LLVM
- 🚀 Hardware-aware optimization
- 🧠 Future AI-based compilation
- 🔄 Containerization & multithreaded execution
- ☁️ Cloud-deployable supercompiler

---

## 📬 Contact & License

**Author:** *Srikanth Karthikeyan*  
**License:** MIT  
**Twitter / GitHub / LinkedIn:** [https://github.com/Srikanth-2004 / https://www.linkedin.com/in/srikanth-karthikeyan-2k4/]

---

> Disclaimer: Pyx is in experimental phase. Contributions, critiques, and collaborations are highly welcome!
