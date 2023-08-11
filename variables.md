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

let (first_number:i32 , second_number:f64) = (243, 544.44);
let large_number:i32 = 1_000_000;

let x1:i32 = 255;
println("The value of the variable in octal {:0} and in hexadecimal {:x} and in binary {:b}", x1,x1,x1);
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
        - 5 types
          - i8, i16, i32, i64, i128
    - Unsigned intergres ( only stores postive values)
        - assigned by u
        - 5 types
            - u8, u16, u32, u64, u128
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
#### Mathmetical Operation in between differnt data type

- we need convert one of them to same data type
- using **as** keyword
- its only temporary

```rust
let n1:i32 = 14;
let n2:f64 = 15.6;

let n3 = n1+n2 as i32; // converting float to interger , answer 29 , we had a loss beacuse converting float to interger

// so convertiong n1 to float
let n4 = n1 as f64 + n2; // now 29.6
 
``` 
