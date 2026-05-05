# tinyforge

A from-scratch transformer language model in C++/CUDA. Built to learn ML systems engineering from the ground up.

## Status

🚧 **Under construction (Summer 2026 build).** Updates weekly.

## Goals

- Implement a working transformer architecture from scratch in C++ with CUDA kernels for the heavy ops
- Train a small (10–50M parameter) GPT-style model on a real dataset
- Match or beat reference implementations (PyTorch, nanoGPT) on inference speed for small models
- Document the build with a technical blog post and benchmarks

## Repo Structure
picoGPT/
├── python/        # PyTorch reference implementation + tokenizer
├── src/           # C++ core (Tensor, ops, model)
├── kernels/       # CUDA kernels
├── tests/         # Unit tests
├── benchmarks/    # Benchmark scripts and results
├── data/          # Training data (gitignored)
├── docs/          # Blog post, charts
└── CMakeLists.txt

## Build

(Coming once C++ side starts — Week 4.)

## Benchmarks

(Coming Week 12.)

## Acknowledgments

Heavily inspired by Andrej Karpathy's `nanoGPT` and `llm.c` projects, and the foundational *Attention Is All You Need* paper (Vaswani et al., 2017).

## License

MIT — see [LICENSE](LICENSE).
