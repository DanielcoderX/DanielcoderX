# Hey, I'm DX 👋

I build systems that make sense — clean, high-performance, and built to last. Code is how I think out loud.

🌐 [danielcoderx.github.io](https://danielcoderx.github.io/) · ✍️ [Blog](https://danielcoderx.github.io/blog) · 💬 [Telegram](https://t.me/danielcoderx)

---

**Stack:** Go, Rust, C/C++, Flutter, Kotlin
**Focus:** low-level memory management (arena allocators, GC control) · network transport (QUIC, WebSocket, TLS 1.3) · systems/backend infra · compiler internals

---

## 🚀 Featured Projects

**[rustygo](https://github.com/DanielcoderX/rustygo)** — Rust-inspired arena allocator and static analyzer for Go. Proves allocation lifetimes via SSA analysis and transparently routes provably-safe allocations to thread-local arenas, bypassing the GC entirely — with a conservative heap fallback everywhere else. Bump allocation backed by `mmap` (Linux/macOS) and `VirtualAlloc` (Windows). **0 B/op · 0 allocs/op** on eligible paths. *(WIP)*

**[gat](https://github.com/DanielcoderX/gat)** — A self-hosting, low-level systems language, originally Windows-native and now cross-platform (Windows PE + Linux ELF64, the latter via raw syscalls with zero libc). ARC-based memory management with value-type structs, weak references for cycle collection, generics, closures, and basic concurrency (thread-local heaps, compile-time thread-safety checks). Bootstrapped from Go, now fully self-compiling — the compiler compiles itself to a bitwise-identical binary across three stages. Comes with its own package manager, LSP tooling, and stdlib.

---

> *"Simplicity isn't the absence of complexity — it's mastery over it."*
