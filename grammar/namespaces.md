## Namespaces

### Defining a Namespace
```
namespace name
```

* A namespace is required to be used in another file or namespace

### Importing
```
import name [as newName]
```

* Adds a namespace into the current namespace
* Using imported items uses a dot notation
* The `as` clause changes the name used for the dot notation

```
import Point
import Point2 as P

Point.add()
p.add()

```