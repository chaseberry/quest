## Variables

### Creation
| Type | Details | Example |
| ---- | ------- | ------- |
| Direct | Defines a variable for later use. Can set the type and scope. | `def x` |
| Indirect | Creates a variable for immediate use. Can set the type. | `5 => x` |

#### Direct

`def [Scope] name[:Type][= Default Literal]`
* If no type is given the variable will have a type of `Any?`
* If no scope is given the variable will have a scope of `local` when outside a class
and `public?` when inside a class

##### Setters and Getters

Direct variables can have custom setters and getters. By default they simply get/set.
```
def x: Int

```

#### Indirect

`Literal|Expression Assignment name[: Type]`
* Uses the type of the Literal | Expression unless a type is provided.
* If a type is given, the Literal | Expression must be or support the given type
