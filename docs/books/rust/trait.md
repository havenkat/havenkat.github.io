#### Triats  

In any familiar OOPS supported programing languages, we would have seen creating interfaces, abstraction, for these approaches the answer from Rust is traits.

A trait is a common interface that a group of types can implement.

How do we define in Rust? :

```
trait Tyre {
    fn size(&self) -> u32;
}

struct Cycle {
    tyre: u32,    
}

struct Bike {
    tyre: u32,
}

impl Tyre for Cycle {
    fn size(&self) -> u32 {
        tyre
    }
}

impl Tyre for Bike {
    fn area(&self) -> u32 {
        tyre
    }
}

```

----
[Home](../../README.md)

