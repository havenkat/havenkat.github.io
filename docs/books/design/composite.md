#### Composite

This pattern speaks about "has a clause".

```
struct Engineer interface {
    Dowork()
}

struct developer struct {}
func (dev *developer) Dowork() {

}

struct architect struct {}
func (arch *architect) Dowork() {

}

// Here has a clause 
type allofjack struct {
    arch architect
    dev  developer
}


func getWorkDone(joker *allofjack){
    joker.architect.Dowork()
    joker.developer.Dowork()
}


```

----
[Home](../../README.md)
