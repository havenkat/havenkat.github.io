#### Factory

This pattern is delegating the creation of instances to the totally different control.
Knows the abstract layer.

```
struct Engineer interface {
    Dowork()
}

struct developer struct {}
func (dev *developer)Dowork() {

}


struct architect struct {}
func (arch *architect) Dowork() {

}

Const {
    dev  =1
    arch =2
}

func getWorkDone(who int)(Engineer,error){
    switch who {
        case dev:
        return new developer(),nil
        case arch:
        return new architect(),nil
        default :
        return nil,errors.new("don't know that person")
    }
}


```

----
[Home](../../README.md)
