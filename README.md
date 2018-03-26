# LIR
A lisp implementation for the rust interop.

The original idea was to develop such a language which satisfied these criteria:

1. It is a LISP for Rust as Clojure for Java.
2. It ensures all the best things in Rust in LISP manner (type safety, compilation, crates)
3. It has full rust interop (we may call **Rust** functions from **LIR** and call **LIR** functions from rust).
4. It is compiled to **llvm** or **MIR** so it has both speed and performance and as good as **Rust** itself.
5. It has very minor differences in the LISP syntax from Clojure. Clojure provides a small amount of differences to Common Lisp in syntax as I think. The most important thing is that it is **comfortable for use** and **safe & efficient**.


# Links
[Reddit post #1](https://www.reddit.com/r/rust/comments/86jm7m/thinking_about_lisplike_language_with_rust_interop/)
