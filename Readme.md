# Sorting Library

## Usage

### import
Cargo toml
```
[dependencies]
sorting_library = { git = "https://github.com/cowbuno/ass1.git", branch = "main" }
```

### Build
bash
```
cargo build
```

### Implement
main.rs
```
extern crate ass1;

fn main() {
    let mut vec = vec![34, 7, 23, 32, 5, 62];
    ass1::quick_sort(&mut vec);
    println!("Sorted array: {:?}", vec);
}

```