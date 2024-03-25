#### Composite

This pattern speaks about "has a clause".

```
type Engineer interface {
    Dowork()
}

type developer struct {}
func (dev *developer) Dowork() {
  todo("")
}

type architect struct {}
func (arch *architect) Dowork() {
  todo("")
}

// Here has a clause 
type manager struct {
    arch has_architect
    dev  has_developer
}


func getWorkDone(joker *manager){
    manager.has_architect.Dowork()
    manager.has_developer.Dowork()
}


```

----
[Home](../../README.md)
