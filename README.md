# rust-python

## Read line from stdin

Rust
```
println!("Type something")
let mut line = String:new();
std::io::stdin.read_line(&mut line)
```

Python
```
line = input("Type something")
```

## Print formatted string

Rust
```
let x = 5
println!("Variable x equals to {x}")
```

Python
```
x = 5
print(f"Variable x equals to {x}")
```
