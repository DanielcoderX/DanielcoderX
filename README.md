# Hey, I'm DX 👋

I build systems that make sense — clean, high-performance, and built to last.
I'm not chasing trends; I'm chasing precision. Code is how I think out loud.

🌐 **Website:** [danielcoderx.github.io](https://danielcoderx.github.io/)

---

## 🧭 What Drives Me

I care about understanding how things actually work — not just using a framework, but tracing it down to the syscall.
From low-level memory behavior to system architecture, the goal is always the same: **clarity, simplicity, and raw performance.**

- Write code that's minimal, not clever.
- Build things that serve a real purpose.
- Question defaults instead of inheriting them.

Code isn't a career for me — it's a craft, and I take it seriously.

---

## ⚙️ What I Work With

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-555555?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

**Focus Areas**
- Low-level memory management — arena allocators, object pools, GC control
- Network transport engineering — QUIC, WebSocket, TLS 1.3
- Systems and backend infrastructure, distributed logic
- Compiler internals, concurrency, cross-platform binaries

---

## 🚀 Featured Projects

### [`rustygo`](https://github.com/DanielcoderX/rustygo) — Arena allocation & SSA lifetime analysis for Go
> Rust-inspired arena allocator, object pools, and GC control, plus a static analyzer that proves allocation
> lifetimes and transparently routes safe allocations to thread-local arenas — bypassing the GC where it's
> provably safe to do so, with a conservative heap fallback everywhere else.
> Bump allocation backed by `mmap` on Linux/macOS and `VirtualAlloc` on Windows.
> **0 B/op · 0 allocs/op** for eligible allocation paths in benchmarks vs. the heap.

`Go` · `arena-allocator` · `ssa` · `static-analysis` · `memory-management` · `performance` · `WIP`

---

### [`anylink`](https://github.com/DanielcoderX/anylink) — TCP → WebSocket / QUIC bridge
> Expose any TCP service (SSH, Redis, PostgreSQL...) as a WebSocket or QUIC endpoint.
> QUIC (RFC 9000) · TLS 1.3 · 0-RTT · dynamic key rotation · TCP pooling · Prometheus metrics.

`Go` · `quic` · `websocket` · `tls` · `networking` · `tunneling`

---

### [`rwfs`](https://github.com/DanielcoderX/rwfs) — In-memory read-write file system
> A full-featured virtual filesystem for Go — directories, permissions, compression, encryption, ACLs,
> concurrency-safe by design. Optional disk persistence with a transparent hybrid in-memory + local mode.

`Go` · `filesystem` · `in-memory` · `compression` · `security`

---

## 📝 Writing

I write about systems engineering, performance, and the occasional deep dive into things most people skip over.
👉 **[danielcoderx.github.io/blog](https://danielcoderx.github.io/blog)**

---

## 🌌 Beyond Code

I read a lot about physics, philosophy, and human behavior. Software reflects the mind that built it —
clean logic tends to come from clear thinking. Understand first, create second.

---

## 🪐 Connect

- **Website:** [danielcoderx.github.io](https://danielcoderx.github.io/)
- **Telegram:** [@danielcoderx](https://t.me/danielcoderx)

---

> *"Simplicity isn't the absence of complexity — it's mastery over it."*
