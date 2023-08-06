## Variables

- Statically typed
- all variable are immutable
- we can assign **mut** keyword to make variable mutable
- only letters, digit and underscores
- only startwith letters and underscores
- case sensitive
- style - **snake_case**

```rust
let x:i32 = 5; //immutable

let y:i32; //rare but we can do
y=2+2; 

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

#### Float

  - Numbers with dicimal points
  - 2 types
        - f64 (default type for float)
        - f32

> **Warning**
> In Rust we can't perform mathmatical operations on different types. if we want we have to convert one of them to other type

  ```rust
  let z:f64 = 3.14;
  ```
#### Boolean

- Two possible value true or false
- Rust don't accept truthly or flasly value
- assing by **bool** keyword
```rust
let status:bool = flase;
let not_equals:bool = 18 != 18; 
```
#### Characters
- Single letter, digit, emoji's or unicode scalar values
- only in single quotes

```rust
let c1: char = 'c';
let c2: char = '4';
let c3: char = '+';
let c4: char = '\u{288A}';
let c5: char = '\"';
```
