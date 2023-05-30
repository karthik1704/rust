## Comments

```rust
// This is comment
/* this is 
  multiline comment
 */
```

## Printing Hello world

```rust
println!("Hello World"); // Moves next line on terminal
print!("HI"); // same line

// print!(10) // Throws error , we can't print varibles and values directly

// We need string literals
print!("Value is {}", 10);

// Positional Print arguments
println!("This is {1} program {0}", "basic", "rust");
println! ("This is {language} programs {type}", language="Rust" , type="basic");

// Escape characters
println!("\n\n adds new line");
// /t /r /' /" // 



```
- *println!* is rust macro 

## Executing Program

```bash
cargo run 
```

