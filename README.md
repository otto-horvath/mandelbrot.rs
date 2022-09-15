# mandelbrot.rs
Mandelbrot generator in Rust.

![Mandelbrot sample](https://github.com/otto-horvath/mandelbrot.rs/blob/1d8d377e03ad30b3788105ffcd408d8d8b943cb6/mandelbrot.png)
Image generated with `mandelbrot mandelbrot.png 4000x3000 -1.20,0.35 -1,0.20`


Based on example from [Programming Rust, 2nd Edition](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/).

```
Usage: ./target/release/mandelbrot FILE PIXELS UPPERLEFT LOWERRIGHT
Example: ./target/release/mandelbrot mandel.png 1000x750 -1.20,0.35 -1,0.20
```
