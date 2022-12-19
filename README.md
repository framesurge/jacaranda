# Jacaranda

Jacaranda is a Rust styling system for [Sycamore](https://github.com/sycamore-rs/sycamore) that is **fully typed**, and **reactive**. No more manually updating styles on components, or mistyping a CSS property value!

Jacaranda is currently under active development, and v0.1.0 can be expected around the end of January 2023.

## Motivation

When Jacaranda was first written, there were no substantial styling solutions for Sycamore, a library for building reactive web apps in Rust, and no major attempts to build a typed system for CSS in the WebAssembly world. Jacaranda was mainly inspired by systems like [Elm UI](https://github.com/mdgriffith/elm-ui/), which offers a fully typed system styling system for the [Elm language](https://elm-lang.org/). Jacaranda not only provides typed CSS, but also a generic engine for modifying Sycamore nodes arbitrarily, which allows it to provide an extensible solution for common styling systems. This allows CSS classes to become libraries in their own right, enabling user interface design to transcend the boundaries of stylesheets and enter the world of code-sharing through crates!

Moreover, Sycamore is built to be generic over rendering backend from the core, meaning you can use it to build a web app just as easily as a native macOS one. By operating directly on Sycamore `Node`s, Jacaranda achieves the same outcome, meaning all its features are fully transferable to any rendering backend. In future, we want to bring Jacaranda far beyond the realm of the web!

## License

See [`LICENSE`](./LICENSE).
