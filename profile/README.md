# **A dual-mode compiled programming language — written in Rust.**

Functions run as **native machine code** (via LLVM) or **bytecode VM** in the same binary. You choose per function, or let the compiler decide.
```kira
@Native
func square(x: int) -> int {
    return x * x;
}

@Runtime
func main() {
    printIn(square(9)); // 81 — real machine code
}
```

## Links

🌐 [kira-lang.com](https://kira-lang.com) · 📖 Docs *(coming soon)*