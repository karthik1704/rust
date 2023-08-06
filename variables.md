## Variables

- Statically typed
- all variable are immutable
- only letters, digit and underscores
- only startwith letters and underscores
- case sensitive
- 
```rust
let x:i32 = 5; //immutable
let mut y:i32 = 15; //mutabale
y=20;
```
## Data types

- 2 types - scalar and compound types

### Scalar Types

- Represents single value
- 4 types
    - Integer
    - float
    - booleans
    - characters

#### Interger

- interger is a number without a fractional component
- 2 types
    - Signed integers (stores positive and negative values)
        - assiged by i
        - 4 types
          - i8, i16, i32, i64
    - Unsigned intergres ( only stores postive values)
        - assigned by u
        - 4 types
            - u8, u16, u32, u64
- To check max value of types
  ```rust
  println!(std::i8::MAX);
  ```
