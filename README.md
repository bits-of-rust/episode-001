# episode-001
Where we compile our first program

## Setup
The following needs to be prepared:

* A terminal with access to `rustc`
* An editor, we use [Sublime Text][sublime-text]

## Script

You have installed [Rust][rust-lang] so lets use it to compile a rust program. Open a file `hello.rs` and enter the following code

```rust
fn main() {
	println!("Hello, World!");
}
```

This creates a function with the name `main`, which [Rust][rust-lang] will pick up as the entry point of the program.

Head over to the terminal, enter the directory in which you created the file and type the following command

```sh
rustc hello.rs
```

This will create an executable file called `hello`. Run it by executing

```sh
./hello
```

It prints

```
Hello, World!
```

to the console.

And there you have it, you compiled your first [Rust][rust-lang] program.

[sublime-text]: http://www.sublimetext.com/
[rust-lang]: https://www.rust-lang.org/
