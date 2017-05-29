### Types

#### Built in Types
| Name | Description |
| ---- | ----------- |
| Boolean | A Boolean value of either `true` or `false` |
| Int | A non floating point number |
| Double | A floating point number |
| String | A list of characters |
| Byte | 8 unsigned bits |

#### Optionality
No Type on it's own can nullable. Postfix any type with a `?` to allow null to be assigned.

```

null => i: Int // ERR
null -> i2:Int? // OK

```

```
def i: Int
null => i // ERR
def i2: Int? 
null -> i2 // OK
```

#### Custom Types

* Any class can be used as a Type as long as it's known by the runtime.