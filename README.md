# LIR
A lisp implementation for the rust interop.

The original idea was to develop such a language which satisfied these criteria:

1. It is a LISP for Rust as Clojure for Java.
2. It ensures all the best things in Rust in LISP manner (type safety, compilation, crates)
3. It has full rust interop (we may call **Rust** functions from **LIR** and call **LIR** functions from rust).
4. It is compiled to **llvm** or **MIR** so it has both speed and performance and as good as **Rust** itself.
5. It has very minor differences in the LISP syntax from Clojure. Clojure provides a small amount of differences to Common Lisp in syntax as I think. The most important thing is that it is **comfortable for use** and **safe & efficient**.
6. It has minor differences in what **Rust** has for building. The best way is to refactor `rustc` so that it is possible to export some AST into `rust` ast or to produce `MIR` code using `librustc` without pain, or to patch `rustc` itself.

# Are these criterias fixed?
No. They may evolve, at any time.

# What's this repo for?
1. This repo will contain different design intended for discussion and choosing what is better. Something like RFC but less strict.
2. This repo will also gather all the issues for gathering the feedback. Ask anything, propose anything, contribute anything.

# Who am I?
Don't think of it. I am not a language expert. I am not genius. I have a problem that I like both Rust and LISP. I want to solve this problem. I am unknown to you and would like to stay so.

# Links
[Reddit post #1](https://www.reddit.com/r/rust/comments/86jm7m/thinking_about_lisplike_language_with_rust_interop/)
