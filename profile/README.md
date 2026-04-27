# **A dual-mode compiled programming language — written in Zig.**

Functions run as **native machine code** (via LLVM) or **bytecode VM** in the same binary. You choose per function, or let the compiler decide.
```kira
@Native
function square(x: int) -> int {
    return x * x;
}

@Runtime
function main() {
    print(square(9)); // 81 — real machine code
}
```

## Links

🌐 [kira-doc.vercel.app](https://kira-doc.vercel.app) · 📖 Docs *(coming soon)*
