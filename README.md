# Juvix 🌟
A functional programming language for intent-centric and declarative decentralized applications.
## ✨ Features
- Functional: Pure functions, immutable data
- Type-safe: Strong static typing with inference  
- Intent-centric: Built for Anoma ecosystem
- Compiles to: WASM, LLVM, native code
- Zero-knowledge: Integrated ZK proof generation
## 🚀 Quick Start
### Installation
Using snap (Ubuntu/Debian): sudo snap install juvix
Using brew (macOS): brew install juvix
From source: git clone https://github.com/anoma/juvix.git && cd juvix && make install
### Hello World
Create Hello.juvix: module Hello; open import Stdlib.Prelude; main : IO; main := printStringLn "Hello, Juvix!";
Compile and run: juvix compile Hello.juvix && ./Hello
## 📚 Documentation
Official Docs: https://docs.juvix.org - Complete language reference
Getting Started: https://docs.juvix.org/getting-started - Step-by-step tutorial
Language Reference: https://docs.juvix.org/reference - Syntax and semantics
Examples: https://docs.juvix.org/examples - Code examples
## 🎯 Examples
Basic Functions: factorial : Nat -> Nat; factorial zero := 1; factorial (suc n) := suc n * factorial n;
Data Types: type Tree (A : Type) := | leaf : A -> Tree A | node : Tree A -> Tree A -> Tree A;
## 🔧 Development
Building from Source: git clone https://github.com/anoma/juvix.git && cd juvix && make dependencies && make build
Running Tests: make test
## 🤝 Contributing
We welcome contributions! Please see our Contributing Guide for details.
Good First Issues: https://github.com/anoma/juvix/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22
Development Docs: https://docs.juvix.org/development
## 💬 Community
Discord: https://discord.gg/anoma - Chat with developers
Forum: https://forum.anoma.net - Technical discussions
Matrix: https://matrix.to/#/#juvix:matrix.org - Open protocol chat
## 📄 License
Licensed under the GPL-3.0-only License. See LICENSE for details.
## 🙏 Acknowledgments
Juvix is developed by Anoma and contributors.
