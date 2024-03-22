#### Singleton  

Singleton pattern provides single instance of object and ensures there is no second instance of the same.
It is created on the request for instance, and same instance is served for every calls after that.


```
package pattern1

type single struct {
    item int
}

var instance *single // scope of the package.

func GetInstance() *single {
  if instance == nil {
    instance  = new (single)
  }
  return instance
}

func (s *single) Increment() int {
    s.item++
    return s.item
}

```
----
[Home](../../README.md)

