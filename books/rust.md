- Modern systems programming language

Focuses on safety, speed, and concurrency.  Here’s a quick rundown of Rust basics:

##### Variables: 
By default, variables in Rust are immutable. 

let x = 5; // immutable

let mut y = 10; // mutable

##### Control Flow: 
Rust provides if statements and loops (loop, while, and for) for control flow.
--
if x == 5 {
    println!("x is five!");
}
--

for i in 0..5 {
    println!("{}", i); // prints numbers from 0 to 4
}
--
##### Functions: 
Functions are declared with fn and have a set of parameters and an optional return type.

fn add(a: i32, b: i32) -> i32 {
    a + b
}

----
##### Ownership: 
A unique feature of Rust that ensures memory safety without a garbage collector. Ownership rules help manage heap data.


