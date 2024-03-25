#### Proxy

Proxy pattern is for hiding an object,hide features, and providing an layer of abstraction.

```Rust

struct Stack<T> {
    item: Vec<T>,
  }
  impl<T> Stack<T> {
    pub fn new() -> Self {
      Stack { item: Vec::new() }
    }
  
    pub fn push(&mut self, element: T) {
      self.item.push(element);
    }
  
    pub fn pop(&mut self) -> Option<T> {
      self.item.pop()
    }

    pub fn is_empty(&self) -> bool {
      self.item.is_empty()
    }

    pub fn size(&self) -> usize {
        self.item.len()
    }
  }

// Vault is behaving as proxy for stack implementation.
pub struct Vault<T>{
    vault:Stack<T>
}

impl<T> Vault<T>  {
  
  pub fn new() -> Self {
    Vault{ 
      vault: Stack::new(),
    }
    
  }
  pub fn store(&mut self,element:T){
    self.vault.push(element);
  }   

  pub fn get(&mut self)->Option<T>{
    self.vault.pop()
  } 
}

```

----
[Home](../../README.md)
