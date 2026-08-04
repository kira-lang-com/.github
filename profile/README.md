# **A dual-mode compiled programming language, written in Rust.**

Functions run as **native machine code** (via LLVM) or **bytecode VM** in the same binary. You choose per function, or let the compiler decide.
```kira
@Native
function square(x: int) -> Int {
    return x * x;
}

@Runtime
function main() {
    print(square(9)); // 81 — real machine code
}
```

## Official Website

🌐 **[Kira Programming Language](https://kira.sunday-cloud.com/)**  
The official website for Kira, including documentation, examples, packages, installation guides, and language syntax.

## Links

🌐 [kira-doc.vercel.app](https://kira-doc.vercel.app) · 📖 Docs

